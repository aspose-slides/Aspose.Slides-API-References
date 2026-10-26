---
title: Read()
second_title: Aspose.Slides för C++ API-referens
description: Läser ett enda tecken från strömmen.
type: docs
weight: 40
url: /sv/system.io/stringreader/read/
---
## StringReader::Read() metod


Läser ett enda tecken från strömmen.

```cpp
virtual int System::IO::StringReader::Read() override
```


### Returvärde

Ett läst tecken eller -1 om inget tecken har lästs

## StringReader::Read(ArrayPtr\<char_t\>, int, int) metod


Läser det angivna antalet tecken från strömmen till den angivna teckenarrayen med start vid den angivna positionen.

```cpp
virtual int System::IO::StringReader::Read(ArrayPtr<char_t> buffer, int index, int count) override
```


### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Teckenarrayen att skriva de lästa tecknen från strömmen till |
| index | int | Ett 0-baserat index i **buffer** där skrivning ska börja |
| count | int | Antalet tecken att läsa från strömmen |

### Returvärde

Antalet tecken som lästs från strömmen

## Se också

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klass [StringReader](../)
* Namnrymd [System::IO](../../)
* Bibliotek [Aspose.Slides](../../../)