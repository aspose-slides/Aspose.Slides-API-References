---
title: FileStream()
second_title: Aspose.Slides für C++ API-Referenz
description: Konstruiert eine neue Instanz der Klasse FileStream und initialisiert sie mit den angegebenen Parametern.
type: docs
weight: 1
url: /de/system.io/filestream/filestream/
---
## FileStream::FileStream(const String\&, FileMode) Konstruktor

Konstruiert eine neue Instanz der Klasse [FileStream](../) und initialisiert sie mit den angegebenen Parametern.

```cpp
System::IO::FileStream::FileStream(const String &path, FileMode mode)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Der Pfad der zu öffnenden Datei. |
| mode | [FileMode](../../filemode/) | Gibt den Modus an, in dem die Datei geöffnet werden soll. |

## FileStream::FileStream(const String\&, FileMode, FileAccess, FileShare, int32_t, FileOptions) Konstruktor

Konstruiert eine neue Instanz der Klasse [FileStream](../) und initialisiert sie mit den angegebenen Parametern.

```cpp
System::IO::FileStream::FileStream(const String &path, FileMode mode, FileAccess access, FileShare share=FileShare::Read, int32_t buffer_size=DefaultBufferSize, FileOptions options=FileOptions::SequentialScan)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Der Pfad der zu öffnenden Datei. |
| mode | [FileMode](../../filemode/) | Gibt den Modus an, in dem die Datei geöffnet werden soll. |
| access | [FileAccess](../../fileaccess/) | Der angeforderte Zugriffstyp. |
| share | [FileShare](../../fileshare/) | Der Zugriffstyp, den andere [FileStream](../)-Objekte auf die geöffnete Datei haben. |
| buffer_size | **int32_t** | Die Anzahl der während Lese- und Schreibvorgängen gepufferten Bytes. |
| options | [FileOptions](../../fileoptions/) | Zusätzliche Optionen. |

## FileStream::FileStream(const String\&, FileMode, FileAccess, FileShare, int32_t, bool) Konstruktor

Konstruiert eine neue Instanz der Klasse [FileStream](../) und initialisiert sie mit den angegebenen Parametern.

```cpp
System::IO::FileStream::FileStream(const String &path, FileMode mode, FileAccess access, FileShare share, int32_t buffer_size, bool useAsync)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Der Pfad der zu öffnenden Datei. |
| mode | [FileMode](../../filemode/) | Gibt den Modus an, in dem die Datei geöffnet werden soll. |
| access | [FileAccess](../../fileaccess/) | Der angeforderte Zugriffstyp. |
| share | [FileShare](../../fileshare/) | Der Zugriffstyp, den andere [FileStream](../)-Objekte auf die geöffnete Datei haben. |
| buffer_size | **int32_t** | Die Anzahl der während Lese- und Schreibvorgängen gepufferten Bytes. |
| useAsync | **bool** | Gibt an, ob asynchrones I/O oder synchrones I/O verwendet werden soll. |

## Anmerkungen

Das zugrunde liegende Betriebssystem unterstützt möglicherweise kein asynchrones I/O. 

## FileStream::FileStream(const FileStream\&) Konstruktor

```cpp
System::IO::FileStream::FileStream(const FileStream &)=delete
```

## Siehe auch

* Enum [FileMode](../../filemode/)
* Enum [FileAccess](../../fileaccess/)
* Enum [FileShare](../../fileshare/)
* Enum [FileOptions](../../fileoptions/)
* Class [String](../../../system/string/)
* Class [FileStream](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)