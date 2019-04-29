# dev-environment
My Dev Environment Setting

## VS Code Extension

<details>
  <summary>show</summary>
  
```json
code --install-extension alefragnani.project-manager
code --install-extension bang.antd-snippets
code --install-extension bradgashler.htmltagwrap
code --install-extension christian-kohler.npm-intellisense
code --install-extension christian-kohler.path-intellisense
code --install-extension cmstead.jsrefactor
code --install-extension cssho.vscode-svgviewer
code --install-extension daixiangyu13.ivue
code --install-extension dariofuzinato.vue-peek
code --install-extension dbaeumer.vscode-eslint
code --install-extension drKnoxy.eslint-disable-snippets
code --install-extension eamodio.gitlens
code --install-extension eg2.vscode-npm-script
code --install-extension esbenp.prettier-vscode
code --install-extension formulahendry.auto-close-tag
code --install-extension formulahendry.auto-rename-tag
code --install-extension HookyQR.beautify
code --install-extension hoovercj.vscode-power-mode
code --install-extension idbartosz.darkpp-italic
code --install-extension ionutvmi.path-autocomplete
code --install-extension k--kato.intellij-idea-keybindings
code --install-extension kisstkondoros.vscode-codemetrics
code --install-extension mrmlnc.vscode-attrs-sorter
code --install-extension MS-CEINTL.vscode-language-pack-ko
code --install-extension mubaidr.vuejs-extension-pack
code --install-extension octref.vetur
code --install-extension PeterJausovec.vscode-docker
code --install-extension sdras.vue-vscode-snippets
code --install-extension shd101wyy.markdown-preview-enhanced
code --install-extension shinnn.stylelint
code --install-extension tombonnike.vscode-status-bar-format-toggle
code --install-extension xabikos.JavaScriptSnippets
code --install-extension Zignd.html-css-class-completion
```

</details>

## VS Code Setting

<details>
  <summary>show</summary>
  
```json
{
    //"files.autoSave": "onFocusChange",
    "files.exclude": {
        "**/.git": true,
        "**/.svn": true,
        "**/.hg": true,
        "**/CVS": true,
        "**/.DS_Store": true,
        "node_modules/**/*": true
    },
    // "editor.formatOnPaste": true,
    // "editor.formatOnSave": true,
    "editor.tabSize": 2,
    "eslint.options": {
        "configFile": ".eslintrc.js"
    },
    "eslint.validate": [{
            "autoFix": true,
            "language": "javascript"
        },
        {
            "autoFix": true,
            "language": "vue"
        },
        {
            "autoFix": true,
            "language": "html"
        },
        {
            "autoFix": true,
            "language": "vue-html"
        }
    ],
    "editor.tabCompletion": "on",
    "editor.fontSize": 16,
    "[yaml]": {
        "editor.insertSpaces": false,
        "editor.tabSize": 2,
        "editor.autoIndent": false
    },
    "eslint.provideLintTask": false,
    "eslint.nodePath": "/usr/local/bin/npm",
    "terminal.integrated.cwd": "",
    "terminal.external.osxExec": "iTerm.app",
    "vetur.validation.template": false,
    "window.openFilesInNewWindow": "on",
    "explorer.confirmDragAndDrop": false,
    "explorer.confirmDelete": false,
    "editor.rulers": [
        100
    ],
    "powermode.shakeIntensity": 0,
    "powermode.maxExplosions": 50,
    "powermode.explosionDuration": 500,
    "powermode.explosionSize": 15,
    "powermode.explosionFrequency": 3,
    // A stylelint configuration object.
    "stylelint.config": null,

    // A partial stylelint config whose properties override the existing ones.
    "stylelint.configOverrides": null,

    // Control whether stylelint is enabled for CSS/SCSS/Less files or not.
    "stylelint.enable": true,
    "[vue]": {},

    // "editor.formatOnPaste": true,
    // "editor.formatOnSave": true,
    // "editor.formatOnType": true,
    "eslint.run": "onSave",
    "prettier.singleQuote": true,
    "window.zoomLevel": 0,
    "editor.renderControlCharacters": false,
    "editor.renderWhitespace": "all",
    "editor.formatOnSave": false,
    "editor.formatOnType": false,
    "window.newWindowDimensions": "maximized",
    "window.openFoldersInNewWindow": "on",
    "workbench.colorTheme": "Dark++ Italic",
    "path-intellisense.extensionOnImport": true,
    "path-autocomplete.extensionOnImport": true,
    "path-autocomplete.pathMappings": {
        "@":"${folder}/src"
    },
    "path-intellisense.mappings": {
        "@":"${folder}/src"
    },
    "vue-peek.targetFileExtensions": [
        ".vue",
        ".js"
    ],
    "vue-peek.supportedLanguages": [
        "vue",
        "javascript"
    ],
    "javascript.updateImportsOnFileMove.enabled": "always",
    "eslint.autoFixOnSave": true,
    "[json]": {
        "editor.defaultFormatter": "vscode.json-language-features"
    }
}
```
</details>

## Slack Dark Theme

<details>
	<summary>show</summary>

`app.asar.unpacked/src/static/ssb-interop.js`

```javascript
document.addEventListener('DOMContentLoaded', function() {
 $.ajax({
   url: 'https://raw.githubusercontent.com/laCour/slack-night-mode/master/css/raw/black.css',
   success: function(css) {
     $("<style></style>").appendTo('head').html(css);
   }
 });
});
```
</details>

## iTerm2

<details>
  <summary>show</summary>

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
<plist version="1.0">
<dict>
	<key>AllowClipboardAccess</key>
	<false/>
	<key>AlternateMouseScroll</key>
	<true/>
	<key>AppleAntiAliasingThreshold</key>
	<integer>1</integer>
	<key>AppleScrollAnimationEnabled</key>
	<integer>0</integer>
	<key>AppleSmoothFixedFontsSizeThreshold</key>
	<integer>1</integer>
	<key>AppleWindowTabbingMode</key>
	<string>manual</string>
	<key>CopyLastNewline</key>
	<false/>
	<key>Default Bookmark Guid</key>
	<string>DA32AF2D-C2C7-445C-9150-822C1CCDE5AE</string>
	<key>FocusFollowsMouse</key>
	<false/>
	<key>HotkeyMigratedFromSingleToMulti</key>
	<true/>
	<key>LoadPrefsFromCustomFolder</key>
	<true/>
	<key>NSFontPanelAttributes</key>
	<string>1, 0</string>
	<key>NSNavLastRootDirectory</key>
	<string>~/Desktop</string>
	<key>NSNavPanelExpandedSizeForOpenMode</key>
	<string>{712, 448}</string>
	<key>NSQuotedKeystrokeBinding</key>
	<string></string>
	<key>NSRepeatCountBinding</key>
	<string></string>
	<key>NSScrollAnimationEnabled</key>
	<false/>
	<key>NSScrollViewShouldScrollUnderTitlebar</key>
	<false/>
	<key>NSTableView Columns KeyBingingTable</key>
	<array>
		<data>
		BAtzdHJlYW10eXBlZIHoA4QBQISEhAhOU1N0cmluZwGEhAhOU09iamVjdACF
		hAErATCG
		</data>
		<string>198</string>
		<data>
		BAtzdHJlYW10eXBlZIHoA4QBQISEhAhOU1N0cmluZwGEhAhOU09iamVjdACF
		hAErATGG
		</data>
		<string>315</string>
	</array>
	<key>NSTableView Columns v2 KeyBingingTable</key>
	<data>
	YnBsaXN0MDDUAQIDBAUGNjdYJHZlcnNpb25YJG9iamVjdHNZJGFyY2hpdmVyVCR0b3AS
	AAGGoK4HCA8aGxwdHh8gJjAxMlUkbnVsbNIJCgsOWk5TLm9iamVjdHNWJGNsYXNzogwN
	gAKACoAN0xAJChEVGVdOUy5rZXlzoxITFIADgASABaMWFxiABoAHgAiACVpJZGVudGlm
	aWVyVVdpZHRoVkhpZGRlblEwI0BowAAAAAAACNIhIiMkWiRjbGFzc25hbWVYJGNsYXNz
	ZXNcTlNEaWN0aW9uYXJ5oiMlWE5TT2JqZWN00xAJCicrGaMSExSAA4AEgAWjLC0YgAuA
	DIAIgAlRMSNAdCGdsi0OVtIhIjM0Xk5TTXV0YWJsZUFycmF5ozM1JVdOU0FycmF5XxAP
	TlNLZXllZEFyY2hpdmVy0Tg5VUFycmF5gAEACAARABoAIwAtADIANwBGAEwAUQBcAGMA
	ZgBoAGoAbABzAHsAfwCBAIMAhQCJAIsAjQCPAJEAnACiAKkAqwC0ALUAugDFAM4A2wDe
	AOcA7gDyAPQA9gD4APwA/gEAAQIBBAEGAQ8BFAEjAScBLwFBAUQBSgAAAAAAAAIBAAAA
	AAAAADoAAAAAAAAAAAAAAAAAAAFM
	</data>
	<key>NSTableView Hidden Columns KeyBingingTable</key>
	<array/>
	<key>NSTableView Sort Ordering KeyBingingTable</key>
	<array/>
	<key>NSTableView Sort Ordering v2 KeyBingingTable</key>
	<data>
	YnBsaXN0MDDUAQIDBAUGFBVYJHZlcnNpb25YJG9iamVjdHNZJGFyY2hpdmVyVCR0b3AS
	AAGGoKMHCA1VJG51bGzSCQoLDFpOUy5vYmplY3RzViRjbGFzc6CAAtIODxARWiRjbGFz
	c25hbWVYJGNsYXNzZXNeTlNNdXRhYmxlQXJyYXmjEBITV05TQXJyYXlYTlNPYmplY3Rf
	EA9OU0tleWVkQXJjaGl2ZXLRFhdVQXJyYXmAAQgRGiMtMjc7QUZRWFlbYGt0g4ePmKqt
	swAAAAAAAAEBAAAAAAAAABgAAAAAAAAAAAAAAAAAAAC1
	</data>
	<key>NSTableView Supports v2 KeyBingingTable</key>
	<true/>
	<key>NSToolbar Configuration com.apple.NSColorPanel</key>
	<dict>
		<key>TB Is Shown</key>
		<integer>1</integer>
	</dict>
	<key>NSWindow Frame NSFontPanel</key>
	<string>514 404 663 367 0 0 1920 1177 </string>
	<key>NSWindow Frame SessionsPreferences</key>
	<string>2253 317 606 469 1440 103 1920 1200 </string>
	<key>NSWindow Frame SharedPreferences</key>
	<string>1634 330 796 474 1440 103 1920 1200 </string>
	<key>NSWindow Frame iTerm Window 0</key>
	<string>1440 103 1920 1173 1440 103 1920 1177 </string>
	<key>NSWindow Frame iTerm Window 1</key>
	<string>359 342 570 377 0 0 1920 1177 </string>
	<key>NSWindow Frame iTerm Window 2</key>
	<string>759 581 570 377 0 0 1920 1177 </string>
	<key>New Bookmarks</key>
	<array>
		<dict>
			<key>ASCII Anti Aliased</key>
			<true/>
			<key>Ambiguous Double Width</key>
			<false/>
			<key>Ansi 0 Color</key>
			<dict>
				<key>Blue Component</key>
				<real>0.0</real>
				<key>Green Component</key>
				<real>0.0</real>
				<key>Red Component</key>
				<real>0.0</real>
			</dict>
			<key>Ansi 1 Color</key>
			<dict>
				<key>Blue Component</key>
				<real>0.0</real>
				<key>Green Component</key>
				<real>0.0</real>
				<key>Red Component</key>
				<real>0.73333334922790527</real>
			</dict>
			<key>Ansi 10 Color</key>
			<dict>
				<key>Blue Component</key>
				<real>0.3333333432674408</real>
				<key>Green Component</key>
				<real>1</real>
				<key>Red Component</key>
				<real>0.3333333432674408</real>
			</dict>
			<key>Ansi 11 Color</key>
			<dict>
				<key>Blue Component</key>
				<real>0.3333333432674408</real>
				<key>Green Component</key>
				<real>1</real>
				<key>Red Component</key>
				<real>1</real>
			</dict>
			<key>Ansi 12 Color</key>
			<dict>
				<key>Blue Component</key>
				<real>1</real>
				<key>Green Component</key>
				<real>0.3333333432674408</real>
				<key>Red Component</key>
				<real>0.3333333432674408</real>
			</dict>
			<key>Ansi 13 Color</key>
			<dict>
				<key>Blue Component</key>
				<real>1</real>
				<key>Green Component</key>
				<real>0.3333333432674408</real>
				<key>Red Component</key>
				<real>1</real>
			</dict>
			<key>Ansi 14 Color</key>
			<dict>
				<key>Blue Component</key>
				<real>1</real>
				<key>Green Component</key>
				<real>1</real>
				<key>Red Component</key>
				<real>0.3333333432674408</real>
			</dict>
			<key>Ansi 15 Color</key>
			<dict>
				<key>Blue Component</key>
				<real>1</real>
				<key>Green Component</key>
				<real>1</real>
				<key>Red Component</key>
				<real>1</real>
			</dict>
			<key>Ansi 2 Color</key>
			<dict>
				<key>Blue Component</key>
				<real>0.0</real>
				<key>Green Component</key>
				<real>0.73333334922790527</real>
				<key>Red Component</key>
				<real>0.0</real>
			</dict>
			<key>Ansi 3 Color</key>
			<dict>
				<key>Blue Component</key>
				<real>0.0</real>
				<key>Green Component</key>
				<real>0.73333334922790527</real>
				<key>Red Component</key>
				<real>0.73333334922790527</real>
			</dict>
			<key>Ansi 4 Color</key>
			<dict>
				<key>Blue Component</key>
				<real>0.73333334922790527</real>
				<key>Green Component</key>
				<real>0.0</real>
				<key>Red Component</key>
				<real>0.0</real>
			</dict>
			<key>Ansi 5 Color</key>
			<dict>
				<key>Blue Component</key>
				<real>0.73333334922790527</real>
				<key>Green Component</key>
				<real>0.0</real>
				<key>Red Component</key>
				<real>0.73333334922790527</real>
			</dict>
			<key>Ansi 6 Color</key>
			<dict>
				<key>Blue Component</key>
				<real>0.73333334922790527</real>
				<key>Green Component</key>
				<real>0.73333334922790527</real>
				<key>Red Component</key>
				<real>0.0</real>
			</dict>
			<key>Ansi 7 Color</key>
			<dict>
				<key>Blue Component</key>
				<real>0.73333334922790527</real>
				<key>Green Component</key>
				<real>0.73333334922790527</real>
				<key>Red Component</key>
				<real>0.73333334922790527</real>
			</dict>
			<key>Ansi 8 Color</key>
			<dict>
				<key>Blue Component</key>
				<real>0.3333333432674408</real>
				<key>Green Component</key>
				<real>0.3333333432674408</real>
				<key>Red Component</key>
				<real>0.3333333432674408</real>
			</dict>
			<key>Ansi 9 Color</key>
			<dict>
				<key>Blue Component</key>
				<real>0.3333333432674408</real>
				<key>Green Component</key>
				<real>0.3333333432674408</real>
				<key>Red Component</key>
				<real>1</real>
			</dict>
			<key>BM Growl</key>
			<true/>
			<key>Background Color</key>
			<dict>
				<key>Blue Component</key>
				<real>0.0</real>
				<key>Green Component</key>
				<real>0.0</real>
				<key>Red Component</key>
				<real>0.0</real>
			</dict>
			<key>Background Image Location</key>
			<string></string>
			<key>Badge Text</key>
			<string></string>
			<key>Blinking Cursor</key>
			<false/>
			<key>Blur</key>
			<false/>
			<key>Bold Color</key>
			<dict>
				<key>Blue Component</key>
				<real>1</real>
				<key>Green Component</key>
				<real>1</real>
				<key>Red Component</key>
				<real>1</real>
			</dict>
			<key>Character Encoding</key>
			<integer>4</integer>
			<key>Close Sessions On End</key>
			<true/>
			<key>Columns</key>
			<integer>80</integer>
			<key>Command</key>
			<string></string>
			<key>Cursor Color</key>
			<dict>
				<key>Blue Component</key>
				<real>0.73333334922790527</real>
				<key>Green Component</key>
				<real>0.73333334922790527</real>
				<key>Red Component</key>
				<real>0.73333334922790527</real>
			</dict>
			<key>Cursor Text Color</key>
			<dict>
				<key>Blue Component</key>
				<real>1</real>
				<key>Green Component</key>
				<real>1</real>
				<key>Red Component</key>
				<real>1</real>
			</dict>
			<key>Custom Command</key>
			<string>No</string>
			<key>Custom Directory</key>
			<string>No</string>
			<key>Default Bookmark</key>
			<string>No</string>
			<key>Description</key>
			<string>Default</string>
			<key>Disable Window Resizing</key>
			<true/>
			<key>Flashing Bell</key>
			<false/>
			<key>Foreground Color</key>
			<dict>
				<key>Blue Component</key>
				<real>0.73333334922790527</real>
				<key>Green Component</key>
				<real>0.73333334922790527</real>
				<key>Red Component</key>
				<real>0.73333334922790527</real>
			</dict>
			<key>Guid</key>
			<string>FFF747E4-FB98-4FC4-BEEE-C914FE2F5B7F</string>
			<key>Horizontal Spacing</key>
			<real>1</real>
			<key>Idle Code</key>
			<integer>0</integer>
			<key>Jobs to Ignore</key>
			<array>
				<string>rlogin</string>
				<string>ssh</string>
				<string>slogin</string>
				<string>telnet</string>
			</array>
			<key>Keyboard Map</key>
			<dict>
				<key>0x2d-0x40000</key>
				<dict>
					<key>Action</key>
					<integer>11</integer>
					<key>Text</key>
					<string>0x1f</string>
				</dict>
				<key>0x32-0x40000</key>
				<dict>
					<key>Action</key>
					<integer>11</integer>
					<key>Text</key>
					<string>0x00</string>
				</dict>
				<key>0x33-0x40000</key>
				<dict>
					<key>Action</key>
					<integer>11</integer>
					<key>Text</key>
					<string>0x1b</string>
				</dict>
				<key>0x34-0x40000</key>
				<dict>
					<key>Action</key>
					<integer>11</integer>
					<key>Text</key>
					<string>0x1c</string>
				</dict>
				<key>0x35-0x40000</key>
				<dict>
					<key>Action</key>
					<integer>11</integer>
					<key>Text</key>
					<string>0x1d</string>
				</dict>
				<key>0x36-0x40000</key>
				<dict>
					<key>Action</key>
					<integer>11</integer>
					<key>Text</key>
					<string>0x1e</string>
				</dict>
				<key>0x37-0x40000</key>
				<dict>
					<key>Action</key>
					<integer>11</integer>
					<key>Text</key>
					<string>0x1f</string>
				</dict>
				<key>0x38-0x40000</key>
				<dict>
					<key>Action</key>
					<integer>11</integer>
					<key>Text</key>
					<string>0x7f</string>
				</dict>
				<key>0xf700-0x220000</key>
				<dict>
					<key>Action</key>
					<integer>10</integer>
					<key>Text</key>
					<string>[1;2A</string>
				</dict>
				<key>0xf700-0x240000</key>
				<dict>
					<key>Action</key>
					<integer>10</integer>
					<key>Text</key>
					<string>[1;5A</string>
				</dict>
				<key>0xf700-0x260000</key>
				<dict>
					<key>Action</key>
					<integer>10</integer>
					<key>Text</key>
					<string>[1;6A</string>
				</dict>
				<key>0xf700-0x280000</key>
				<dict>
					<key>Action</key>
					<integer>11</integer>
					<key>Text</key>
					<string>0x1b 0x1b 0x5b 0x41</string>
				</dict>
				<key>0xf701-0x220000</key>
				<dict>
					<key>Action</key>
					<integer>10</integer>
					<key>Text</key>
					<string>[1;2B</string>
				</dict>
				<key>0xf701-0x240000</key>
				<dict>
					<key>Action</key>
					<integer>10</integer>
					<key>Text</key>
					<string>[1;5B</string>
				</dict>
				<key>0xf701-0x260000</key>
				<dict>
					<key>Action</key>
					<integer>10</integer>
					<key>Text</key>
					<string>[1;6B</string>
				</dict>
				<key>0xf701-0x280000</key>
				<dict>
					<key>Action</key>
					<integer>11</integer>
					<key>Text</key>
					<string>0x1b 0x1b 0x5b 0x42</string>
				</dict>
				<key>0xf702-0x220000</key>
				<dict>
					<key>Action</key>
					<integer>10</integer>
					<key>Text</key>
					<string>[1;2D</string>
				</dict>
				<key>0xf702-0x240000</key>
				<dict>
					<key>Action</key>
					<integer>10</integer>
					<key>Text</key>
					<string>[1;5D</string>
				</dict>
				<key>0xf702-0x260000</key>
				<dict>
					<key>Action</key>
					<integer>10</integer>
					<key>Text</key>
					<string>[1;6D</string>
				</dict>
				<key>0xf702-0x280000</key>
				<dict>
					<key>Action</key>
					<integer>11</integer>
					<key>Text</key>
					<string>0x1b 0x1b 0x5b 0x44</string>
				</dict>
				<key>0xf703-0x220000</key>
				<dict>
					<key>Action</key>
					<integer>10</integer>
					<key>Text</key>
					<string>[1;2C</string>
				</dict>
				<key>0xf703-0x240000</key>
				<dict>
					<key>Action</key>
					<integer>10</integer>
					<key>Text</key>
					<string>[1;5C</string>
				</dict>
				<key>0xf703-0x260000</key>
				<dict>
					<key>Action</key>
					<integer>10</integer>
					<key>Text</key>
					<string>[1;6C</string>
				</dict>
				<key>0xf703-0x280000</key>
				<dict>
					<key>Action</key>
					<integer>11</integer>
					<key>Text</key>
					<string>0x1b 0x1b 0x5b 0x43</string>
				</dict>
				<key>0xf704-0x20000</key>
				<dict>
					<key>Action</key>
					<integer>10</integer>
					<key>Text</key>
					<string>[1;2P</string>
				</dict>
				<key>0xf705-0x20000</key>
				<dict>
					<key>Action</key>
					<integer>10</integer>
					<key>Text</key>
					<string>[1;2Q</string>
				</dict>
				<key>0xf706-0x20000</key>
				<dict>
					<key>Action</key>
					<integer>10</integer>
					<key>Text</key>
					<string>[1;2R</string>
				</dict>
				<key>0xf707-0x20000</key>
				<dict>
					<key>Action</key>
					<integer>10</integer>
					<key>Text</key>
					<string>[1;2S</string>
				</dict>
				<key>0xf708-0x20000</key>
				<dict>
					<key>Action</key>
					<integer>10</integer>
					<key>Text</key>
					<string>[15;2~</string>
				</dict>
				<key>0xf709-0x20000</key>
				<dict>
					<key>Action</key>
					<integer>10</integer>
					<key>Text</key>
					<string>[17;2~</string>
				</dict>
				<key>0xf70a-0x20000</key>
				<dict>
					<key>Action</key>
					<integer>10</integer>
					<key>Text</key>
					<string>[18;2~</string>
				</dict>
				<key>0xf70b-0x20000</key>
				<dict>
					<key>Action</key>
					<integer>10</integer>
					<key>Text</key>
					<string>[19;2~</string>
				</dict>
				<key>0xf70c-0x20000</key>
				<dict>
					<key>Action</key>
					<integer>10</integer>
					<key>Text</key>
					<string>[20;2~</string>
				</dict>
				<key>0xf70d-0x20000</key>
				<dict>
					<key>Action</key>
					<integer>10</integer>
					<key>Text</key>
					<string>[21;2~</string>
				</dict>
				<key>0xf70e-0x20000</key>
				<dict>
					<key>Action</key>
					<integer>10</integer>
					<key>Text</key>
					<string>[23;2~</string>
				</dict>
				<key>0xf70f-0x20000</key>
				<dict>
					<key>Action</key>
					<integer>10</integer>
					<key>Text</key>
					<string>[24;2~</string>
				</dict>
				<key>0xf729-0x20000</key>
				<dict>
					<key>Action</key>
					<integer>10</integer>
					<key>Text</key>
					<string>[1;2H</string>
				</dict>
				<key>0xf729-0x40000</key>
				<dict>
					<key>Action</key>
					<integer>10</integer>
					<key>Text</key>
					<string>[1;5H</string>
				</dict>
				<key>0xf72b-0x20000</key>
				<dict>
					<key>Action</key>
					<integer>10</integer>
					<key>Text</key>
					<string>[1;2F</string>
				</dict>
				<key>0xf72b-0x40000</key>
				<dict>
					<key>Action</key>
					<integer>10</integer>
					<key>Text</key>
					<string>[1;5F</string>
				</dict>
			</dict>
			<key>Mouse Reporting</key>
			<true/>
			<key>Name</key>
			<string>Default</string>
			<key>Non Ascii Font</key>
			<string>Monaco 12</string>
			<key>Non-ASCII Anti Aliased</key>
			<true/>
			<key>Normal Font</key>
			<string>Monaco 12</string>
			<key>Option Key Sends</key>
			<integer>0</integer>
			<key>Prompt Before Closing 2</key>
			<false/>
			<key>Right Option Key Sends</key>
			<integer>0</integer>
			<key>Rows</key>
			<integer>25</integer>
			<key>Screen</key>
			<integer>-1</integer>
			<key>Scrollback Lines</key>
			<integer>1000</integer>
			<key>Selected Text Color</key>
			<dict>
				<key>Blue Component</key>
				<real>0.0</real>
				<key>Green Component</key>
				<real>0.0</real>
				<key>Red Component</key>
				<real>0.0</real>
			</dict>
			<key>Selection Color</key>
			<dict>
				<key>Blue Component</key>
				<real>1</real>
				<key>Green Component</key>
				<real>0.8353000283241272</real>
				<key>Red Component</key>
				<real>0.70980000495910645</real>
			</dict>
			<key>Send Code When Idle</key>
			<false/>
			<key>Shortcut</key>
			<string></string>
			<key>Silence Bell</key>
			<false/>
			<key>Sync Title</key>
			<false/>
			<key>Tags</key>
			<array/>
			<key>Terminal Type</key>
			<string>xterm-256color</string>
			<key>Transparency</key>
			<real>0.0</real>
			<key>Unlimited Scrollback</key>
			<false/>
			<key>Use Bold Font</key>
			<true/>
			<key>Use Bright Bold</key>
			<true/>
			<key>Use Italic Font</key>
			<true/>
			<key>Use Non-ASCII Font</key>
			<false/>
			<key>Vertical Spacing</key>
			<real>1</real>
			<key>Visual Bell</key>
			<true/>
			<key>Window Type</key>
			<integer>0</integer>
			<key>Working Directory</key>
			<string>/Users/Mudin</string>
		</dict>
		<dict>
			<key>ASCII Anti Aliased</key>
			<true/>
			<key>Ambiguous Double Width</key>
			<false/>
			<key>Ansi 0 Color</key>
			<dict>
				<key>Blue Component</key>
				<string>0</string>
				<key>Green Component</key>
				<string>0</string>
				<key>Red Component</key>
				<string>0</string>
			</dict>
			<key>Ansi 1 Color</key>
			<dict>
				<key>Blue Component</key>
				<string>0</string>
				<key>Green Component</key>
				<string>0</string>
				<key>Red Component</key>
				<string>0.8</string>
			</dict>
			<key>Ansi 10 Color</key>
			<dict>
				<key>Blue Component</key>
				<string>0.2039216</string>
				<key>Green Component</key>
				<string>0.8862745</string>
				<key>Red Component</key>
				<string>0.5411764999999999</string>
			</dict>
			<key>Ansi 11 Color</key>
			<dict>
				<key>Blue Component</key>
				<string>0.3098039</string>
				<key>Green Component</key>
				<string>0.9137255</string>
				<key>Red Component</key>
				<string>0.9882353</string>
			</dict>
			<key>Ansi 12 Color</key>
			<dict>
				<key>Blue Component</key>
				<string>0.8117647</string>
				<key>Green Component</key>
				<string>0.6235294</string>
				<key>Red Component</key>
				<string>0.4470588</string>
			</dict>
			<key>Ansi 13 Color</key>
			<dict>
				<key>Blue Component</key>
				<string>0.6588235</string>
				<key>Green Component</key>
				<string>0.4980392</string>
				<key>Red Component</key>
				<string>0.6784314</string>
			</dict>
			<key>Ansi 14 Color</key>
			<dict>
				<key>Blue Component</key>
				<string>0.8862745</string>
				<key>Green Component</key>
				<string>0.8862745</string>
				<key>Red Component</key>
				<string>0.2039216</string>
			</dict>
			<key>Ansi 15 Color</key>
			<dict>
				<key>Blue Component</key>
				<string>0.9254902</string>
				<key>Green Component</key>
				<string>0.9333333</string>
				<key>Red Component</key>
				<string>0.9333333</string>
			</dict>
			<key>Ansi 2 Color</key>
			<dict>
				<key>Blue Component</key>
				<string>0.02352941</string>
				<key>Green Component</key>
				<string>0.6039215999999999</string>
				<key>Red Component</key>
				<string>0.3058824</string>
			</dict>
			<key>Ansi 3 Color</key>
			<dict>
				<key>Blue Component</key>
				<string>0</string>
				<key>Green Component</key>
				<string>0.627451</string>
				<key>Red Component</key>
				<string>0.7686275</string>
			</dict>
			<key>Ansi 4 Color</key>
			<dict>
				<key>Blue Component</key>
				<string>0.6431373</string>
				<key>Green Component</key>
				<string>0.3960784</string>
				<key>Red Component</key>
				<string>0.2039216</string>
			</dict>
			<key>Ansi 5 Color</key>
			<dict>
				<key>Blue Component</key>
				<string>0.4823529</string>
				<key>Green Component</key>
				<string>0.3137255</string>
				<key>Red Component</key>
				<string>0.4588235</string>
			</dict>
			<key>Ansi 6 Color</key>
			<dict>
				<key>Blue Component</key>
				<string>0.6039215999999999</string>
				<key>Green Component</key>
				<string>0.5960785</string>
				<key>Red Component</key>
				<string>0.02352941</string>
			</dict>
			<key>Ansi 7 Color</key>
			<dict>
				<key>Blue Component</key>
				<string>0.8117647</string>
				<key>Green Component</key>
				<string>0.8431373</string>
				<key>Red Component</key>
				<string>0.827451</string>
			</dict>
			<key>Ansi 8 Color</key>
			<dict>
				<key>Blue Component</key>
				<string>0.3254902</string>
				<key>Green Component</key>
				<string>0.3411765</string>
				<key>Red Component</key>
				<string>0.3333333</string>
			</dict>
			<key>Ansi 9 Color</key>
			<dict>
				<key>Blue Component</key>
				<string>0.1607843</string>
				<key>Green Component</key>
				<string>0.1607843</string>
				<key>Red Component</key>
				<string>0.9372549</string>
			</dict>
			<key>Application Keypad Allowed</key>
			<true/>
			<key>BM Growl</key>
			<true/>
			<key>Background Color</key>
			<dict>
				<key>Blue Component</key>
				<string>0</string>
				<key>Green Component</key>
				<string>0</string>
				<key>Red Component</key>
				<string>0</string>
			</dict>
			<key>Background Image Is Tiled</key>
			<false/>
			<key>Badge Color</key>
			<dict>
				<key>Alpha Component</key>
				<real>0.5</real>
				<key>Blue Component</key>
				<real>0.0</real>
				<key>Color Space</key>
				<string>Calibrated</string>
				<key>Green Component</key>
				<real>0.0</real>
				<key>Red Component</key>
				<real>1</real>
			</dict>
			<key>Badge Text</key>
			<string></string>
			<key>Blend</key>
			<real>0.25189052483974367</real>
			<key>Blink Allowed</key>
			<true/>
			<key>Blinking Cursor</key>
			<true/>
			<key>Blur</key>
			<false/>
			<key>Blur Radius</key>
			<real>3.303137812377976</real>
			<key>Bold Color</key>
			<dict>
				<key>Blue Component</key>
				<string>1</string>
				<key>Green Component</key>
				<string>1</string>
				<key>Red Component</key>
				<string>1</string>
			</dict>
			<key>Bound Hosts</key>
			<array/>
			<key>Character Encoding</key>
			<integer>4</integer>
			<key>Close Sessions On End</key>
			<true/>
			<key>Columns</key>
			<integer>80</integer>
			<key>Command</key>
			<string></string>
			<key>Cursor Color</key>
			<dict>
				<key>Blue Component</key>
				<string>1</string>
				<key>Green Component</key>
				<string>1</string>
				<key>Red Component</key>
				<string>1</string>
			</dict>
			<key>Cursor Guide Color</key>
			<dict>
				<key>Alpha Component</key>
				<real>0.25</real>
				<key>Blue Component</key>
				<real>1</real>
				<key>Color Space</key>
				<string>Calibrated</string>
				<key>Green Component</key>
				<real>0.91000000000000003</real>
				<key>Red Component</key>
				<real>0.65000000000000002</real>
			</dict>
			<key>Cursor Text Color</key>
			<dict>
				<key>Blue Component</key>
				<string>0</string>
				<key>Green Component</key>
				<string>0</string>
				<key>Red Component</key>
				<string>0</string>
			</dict>
			<key>Cursor Type</key>
			<integer>2</integer>
			<key>Custom Command</key>
			<string>No</string>
			<key>Custom Directory</key>
			<string>Recycle</string>
			<key>Default Bookmark</key>
			<string>No</string>
			<key>Description</key>
			<string>Default</string>
			<key>Disable Window Resizing</key>
			<true/>
			<key>Flashing Bell</key>
			<false/>
			<key>Foreground Color</key>
			<dict>
				<key>Alpha Component</key>
				<real>1</real>
				<key>Blue Component</key>
				<real>0.17254901960784313</real>
				<key>Color Space</key>
				<string>Calibrated</string>
				<key>Green Component</key>
				<real>0.96862745098039216</real>
				<key>Red Component</key>
				<real>0.0</real>
			</dict>
			<key>Guid</key>
			<string>DA32AF2D-C2C7-445C-9150-822C1CCDE5AE</string>
			<key>Horizontal Spacing</key>
			<real>0.90471220820783127</real>
			<key>Idle Code</key>
			<integer>0</integer>
			<key>Jobs to Ignore</key>
			<array>
				<string>rlogin</string>
				<string>ssh</string>
				<string>slogin</string>
				<string>telnet</string>
			</array>
			<key>Keyboard Map</key>
			<dict>
				<key>0x2d-0x40000</key>
				<dict>
					<key>Action</key>
					<integer>11</integer>
					<key>Text</key>
					<string>0x1f</string>
				</dict>
				<key>0x32-0x40000</key>
				<dict>
					<key>Action</key>
					<integer>11</integer>
					<key>Text</key>
					<string>0x00</string>
				</dict>
				<key>0x33-0x40000</key>
				<dict>
					<key>Action</key>
					<integer>11</integer>
					<key>Text</key>
					<string>0x1b</string>
				</dict>
				<key>0x34-0x40000</key>
				<dict>
					<key>Action</key>
					<integer>11</integer>
					<key>Text</key>
					<string>0x1c</string>
				</dict>
				<key>0x35-0x40000</key>
				<dict>
					<key>Action</key>
					<integer>11</integer>
					<key>Text</key>
					<string>0x1d</string>
				</dict>
				<key>0x36-0x40000</key>
				<dict>
					<key>Action</key>
					<integer>11</integer>
					<key>Text</key>
					<string>0x1e</string>
				</dict>
				<key>0x37-0x40000</key>
				<dict>
					<key>Action</key>
					<integer>11</integer>
					<key>Text</key>
					<string>0x1f</string>
				</dict>
				<key>0x38-0x40000</key>
				<dict>
					<key>Action</key>
					<integer>11</integer>
					<key>Text</key>
					<string>0x7f</string>
				</dict>
				<key>0x7f-0x100000</key>
				<dict>
					<key>Action</key>
					<integer>11</integer>
					<key>Text</key>
					<string>0x15</string>
				</dict>
				<key>0xf700-0x220000</key>
				<dict>
					<key>Action</key>
					<integer>47</integer>
					<key>Text</key>
					<string>2</string>
				</dict>
				<key>0xf700-0x240000</key>
				<dict>
					<key>Action</key>
					<integer>10</integer>
					<key>Text</key>
					<string>[1;5A</string>
				</dict>
				<key>0xf700-0x260000</key>
				<dict>
					<key>Action</key>
					<integer>10</integer>
					<key>Text</key>
					<string>[1;6A</string>
				</dict>
				<key>0xf700-0x280000</key>
				<dict>
					<key>Action</key>
					<integer>11</integer>
					<key>Text</key>
					<string>0x1b 0x1b 0x5b 0x41</string>
				</dict>
				<key>0xf701-0x220000</key>
				<dict>
					<key>Action</key>
					<integer>46</integer>
					<key>Text</key>
					<string>2</string>
				</dict>
				<key>0xf701-0x240000</key>
				<dict>
					<key>Action</key>
					<integer>10</integer>
					<key>Text</key>
					<string>[1;5B</string>
				</dict>
				<key>0xf701-0x260000</key>
				<dict>
					<key>Action</key>
					<integer>10</integer>
					<key>Text</key>
					<string>[1;6B</string>
				</dict>
				<key>0xf701-0x280000</key>
				<dict>
					<key>Action</key>
					<integer>11</integer>
					<key>Text</key>
					<string>0x1b 0x1b 0x5b 0x42</string>
				</dict>
				<key>0xf702-0x220000</key>
				<dict>
					<key>Action</key>
					<integer>47</integer>
					<key>Text</key>
					<string>0</string>
				</dict>
				<key>0xf702-0x240000</key>
				<dict>
					<key>Action</key>
					<integer>10</integer>
					<key>Text</key>
					<string>[1;5D</string>
				</dict>
				<key>0xf702-0x260000</key>
				<dict>
					<key>Action</key>
					<integer>10</integer>
					<key>Text</key>
					<string>[1;6D</string>
				</dict>
				<key>0xf702-0x280000</key>
				<dict>
					<key>Action</key>
					<integer>10</integer>
					<key>Text</key>
					<string>b</string>
				</dict>
				<key>0xf702-0x2a0000</key>
				<dict>
					<key>Action</key>
					<integer>47</integer>
					<key>Text</key>
					<string>1</string>
				</dict>
				<key>0xf702-0x300000</key>
				<dict>
					<key>Action</key>
					<integer>11</integer>
					<key>Text</key>
					<string>0x01</string>
				</dict>
				<key>0xf702-0x320000</key>
				<dict>
					<key>Action</key>
					<integer>2</integer>
					<key>Text</key>
					<string></string>
				</dict>
				<key>0xf703-0x220000</key>
				<dict>
					<key>Action</key>
					<integer>46</integer>
					<key>Text</key>
					<string>0</string>
				</dict>
				<key>0xf703-0x240000</key>
				<dict>
					<key>Action</key>
					<integer>10</integer>
					<key>Text</key>
					<string>[1;5C</string>
				</dict>
				<key>0xf703-0x260000</key>
				<dict>
					<key>Action</key>
					<integer>10</integer>
					<key>Text</key>
					<string>[1;6C</string>
				</dict>
				<key>0xf703-0x280000</key>
				<dict>
					<key>Action</key>
					<integer>10</integer>
					<key>Text</key>
					<string>f</string>
				</dict>
				<key>0xf703-0x2a0000</key>
				<dict>
					<key>Action</key>
					<integer>46</integer>
					<key>Text</key>
					<string>1</string>
				</dict>
				<key>0xf703-0x300000</key>
				<dict>
					<key>Action</key>
					<integer>11</integer>
					<key>Text</key>
					<string>0x05</string>
				</dict>
				<key>0xf703-0x320000</key>
				<dict>
					<key>Action</key>
					<integer>0</integer>
					<key>Text</key>
					<string></string>
				</dict>
				<key>0xf704-0x20000</key>
				<dict>
					<key>Action</key>
					<integer>10</integer>
					<key>Text</key>
					<string>[1;2P</string>
				</dict>
				<key>0xf705-0x20000</key>
				<dict>
					<key>Action</key>
					<integer>10</integer>
					<key>Text</key>
					<string>[1;2Q</string>
				</dict>
				<key>0xf706-0x20000</key>
				<dict>
					<key>Action</key>
					<integer>10</integer>
					<key>Text</key>
					<string>[1;2R</string>
				</dict>
				<key>0xf707-0x20000</key>
				<dict>
					<key>Action</key>
					<integer>10</integer>
					<key>Text</key>
					<string>[1;2S</string>
				</dict>
				<key>0xf708-0x20000</key>
				<dict>
					<key>Action</key>
					<integer>10</integer>
					<key>Text</key>
					<string>[15;2~</string>
				</dict>
				<key>0xf709-0x20000</key>
				<dict>
					<key>Action</key>
					<integer>10</integer>
					<key>Text</key>
					<string>[17;2~</string>
				</dict>
				<key>0xf70a-0x20000</key>
				<dict>
					<key>Action</key>
					<integer>10</integer>
					<key>Text</key>
					<string>[18;2~</string>
				</dict>
				<key>0xf70b-0x20000</key>
				<dict>
					<key>Action</key>
					<integer>10</integer>
					<key>Text</key>
					<string>[19;2~</string>
				</dict>
				<key>0xf70c-0x20000</key>
				<dict>
					<key>Action</key>
					<integer>10</integer>
					<key>Text</key>
					<string>[20;2~</string>
				</dict>
				<key>0xf70d-0x20000</key>
				<dict>
					<key>Action</key>
					<integer>10</integer>
					<key>Text</key>
					<string>[21;2~</string>
				</dict>
				<key>0xf70e-0x20000</key>
				<dict>
					<key>Action</key>
					<integer>10</integer>
					<key>Text</key>
					<string>[23;2~</string>
				</dict>
				<key>0xf70f-0x20000</key>
				<dict>
					<key>Action</key>
					<integer>10</integer>
					<key>Text</key>
					<string>[24;2~</string>
				</dict>
				<key>0xf729-0x20000</key>
				<dict>
					<key>Action</key>
					<integer>47</integer>
					<key>Text</key>
					<string>3</string>
				</dict>
				<key>0xf729-0x40000</key>
				<dict>
					<key>Action</key>
					<integer>10</integer>
					<key>Text</key>
					<string>[1;5H</string>
				</dict>
				<key>0xf72b-0x20000</key>
				<dict>
					<key>Action</key>
					<integer>46</integer>
					<key>Text</key>
					<string>2</string>
				</dict>
				<key>0xf72b-0x40000</key>
				<dict>
					<key>Action</key>
					<integer>10</integer>
					<key>Text</key>
					<string>[1;5F</string>
				</dict>
			</dict>
			<key>Link Color</key>
			<dict>
				<key>Alpha Component</key>
				<real>1</real>
				<key>Blue Component</key>
				<real>0.67800000000000005</real>
				<key>Color Space</key>
				<string>Calibrated</string>
				<key>Green Component</key>
				<real>0.27000000000000002</real>
				<key>Red Component</key>
				<real>0.023</real>
			</dict>
			<key>Minimum Contrast</key>
			<real>0.0</real>
			<key>Mouse Reporting</key>
			<true/>
			<key>Name</key>
			<string>jeong</string>
			<key>Non Ascii Font</key>
			<string>Monaco 12</string>
			<key>Non-ASCII Anti Aliased</key>
			<true/>
			<key>Normal Font</key>
			<string>AndaleMono 14</string>
			<key>Option Key Sends</key>
			<integer>2</integer>
			<key>Prompt Before Closing 2</key>
			<false/>
			<key>Right Option Key Sends</key>
			<integer>2</integer>
			<key>Rows</key>
			<integer>25</integer>
			<key>Screen</key>
			<integer>-1</integer>
			<key>Scrollback Lines</key>
			<integer>1000</integer>
			<key>Scrollback With Status Bar</key>
			<true/>
			<key>Scrollback in Alternate Screen</key>
			<true/>
			<key>Selected Text Color</key>
			<dict>
				<key>Alpha Component</key>
				<real>1</real>
				<key>Blue Component</key>
				<real>0.17224940657615662</real>
				<key>Color Space</key>
				<string>Calibrated</string>
				<key>Green Component</key>
				<real>0.96817153692245483</real>
				<key>Red Component</key>
				<real>0.12705568969249725</real>
			</dict>
			<key>Selection Color</key>
			<dict>
				<key>Alpha Component</key>
				<real>1</real>
				<key>Blue Component</key>
				<real>0.67799997329999995</real>
				<key>Color Space</key>
				<string>Calibrated</string>
				<key>Green Component</key>
				<real>0.27000001070000001</real>
				<key>Red Component</key>
				<real>0.023000000039999999</real>
			</dict>
			<key>Send Code When Idle</key>
			<false/>
			<key>Shortcut</key>
			<string></string>
			<key>Silence Bell</key>
			<false/>
			<key>Smart Cursor Color</key>
			<true/>
			<key>Sync Title</key>
			<false/>
			<key>Tab Color</key>
			<dict>
				<key>Alpha Component</key>
				<real>1</real>
				<key>Blue Component</key>
				<real>0.99449777603149414</real>
				<key>Color Space</key>
				<string>Calibrated</string>
				<key>Green Component</key>
				<real>1</real>
				<key>Red Component</key>
				<real>1</real>
			</dict>
			<key>Tags</key>
			<array/>
			<key>Terminal Type</key>
			<string>xterm-256color</string>
			<key>Thin Strokes</key>
			<integer>2</integer>
			<key>Transparency</key>
			<real>0.094526838411978509</real>
			<key>Unlimited Scrollback</key>
			<false/>
			<key>Use Bold Font</key>
			<true/>
			<key>Use Bright Bold</key>
			<true/>
			<key>Use HFS Plus Mapping</key>
			<true/>
			<key>Use Italic Font</key>
			<true/>
			<key>Use Non-ASCII Font</key>
			<true/>
			<key>Use Tab Color</key>
			<true/>
			<key>Vertical Spacing</key>
			<real>1.3036462255271082</real>
			<key>Visual Bell</key>
			<true/>
			<key>Window Type</key>
			<integer>0</integer>
			<key>Working Directory</key>
			<string>/Users/jeong</string>
		</dict>
	</array>
	<key>NoSyncConfirmBeta</key>
	<true/>
	<key>NoSyncHaveWarnedAboutPasteConfirmationChange</key>
	<true/>
	<key>NoSyncInstallationId</key>
	<string>C79F937A-22C6-4ADC-AEEA-A4B50A6EF742</string>
	<key>NoSyncPermissionToShowTip</key>
	<false/>
	<key>NoSyncSuppressBroadcastInputWarning</key>
	<true/>
	<key>NoSyncSuppressBroadcastInputWarning_selection</key>
	<integer>0</integer>
	<key>NoSyncSuppressMissingProfileInArrangementWarning</key>
	<true/>
	<key>NoSyncTimeOfFirstLaunchOfVersionWithTip</key>
	<real>522117974.90532398</real>
	<key>PointerActions</key>
	<dict>
		<key>Button,1,1,,</key>
		<dict>
			<key>Action</key>
			<string>kContextMenuPointerAction</string>
		</dict>
		<key>Button,2,1,,</key>
		<dict>
			<key>Action</key>
			<string>kPasteFromSelectionPointerAction</string>
		</dict>
		<key>Gesture,ThreeFingerSwipeDown,,</key>
		<dict>
			<key>Action</key>
			<string>kPrevWindowPointerAction</string>
		</dict>
		<key>Gesture,ThreeFingerSwipeLeft,,</key>
		<dict>
			<key>Action</key>
			<string>kPrevTabPointerAction</string>
		</dict>
		<key>Gesture,ThreeFingerSwipeRight,,</key>
		<dict>
			<key>Action</key>
			<string>kNextTabPointerAction</string>
		</dict>
		<key>Gesture,ThreeFingerSwipeUp,,</key>
		<dict>
			<key>Action</key>
			<string>kNextWindowPointerAction</string>
		</dict>
	</dict>
	<key>PrefsCustomFolder</key>
	<string>/Users/jeong/Desktop</string>
	<key>PromptOnQuit</key>
	<false/>
	<key>QuitWhenAllWindowsClosed</key>
	<true/>
	<key>SUEnableAutomaticChecks</key>
	<false/>
	<key>SUFeedAlternateAppNameKey</key>
	<string>iTerm</string>
	<key>SUFeedURL</key>
	<string>https://iterm2.com/appcasts/final.xml?shard=94</string>
	<key>SUHasLaunchedBefore</key>
	<true/>
	<key>SUSendProfileInfo</key>
	<false/>
	<key>ShowFullScreenTabBar</key>
	<true/>
	<key>SwitchPaneModifier</key>
	<integer>5</integer>
	<key>SwitchWindowModifier</key>
	<integer>6</integer>
	<key>TabStyle</key>
	<integer>3</integer>
	<key>WordCharacters</key>
	<string>/-+\~_.</string>
	<key>iTerm Version</key>
	<string>3.1.5</string>
	<key>kCPKSelectionViewPreferredModeKey</key>
	<integer>7</integer>
	<key>kCPKSelectionViewShowHSBTextFieldsKey</key>
	<false/>
</dict>
</plist>
```

</details>
