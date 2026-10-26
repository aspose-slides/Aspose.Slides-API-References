---
title: Open()
second_title: Aspose.Slides für C++ API-Referenz
description: Öffnet die durch das aktuelle Objekt dargestellte Datei im angegebenen Modus zum Lesen und Schreiben und ohne Freigabe.
type: docs
weight: 183
url: /de/system.io/fileinfo/open/
---
## FileInfo::Open(FileMode) Methode

Öffnet die durch das aktuelle Objekt dargestellte Datei im angegebenen Modus zum Lesen und Schreiben und ohne Freigabe.

```cpp
FileStreamPtr System::IO::FileInfo::Open(FileMode mode)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| mode | [FileMode](../../filemode/) | Gibt den Modus an, in dem die Datei geöffnet werden soll |

### Rückgabewert

Ein [FileStream](../../filestream/)-Objekt, das mit der durch das aktuelle Objekt dargestellten Datei verknüpft ist

## FileInfo::Open(FileMode, FileAccess) Methode

Öffnet die durch das aktuelle Objekt dargestellte Datei im angegebenen Modus, mit dem angegebenen Zugriffstyp und ohne Freigabe.

```cpp
FileStreamPtr System::IO::FileInfo::Open(FileMode mode, FileAccess access)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| mode | [FileMode](../../filemode/) | Gibt den Modus an, in dem die Datei geöffnet werden soll |
| access | [FileAccess](../../fileaccess/) | Der angeforderte Zugriffstyp |

### Rückgabewert

Ein [FileStream](../../filestream/)-Objekt, das mit der durch das aktuelle Objekt dargestellten Datei verknüpft ist

## FileInfo::Open(FileMode, FileAccess, FileShare) Methode

Öffnet die durch das aktuelle Objekt dargestellte Datei im angegebenen Modus, mit dem angegebenen Zugriffstyp und der Freigabeoption.

```cpp
FileStreamPtr System::IO::FileInfo::Open(FileMode mode, FileAccess access, FileShare share)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| mode | [FileMode](../../filemode/) | Gibt den Modus an, in dem die Datei geöffnet werden soll |
| access | [FileAccess](../../fileaccess/) | Der angeforderte Zugriffstyp |
| share | [FileShare](../../fileshare/) | Der Zugriffstyp, den andere [FileStream](../../filestream/)-Objekte auf die geöffnete Datei haben |

### Rückgabewert

Ein [FileStream](../../filestream/)-Objekt, das mit der durch das aktuelle Objekt dargestellten Datei verknüpft ist

## Siehe auch

* Enum [FileMode](../../filemode/)
* Enum [FileAccess](../../fileaccess/)
* Enum [FileShare](../../fileshare/)
* Typedef [FileStreamPtr](../../../system/filestreamptr/)
* Klasse [FileInfo](../)
* Namensraum [System::IO](../../)
* Bibliothek [Aspose.Slides](../../../)