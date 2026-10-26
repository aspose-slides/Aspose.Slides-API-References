---
title: BinaryReader()
second_title: Aspose.Slides C++ API referencia
description: Létrehoz egy BinaryReader osztály példányt, amely a megadott adatfolyamból UTF-8 kódolással olvas adatot.
type: docs
weight: 1
url: /hu/system.io/binaryreader/binaryreader/
---
## BinaryReader::BinaryReader(const SharedPtr\<Stream\>\&) konstruktor


Létrehoz egy [BinaryReader](../) osztály példányt, amely a megadott adatfolyamból UTF-8 kódolással olvas adatot.

```cpp
System::IO::BinaryReader::BinaryReader(const SharedPtr<Stream> &input)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | A bemeneti adatfolyam |

## BinaryReader::BinaryReader(const SharedPtr\<Stream\>\&, const SharedPtr\<Text::Encoding\>\&) konstruktor


Létrehoz egy [BinaryReader](../) osztály példányt, amely a megadott adatfolyamból a megadott kódolással olvas adatot.

```cpp
System::IO::BinaryReader::BinaryReader(const SharedPtr<Stream> &input, const SharedPtr<Text::Encoding> &encoding)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | A bemeneti adatfolyam |
| encoding | const [SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | A használandó kódolás |

## BinaryReader::BinaryReader(const SharedPtr\<Stream\>\&, const SharedPtr\<Text::Encoding\>\&, bool) konstruktor


Létrehoz egy [BinaryReader](../) osztály példányt, amely a megadott adatfolyamból a megadott kódolással olvas adatot.

```cpp
System::IO::BinaryReader::BinaryReader(const SharedPtr<Stream> &input, const SharedPtr<Text::Encoding> &encoding, bool leaveOpen)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | A bemeneti adatfolyam |
| encoding | const [SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | A használandó kódolás |
| leaveOpen | **bool** | Megadja, hogy a **input** adatfolyam nyitva marad-e (true) az aktuális objektum eldobása után, vagy ne (false) |

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [Stream](../../stream/)
* Osztály [BinaryReader](../)
* Osztály [Encoding](../../../system.text/encoding/)
* Névterület [System::IO](../../)
* Könyvtár [Aspose.Slides](../../../)