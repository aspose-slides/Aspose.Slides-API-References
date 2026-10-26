---
title: Write()
second_title: Aspose.Slides för C++ API-referens
description: Skriver den angivna delmängden byte från den angivna bytearrayen till strömmen.
type: docs
weight: 248
url: /sv/system.io/filestream/write/
---
## FileStream::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) metod

Skriver den angivna delmängden byte från den angivna bytearrayen till strömmen.

```cpp
void System::IO::FileStream::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Arrayen som innehåller de byte som ska skrivas. |
| offset | **int32_t** | Ett nollbaserat index för elementet i **buffer** där delmängden som ska skrivas börjar. |
| count | **int32_t** | Antalet element i den delmängd som ska skrivas. |

## FileStream::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) metod

Skriver den angivna delmängden byte från den angivna bytearrayen till strömmen.

```cpp
void System::IO::FileStream::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Array-vyn som innehåller de byte som ska skrivas. |
| offset | **int32_t** | Ett nollbaserat index för elementet i **buffer** där delmängden som ska skrivas börjar. |
| count | **int32_t** | Antalet element i den delmängd som ska skrivas. |

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klass [FileStream](../)
* Namnrymd [System::IO](../../)
* Library [Aspose.Slides](../../../)