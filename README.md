# SpreadsheetGear code samples for C# in Jupyter Notebooks #

These code samples have been tested in [Visual Studio Code (VSCode)](https://code.visualstudio.com/) for Windows, Linux and MacOS.

Microsoft uses the term [Polyglot Notebooks](https://marketplace.visualstudio.com/items?itemName=ms-dotnettools.dotnet-interactive-vscode) for Jupyter Notebooks that use the .NET Interactive kernel. In addition to C#, Polyglot Notebooks support additional languages such as F#, Powershell, Javascript, HTML, Mermaid and SQL. 

See [SpreadsheetGear code samples for Python in Jupyter Notebooks](https://github.com/tracktownsoftware/SpreadsheetGearCodeSamples_JupyterPython) for Jupyter Notebooks that use the Python kernel. 

## Package dependencies ##
*   **[SpreadsheetGear Engine for .NET](https://www.nuget.org/packages/SpreadsheetGear/9.1.44-beta)** - A Nuget package that is the primary SpreadsheetGear library and provides a core set of APIs to read, write, manipulate and calculate workbooks, build charts, format worksheets and cells, and more. Learn more about SpreadsheetGear products on its [Features Page](https://www.spreadsheetgear.com/Products/Features) and [Comparison Page](https://www.spreadsheetgear.com/Products/Compare).

## Run code samples in Github Codespaces ##
- [Open a Github Codespace for this repo in a browser based VSCode editor (No install required)](./docs/SampleCodeInVSCode.md#open-a-github-codespace-for-this-repo-in-a-browser-based-vscode-editor-no-install-required)
- [Open a Github Codespace for this repo in your local VSCode editor (requires the VSCode extension Github Codespaces)](./docs/SampleCodeInVSCode.md#open-a-github-codespace-for-this-repo-in-your-local-vscode-editor-requires-the-vscode-extension-github-codespaces)

## Run code samples in a local Docker Dev Container ##
- [Clone this repo and open a local Dev Container in your VSCode editor (requires Docker Desktop and VSCode Dev Containers extension)](./docs/SampleCodeInVSCode.md#clone-this-repo-and-open-a-local-devcontainer-in-your-vscode-editor-requires-docker-desktop-and-vscode-dev-containers-extension)

## Run code samples in Visual Studio Code with all requirements installed ##

*There is no need to install this list of requirements if using Github Codespaces or a local Docker Dev Container.*

*These instructions are for SpreadsheetGear code samples for C# in Jupyter Notebooks and should work for Windows, MacOS and Linux*

1. From [Download .NET](https://dotnet.microsoft.com/en-us/download)
    - Install the .NET 7.0 SDK - *Required for .NET Extension Pack for Visual Studio Code. SpreadsheetGear works with .NET SDK version 6.0 and later*
2. Install [Visual Studio Code](https://code.visualstudio.com/)
3. Install [.NET Extension Pack for Visual Studio Code](https://marketplace.visualstudio.com/items?itemName=ms-dotnettools.vscode-dotnet-pack)
    - Ignore the "Getting Started with .NET" prompt to "Install .NET SDK". You already installed it in step 1.
4. Install [Git version control](https://git-scm.com/download)
5. Clone this repo and open its local folder in VSCode.

