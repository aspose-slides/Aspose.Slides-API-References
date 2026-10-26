---
title: Directory
second_title: Aspose.Slides für C++ API-Referenz
description: Enthält Methoden zur Manipulation von Verzeichnissen. Dies ist ein statischer Typ ohne Instanzdienste. Sie sollten niemals Instanzen davon auf irgendeine Weise erstellen.
type: docs
weight: 235
url: /de/system.io/directory/
---

## Directory Klasse

Enthält Methoden zur Manipulation von Verzeichnissen. Dies ist ein statischer Typ ohne Instanzdienste. Sie sollten niemals Instanzen davon auf irgendeine Weise erstellen.

```cpp
class Directory
```

## Methoden

| Method | Beschreibung |
| --- | --- |
| static void [CreateDirectory_](./createdirectory_/)(const [String](../../system/string/)\&) | Erstellt alle Verzeichnisse im angegebenen Pfad, falls diese nicht existieren. |
| static void [Delete](./delete/)(const [String](../../system/string/)\&, **bool**) | Entfernt die angegebene Datei oder das Verzeichnis. Wirft keine Ausnahme. |
| static [StringEnumerablePtr](./stringenumerableptr/) [EnumerateDirectories](./enumeratedirectories/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Durchsucht die Verzeichnisse, die die angegebenen Suchkriterien erfüllen, entweder im angegebenen Verzeichnis oder im gesamten Verzeichnisbaum, der im angegebenen Verzeichnis verwurzelt ist. |
| static [StringEnumerablePtr](./stringenumerableptr/) [EnumerateFiles](./enumeratefiles/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Durchsucht die Dateien, die die angegebenen Suchkriterien erfüllen, entweder im angegebenen Verzeichnis oder im gesamten Verzeichnisbaum, der im angegebenen Verzeichnis verwurzelt ist. |
| static [StringEnumerablePtr](./stringenumerableptr/) [EnumerateFileSystemEntries](./enumeratefilesystementries/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Durchsucht die Dateien und Verzeichnisse, die die angegebenen Suchkriterien erfüllen, entweder im angegebenen Verzeichnis oder im gesamten Verzeichnisbaum, der im angegebenen Verzeichnis verwurzelt ist. |
| static **bool** [Exists](./exists/)(const [String](../../system/string/)\&) | Bestimmt, ob der angegebene Pfad auf ein vorhandenes Verzeichnis verweist. |
| static [DateTime](../../system/datetime/) [GetCreationTime](./getcreationtime/)(const [String](../../system/string/)\&) | Gibt die Erstellungszeit der angegebenen Entität als Ortszeit zurück. |
| static [DateTime](../../system/datetime/) [GetCreationTimeUtc](./getcreationtimeutc/)(const [String](../../system/string/)\&) | Gibt die Erstellungszeit der angegebenen Entität als UTC-Zeit zurück. |
| static [String](../../system/string/) [GetCurrentDirectory](./getcurrentdirectory/)() | Gibt den vollständigen Namen (einschließlich Pfad) des aktuellen Verzeichnisses zurück. |
| static [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [GetDirectories](./getdirectories/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Durchsucht die Verzeichnisse, die die angegebenen Suchkriterien erfüllen, entweder im angegebenen Verzeichnis oder im gesamten Verzeichnisbaum, der im angegebenen Verzeichnis verwurzelt ist. |
| static [String](../../system/string/) [GetDirectoryRoot](./getdirectoryroot/)(const [String](../../system/string/)\&) | Gibt das Stammverzeichnis des angegebenen Pfads zurück. |
| static [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [GetFiles](./getfiles/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Durchsucht die Dateien, die die angegebenen Suchkriterien erfüllen, entweder im angegebenen Verzeichnis oder im gesamten Verzeichnisbaum, der im angegebenen Verzeichnis verwurzelt ist. |
| static [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [GetFileSystemEntries](./getfilesystementries/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Durchsucht die Dateien und Verzeichnisse, die die angegebenen Suchkriterien erfüllen, entweder im angegebenen Verzeichnis oder im gesamten Verzeichnisbaum, der im angegebenen Verzeichnis verwurzelt ist. |
| static [DateTime](../../system/datetime/) [GetLastAccessTime](./getlastaccesstime/)(const [String](../../system/string/)\&) | Gibt die letzte Zugriffszeit der angegebenen Entität als Ortszeit zurück. |
| static [DateTime](../../system/datetime/) [GetLastAccessTimeUtc](./getlastaccesstimeutc/)(const [String](../../system/string/)\&) | Gibt die letzte Zugriffszeit der angegebenen Entität als UTC-Zeit zurück. |
| static [DateTime](../../system/datetime/) [GetLastWriteTime](./getlastwritetime/)(const [String](../../system/string/)\&) | Gibt die letzte Schreibzeit der angegebenen Entität als Ortszeit zurück. |
| static [DateTime](../../system/datetime/) [GetLastWriteTimeUtc](./getlastwritetimeutc/)(const [String](../../system/string/)\&) | Gibt die letzte Schreibzeit der angegebenen Entität als UTC-Zeit zurück. |
| static [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [GetLogicalDrives](./getlogicaldrives/)() | NICHT IMPLEMENTIERT. |
| static [DirectoryInfoPtr](../../system/directoryinfoptr/) [GetParent](./getparent/)(const [String](../../system/string/)\&) | Gibt einen Shared-Pointer auf das [DirectoryInfo](../directoryinfo/)-Objekt zurück, das das übergeordnete Verzeichnis der angegebenen Entität darstellt. |
| static void [Move](./move/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Verschiebt die angegebene Entität an den neuen Ort. Wenn die zu verschiebende Entität ein Verzeichnis ist, wird es mit seinem gesamten Inhalt verschoben. |
| static void [SetCreationTime](./setcreationtime/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | Setzt die Erstellungszeit der angegebenen Entität als Ortszeit. |
| static void [SetCreationTimeUtc](./setcreationtimeutc/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | Setzt die Erstellungszeit der angegebenen Entität als UTC-Zeit. |
| static void [SetCurrentDirectory](./setcurrentdirectory/)(const [String](../../system/string/)\&) | Setzt das aktuelle Verzeichnis. |
| static void [SetLastAccessTime](./setlastaccesstime/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | Setzt die letzte Zugriffszeit der angegebenen Entität als Ortszeit. |
| static void [SetLastAccessTimeUtc](./setlastaccesstimeutc/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | Setzt die letzte Zugriffszeit der angegebenen Entität als UTC-Zeit. |
| static void [SetLastWriteTime](./setlastwritetime/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | Setzt die letzte Schreibzeit der angegebenen Entität als Ortszeit. |
| static void [SetLastWriteTimeUtc](./setlastwritetimeutc/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | Setzt die letzte Schreibzeit der angegebenen Entität als UTC-Zeit. |

## Typedefs

| Typedef | Beschreibung |
| --- | --- |
| [StringEnumerablePtr](./stringenumerableptr/) | Ein Alias für einen Shared-Pointer auf ein IEnumerable-Objekt, das über eine Menge von [String](../../system/string/)-Objekten iteriert. |

## Anmerkungen



```cpp
#include "system/io/directory.h"
#include "system/io/path.h"
#include "system/string.h"
#include <iostream>

void PrintMessage(const System::String &path)
{
  std::cout << "Directory '" << path << (System::IO::Directory::Exists(path) ? "' exists." : "' doesn't exist.") << std::endl;
}

int main()
{
  // Erstelle Zeichenketten, die Pfade zu Verzeichnissen enthalten.
  System::String discPath(u"C:\\");
  System::String directoryPath(u"C:\\Some directory");
  auto tempPath = System::IO::Path::GetTempPath();

  // Prüfe, ob Verzeichnisse existieren.
  PrintMessage(discPath);
  PrintMessage(directoryPath);
  PrintMessage(tempPath);

  // Gib die Informationen des temporären Verzeichnisses aus.
  std::cout <<
    "Creation Time: " << System::IO::Directory::GetCreationTime(tempPath) << std::endl <<
    "Last Access Time: " << System::IO::Directory::GetLastAccessTime(tempPath) << std::endl <<
    "Last Write Time: " << System::IO::Directory::GetLastWriteTime(tempPath) << std::endl;

  return 0;
}
/*
Dieses Codebeispiel erzeugt die folgende Ausgabe:
Verzeichnis 'C:\' existiert.
Verzeichnis 'C:\Some directory' existiert nicht.
Verzeichnis 'C:\Users\lanor\AppData\Local\Temp\' existiert.
Erstellungszeit: 27.08.2021 14:21:42
Letzte Zugriffszeit: 07.10.2021 12:16:41
Letzte Schreibzeit: 07.10.2021 12:16:41
*/
```

## Siehe auch

* Namensraum [System::IO](../)
* Bibliothek [Aspose.Slides](../../)