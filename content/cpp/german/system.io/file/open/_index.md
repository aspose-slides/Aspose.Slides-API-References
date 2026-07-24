---
title: Open()
second_title: Aspose.Slides für C++ API-Referenz
description: Öffnet die angegebene Datei im angegebenen Modus zum Lesen und Schreiben ohne Freigabe.
type: docs
weight: 235
url: /de/system.io/file/open/
---
## File::Open(const String\&, FileMode) Methode


Öffnet die angegebene Datei im angegebenen Modus zum Lesen und Schreiben ohne Freigabe.

```cpp
static FileStreamPtr System::IO::File::Open(const String &path, FileMode mode)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Der Pfad der zu öffnenden Datei |
| mode | [FileMode](../../filemode/) | Der Modus, in dem die Datei geöffnet werden soll |

### Rückgabewert

Ein [FileStream](../../filestream/)-Objekt, das mit der geöffneten Datei verknüpft ist

## File::Open(const String\&, FileMode, FileAccess, FileShare) Methode


Öffnet die angegebene Datei im angegebenen Modus, mit dem angegebenen Zugriffstyp und Freigabeoption.

```cpp
static FileStreamPtr System::IO::File::Open(const String &path, FileMode mode, FileAccess access, FileShare share=FileShare::None)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Der Pfad der zu öffnenden Datei |
| mode | [FileMode](../../filemode/) | Der Modus, in dem die Datei geöffnet werden soll |
| access | [FileAccess](../../fileaccess/) | Der angeforderte Zugriffstyp |
| share | [FileShare](../../fileshare/) | Der Zugriffstyp, den andere [FileStream](../../filestream/)-Objekte auf die geöffnete Datei haben |

### Rückgabewert

Ein [FileStream](../../filestream/)-Objekt, das mit der geöffneten Datei verknüpft ist

## Siehe auch

* Enum [FileMode](../../filemode/)
* Enum [FileAccess](../../fileaccess/)
* Enum [FileShare](../../fileshare/)
* Typedef [FileStreamPtr](../../../system/filestreamptr/)
* Klasse [String](../../../system/string/)
* Klasse [File](../)
* Namensraum [System::IO](../../)
* Bibliothek [Aspose.Slides](../../../)