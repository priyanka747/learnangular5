
### Angular
App framework 
    Two versions
       v 1. AngularJS 
        v 1. AngularJS+(Angular)
    component based
    modular

## features
    1. data binding(two way data binding)
    1. Templates
    1. CLI 
        terminal based interface
        scaffolds an application - allows to create basic appliction with predefined comman configuration
        highly opinionted
        Requirements 
        Main CLI command
        ````
            ng new NAME
            ng serve (application in developer mode)
            ng build (deployment )
            ng g TYPE NAME
            ````n
        installation 
        ```
             npm install -g @angular/cli
             ```
             if installation gives error
        ps1 cannot be loaded because running scripts is disabled on this    
system.
        ```
        Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser
        ```
        execute command  given above

        Run Application on dummy live server
            ```
             ng serve -o

            ``
        Build application
            ```
                ng build
            ``
