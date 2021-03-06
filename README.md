# Markdown checkbox
[![Version](https://vsmarketplacebadge.apphb.com/version/PKief.markdown-checkbox.svg)](https://marketplace.visualstudio.com/items?itemName=PKief.markdown-checkbox)
[![Rating](https://vsmarketplacebadge.apphb.com/rating-short/PKief.markdown-checkbox.svg)](https://marketplace.visualstudio.com/items?itemName=PKief.markdown-checkbox)
[![Installs](https://vsmarketplacebadge.apphb.com/installs/PKief.markdown-checkbox.svg)](https://marketplace.visualstudio.com/items?itemName=PKief.markdown-checkbox)
[![Build Status](https://travis-ci.org/PKief/vscode-material-icon-theme.svg?branch=master)](https://travis-ci.org/PKief/vscode-material-icon-theme)
[![Build status](https://ci.appveyor.com/api/projects/status/n7ot0okpi5fdrm1y?svg=true)](https://ci.appveyor.com/project/PKief/vscode-markdown-checkbox)
  
## Description
With this extension for Visual Studio Code it's possible to create your todo list in markdown. The extension provides shortcuts and some workspace configurations so you can create a checkbox and mark it quickly and smoothly.

## How to use
![Preview](https://raw.githubusercontent.com/PKief/vscode-extension-markdown-checkbox/master/images/preview.gif)

## Information in status bar
![Preview of status bar information](https://raw.githubusercontent.com/PKief/vscode-extension-markdown-checkbox/master/images/statusbar_preview.png)

*You have to create at least one checkbox to see this information.*

## Pick Checkboxes
Toggle all checkboxes in the current document with the Multi-Select QuickPick:

![Preview of Multi-Select QuickPick](images/pick_checkboxes.gif)

The QuickPick can be opened either from the command palette or by clicking on the status bar item.

## Keybindings
Create a checkbox:

> `ctrl`+`shift`+`c` or `⌘⇧c` (Mac)

Toggle checkbox:

> `ctrl`+`shift`+`enter` or `⇧Enter` (Mac)


## Configuration
You can customize this extension with the following options.

> *File -> Preferences -> Workspace Settings*


### Need a bullet point?
Do you need a bullet point before the created checkbox? Select true (*default*) for this:

    options: true | false

```json
"markdown-checkbox.withBulletPoint": true
```
Example:
```
* [ ] todo
```

### Type of bullet points
Select a type of bullet point:

    options: "*" | "-" | "+"
  
```json
"markdown-checkbox.typeOfBulletPoint": "*"
```

Example
```
* [ ] asterisk
- [ ] minus
+ [ ] plus
```

### Italic
Italic font style of line of the checkbox after the checkbox has been checked:

    options: true | false
  
```json
"markdown-checkbox.italicWhenChecked": true
```
Preview
* [X] *this line is italic*

### Strikethrough
Strikethrough the line of the checkbox after the checkbox has been checked:

    options: true | false
  
```json
"markdown-checkbox.strikeThroughWhenChecked": true
```
Preview:
* [X] ~~*this line has been crossed out*~~

### Date when checked
Add date behind the checkbox item after the checkbox has been checked:

    options: true | false
  
```json
"markdown-checkbox.dateWhenChecked": true
```
Preview:
* [X] ~~*sample with date*~~ [2017-11-23]