---
title: Read()
second_title: Aspose.Slides för C++ API-referens
description: Läser ett tecken från strömmen.
type: docs
weight: 40
url: /sv/system.io/streamreader/read/
---
## StreamReader::Read() metod


Läser ett tecken från strömmen.

```cpp
virtual int System::IO::StreamReader::Read() override
```


### Returvärde

Läst tecken kodat med UTF-16; om det lästa tecknet representeras av två kodpunkter i UTF-16-kodning returneras endast den höga surrogaten.

## StreamReader::Read(ArrayPtr\<char_t\>, int, int) metod


Läser det angivna antalet tecken från strömmen, konverterar dem till UTF-16-kodning och skriver de resulterande UTF-16-tecknen till den angivna teckenarrayen med början på den angivna positionen.

```cpp
virtual int System::IO::StreamReader::Read(ArrayPtr<char_t> buffer, int index, int count) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | UTF-16-teckenarrayen att skriva de tecken som läses från strömmen till |
| index | int | Ett 0-baserat index i **buffer** där skrivandet ska börja |
| count | int | Antalet tecken att läsa från strömmen |

### Returvärde

Antalet tecken som lästes från strömmen

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klass [StreamReader](../)
* Namnrymd [System::IO](../../)
* Bibliotek [Aspose.Slides](../../../)