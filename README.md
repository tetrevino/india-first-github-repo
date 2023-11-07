# India First Github Repo

## Exploring GitHub

### Vocabulary

- git - version, local
- GitHub - online platform that allows for code sharing, remote
- repositoryy/repo - named folder of GitHub
- cloning - bringing a repo from the remote to the local


### PAT
(Personal Access Token)
--Configure global git username in terminal.
- git config --global user.name "Your Name Here"

--Configure global git email address in terminal.
- git config --global user.email "your-email@example.com"
Configure the credential helper.

- git config --global credential.helper osxkeychain
--Verify all git configurations are correct.

- git config -l
--You should see the following list.
credential.helper=osxkeychain
user.name=Mona Lisa
user.email=email@example.com

(On GitHub)
select photo
developer settings
personal access tokens
generate new token
name your token with something generic
change EXP date to atleast six months in the future
select the following scopes:
    -repo
    -workflow
    -admin:org
    -notifications
    -user
click generate token
    DO NOT NAVIGATE AWAY FROM PAGE UNTIL YOU HAVE COPIED THE TOKEN AND PASTED IT SOMEWHERE IN A SAFE PLACE
paste the token in a note file for temp storage


### Steps to Push to GitHub
- git status (See changes, made)
- git add <file name> (Stages)
- git commit -m "Update" (Active voice, descriptive message, version control occurs)
- git push origin <branch name>
- reconciles the diff between local and remote