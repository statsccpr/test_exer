# A skeleton directory to jumpstart an analysis project

# Setup

1. Start a New Project in [Rstudio](https://www.rstudio.com/) 
2. Use `Version Control` > `Git` > Repo Url `https://github.com/mikejacktzen/proj_skel.git`
3. Use a relevant domain-specific name for your local project (**NOT** `proj_skel`)
4. Choose local destination for your local project

* Note: uses `/misc/.Rprofile` which you can modify


# Instructions

* place chickenscratch prototype scripts in `/tests/proto/`
* place good-standing scripts in `/scripts/`
* place raw data in `/data/raw/`
* place processed data in `/data/proc/`
* place output in `/output/`
* place writeup in `/writeup/`
* formal assertion-travisci tests in `/tests/`

## Optional push to Github
* push your local project to new github repo (**NOT** `proj_skel`)
1. https://github.com/new
2. See [this](http://r-pkgs.had.co.nz/git.html#github-init)
* git remote add github git@foo_new_name_from_step_1
* git push -u github master
3. See general reference on [remote](https://git-scm.com/book/en/v2/Git-Basics-Working-with-Remotes)

## Optional Collaboraters
1. Tell collaborators to `Fork` your github repo as their own local repo
2. They make changes and `Push` to their own global repo
3. Everyone can `New Pull Request` > `Compare Across Forks` 
4. Pull `head fork` edits (yours) into `base fork` edits (theirs) 

