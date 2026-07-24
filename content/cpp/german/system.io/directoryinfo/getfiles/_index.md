---
title: GetFiles()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt ein Array zurück, das Shared pointers auf FileInfo-Objekte enthält, die alle Verzeichnisse darstellen, die sich im durch das aktuelle Objekt repräsentierten Verzeichnis befinden.
type: docs
weight: 157
url: /de/system.io/directoryinfo/getfiles/
---
## DirectoryInfo::GetFiles() Methode

Gibt ein Array zurück, das Shared pointers auf [FileInfo](../../fileinfo/)-Objekte enthält, die alle Verzeichnisse darstellen, die sich im durch das aktuelle Objekt repräsentierten Verzeichnis befinden.

```cpp
ArrayPtr<FileInfoPtr> System::IO::DirectoryInfo::GetFiles()
```

## DirectoryInfo::GetFiles(const String\&) Methode

Durchsucht das durch das aktuelle Objekt repräsentierte Verzeichnis nach Dateien, die die angegebenen Suchkriterien erfüllen.

```cpp
ArrayPtr<FileInfoPtr> System::IO::DirectoryInfo::GetFiles(const String &searchPattern)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | Das Namensmuster der zu suchenden Dateien |

### Rückgabewert

Ein Array von Shared pointers auf [FileInfo](../../fileinfo/)-Objekte, die die gefundenen Dateien darstellen, deren Namen dem **searchPattern** entsprechen.

## DirectoryInfo::GetFiles(const String\&, SearchOption) Methode

Durchsucht entweder das durch das aktuelle Objekt repräsentierte Verzeichnis oder den gesamten Verzeichnisbaum, der im durch das aktuelle Objekt repräsentierten Verzeichnis wurzelt, nach Dateien, die die angegebenen Suchkriterien erfüllen.

```cpp
ArrayPtr<FileInfoPtr> System::IO::DirectoryInfo::GetFiles(const String &searchPattern, SearchOption searchOption)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | Das Namensmuster der zu suchenden Dateien |
| searchOption | [SearchOption](../../searchoption/) | Gibt an, ob die Suche nur im durch das aktuelle Objekt repräsentierten Verzeichnis oder im gesamten Verzeichnisbaum, der dort wurzelt, durchgeführt werden soll |

### Rückgabewert

Ein Array von Shared pointers auf [FileInfo](../../fileinfo/)-Objekte, die die gefundenen Dateien darstellen, deren Namen dem **searchPattern** entsprechen.

## Siehe auch

* Enum [SearchOption](../../searchoption/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [FileInfoPtr](../../../system/fileinfoptr/)
* Klasse [DirectoryInfo](../)
* Klasse [String](../../../system/string/)
* Namensraum [System::IO](../../)
* Library [Aspose.Slides](../../../)