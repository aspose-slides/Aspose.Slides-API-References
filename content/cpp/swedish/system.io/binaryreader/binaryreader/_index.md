---
title: BinaryReader()
second_title: Aspose.Slides för C++ API-referens
description: Skapar en instans av klassen BinaryReader som läser data från den angivna strömmen med UTF-8-kodning.
type: docs
weight: 1
url: /sv/system.io/binaryreader/binaryreader/
---
## BinaryReader::BinaryReader(const SharedPtr\<Stream\>\&) konstruktor

Skapar en instans av klassen [BinaryReader](../) som läser data från den angivna strömmen med UTF-8-kodning.

```cpp
System::IO::BinaryReader::BinaryReader(const SharedPtr<Stream> &input)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | Inmatningsströmmen |

## BinaryReader::BinaryReader(const SharedPtr\<Stream\>\&, const SharedPtr\<Text::Encoding\>\&) konstruktor

Skapar en instans av klassen [BinaryReader](../) som läser data från den angivna strömmen med den angivna kodningen.

```cpp
System::IO::BinaryReader::BinaryReader(const SharedPtr<Stream> &input, const SharedPtr<Text::Encoding> &encoding)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | Inmatningsströmmen |
| encoding | const [SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | Kodningen som ska användas |

## BinaryReader::BinaryReader(const SharedPtr\<Stream\>\&, const SharedPtr\<Text::Encoding\>\&, bool) konstruktor

Skapar en instans av klassen [BinaryReader](../) som läser data från den angivna strömmen med den angivna kodningen.

```cpp
System::IO::BinaryReader::BinaryReader(const SharedPtr<Stream> &input, const SharedPtr<Text::Encoding> &encoding, bool leaveOpen)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | Inmatningsströmmen |
| encoding | const [SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | Kodningen som ska användas |
| leaveOpen | **bool** | Anger om strömmen **input** ska lämnas öppen (true) efter att det aktuella objektet har frigjorts eller inte (false) |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [Stream](../../stream/)
* Klass [BinaryReader](../)
* Klass [Encoding](../../../system.text/encoding/)
* Namnrymd [System::IO](../../)
* Bibliotek [Aspose.Slides](../../../)