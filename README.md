gitlab-tree
=========

A role can be use to get the file tree for a gitlab repository

Requirements
------------

* have a gitlab.com repository
* have gitlab access token


Role Variables
--------------

* gitlab_project_id: Project ID
* branch_name: git branch name, master for example
* page_num: page number, start from 1
* gitlab_access_token: gitlab personal token
* gitlab_repo_file_list: the file tree result, a list of file names

Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
