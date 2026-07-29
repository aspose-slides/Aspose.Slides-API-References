---
title: Read()
second_title: Aspose.Slides för C++ API-referens
description: Läser ett tecken från strömmen.
type: docs
weight: 40
url: /sv/system.io/textreader/read/
---
## TextReader::Read() metod


Läser ett tecken från strömmen.

```cpp
virtual int System::IO::TextReader::Read()
```


### Returvärde

Läs tecken kodade med UTF-16; om det lästa tecknet representeras av två kodpunkter i UTF-16 kodning returneras endast den högre surrogaten.

## TextReader::Read(ArrayPtr\<char_t\>, int, int) metod


Läser det angivna antalet tecken från strömmen och skriver dem till den angivna teckenarrayen med början vid den angivna positionen.

```cpp
virtual int System::IO::TextReader::Read(ArrayPtr<char_t> buffer, int index, int count)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | UTF-16-teckenarrayen att skriva tecknen som lästs från strömmen till |
| index | int | Ett 0-baserat index i **buffer** där skrivning ska påbörjas |
| count | int | Antalet tecken att läsa från strömmen |

### Returvärde

Antalet tecken som lästs från strömmen

## Se också

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klass [TextReader](../)
* Namnrymd [System::IO](../../)
* Library [Aspose.Slides](../../../)