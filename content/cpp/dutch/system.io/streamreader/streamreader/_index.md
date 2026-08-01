---
title: StreamReader()
second_title: Aspose.Slides voor C++ API-referentie
description: Construeert een instantie van StreamReader-object die tekens leest van de opgegeven onderliggende stream met UTF-8-codering en een buffer met een standaardgrootte van 1024 bytes.
type: docs
weight: 1
url: /nl/system.io/streamreader/streamreader/
---
## StreamReader::StreamReader(const SharedPtr\<Stream\>\&) constructor

Construeert een instantie van [StreamReader](../) object dat tekens leest van de opgegeven onderliggende stream met UTF-8-codering en een buffer met een standaardgrootte van 1024 bytes.

```cpp
System::IO::StreamReader::StreamReader(const SharedPtr<Stream> &stream)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | De onderliggende stream om tekens van te lezen |

## StreamReader::StreamReader(const SharedPtr\<Stream\>\&, bool) constructor

Construeert een instantie van [StreamReader](../) object dat tekens leest van de opgegeven onderliggende stream met UTF-8-codering en een buffer met een standaardgrootte van 1024 bytes. Een parameter geeft aan of detectie van byte order marks moet worden ingeschakeld.

```cpp
System::IO::StreamReader::StreamReader(const SharedPtr<Stream> &stream, bool detectEncodingFromByteOrderMarks)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | De onderliggende stream om tekens van te lezen |
| detectEncodingFromByteOrderMarks | **bool** | True om te zoeken naar byte order marks aan het begin van de stream, anders - false |

## StreamReader::StreamReader(const SharedPtr\<Stream\>\&, const EncodingPtr\&) constructor

Construeert een instantie van [StreamReader](../) object dat tekens leest van de opgegeven onderliggende stream met de opgegeven codering en een buffer met een standaardgrootte van 1024 bytes.

```cpp
System::IO::StreamReader::StreamReader(const SharedPtr<Stream> &stream, const EncodingPtr &encoding)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | De onderliggende stream om tekens van te lezen |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | De te gebruiken codering |

## StreamReader::StreamReader(const SharedPtr\<Stream\>\&, const EncodingPtr\&, bool) constructor

Construeert een instantie van [StreamReader](../) object dat tekens leest van de opgegeven onderliggende stream met de opgegeven codering en een buffer met een standaardgrootte van 1024 bytes. Een parameter geeft aan of detectie van byte order marks moet worden ingeschakeld.

```cpp
System::IO::StreamReader::StreamReader(const SharedPtr<Stream> &stream, const EncodingPtr &encoding, bool detectEncodingFromByteOrderMarks)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | De onderliggende stream om tekens van te lezen |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | De te gebruiken codering |
| detectEncodingFromByteOrderMarks | **bool** | True om te zoeken naar byte order marks aan het begin van de stream, anders - false |

## StreamReader::StreamReader(const SharedPtr\<Stream\>\&, const EncodingPtr\&, bool, int) constructor

Construeert een instantie van [StreamReader](../) object dat tekens leest van de opgegeven onderliggende stream met de opgegeven codering en een buffer met de opgegeven grootte. Een parameter geeft aan of detectie van byte order marks moet worden ingeschakeld.

```cpp
System::IO::StreamReader::StreamReader(const SharedPtr<Stream> &stream, const EncodingPtr &encoding, bool detectEncodingFromByteOrderMarks, int bufferSize)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | De onderliggende stream om tekens van te lezen |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | De te gebruiken codering |
| detectEncodingFromByteOrderMarks | **bool** | True om te zoeken naar byte order marks aan het begin van de stream, anders - false |
| bufferSize | int | De minimale grootte van de buffer in bytes |

## StreamReader::StreamReader(const System::String\&) constructor

Construeert een instantie van [StreamReader](../) object dat tekens leest van het opgegeven bestand met UTF-8-codering en een buffer met een standaardgrootte van 4096 bytes.

```cpp
System::IO::StreamReader::StreamReader(const System::String &path)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| path | const [System::String](../../../system/string/)\& | Het pad van het bestand om tekens van te lezen |

## StreamReader::StreamReader(const System::String\&, bool) constructor

Construeert een instantie van [StreamReader](../) object dat tekens leest van het opgegeven bestand met UTF-8-codering en een buffer met een standaardgrootte van 4096 bytes. Een parameter geeft aan of detectie van byte order marks moet worden ingeschakeld.

```cpp
System::IO::StreamReader::StreamReader(const System::String &path, bool detectEncodingFromByteOrderMarks)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| path | const [System::String](../../../system/string/)\& | Het pad van het bestand om tekens van te lezen |
| detectEncodingFromByteOrderMarks | **bool** | True om te zoeken naar byte order marks aan het begin van het bestand, anders - false |

## StreamReader::StreamReader(const System::String\&, const EncodingPtr\&) constructor

Construeert een instantie van [StreamReader](../) object dat tekens leest van het opgegeven bestand met de opgegeven codering en een buffer met een standaardgrootte van 4096 bytes.

```cpp
System::IO::StreamReader::StreamReader(const System::String &path, const EncodingPtr &encoding)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| path | const [System::String](../../../system/string/)\& | Het pad van het bestand om tekens van te lezen |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | De te gebruiken codering |

## StreamReader::StreamReader(const System::String\&, const EncodingPtr\&, bool) constructor

Construeert een instantie van [StreamReader](../) object dat tekens leest van de opgegeven onderliggende stream met de opgegeven codering en een buffer met een standaardgrootte van 4096 bytes. Een parameter geeft aan of detectie van byte order marks moet worden ingeschakeld.

```cpp
System::IO::StreamReader::StreamReader(const System::String &path, const EncodingPtr &encoding, bool detectEncodingFromByteOrderMarks)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| path | const [System::String](../../../system/string/)\& | Het pad van het bestand om tekens van te lezen |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | De te gebruiken codering |
| detectEncodingFromByteOrderMarks | **bool** | True om te zoeken naar byte order marks aan het begin van het bestand, anders - false |

## StreamReader::StreamReader(const System::String\&, const EncodingPtr\&, bool, int) constructor

Construeert een instantie van [StreamReader](../) object dat tekens leest van het opgegeven bestand met de opgegeven codering en een buffer met de opgegeven grootte. Een parameter geeft aan of detectie van byte order marks moet worden ingeschakeld.

```cpp
System::IO::StreamReader::StreamReader(const System::String &path, const EncodingPtr &encoding, bool detectEncodingFromByteOrderMarks, int bufferSize)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| path | const [System::String](../../../system/string/)\& | Het pad van het bestand om tekens van te lezen |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | De te gebruiken codering |
| detectEncodingFromByteOrderMarks | **bool** | True om te zoeken naar byte order marks aan het begin van het bestand, anders - false |
| bufferSize | int | De minimale grootte van de buffer in bytes |

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [Stream](../../stream/)
* Class [StreamReader](../)
* Class [String](../../../system/string/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)