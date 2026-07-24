---
title: GetDirectories()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt ein Array zurück, das gemeinsame Zeiger auf DirectoryInfo-Objekte enthält, die alle im durch das aktuelle Objekt dargestellten Verzeichnis befindlichen Verzeichnisse repräsentieren.
type: docs
weight: 144
url: /de/system.io/directoryinfo/getdirectories/
---
## DirectoryInfo::GetDirectories() Methode

Gibt ein Array zurück, das gemeinsame Zeiger auf [DirectoryInfo](../)-Objekte enthält, die alle im durch das aktuelle Objekt dargestellten Verzeichnis befindlichen Verzeichnisse repräsentieren.

```cpp
ArrayPtr<DirectoryInfoPtr> System::IO::DirectoryInfo::GetDirectories()
```

## DirectoryInfo::GetDirectories(const String\&) Methode

Durchsucht das vom aktuellen Objekt dargestellte Verzeichnis nach den Verzeichnissen, die die angegebenen Suchkriterien erfüllen.

```cpp
ArrayPtr<DirectoryInfoPtr> System::IO::DirectoryInfo::GetDirectories(const String &searchPattern)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | Das Namensmuster der zu suchenden Verzeichnisse |

### Rückgabewert

Ein Array von gemeinsamen Zeigern auf [DirectoryInfo](../)-Objekte, die die gefundenen Verzeichnisse repräsentieren, deren Namen dem **searchPattern** entsprechen.

## DirectoryInfo::GetDirectories(const String\&, SearchOption) Methode

Durchsucht entweder das vom aktuellen Objekt dargestellte Verzeichnis oder den gesamten Verzeichnisbaum, der im vom aktuellen Objekt dargestellten Verzeichnis wurzelt, nach den Verzeichnissen, die die angegebenen Suchkriterien erfüllen.

```cpp
ArrayPtr<DirectoryInfoPtr> System::IO::DirectoryInfo::GetDirectories(const String &searchPattern, SearchOption searchOption)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | Das Namensmuster der zu suchenden Verzeichnisse |
| searchOption | [SearchOption](../../searchoption/) | Gibt an, ob die Suche nur im vom aktuellen Objekt dargestellten Verzeichnis oder im gesamten Verzeichnisbaum, der im vom aktuellen Objekt dargestellten Verzeichnis wurzelt, durchgeführt werden muss |

### Rückgabewert

Ein Array von gemeinsamen Zeigern auf [DirectoryInfo](../)-Objekte, die die gefundenen Verzeichnisse repräsentieren, deren Namen dem **searchPattern** entsprechen.

## Siehe auch

* Enum [SearchOption](../../searchoption/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [DirectoryInfoPtr](../../../system/directoryinfoptr/)
* Class [DirectoryInfo](../)
* Class [String](../../../system/string/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)