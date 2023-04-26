Seeing your first suggestion
Note: If you have duplication detection enabled for GitHub Copilot, you may receive limited suggestions, or no suggestions, when using the code examples provided. As an alternative, you can start by typing your own code to see suggestions from GitHub Copilot. For more information on duplication detection, see "Configuring GitHub Copilot settings on GitHub.com."

GitHub Copilot provides suggestions for numerous languages and a wide variety of frameworks, but works especially well for Python, JavaScript, TypeScript, Ruby, Go, C# and C++. The following samples are in JavaScript, but other languages will work similarly.

In Visual Studio Code, create a new JavaScript (*.js) file.

In the JavaScript file, type the following function header. GitHub Copilot will automatically suggest an entire function body in grayed text, as shown below. The exact suggestion may vary.

JavaScript
function calculateDaysBetweenDates(begin, end) {
To accept the suggestion, press Tab.

Seeing alternative suggestions
For any given input, GitHub Copilot may offer multiple suggestions. You can select which suggestion to use, or reject all suggestions.

In Visual Studio Code, create a new JavaScript (*.js) file.

In the JavaScript file, type the following function header. GitHub Copilot will show you a suggestion.

JavaScript
function calculateDaysBetweenDates(begin, end) {
Optionally, you can see alternative suggestions, if any are available.

OS	See next suggestion	See previous suggestion
macOS	Option (⌥) or Alt+]	Option (⌥) or Alt+[
Windows	Alt+]	Alt+[
Linux	Alt+]	Alt+[
Alternatively, you can hover over the suggestion to see the GitHub Copilot command palette for choosing suggestions.

To accept a suggestion, press Tab. To reject all suggestions, press Esc.

Seeing multiple suggestions in a new tab
You may not want any of the initial suggestions GitHub Copilot offers. You can use a keyboard shortcut to prompt GitHub Copilot to show you multiple suggestions in a new tab.

In Visual Studio Code, create a new JavaScript (*.js) file.
In the JavaScript file, type the following function header. GitHub Copilot will show you a suggestion.
JavaScript
function calculateDaysBetweenDates(begin, end) {
To open a new tab with multiple additional options, press Ctrl+Enter.
To accept a suggestion, above the suggestion, click Accept Solution. To reject all suggestions, close the tab.
Generating code suggestions from comments
You can describe something you want to do using natural language within a comment, and GitHub Copilot will suggest the code to accomplish your goal.

In Visual Studio Code, create a new JavaScript (*.js) file.
In the JavaScript file, type the following comment. GitHub Copilot will suggest an implementation of the function.
JavaScript
// find all images without alternate text
// and give them a red border
function process() {
Using a framework
You can also use GitHub Copilot to generate suggestions for APIs and frameworks. The following example uses GitHub Copilot to create a simple Express server that returns the current time.

In Visual Studio Code, create a new JavaScript (*.js) file.
In the JavaScript file, type the following comment and then press Enter. GitHub Copilot will suggest an implementation of the Express app.
JavaScript
// Express server on port 3000
To accept each line, press Tab, then Enter.
Type the following comment and then press Enter. GitHub Copilot will suggest an implementation for the default handler.
JavaScript
// Return the current time
To accept each line, press Tab.
Enabling or disabling GitHub Copilot
You can enable or disable GitHub Copilot from within Visual Studio Code. The GitHub Copilot status icon in the bottom panel of the Visual Studio Code window indicates whether GitHub Copilot is enabled or disabled. When enabled, the background color of the icon will match the color of the status bar. When disabled, the background color of the icon will contrast with the color of the status bar.

To enable or disable GitHub Copilot, click the status icon in the bottom panel of the Visual Studio Code window.

Screenshot of the bottom panel in Visual Studio Code. The GitHub Copilot icon is outlined in dark orange.

If you are disabling GitHub Copilot, you will be asked whether you want to disable suggestions globally, or for the language of the file you are currently editing.

To disable suggestions from GitHub Copilot globally, click Disable Globally.
To disable suggestions from GitHub Copilot for the specified language, click Disable for LANGUAGE.
