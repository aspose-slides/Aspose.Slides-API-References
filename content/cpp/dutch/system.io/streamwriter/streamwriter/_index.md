---
title: StreamWriter()
second_title: Aspose.Slides voor C++ API-referentie
description: Construeert een exemplaar van het StreamWriter-object dat tekens naar de opgegeven onderliggende stream schrijft met UTF-8-codering en een buffer met een standaardgrootte van 1024 bytes.
type: docs
weight: 1
url: /nl/system.io/streamwriter/streamwriter/
---
## StreamWriter::StreamWriter(const SharedPtr\<Stream\>\&) constructor

Construeert een exemplaar van het [StreamWriter](../) object dat tekens naar de opgegeven onderliggende stream schrijft met UTF-8-codering en een buffer met een standaardgrootte van 1024 bytes.

```cpp
System::IO::StreamWriter::StreamWriter(const SharedPtr<Stream> &stream)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | De onderliggende stream om tekens naar te schrijven |

## StreamWriter::StreamWriter(const SharedPtr\<Stream\>\&, const EncodingPtr\&) constructor

Construeert een exemplaar van het [StreamWriter](../) object dat tekens naar de opgegeven onderliggende stream schrijft met de opgegeven codering en een buffer met een standaardgrootte van 1024 bytes.

```cpp
System::IO::StreamWriter::StreamWriter(const SharedPtr<Stream> &stream, const EncodingPtr &encoding)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | De onderliggende stream om tekens naar te schrijven |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | De te gebruiken codering |

## StreamWriter::StreamWriter(const SharedPtr\<Stream\>\&, const EncodingPtr\&, int, bool) constructor

Construeert een exemplaar van het [StreamWriter](../) object dat tekens naar de opgegeven onderliggende stream schrijft met de opgegeven codering en een buffer van de gespecificeerde grootte. Een parameter geeft aan of de onderliggende stream moet worden gesloten wanneer het [StreamWriter](../) object wordt vrijgegeven.

```cpp
System::IO::StreamWriter::StreamWriter(const SharedPtr<Stream> &stream, const EncodingPtr &encoding, int buffer_size, bool leave_open=false)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | De onderliggende stream om tekens naar te schrijven |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | De te gebruiken codering |
| buffer_size | int | De minimale grootte van de buffer in bytes |
| leave_open | **bool** | Geeft aan of de onderliggende stream open moet blijven nadat het huidige [StreamWriter](../) object is vrijgegeven |

## StreamWriter::StreamWriter(const String\&) constructor

Construeert een exemplaar van het [StreamWriter](../) object dat tekens naar het opgegeven bestand schrijft met UTF-8-codering en een buffer met een standaardgrootte van 1024 bytes.

```cpp
System::IO::StreamWriter::StreamWriter(const String &path)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Het pad van het bestand waarin tekens moeten worden geschreven |

## StreamWriter::StreamWriter(const String\&, bool, const EncodingPtr\&) constructor

Construeert een exemplaar van het [StreamWriter](../) object dat tekens naar het opgegeven bestand schrijft met de opgegeven codering en een buffer met een standaardgrootte van 1024 bytes. Een parameter geeft aan of de gegevens aan het bestand moeten worden toegevoegd of dat het bestand moet worden overschreven.

```cpp
System::IO::StreamWriter::StreamWriter(const String &path, bool append, const EncodingPtr &encoding=System::Text::Encoding::get_UTF8Unmarked())
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Het pad van het bestand waarin tekens moeten worden geschreven |
| append | **bool** | Geeft aan of de gegevens aan het opgegeven bestand moeten worden toegevoegd (true) of dat het bestand moet worden overschreven (false) |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | De te gebruiken codering |

## StreamWriter::StreamWriter(const String\&, bool, const EncodingPtr\&, int) constructor

Construeert een exemplaar van het [StreamWriter](../) object dat tekens naar het opgegeven bestand schrijft met de opgegeven codering en een buffer van de opgegeven grootte. Een parameter geeft aan of de gegevens aan het bestand moeten worden toegevoegd of dat het bestand moet worden overschreven.

```cpp
System::IO::StreamWriter::StreamWriter(const String &path, bool append, const EncodingPtr &encoding, int buffer_size)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Het pad van het bestand waarin tekens moeten worden geschreven |
| append | **bool** | Geeft aan of de gegevens aan het opgegeven bestand moeten worden toegevoegd (true) of dat het bestand moet worden overschreven (false) |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | De te gebruiken codering |
| buffer_size | int | De grootte van de te gebruiken buffer |

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [Stream](../../stream/)
* Class [StreamWriter](../)
* Class [String](../../../system/string/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)