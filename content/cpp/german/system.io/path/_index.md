---
title: Path
second_title: Aspose.Slides für C++ API-Referenz
description: Stellt Methoden zum Manipulieren von Pfaden bereit. Dies ist ein statischer Typ ohne Instanzdienste. Sie sollten niemals Instanzen davon auf irgendeine Weise erstellen.
type: docs
weight: 339
url: /de/system.io/path/
---
## Path Klasse

Stellt Methoden zum Manipulieren von Pfaden bereit. Dies ist ein statischer Typ ohne Instanzdienste. Sie sollten niemals Instanzen davon auf irgendeine Weise erstellen.

```cpp
class Path
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| static [String](../../system/string/) [ChangeExtension](./changeextension/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Ändert die Erweiterung im angegebenen Dateipfad. |
| static void [CheckPath](./checkpath/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, **bool**) | Bestimmt, ob der angegebene Pfad gültig ist, indem geprüft wird, ob er ungültige Zeichen enthält. Eine Ausnahme wird ausgelöst, wenn der Pfad ungültige Zeichen enthält. |
| static [String](../../system/string/) [Combine](./combine/)(const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | Kombiniert die angegebenen Pfadsegmente zu einem einzigen Pfad und fügt bei Bedarf Trennzeichen für Verzeichnisse zwischen den Segmenten ein. |
| static [String](../../system/string/) [Combine](./combine/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Kombiniert zwei angegebene Pfadsegmente zu einem einzigen Pfad und fügt bei Bedarf ein Trennzeichen für Verzeichnisse zwischen den Segmenten ein. |
| static [String](../../system/string/) [Combine](./combine/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Kombiniert drei angegebene Pfadsegmente zu einem einzigen Pfad und fügt bei Bedarf Trennzeichen für Verzeichnisse zwischen den Segmenten ein. |
| static [String](../../system/string/) [Combine](./combine/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Kombiniert vier angegebene Pfadsegmente zu einem einzigen Pfad und fügt bei Bedarf Trennzeichen für Verzeichnisse zwischen den Segmenten ein. |
| static [String](../../system/string/) [GetDirectoryName](./getdirectoryname/)(const [String](../../system/string/)\&) | Gibt den Namen des Verzeichnisses zurück, auf das der angegebene Pfad verweist. |
| static [String](../../system/string/) [GetExtension](./getextension/)(const [String](../../system/string/)\&) | Gibt die Erweiterung der Datei zurück, auf die der angegebene Pfad verweist. |
| static [String](../../system/string/) [GetFileName](./getfilename/)(const [String](../../system/string/)\&) | Gibt den Namen der Datei zurück, auf die der angegebene Pfad verweist. |
| static [String](../../system/string/) [GetFileNameWithoutExtension](./getfilenamewithoutextension/)(const [String](../../system/string/)\&) | Gibt den Namen ohne Erweiterung der Datei zurück, auf die der angegebene Pfad verweist. |
| static [String](../../system/string/) [GetFullPath](./getfullpath/)(const [String](../../system/string/)\&) | Konvertiert den angegebenen Pfad in einen absoluten Pfad. |
| static [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetInvalidFileNameChars](./getinvalidfilenamechars/)() | Gibt ein Array zurück, das Zeichen enthält, die in Dateinamen nicht zulässig sind. |
| static [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetInvalidPathChars](./getinvalidpathchars/)() | Gibt ein Array zurück, das Zeichen enthält, die in Pfadnamen nicht zulässig sind. |
| static [String](../../system/string/) [GetPathRoot](./getpathroot/)(const [String](../../system/string/)\&) | Gibt das Stammverzeichnis des angegebenen Pfads zurück. |
| static [String](../../system/string/) [GetRandomFileName](./getrandomfilename/)() | Gibt einen zufällig generierten Dateinamen zurück. |
| static [String](../../system/string/) [GetTempFileName_](./gettempfilename_/)() | Erstellt eine neue Datei mit einem eindeutigen Namen und gibt den vollständigen Pfad dazu zurück. |
| static [String](../../system/string/) [GetTempFileNameSafe](./gettempfilenamesafe/)() | Erstellt eine neue Datei mit einem eindeutigen Namen und gibt den vollständigen Pfad dazu zurück. Ist ein Synonym der Methode [GetTempFileName_()](./gettempfilename_/). |
| static [String](../../system/string/) [GetTempPath](./gettemppath/)() | Gibt den Pfad des temporären Verzeichnisses des aktuellen Benutzers zurück. |
| static **bool** [HasExtension](./hasextension/)(const [String](../../system/string/)\&) | Bestimmt, ob der angegebene Pfad auf eine Datei mit Erweiterung verweist. |
| static **bool** [IsPathRooted](./ispathrooted/)(const [String](../../system/string/)\&) | Bestimmt, ob der angegebene Pfad eine Wurzel enthält. |
| static [String](../../system/string/) [NormalizePath](./normalizepath/)(const [String](../../system/string/)\&) | Normalisiert den angegebenen Pfad. |
| static boost::filesystem::path [ToBoost](./toboost/)(const [String](../../system/string/)\&) | Gibt eine Instanz der Klasse boost::filesystem::path zurück, die den angegebenen Pfad darstellt. |
| static [String](../../system/string/) [ToString](./tostring/)(const boost::filesystem::path\&) | Gibt eine Zeichenkettenrepräsentation des angegebenen Boost-Pfadobjekts zurück. |

## Felder

| Feld | Beschreibung |
| --- | --- |
| static [AltDirectorySeparatorChar](./altdirectoryseparatorchar/) | Ein alternatives Zeichen, das verwendet wird, um Verzeichnisebenen in einem Pfad zu trennen. |
| static [DirectorySeparatorChar](./directoryseparatorchar/) | Ein Zeichen, das verwendet wird, um Verzeichnisebenen in einem Pfad zu trennen. |
| static [PathSeparator](./pathseparator/) | Ein Trennzeichen, das verwendet wird, um Pfadzeichenketten in Umgebungsvariablen zu trennen. |
| static [VolumeSeparatorChar](./volumeseparatorchar/) | Ein Laufwerks-Trennzeichen. |

## Anmerkungen



```cpp
#include "system/io/path.h"
#include <iostream>

int main()
{
  using namespace System::IO;

  // Erzeugt einen zufälligen Dateinamen.
  auto filename = Path::GetRandomFileName();

  // Gibt Informationen über den Dateinamen aus.
  std::cout <<
    "Filename: " << Path::GetFileName(filename) << std::endl <<
    "Filename w/o an extension: " << Path::GetFileNameWithoutExtension(filename) << std::endl <<
    "Extension: " << Path::GetExtension(filename) << std::endl;

  return 0;
}
/*
Dieses Codebeispiel erzeugt die folgende Ausgabe:
Dateiname: qhuzkyqv.y6p
Dateiname ohne Erweiterung: qhuzkyqv
Erweiterung: .y6p
*/
```

## Siehe auch

* Namensraum [System::IO](../)
* Bibliothek [Aspose.Slides](../../)