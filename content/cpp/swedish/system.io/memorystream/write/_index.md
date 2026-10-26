---
title: Write()
second_title: Aspose.Slides för C++ API-referens
description: Skriver den angivna delmängden av byte från den angivna bytearrayen till strömmen.
type: docs
weight: 92
url: /sv/system.io/memorystream/write/
---
## MemoryStream::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) metod

Skriver den angivna delmängden av byte från den angivna bytearrayen till strömmen.

```cpp
void System::IO::MemoryStream::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Arrayen som innehåller byte som ska skrivas |
| offset | **int32_t** | Ett nollbaserat index för elementet i **buffer** där delintervallet som ska skrivas börjar |
| count | **int32_t** | Antalet element i delintervallet som ska skrivas |

## MemoryStream::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) metod

Skriver den angivna delmängden av byte från den angivna bytearrayen till strömmen.

```cpp
void System::IO::MemoryStream::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Arrayvyn som innehåller byte som ska skrivas |
| offset | **int32_t** | Ett nollbaserat index för elementet i **buffer** där delintervallet som ska skrivas börjar |
| count | **int32_t** | Antalet element i delintervallet som ska skrivas |

## Se också

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klass [MemoryStream](../)
* Namnrymd [System::IO](../../)
* Bibliotek [Aspose.Slides](../../../)