---
title: Write()
second_title: Aspose.Slides för C++ API-referens
description: Skriver det angivna delintervallet av byte från den angivna bytearrayen till den underliggande strömmen.
type: docs
weight: 66
url: /sv/system.io/bufferedstream/write/
---
## BufferedStream::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) metod

Skriver det angivna delintervallet av byte från den angivna bytearrayen till den underliggande strömmen.

```cpp
virtual void System::IO::BufferedStream::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Arrayen som innehåller byte att skriva |
| offset | **int32_t** | Ett 0-baserat index för elementet i **buffer** där delintervallet som ska skrivas börjar |
| count | **int32_t** | Antalet element i delintervallet som ska skrivas |

## BufferedStream::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) metod

Skriver det angivna delintervallet av byte från den angivna bytearrayen till den underliggande strömmen.

```cpp
virtual void System::IO::BufferedStream::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Arrayen som innehåller byte att skriva |
| offset | **int32_t** | Ett 0-baserat index för elementet i **buffer** där delintervallet som ska skrivas börjar |
| count | **int32_t** | Antalet element i delintervallet som ska skrivas |

## Se också

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klass [BufferedStream](../)
* Namnrymd [System::IO](../../)
* Bibliotek [Aspose.Slides](../../../)