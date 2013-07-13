# HTML to Haml plugin for Sublime Text 3

Converts files, selection and clipboard content from HTML or ERB to HAML using http://html2haml.heroku.com API

## Installation

### [Sublime Package Control](http://wbond.net/sublime_packages/package_control)

In the command Pallette choose **Package Control: Install Repository** and select **HTML2Haml**

### Git installation

Clone the repository in your Sublime Text "Packages" directory:

    git clone https://github.com/pavelpachkovskij/sublime-html-to-haml.git "HTML2Haml"

The "Packages" directory is located at:

* OS X:

        ~/Library/Application Support/Sublime Text 3/Packages/

* Linux:

        ~/.config/sublime-text-3/Packages/

* Windows:

        %APPDATA%/Sublime Text 3/Packages/

## Usage

* **Convert hole ERB or HTML file** `Shift+Alt+F` - creates new file in the same folder using the same name as the source ending with '.html.haml'.
* **Convert selection** `Shift+Alt+S` - replaces selection of HTML or ERB with HAML content.
* **Convert clipboard content** `Shift+Alt+V` - inserts HAML of converted clipboard HTML or ERB content.

### In Command Palette:

* **HTML2Haml: Convert file**
* **HTML2Haml: Convert selection**
* **HTML2Haml: Convert clipboard content**

## Sublime Text 2

Follow the instruction from [Sublime Text 2 branch](https://github.com/pavelpachkovskij/sublime-html-to-haml/tree/SublimeText2)
