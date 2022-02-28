# Sublime Text 3 - Dark Monokai Theme
Only for those who are using Material Dark theme and still wants to have monokai.

Download the "Monokai theme" file and put it in "Packages/User" directory.

TODO: --
## Extended Settings-

````
{
    "bold_folder_labels": true,
    "caret_extra_width": 1,
    "caret_style": "phase",
    "close_windows_when_empty": false,
    "color_scheme": "Packages/Predawn/predawn.tmTheme",
    "copy_with_empty_selection": false,
    "drag_text": false,
    "draw_minimap_border": true,
    "draw_white_space": "none",
    "enable_tab_scrolling": false,
    "ensure_newline_at_eof_on_save": true,
    "file_exclude_patterns":
    [
        "*.pyc",
        "*.pyo",
        "*.exe",
        "*.dll",
        "*.obj",
        "*.o",
        "*.a",
        "*.lib",
        "*.so",
        "*.dylib",
        "*.ncb",
        "*.sdf",
        "*.suo",
        "*.pdb",
        "*.idb",
        ".DS_Store",
        "*.class",
        "*.psd",
        "*.sublime-workspace"
    ],
    "font_face": "Source Code Pro",
    "font_options":
    [
        "no_round"
    ],
    "font_size": 20,
    "highlight_line": true,
    "highlight_modified_tabs": true,
    "ignored_packages":
    [
        "ActionScript",
        "AppleScript",
        "ASP",
        "D",
        "Diff",
        "Erlang",
        "Graphviz",
        "Groovy",
        "HTML-CSS-JS Prettify",
        "Lisp",
        "Lua",
        "Objective-C",
        "OCaml",
        "Rails",
        "Ruby",
        "Vintage"
    ],
    "installed_packages":[
        "Anaconda",
        "BracketHighlighter",
        "Material Theme",
        "Predawn",
        "SideBarEnhancements"
    ],
    "line_padding_bottom": 1,
    "line_padding_top": 1,
    "match_brackets_content": false,
    "match_selection": false,
    "match_tags": false,
    "material_theme_accent_graphite": true,
    "material_theme_compact_sidebar": true,
    "mini_diff": false,
    "open_files_in_new_window": false,
    "overlay_scroll_bars": "enabled",
    "preview_on_click": false,
    "scroll_past_end": true,
    "scroll_speed": 5.0,
    "show_definitions": false,
    "show_encoding": true,
    "show_errors_inline": false,
    "show_full_path": false,
    "sidebar_default": true,
    "swallow_startup_errors": true,
    "theme": "Material-Theme-Darker.sublime-theme",
    "translate_tabs_to_spaces": true,
    "trim_trailing_white_space_on_save": true,
    "use_simple_full_screen": true,
    "word_wrap": false
}
````
## Settings 
```JavaScript
{
	"always_show_minimap_viewport": true,
	"bold_folder_labels": true,
	"caret_extra_bottom": 2,
	"caret_extra_top": 2,
	"caret_extra_width": 2,
	"caret_style": "phase",
	"color_scheme": "Packages/User/Monokai (SL).tmTheme",
	"drag_text": false,
	"font_face": "INCONSOLATA",
	"font_options":
	[
		"gray_antialias",
		"subpixel_antialias"
	],
	"font_size": 11,
	"highlight_line": true,
	"ignored_packages":
	[
		"Vintage"
	],
	"indent_guide_options":
	[
		"draw_normal",
		"draw_active"
	],
	"line_padding_bottom": 3,
	"line_padding_top": 3,
	"material_theme_accent_scrollbars": true,
	"material_theme_accent_titlebar": true,
	"material_theme_arrow_folders": true,
	"material_theme_bold_tab": true,
	"material_theme_bright_scrollbars": true,
	"material_theme_bullet_tree_indicator": true,
	"material_theme_compact_panel": true,
	"material_theme_compact_sidebar": true,
	"material_theme_contrast_mode": true,
	"material_theme_disable_folder_animation": true,
	"material_theme_disable_tree_indicator": true,
	"material_theme_panel_separator": true,
	"material_theme_small_statusbar": true,
	"material_theme_small_tab": true,
	"material_theme_tabs_autowidth": true,
	"material_theme_tabs_separator": true,
	"material_theme_titlebar": true,
	"overlay_scroll_bars": "enabled",
	"scroll_past_end": true,
	"tab_size": 4,
	"theme": "Material Seti.sublime-theme",
	"trim_trailing_white_space_on_save": true,
	"update_check": false
}


```


## VS Code
````
{
  "editor.minimap.enabled": false,
  "workbench.iconTheme": "vscode-icons",
  "editor.suggestSelection": "first",
  "vsintellicode.modify.editor.suggestSelection": "automaticallyOverrodeDefaultValue",
  "editor.fontFamily": "Fira Code",
  "python.jediEnabled": false,
  "editor.fontSize": 18,
  "workbench.colorTheme": "Monokai",
  "terminal.integrated.fontSize": 16,
  "editor.fontLigatures": true,
  "window.closeWhenEmpty": false,
  "editor.emptySelectionClipboard": false,
  "editor.detectIndentation": false,
  "editor.dragAndDrop": false,
  "editor.renderWhitespace": "none",
  "files.insertFinalNewline": true,
  "editor.selectionHighlight": false,
  "window.openFilesInNewWindow": "off",
  "workbench.editor.enablePreview": false,
  "editor.scrollBeyondLastLine": true,
  "editor.mouseWheelScrollSensitivity": 0.5,
  "window.title": "${activeEditorShort}${separator}${rootName}",
  "files.trimTrailingWhitespace": true,
  "editor.wordWrap": "off",
  "editor.formatOnPaste": true,
  "editor.multiCursorModifier": "ctrlCmd",
  "editor.snippetSuggestions": "top",
  "liveServer.settings.port": 5000,
  "[javascript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[html]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "editor.codeActionsOnSave": {
    "source.fixAll": true
  },
  "editor.defaultFormatter": "esbenp.prettier-vscode",
  "workbench.colorCustomizations": {
    "list.inactiveSelectionBackground": "#636566",
    "sideBar.background": "#141414",
    "sideBar.foreground": "#FFFFFF",
    "sideBarTitle.foreground": "#eeeaea",
    "editor.background": "#141414",
    "editor.foreground": "#FFFFFF",
    "sideBarSectionHeader.background": "#2c3237",
    "sideBarSectionHeader.foreground": "#eeeaea",
    "tab.activeBackground": "#2c3237",
    "tab.inactiveBackground": "#141414",
    "tab.unfocusedActiveForeground": "#eeeaea",
    "scrollbarSlider.activeBackground": "#2c3237",
    "scrollbarSlider.hoverBackground": "#2c3237",
    "badge.background": "#141414",
    "activityBar.border": "#141414",
    "activityBar.background": "#141414",
    // "menu.background": "#16161d",
    // "menu.selectionBackground": "#636566",
    // "menubar.selectionForeground": "#FFF",
    "titleBar.activeBackground": "#141414",
    "titleBar.activeForeground": "#fff",
    "titleBar.inactiveBackground": "#141414",
    "titleBar.inactiveForeground": "#fff",
    "titleBar.border": "#141414",
    "editorGroupHeader.tabsBackground": "#141313", // tabs dark background
    "statusBar.background" : "#1A1A1A",
    "statusBar.noFolderBackground" : "#212121",
    "statusBar.debuggingBackground": "#263238",
  },
  "window.menuBarVisibility": "default",
  "workbench.statusBar.visible": true,
  "workbench.activityBar.visible": true,
  "liveServer.settings.donotShowInfoMsg": true,
  "liveServer.settings.AdvanceCustomBrowserCmdLine": "",
  "terminal.integrated.shell.osx": "/bin/zsh",
  "python.languageServer": "Pylance",
  "git.confirmSync": false,
  "[css]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "scm.alwaysShowRepositories": true,
  //"editor.defaultFormatter": "vscode.configuration-editing",
  "json.schemas": [],
  "notebook.kernelProviderAssociations": [],
  "beautify.config": "",
  "html.format.enable": false,
  "editor.formatOnSaveMode": "modifications",
  "editor.tabSize": 2,
  "files.associations": {
    "*.mdx": "javascriptreact"
  },
  "workbench.editorAssociations": {
    "*.ipynb": "jupyter-notebook"
  },
  "python.pythonPath": "/usr/local/bin/python3",
  "editor.codeLensFontFamily": "Fira Code",
  "editor.inlineHints.fontFamily": "Product Sans",
  "workbench.productIconTheme": "fluent-icons",
  "appService.showSavePrompt": false,
  "showOutput": "never",
  "debug.internalConsoleOptions": "neverOpen",
  // Output panel
  "[Log]": {
    "editor.fontSize": 16,
    "editor.fontFamily": "Fira Code",
    "editor.fontLigatures": true
  },
  "security.workspace.trust.untrustedFiles": "open",
  "workbench.sideBar.location": "right",
  "notebook.cellToolbarLocation": {
    "default": "right",
    "jupyter-notebook": "left"
  },
  "python.defaultInterpreterPath": "/usr/local/bin/python3",
"editor.bracketPairColorization.enabled": true,
"editor.inlineSuggest.enabled": true,
"github.copilot.enable": {
  "*": false,
  "yaml": false,
  "plaintext": false,
  "markdown": false
}
}
````
