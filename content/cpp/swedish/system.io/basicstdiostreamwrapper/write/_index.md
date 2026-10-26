---
title: Write()
second_title: Aspose.Slides för C++ API-referens
description: Om omslagläge är binärt skrivs det angivna delintervallet av byte från den angivna byte-arrayen till strömmen, annars konverteras det angivna delintervallet av byte från den angivna byte-arrayen till char_type-typen och skrivs sedan resultatet till strömmen.
type: docs
weight: 79
url: /sv/system.io/basicstdiostreamwrapper/write/
---
## BasicSTDIOStreamWrapper::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) metod

Om omslagsläget är binärt, skrivs den angivna delintervallet av byte från den angivna byte-arrayen till strömmen, annars konverteras det angivna delintervallet av byte från den angivna byte-arrayen till char_type-typen och skrivs sedan resultatet till strömmen.

```cpp
virtual void System::IO::BasicSTDIOStreamWrapper<T, typename>::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Arguments

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Arrayen som innehåller de byte som ska skrivas |
| offset | **int32_t** | Ett 0-baserat index för elementet i **buffer** där delintervallet som ska skrivas börjar |
| count | **int32_t** | Antalet element i delintervallet som ska skrivas |

## BasicSTDIOStreamWrapper::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) metod

Skriver det angivna delintervallet av byte från den angivna byte-arrayen till strömmen.

```cpp
virtual void System::IO::BasicSTDIOStreamWrapper<T, typename>::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Arguments

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Array-vyn som innehåller de byte som ska skrivas |
| offset | **int32_t** | Ett 0-baserat index för elementet i **buffer** där delintervallet som ska skrivas börjar |
| count | **int32_t** | Antalet element i delintervallet som ska skrivas |

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klass [BasicSTDIOStreamWrapper](../)
* Namnrymd [System::IO](../../)
* Bibliotek [Aspose.Slides](../../../)