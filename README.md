# Unreal Engine Linter Plugin

This Unreal Engine plugin is a modified version of the Gamemakin Linter plugin, originally created by [Allar](https://github.com/Allar). 

## Notice
Please note that I do not provide support for this plugin.

## Installation Instructions

1. **Download the Plugin:**
   - Go to the [releases](https://github.com/viniciushelder/UE5-Linter/releases) (coming soon) section of this repository.
   - Select the correct version and download the zip file named "Linter 5.x".

2. **Extract the Plugin:**
   - Once downloaded, extract the contents of the zip file.

3. **Install the Plugin:**
   - Navigate to your Unreal Engine project directory.
   - Locate the `Plugins` directory within your project directory (if it doesn't exist, create it).
   - Copy the extracted `Linter` folder into your project's `Plugins` directory.
   - Your folder structure should look like this:
     ```
     YourGameProject/
     ├── YourGame.uproject
     ├── Plugins/
     │   └── Linter/
     │       ├── ...
     │       └── (plugin files)
     └── ...
     ```

4. **Generate Visual Studio Project Files:**
   - Right-click on your `YourGame.uproject` file.
   - Select "Generate Visual Studio Project Files" from the context menu.
   - This step is necessary for compiling the plugin with your project.

5. **Start Your Project:**
   - After generating Visual Studio project files, open your Unreal Engine project.
   - You can now start using the Linter plugin within your project.

## License
This project is licensed under the [MIT License](LICENSE).
