---
title: StreamReader()
second_title: Aspose.Slides för C++ API-referens
description: Skapar en instans av StreamReader-objekt som läser tecken från den specificerade underliggande strömmen med UTF-8-kodning och en buffert med standardstorlek 1024 byte.
type: docs
weight: 1
url: /sv/system.io/streamreader/streamreader/
---
## StreamReader::StreamReader(const SharedPtr\<Stream\>\&) constructor

Skapar en instans av [StreamReader](../)-objekt som läser tecken från den specificerade underliggande strömmen med UTF-8-kodning och en buffert med standardstorlek 1024 byte.

```cpp
System::IO::StreamReader::StreamReader(const SharedPtr<Stream> &stream)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | Den underliggande strömmen att läsa tecken från |

## StreamReader::StreamReader(const SharedPtr\<Stream\>\&, bool) constructor

Skapar en instans av [StreamReader](../)-objekt som läser tecken från den specificerade underliggande strömmen med UTF-8-kodning och en buffert med standardstorlek 1024 byte. En parameter anger om identifiering av byte-ordningsmarkörer ska vara aktiverad.

```cpp
System::IO::StreamReader::StreamReader(const SharedPtr<Stream> &stream, bool detectEncodingFromByteOrderMarks)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | Den underliggande strömmen att läsa tecken från |
| detectEncodingFromByteOrderMarks | **bool** | True för att leta efter byteordningsmarkörer i början av strömmen, annars - false |

## StreamReader::StreamReader(const SharedPtr\<Stream\>\&, const EncodingPtr\&) constructor

Skapar en instans av [StreamReader](../)-objekt som läser tecken från den specificerade underliggande strömmen med den angivna kodningen och en buffert med standardstorlek 1024 byte.

```cpp
System::IO::StreamReader::StreamReader(const SharedPtr<Stream> &stream, const EncodingPtr &encoding)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | Den underliggande strömmen att läsa tecken från |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Kodningen att använda |

## StreamReader::StreamReader(const SharedPtr\<Stream\>\&, const EncodingPtr\&, bool) constructor

Skapar en instans av [StreamReader](../)-objekt som läser tecken från den specificerade underliggande strömmen med den angivna kodningen och en buffert med standardstorlek 1024 byte. En parameter anger om identifiering av byte-ordningsmarkörer ska vara aktiverad.

```cpp
System::IO::StreamReader::StreamReader(const SharedPtr<Stream> &stream, const EncodingPtr &encoding, bool detectEncodingFromByteOrderMarks)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | Den underliggande strömmen att läsa tecken från |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Kodningen att använda |
| detectEncodingFromByteOrderMarks | **bool** | True för att leta efter byteordningsmarkörer i början av strömmen, annars - false |

## StreamReader::StreamReader(const SharedPtr\<Stream\>\&, const EncodingPtr\&, bool, int) constructor

Skapar en instans av [StreamReader](../)-objekt som läser tecken från den specificerade underliggande strömmen med den angivna kodningen och en buffert med angiven storlek. En parameter anger om identifiering av byte-ordningsmarkörer ska vara aktiverad.

```cpp
System::IO::StreamReader::StreamReader(const SharedPtr<Stream> &stream, const EncodingPtr &encoding, bool detectEncodingFromByteOrderMarks, int bufferSize)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | Den underliggande strömmen att läsa tecken från |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Kodningen att använda |
| detectEncodingFromByteOrderMarks | **bool** | True för att leta efter byteordningsmarkörer i början av strömmen, annars - false |
| bufferSize | int | Den minsta storleken på bufferten i byte |

## StreamReader::StreamReader(const System::String\&) constructor

Skapar en instans av [StreamReader](../)-objekt som läser tecken från den specificerade filen med UTF-8-kodning och en buffert med standardstorlek 4096 byte.

```cpp
System::IO::StreamReader::StreamReader(const System::String &path)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| path | const [System::String](../../../system/string/)\& | Sökvägen till filen att läsa tecken från |

## StreamReader::StreamReader(const System::String\&, bool) constructor

Skapar en instans av [StreamReader](../)-objekt som läser tecken från den specificerade filen med UTF-8-kodning och en buffert med standardstorlek 4096 byte. En parameter anger om identifiering av byte-ordningsmarkörer ska vara aktiverad.

```cpp
System::IO::StreamReader::StreamReader(const System::String &path, bool detectEncodingFromByteOrderMarks)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| path | const [System::String](../../../system/string/)\& | Sökvägen till filen att läsa tecken från |
| detectEncodingFromByteOrderMarks | **bool** | True för att leta efter byteordningsmarkörer i början av filen, annars - false |

## StreamReader::StreamReader(const System::String\&, const EncodingPtr\&) constructor

Skapar en instans av [StreamReader](../)-objekt som läser tecken från den specificerade filen med den angivna kodningen och en buffert med standardstorlek 4096 byte.

```cpp
System::IO::StreamReader::StreamReader(const System::String &path, const EncodingPtr &encoding)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| path | const [System::String](../../../system/string/)\& | Sökvägen till filen att läsa tecken från |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Kodningen att använda |

## StreamReader::StreamReader(const System::String\&, const EncodingPtr\&, bool) constructor

Skapar en instans av [StreamReader](../)-objekt som läser tecken från den specificerade underliggande strömmen med den angivna kodningen och en buffert med standardstorlek 4096 byte. En parameter anger om identifiering av byte-ordningsmarkörer ska vara aktiverad.

```cpp
System::IO::StreamReader::StreamReader(const System::String &path, const EncodingPtr &encoding, bool detectEncodingFromByteOrderMarks)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| path | const [System::String](../../../system/string/)\& | Sökvägen till filen att läsa tecken från |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Kodningen att använda |
| detectEncodingFromByteOrderMarks | **bool** | True för att leta efter byteordningsmarkörer i början av filen, annars - false |

## StreamReader::StreamReader(const System::String\&, const EncodingPtr\&, bool, int) constructor

Skapar en instans av [StreamReader](../)-objekt som läser tecken från den specificerade filen med den angivna kodningen och en buffert med angiven storlek. En parameter anger om identifiering av byte-ordningsmarkörer ska vara aktiverad.

```cpp
System::IO::StreamReader::StreamReader(const System::String &path, const EncodingPtr &encoding, bool detectEncodingFromByteOrderMarks, int bufferSize)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| path | const [System::String](../../../system/string/)\& | Sökvägen till filen att läsa tecken från |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Kodningen att använda |
| detectEncodingFromByteOrderMarks | **bool** | True för att leta efter byteordningsmarkörer i början av filen, annars - false |
| bufferSize | int | Den minsta storleken på bufferten i byte |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Klass [Stream](../../stream/)
* Klass [StreamReader](../)
* Klass [String](../../../system/string/)
* Namnrymd [System::IO](../../)
* Bibliotek [Aspose.Slides](../../../)