# VSCode Settings

[Visual Studio Code](https://code.visualstudio.com/) is a code editor redefined and optimized for building and debugging modern web and cloud applications. Visual Studio Code is free and available on your favorite platform - Linux, Mac OSX, and Windows.

## Install

> **Note:**
>
> -   Copy your vscode settings defined in your `.vscode/settings.json` file before installing this package.
> -   If you are using MAC then please make your that you have install `code` command in PATH. Please refer [Microsoft Blog](https://code.visualstudio.com/docs/setup/mac#_launching-from-the-command-line) for more details.

## Essential Extensions

-   [React Native Tools _by Visual Studio Mobile Tools_](https://marketplace.visualstudio.com/items?itemName=vsmobile.vscode-react-native)
-   [Code Spellcheker _by Street Side Software_](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker)
-   [Color Highlight _by Sergii Naumov_](https://marketplace.visualstudio.com/items?itemName=naumovs.color-highlight)
-   [ESLint _by Drik Baeumer_](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)
-   [GitLens — Git supercharged _by Eric Amodio_](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens)
-   [Import Cost _by Wix_](https://marketplace.visualstudio.com/items?itemName=wix.vscode-import-cost)
-   [Indenticator _by SirTori_](https://marketplace.visualstudio.com/items?itemName=SirTori.indenticator)
-   [Lorem ipsum _by Daniel Imms_](https://marketplace.visualstudio.com/items?itemName=Tyriar.lorem-ipsum)
-   [Prettier - JavaScript formatter _by Esben Petersen_](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)
-   [Rainbow Brackets _by 2gua_](https://marketplace.visualstudio.com/items?itemName=2gua.rainbow-brackets)
-   [TODO Highlight _by Wayou Liu_](https://marketplace.visualstudio.com/items?itemName=wayou.vscode-todo-highlight)
-   [vscode-icons _by Roberto Huertas_](https://marketplace.visualstudio.com/items?itemName=robertohuertasm.vscode-icons)

## Settings

To get to the user and workspace settings:

-   On a Windows computer, click File > Preferences > Settings or Press **CTRL** + **,**
-   On a Mac, click Code > Preferences > Settings or Press **⌘** + **,**

Paste following [code](.vscode/settings.json) with your design settings.

## Launching from the Command Line

You can also run VS Code from the terminal by typing `code` after adding it to the path:

-   Launch VS Code.
-   Open the Command Palette (**⇧** + **⌘** + **P**)/(**CRTL** + **SHIFT** + **P**) and type `shell command` to find the Shell Command: Install `code` command in PATH command.
    ![shell-command](https://user-images.githubusercontent.com/963765/34649812-016b6834-f3d8-11e7-9ba9-c262bebf2837.png)
-   Restart the terminal for the new `$PATH` value to take effect.

Use the command `code /path/to/file/or/directory/you/want/to/open` to open your file or `code .` to open the current directory in `VS Code`.

## Curated lists of extensions

    ```bash

code --install-extension 2gua.rainbow-brackets
code --install-extension DaltonMenezes.aura-theme
code --install-extension dbaeumer.vscode-eslint
code --install-extension dsznajder.es7-react-js-snippets
code --install-extension eamodio.gitlens
code --install-extension esbenp.prettier-vscode
code --install-extension mhutchie.git-graph
code --install-extension mikestead.dotenv
code --install-extension ms-python.python
code --install-extension ms-vsliveshare.vsliveshare
code --install-extension msjsdiag.vscode-react-native
code --install-extension naumovs.color-highlight
code --install-extension SirTori.indenticator
code --install-extension skyapps.fish-vscode
code --install-extension streetsidesoftware.code-spell-checker
code --install-extension Tyriar.lorem-ipsum
code --install-extension vscode-icons-team.vscode-icons
code --install-extension wayou.vscode-todo-highlight
code --install-extension wix.vscode-import-cost

    ```
