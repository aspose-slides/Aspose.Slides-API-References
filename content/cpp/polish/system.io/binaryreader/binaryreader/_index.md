---
title: BinaryReader()
second_title: Aspose.Slides dla C++ Referencja API
description: Tworzy instancję klasy BinaryReader, która odczytuje dane z określonego strumienia przy użyciu kodowania UTF-8.
type: docs
weight: 1
url: /pl/system.io/binaryreader/binaryreader/
---
## BinaryReader::BinaryReader(const SharedPtr\<Stream\>\&) konstruktor


Tworzy instancję klasy [BinaryReader](../), która odczytuje dane z określonego strumienia przy użyciu kodowania UTF-8.

```cpp
System::IO::BinaryReader::BinaryReader(const SharedPtr<Stream> &input)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | Strumień wejściowy |

## BinaryReader::BinaryReader(const SharedPtr\<Stream\>\&, const SharedPtr\<Text::Encoding\>\&) konstruktor


Tworzy instancję klasy [BinaryReader](../), która odczytuje dane z określonego strumienia przy użyciu podanego kodowania.

```cpp
System::IO::BinaryReader::BinaryReader(const SharedPtr<Stream> &input, const SharedPtr<Text::Encoding> &encoding)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | Strumień wejściowy |
| encoding | const [SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | Kodowanie do użycia |

## BinaryReader::BinaryReader(const SharedPtr\<Stream\>\&, const SharedPtr\<Text::Encoding\>\&, bool) konstruktor


Tworzy instancję klasy [BinaryReader](../), która odczytuje dane z określonego strumienia przy użyciu podanego kodowania.

```cpp
System::IO::BinaryReader::BinaryReader(const SharedPtr<Stream> &input, const SharedPtr<Text::Encoding> &encoding, bool leaveOpen)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | Strumień wejściowy |
| encoding | const [SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | Kodowanie do użycia |
| leaveOpen | **bool** | Określa, czy strumień **input** powinien pozostać otwarty (true) po zwolnieniu bieżącego obiektu, czy nie (false) |

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [Stream](../../stream/)
* Klasa [BinaryReader](../)
* Klasa [Encoding](../../../system.text/encoding/)
* Przestrzeń nazw [System::IO](../../)
* Biblioteka [Aspose.Slides](../../../)