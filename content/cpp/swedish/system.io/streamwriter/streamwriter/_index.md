---
title: StreamWriter()
second_title: Aspose.Slides för C++ API-referens
description: Skapar en instans av StreamWriter-objekt som skriver tecken till den specificerade underliggande strömmen med UTF-8-kodning och en buffert med standardstorlek 1024 byte.
type: docs
weight: 1
url: /sv/system.io/streamwriter/streamwriter/
---
## StreamWriter::StreamWriter(const SharedPtr\<Stream\>\&) konstruktor

Skapar en instans av [StreamWriter](../)-objekt som skriver tecken till den specificerade underliggande strömmen med UTF-8-kodning och en buffert med standardstorlek 1024 byte.

```cpp
System::IO::StreamWriter::StreamWriter(const SharedPtr<Stream> &stream)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | Den underliggande strömmen som tecken ska skrivas till |

## StreamWriter::StreamWriter(const SharedPtr\<Stream\>\&, const EncodingPtr\&) konstruktor

Skapar en instans av [StreamWriter](../)-objekt som skriver tecken till den specificerade underliggande strömmen med den angivna kodningen och en buffert med standardstorlek 1024 byte.

```cpp
System::IO::StreamWriter::StreamWriter(const SharedPtr<Stream> &stream, const EncodingPtr &encoding)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | Den underliggande strömmen som tecken ska skrivas till |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Kodningen som ska användas |

## StreamWriter::StreamWriter(const SharedPtr\<Stream\>\&, const EncodingPtr\&, int, bool) konstruktor

Skapar en instans av [StreamWriter](../)-objekt som skriver tecken till den specificerade underliggande strömmen med den angivna kodningen och en buffert med den specificerade storleken. En parameter anger huruvida den underliggande strömmen ska stängas när [StreamWriter](../)-objektet har frigjorts.

```cpp
System::IO::StreamWriter::StreamWriter(const SharedPtr<Stream> &stream, const EncodingPtr &encoding, int buffer_size, bool leave_open=false)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | Den underliggande strömmen som tecken ska skrivas till |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Kodningen som ska användas |
| buffer_size | int | Den minsta storleken på bufferten i byte |
| leave_open | **bool** | Anger huruvida den underliggande strömmen ska lämnas öppen efter att det aktuella [StreamWriter](../)-objektet har frigjorts |

## StreamWriter::StreamWriter(const String\&) konstruktor

Skapar en instans av [StreamWriter](../)-objekt som skriver tecken till den specificerade filen med UTF-8-kodning och en buffert med standardstorlek 1024 byte.

```cpp
System::IO::StreamWriter::StreamWriter(const String &path)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Sökvägen till filen som tecken ska skrivas till |

## StreamWriter::StreamWriter(const String\&, bool, const EncodingPtr\&) konstruktor

Skapar en instans av [StreamWriter](../)-objekt som skriver tecken till den specificerade filen med den angivna kodningen och en buffert med standardstorlek 1024 byte. En parameter anger huruvida data ska läggas till i den specificerade filen (true) eller om filen ska skrivas över (false).

```cpp
System::IO::StreamWriter::StreamWriter(const String &path, bool append, const EncodingPtr &encoding=System::Text::Encoding::get_UTF8Unmarked())
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Sökvägen till filen som tecken ska skrivas till |
| append | **bool** | Anger huruvida data ska läggas till i den specificerade filen (true) eller om filen ska skrivas över (false) |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Kodningen som ska användas |

## StreamWriter::StreamWriter(const String\&, bool, const EncodingPtr\&, int) konstruktor

Skapar en instans av [StreamWriter](../)-objekt som skriver tecken till den specificerade filen med den angivna kodningen och buffertstorlek. En parameter anger huruvida data ska läggas till i filen eller om filen ska skrivas över.

```cpp
System::IO::StreamWriter::StreamWriter(const String &path, bool append, const EncodingPtr &encoding, int buffer_size)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Sökvägen till filen som tecken ska skrivas till |
| append | **bool** | Anger huruvida data ska läggas till i den specificerade filen (true) eller om filen ska skrivas över (false) |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Kodningen som ska användas |
| buffer_size | int | Storleken på den buffert som ska användas |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Klass [Stream](../../stream/)
* Klass [StreamWriter](../)
* Klass [String](../../../system/string/)
* Namnrymd [System::IO](../../)
* Bibliotek [Aspose.Slides](../../../)