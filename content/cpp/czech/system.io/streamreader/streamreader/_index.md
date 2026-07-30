---
title: StreamReader()
second_title: Aspose.Slides pro C++ – reference k API
description: Vytvoří instanci objektu StreamReader, který čte znaky ze zadaného podkladového proudu pomocí kódování UTF-8 a bufferu s výchozí velikostí 1024 bajtů.
type: docs
weight: 1
url: /cs/system.io/streamreader/streamreader/
---
## StreamReader::StreamReader(const SharedPtr\<Stream\>\&) constructor

Vytvoří instanci objektu [StreamReader](../) , který čte znaky ze zadaného podkladového proudu pomocí kódování UTF-8 a bufferu s výchozí velikostí 1024 bajtů.

```cpp
System::IO::StreamReader::StreamReader(const SharedPtr<Stream> &stream)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | Podkladový proud, ze kterého se čtou znaky |

## StreamReader::StreamReader(const SharedPtr\<Stream\>\&, bool) constructor

Vytvoří instanci objektu [StreamReader](../) , který čte znaky ze zadaného podkladového proudu pomocí kódování UTF-8 a bufferu s výchozí velikostí 1024 bajtů. Parametr určuje, zda má být povoleno rozpoznávání značky pořadí bajtů.

```cpp
System::IO::StreamReader::StreamReader(const SharedPtr<Stream> &stream, bool detectEncodingFromByteOrderMarks)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | Podkladový proud, ze kterého se čtou znaky |
| detectEncodingFromByteOrderMarks | **bool** | True to look for byte order marks at the beginning of the stream, otherwise - false |

## StreamReader::StreamReader(const SharedPtr\<Stream\>\&, const EncodingPtr\&) constructor

Vytvoří instanci objektu [StreamReader](../) , který čte znaky ze zadaného podkladového proudu pomocí zadaného kódování a bufferu s výchozí velikostí 1024 bajtů.

```cpp
System::IO::StreamReader::StreamReader(const SharedPtr<Stream> &stream, const EncodingPtr &encoding)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | Podkladový proud, ze kterého se čtou znaky |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Kódování, které se má použít |

## StreamReader::StreamReader(const SharedPtr\<Stream\>\&, const EncodingPtr\&, bool) constructor

Vytvoří instanci objektu [StreamReader](../) , který čte znaky ze zadaného podkladového proudu pomocí zadaného kódování a bufferu s výchozí velikostí 1024 bajtů. Parametr určuje, zda má být povoleno rozpoznávání značky pořadí bajtů.

```cpp
System::IO::StreamReader::StreamReader(const SharedPtr<Stream> &stream, const EncodingPtr &encoding, bool detectEncodingFromByteOrderMarks)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | Podkladový proud, ze kterého se čtou znaky |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Kódování, které se má použít |
| detectEncodingFromByteOrderMarks | **bool** | True to look for byte order marks at the beginning of the stream, otherwise - false |

## StreamReader::StreamReader(const SharedPtr\<Stream\>\&, const EncodingPtr\&, bool, int) constructor

Vytvoří instanci objektu [StreamReader](../) , který čte znaky ze zadaného podkladového proudu pomocí zadaného kódování a bufferu o zadané velikosti. Parametr určuje, zda má být povoleno rozpoznávání značky pořadí bajtů.

```cpp
System::IO::StreamReader::StreamReader(const SharedPtr<Stream> &stream, const EncodingPtr &encoding, bool detectEncodingFromByteOrderMarks, int bufferSize)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | Podkladový proud, ze kterého se čtou znaky |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Kódování, které se má použít |
| detectEncodingFromByteOrderMarks | **bool** | True to look for byte order marks at the beginning of the stream, otherwise - false |
| bufferSize | int | Minimální velikost bufferu v bajtech |

## StreamReader::StreamReader(const System::String\&) constructor

Vytvoří instanci objektu [StreamReader](../) , který čte znaky ze zadaného souboru pomocí kódování UTF-8 a bufferu s výchozí velikostí 4096 bajtů.

```cpp
System::IO::StreamReader::StreamReader(const System::String &path)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| path | const [System::String](../../../system/string/)\& | Cesta k souboru, ze kterého se čtou znaky |

## StreamReader::StreamReader(const System::String\&, bool) constructor

Vytvoří instanci objektu [StreamReader](../) , který čte znaky ze zadaného souboru pomocí kódování UTF-8 a bufferu s výchozí velikostí 4096 bajtů. Parametr určuje, zda má být povoleno rozpoznávání značky pořadí bajtů.

```cpp
System::IO::StreamReader::StreamReader(const System::String &path, bool detectEncodingFromByteOrderMarks)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| path | const [System::String](../../../system/string/)\& | Cesta k souboru, ze kterého se čtou znaky |
| detectEncodingFromByteOrderMarks | **bool** | True to look for byte order marks at the beginning of the file, otherwise - false |

## StreamReader::StreamReader(const System::String\&, const EncodingPtr\&) constructor

Vytvoří instanci objektu [StreamReader](../) , který čte znaky ze zadaného souboru pomocí zadaného kódování a bufferu s výchozí velikostí 4096 bajtů.

```cpp
System::IO::StreamReader::StreamReader(const System::String &path, const EncodingPtr &encoding)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| path | const [System::String](../../../system/string/)\& | Cesta k souboru, ze kterého se čtou znaky |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Kódování, které se má použít |

## StreamReader::StreamReader(const System::String\&, const EncodingPtr\&, bool) constructor

Vytvoří instanci objektu [StreamReader](../) , který čte znaky ze zadaného podkladového proudu pomocí zadaného kódování a bufferu s výchozí velikostí 4096 bajtů. Parametr určuje, zda má být povoleno rozpoznávání značky pořadí bajtů.

```cpp
System::IO::StreamReader::StreamReader(const System::String &path, const EncodingPtr &encoding, bool detectEncodingFromByteOrderMarks)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| path | const [System::String](../../../system/string/)\& | Cesta k souboru, ze kterého se čtou znaky |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Kódování, které se má použít |
| detectEncodingFromByteOrderMarks | **bool** | True to look for byte order marks at the beginning of the file, otherwise - false |

## StreamReader::StreamReader(const System::String\&, const EncodingPtr\&, bool, int) constructor

Vytvoří instanci objektu [StreamReader](../) , který čte znaky ze zadaného souboru pomocí zadaného kódování a bufferu o zadané velikosti. Parametr určuje, zda má být povoleno rozpoznávání značky pořadí bajtů.

```cpp
System::IO::StreamReader::StreamReader(const System::String &path, const EncodingPtr &encoding, bool detectEncodingFromByteOrderMarks, int bufferSize)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| path | const [System::String](../../../system/string/)\& | Cesta k souboru, ze kterého se čtou znaky |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Kódování, které se má použít |
| detectEncodingFromByteOrderMarks | **bool** | True to look for byte order marks at the beginning of the file, otherwise - false |
| bufferSize | int | Minimální velikost bufferu v bajtech |

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Třída [Stream](../../stream/)
* Třída [StreamReader](../)
* Třída [String](../../../system/string/)
* Jmenný prostor [System::IO](../../)
* Knihovna [Aspose.Slides](../../../)