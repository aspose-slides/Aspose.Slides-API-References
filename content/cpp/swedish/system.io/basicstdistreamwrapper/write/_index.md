---
title: Write()
second_title: Aspose.Slides för C++ API-referens
description: Om omslagsläget är binärt skrivs den angivna delmängden byte från den angivna byte-arrayen till strömmen, annars konverteras den angivna delmängden byte från den angivna byte-arrayen till char_type-typ och skrivs sedan resultatet till strömmen. Stöds inte!
type: docs
weight: 79
url: /sv/system.io/basicstdistreamwrapper/write/
---
## BasicSTDIStreamWrapper::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) metod

Om omslagsläget är binärt skrivs den angivna delmängden byte från den angivna byte-arrayen till strömmen, annars konverteras den angivna delmängden byte från den angivna byte-arrayen till char_type-typ och sedan skrivs resultatet till strömmen. Stöds inte!

```cpp
virtual void System::IO::BasicSTDIStreamWrapper<T, typename>::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Arrayen som innehåller bytena som ska skrivas. |
| offset | **int32_t** | Ett 0-baserat index för elementet i **buffer** där delmängden som ska skrivas börjar. |
| count | **int32_t** | Antalet element i delmängden som ska skrivas. |

## BasicSTDIStreamWrapper::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) metod

Skriver den angivna delmängden byte från den angivna byte-arrayen till strömmen.

```cpp
virtual void System::IO::BasicSTDIStreamWrapper<T, typename>::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Arrayvyn som innehåller bytena som ska skrivas |
| offset | **int32_t** | Ett 0-baserat index för elementet i **buffer** där delmängden som ska skrivas börjar |
| count | **int32_t** | Antalet element i delmängden som ska skrivas |

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klass [BasicSTDIStreamWrapper](../)
* Namnrymd [System::IO](../../)
* Bibliotek [Aspose.Slides](../../../)