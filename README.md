# Stream Deck for Visual Studio Code

Enables Stream Deck integration within Visual Studio Code.

## Features

- Execute any Visual Studio Code command.
- Create and execute terminal commands.

## WIP Features

- Folder switch based on the type of project.
- Support for Stream Deck Multi Actions.

## Getting Started

1. Download _Visual Studio Code & Visual Studio_ on Stream Deck Store.
2. Download _Stream Deck for Visual Studio Code_ on Visual Studio Code marketplace.

## Settings

You can change the IP and port to the message server in:

_%appdata%\Elgato\StreamDeck\Plugins\com.nicollasr.vsstreamdeck.sdPlugin\appsettings.json_

**Don't forget to change it in Visual Studio Code settings or you won't be able to connect and use the available features.**

_I recommend using 127.0.0.1 as your IP address instead of localhost_.

## Getting Commands ID

In Visual Studio Code open _File->Preferences->Keyboard Shortcuts_, find the command you want, right-click it and _Copy Command Id_.
