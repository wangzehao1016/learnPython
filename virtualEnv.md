Virtual Environment for Python
---
- Build an environment for a unique python program beyond the environment of system
- Method 1: install pipenv

        cd *targetDir*
        pipenv install *targetPackages*
        
        -- Pipfile and Pipfile.lock generated for this directory --
        
        pipenv run python *executableFile*
        
- Method 2: install virtualenv

        cd *targetDir*
        virtualenv *environmentDir*
        
        -- mirrors of Python interpretor will be generated in environment directory --
        
        /*environmentDir*/Script/activate
        
        -- environment will turn into virtual environment, and all thing can be done as normal --
        
        pip install *targetPackages*
        python *executableFile*
        
        -- below are the special ones --
        
        pip freeze > *requirementFile*
        
        -- get the information of all the packages into a file --
        
        pip install -r *requirementFile*
        
        -- load the package as the file informs --
        
        deactivate
        
        -- environment will turnback into system --
        
        
        
        
        
        
        
        