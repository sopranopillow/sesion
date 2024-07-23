## `sesion`, zsh session manager

The aim for this project is to create a session manager for your custom commands and allow ease of usage.

### What is the scope of this project

Currently the features worked on are:

- Easy alias/command addition.
- Session manager that allows multi-level grouping/storage.

### Incentive for this project

While working on personal projects and day time work, I noticed that a simple alias or function might solve repetition of commands and creating shortened version of commands. While this is useful, there are use cases where there is a slight change on a constant in this command that you want to replicate, but is tedious finding this name. Example `alias cmd1=yarn nx run @fluentui/react-components:build` and `alias cmd2=yarn nx run @fluentui-contrib/react-components:build`. This could be fixed by a function, but at some point you are over-engineering this solution and just creating chaos in your zsh config.

This intends to avoid doing so and allow you to have a session manger similar to what a file manager tree would be where you can select your own session for the current project. 

### Future features that could be added

- Config files that load automatically your session commands similar to what .git does.
- Template building to get a kickstart on the session.

### Contribution

Any contribution is welcomed and encouraged!