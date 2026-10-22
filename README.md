# DLLErstellen

Ein Visual-Studio-Projekt zur Einführung in die Erstellung und Verwendung von Dynamic Link Libraries (DLLs) in der .NET-Programmierung.

## Beschreibung

Das Projekt **DLLErstellen** beschäftigt sich mit den Grundlagen der Entwicklung von DLL-Dateien. Eine Dynamic Link Library ermöglicht es, Funktionen und Klassen in einer separaten Bibliothek bereitzustellen und diese in verschiedenen Anwendungen wiederzuverwenden.

Im Mittelpunkt stehen die Erstellung einer Klassenbibliothek, die Bereitstellung wiederverwendbarer Programmkomponenten und die Einbindung von DLL-Dateien in andere Projekte.

## Funktionen

- Erstellung einer DLL-Datei
- Entwicklung wiederverwendbarer Klassen und Methoden
- Auslagerung von Programmfunktionen in eine Klassenbibliothek
- Bereitstellung von Funktionen für andere Anwendungen
- Einbindung und Verwendung externer DLL-Dateien
- Grundlagen der modularen Softwareentwicklung

## Technologien

- Microsoft Visual Studio
- C# / .NET
- Dynamic Link Library (DLL)
- Visual-Studio-Projektmappe (.sln)

## Installation und Ausführung

1. Repository klonen:

   ```bash
   git clone https://github.com/samad-pour/DLLErstellen.git
   ```

2. Die Datei `DLLErstellen.sln` in Visual Studio öffnen.
3. Das Projekt erstellen.
4. Die erzeugte DLL-Datei im entsprechenden Ausgabeordner (`bin/Debug` oder `bin/Release`) finden.
5. Die DLL bei Bedarf als Referenz in ein anderes .NET-Projekt einbinden.

## Projektstruktur

```text
DLLErstellen/
├── DLLErstellen/          # Projektdateien
├── DLLErstellen.sln       # Visual-Studio-Projektmappe
├── .gitignore
└── .gitattributes
```

## Ziel

Das Projekt dient dem Verständnis der Erstellung und Verwendung von DLL-Dateien in .NET. Dabei werden grundlegende Konzepte der modularen Softwareentwicklung, der Wiederverwendung von Programmcode und der Integration von Klassenbibliotheken in andere Anwendungen kennengelernt.
