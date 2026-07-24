---
title: StreamWriter()
second_title: Aspose.Slides für C++ API-Referenz
description: Konstruiert eine Instanz des StreamWriter-Objekts, das Zeichen in den angegebenen zugrunde liegenden Stream schreibt und UTF-8-Kodierung sowie einen Puffer mit einer Standardgröße von 1024 Bytes verwendet.
type: docs
weight: 1
url: /de/system.io/streamwriter/streamwriter/
---
## StreamWriter::StreamWriter(const SharedPtr\<Stream\>\&) Konstruktor

Konstruiert eine Instanz des [StreamWriter](../) Objekts, das Zeichen in den angegebenen zugrunde liegenden Stream schreibt und UTF-8-Kodierung sowie einen Puffer mit einer Standardgröße von 1024 Bytes verwendet.

```cpp
System::IO::StreamWriter::StreamWriter(const SharedPtr<Stream> &stream)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | Der zugrunde liegende Stream, in den Zeichen geschrieben werden sollen |

## StreamWriter::StreamWriter(const SharedPtr\<Stream\>\&, const EncodingPtr\&) Konstruktor

Konstruiert eine Instanz des [StreamWriter](../) Objekts, das Zeichen in den angegebenen zugrunde liegenden Stream schreibt, die angegebene Kodierung verwendet und einen Puffer mit einer Standardgröße von 1024 Bytes nutzt.

```cpp
System::IO::StreamWriter::StreamWriter(const SharedPtr<Stream> &stream, const EncodingPtr &encoding)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | Der zugrunde liegende Stream, in den Zeichen geschrieben werden sollen |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Die zu verwendende Kodierung |

## StreamWriter::StreamWriter(const SharedPtr\<Stream\>\&, const EncodingPtr\&, int, bool) Konstruktor

Konstruiert eine Instanz des [StreamWriter](../) Objekts, das Zeichen in den angegebenen zugrunde liegenden Stream schreibt, die angegebene Kodierung und einen Puffer der angegebenen Größe verwendet. Ein Parameter gibt an, ob der zugrunde liegende Stream geschlossen werden soll, wenn das [StreamWriter](../) Objekt freigegeben wird.

```cpp
System::IO::StreamWriter::StreamWriter(const SharedPtr<Stream> &stream, const EncodingPtr &encoding, int buffer_size, bool leave_open=false)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | Der zugrunde liegende Stream, in den Zeichen geschrieben werden sollen |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Die zu verwendende Kodierung |
| buffer_size | int | Die minimale Größe des Puffers in Bytes |
| leave_open | **bool** | Gibt an, ob der zugrunde liegende Stream nach der Freigabe des aktuellen [StreamWriter](../) Objekts geöffnet bleiben soll |

## StreamWriter::StreamWriter(const String\&) Konstruktor

Konstruiert eine Instanz des [StreamWriter](../) Objekts, das Zeichen in die angegebene Datei schreibt, UTF-8-Kodierung verwendet und einen Puffer mit einer Standardgröße von 1024 Bytes nutzt.

```cpp
System::IO::StreamWriter::StreamWriter(const String &path)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Der Pfad der Datei, in die Zeichen geschrieben werden sollen |

## StreamWriter::StreamWriter(const String\&, bool, const EncodingPtr\&) Konstruktor

Konstruiert eine Instanz des [StreamWriter](../) Objekts, das Zeichen in die angegebene Datei schreibt, die angegebene Kodierung verwendet und einen Puffer mit einer Standardgröße von 1024 Bytes nutzt. Ein Parameter gibt an, ob die Daten an die Datei angehängt werden sollen oder die Datei überschrieben werden soll.

```cpp
System::IO::StreamWriter::StreamWriter(const String &path, bool append, const EncodingPtr &encoding=System::Text::Encoding::get_UTF8Unmarked())
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Der Pfad der Datei, in die Zeichen geschrieben werden sollen |
| append | **bool** | Gibt an, ob die Daten an die angegebene Datei angehängt werden sollen (true) oder die Datei überschrieben werden soll (false) |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Die zu verwendende Kodierung |

## StreamWriter::StreamWriter(const String\&, bool, const EncodingPtr\&, int) Konstruktor

Konstruiert eine Instanz des [StreamWriter](../) Objekts, das Zeichen in die angegebene Datei schreibt, die angegebene Kodierung und Puffergröße verwendet. Ein Parameter gibt an, ob die Daten an die Datei angehängt werden sollen oder die Datei überschrieben werden soll.

```cpp
System::IO::StreamWriter::StreamWriter(const String &path, bool append, const EncodingPtr &encoding, int buffer_size)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Der Pfad der Datei, in die Zeichen geschrieben werden sollen |
| append | **bool** | Gibt an, ob die Daten an die angegebene Datei angehängt werden sollen (true) oder die Datei überschrieben werden soll (false) |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Die zu verwendende Kodierung |
| buffer_size | int | Die zu verwendende Puffergröße |

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Klasse [Stream](../../stream/)
* Klasse [StreamWriter](../)
* Klasse [String](../../../system/string/)
* Namensraum [System::IO](../../)
* Library [Aspose.Slides](../../../)