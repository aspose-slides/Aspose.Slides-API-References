---
title: Write()
second_title: Aspose.Slides för C++ API-referens
description: Om omslagsläget är binärt skrivs det angivna delintervallet av byte från den angivna byte-arrayen till strömmen, annars konverteras det angivna delintervallet av byte från den angivna byte-arrayen till char_type-typ och resultatet skrivs sedan till strömmen.
type: docs
weight: 79
url: /sv/system.io/basicstdostreamwrapper/write/
---
## BasicSTDOStreamWrapper::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) method


Om omslagsläget är binary, skriver den angivna delintervallet av byte från den angivna byte-arrayen till strömmen, annars konverterar den det angivna delintervallet av byte från den angivna byte-arrayen till char_type-typ och skriver sedan resultatet till strömmen.

```cpp
virtual void System::IO::BasicSTDOStreamWrapper<T, typename>::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Arrayen som innehåller byte som ska skrivas |
| offset | **int32_t** | Ett nollbaserat index för elementet i **buffer** där delintervallet som ska skrivas börjar |
| count | **int32_t** | Antalet element i delintervallet som ska skrivas |

## BasicSTDOStreamWrapper::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) method


Skriver det angivna delintervallet av byte från den angivna byte-arrayen till strömmen.

```cpp
virtual void System::IO::BasicSTDOStreamWrapper<T, typename>::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Array-vyn som innehåller byte som ska skrivas |
| offset | **int32_t** | Ett nollbaserat index för elementet i **buffer** där delintervallet som ska skrivas börjar |
| count | **int32_t** | Antalet element i delintervallet som ska skrivas |

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [BasicSTDOStreamWrapper](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)