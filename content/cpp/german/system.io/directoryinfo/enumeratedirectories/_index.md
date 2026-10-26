---
title: EnumerateDirectories()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt eine aufzählbare Sammlung zurück, die alle Verzeichnisse enthält, die im Verzeichnis liegen, das durch das aktuelle Objekt repräsentiert wird.
type: docs
weight: 105
url: /de/system.io/directoryinfo/enumeratedirectories/
---
## DirectoryInfo::EnumerateDirectories() Methode

Gibt eine aufzählbare Sammlung zurück, die alle Verzeichnisse enthält, die im Verzeichnis liegen, das durch das aktuelle Objekt repräsentiert wird.

```cpp
SharedPtr<IEnumerable<DirectoryInfoPtr>> System::IO::DirectoryInfo::EnumerateDirectories()
```

## DirectoryInfo::EnumerateDirectories(const String\&) Methode

Durchsucht das Verzeichnis, das durch das aktuelle Objekt repräsentiert wird, nach den Verzeichnissen, die die angegebenen Suchkriterien erfüllen.

```cpp
SharedPtr<IEnumerable<DirectoryInfoPtr>> System::IO::DirectoryInfo::EnumerateDirectories(const String &searchPattern)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | Das Namensmuster der zu suchenden Verzeichnisse |

### Rückgabewert

Die aufzählbare Sammlung von shared pointers zu [DirectoryInfo](../)-Objekten, die die gefundenen Verzeichnisse darstellen, deren Namen mit **searchPattern** übereinstimmen.

## DirectoryInfo::EnumerateDirectories(const String\&, SearchOption) Methode

Durchsucht entweder das Verzeichnis, das durch das aktuelle Objekt repräsentiert wird, oder den gesamten Verzeichnisbaum, der im Verzeichnis, das durch das aktuelle Objekt repräsentiert wird, verwurzelt ist, nach Verzeichnissen, die die angegebenen Suchkriterien erfüllen.

```cpp
SharedPtr<IEnumerable<DirectoryInfoPtr>> System::IO::DirectoryInfo::EnumerateDirectories(const String &searchPattern, SearchOption searchOption)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | Das Namensmuster der zu suchenden Verzeichnisse |
| searchOption | [SearchOption](../../searchoption/) | Gibt an, ob die Suche ausschließlich im Verzeichnis, das durch das aktuelle Objekt repräsentiert wird, oder im gesamten Verzeichnisbaum, der im Verzeichnis, das durch das aktuelle Objekt repräsentiert wird, verwurzelt ist, durchgeführt werden muss |

### Rückgabewert

Die aufzählbare Sammlung von shared pointers zu [DirectoryInfo](../)-Objekten, die die gefundenen Verzeichnisse darstellen, deren Namen mit **searchPattern** übereinstimmen.

## Siehe auch

* Enum [SearchOption](../../searchoption/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [DirectoryInfoPtr](../../../system/directoryinfoptr/)
* Klasse [IEnumerable](../../../system.collections.generic/ienumerable/)
* Klasse [DirectoryInfo](../)
* Klasse [String](../../../system/string/)
* Namensraum [System::IO](../../)
* Bibliothek [Aspose.Slides](../../../)