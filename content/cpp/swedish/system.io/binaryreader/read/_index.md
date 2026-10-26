---
title: Read()
second_title: Aspose.Slides för C++ API-referens
description: Läser ett tecken från inmatningsströmmen.
type: docs
weight: 66
url: /sv/system.io/binaryreader/read/
---
## BinaryReader::Read() metod


Läser ett enskilt tecken från inmatningsströmmen.

```cpp
virtual int System::IO::BinaryReader::Read()
```


### Returvärde

Läs tecken kodade med UTF-16-kodning; om det lästa tecknet representeras av två kodpunkter i UTF-16-kodning returneras endast den höga surrogaten.

## BinaryReader::Read(ArrayPtr\<uint8_t\>, int, int) metod


Läser det angivna antalet byte från inmatningsströmmen och skriver dem till den angivna bytearrayen.

```cpp
virtual int System::IO::BinaryReader::Read(ArrayPtr<uint8_t> buffer, int index, int count)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Bytearrayen att skriva de lästa byten till |
| index | int | En 0-baserad position i **buffer** att börja skriva vid |
| count | int | Antalet byte att läsa |

### Returvärde

Antalet byte som lästs

## BinaryReader::Read(ArrayPtr\<char_t\>, int, int) metod


Läser det angivna antalet tecken från inmatningsströmmen, konverterar dem till UTF-16-kodning och skriver de resulterande UTF-16-tecknen till den angivna teckenarrayen med början på den angivna positionen.

```cpp
virtual int System::IO::BinaryReader::Read(ArrayPtr<char_t> buffer, int index, int count)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Den UTF-16-teckenarrayen att skriva de tecken som lästs från inmatningsströmmen till |
| index | int | Ett 0-baserat index i **buffer** där skrivning ska påbörjas |
| count | int | Antalet tecken att läsa från strömmen |

### Returvärde

Antalet tecken som lästs från inmatningsströmmen

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klass [BinaryReader](../)
* Namnrymd [System::IO](../../)
* Bibliotek [Aspose.Slides](../../../)