---
title: BinaryReader()
second_title: Aspose.Slides pro C++ referenční příručka API
description: Vytvoří instanci třídy BinaryReader, která čte data ze zadaného proudu pomocí kódování UTF-8.
type: docs
weight: 1
url: /cs/system.io/binaryreader/binaryreader/
---
## BinaryReader::BinaryReader(const SharedPtr\<Stream\>\&) konstruktor


Vytvoří instanci třídy [BinaryReader](../), která čte data ze zadaného proudu pomocí kódování UTF-8.

```cpp
System::IO::BinaryReader::BinaryReader(const SharedPtr<Stream> &input)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | Vstupní proud |

## BinaryReader::BinaryReader(const SharedPtr\<Stream\>\&, const SharedPtr\<Text::Encoding\>\&) konstruktor


Vytvoří instanci třídy [BinaryReader](../), která čte data ze zadaného proudu pomocí zadaného kódování.

```cpp
System::IO::BinaryReader::BinaryReader(const SharedPtr<Stream> &input, const SharedPtr<Text::Encoding> &encoding)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | Vstupní proud |
| encoding | const [SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | Používané kódování |

## BinaryReader::BinaryReader(const SharedPtr\<Stream\>\&, const SharedPtr\<Text::Encoding\>\&, bool) konstruktor


Vytvoří instanci třídy [BinaryReader](../), která čte data ze zadaného proudu pomocí zadaného kódování.

```cpp
System::IO::BinaryReader::BinaryReader(const SharedPtr<Stream> &input, const SharedPtr<Text::Encoding> &encoding, bool leaveOpen)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | Vstupní proud |
| encoding | const [SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | Používané kódování |
| leaveOpen | **bool** | Určuje, zda má být proud **input** po uvolnění aktuálního objektu ponechán otevřený (true) nebo ne (false) |

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [Stream](../../stream/)
* Třída [BinaryReader](../)
* Třída [Encoding](../../../system.text/encoding/)
* Jmenný prostor [System::IO](../../)
* Knihovna [Aspose.Slides](../../../)