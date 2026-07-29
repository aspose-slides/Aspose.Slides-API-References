---
title: Read()
second_title: Aspose.Slides för C++ API-referens
description: Läser det angivna antalet byte från den underliggande strömmen och skriver dem till den angivna byte-arrayen.
type: docs
weight: 53
url: /sv/system.io/bufferedstream/read/
---
## BufferedStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) metod

Läser det angivna antalet byte från den underliggande strömmen och skriver dem till den angivna byte-arrayen.

```cpp
virtual int32_t System::IO::BufferedStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Byte-arrayen som de lästa byten ska skrivas till |
| offset | **int32_t** | En 0-baserad position i **buffer** för att börja skriva |
| count | **int32_t** | Antalet byte att läsa |

### Returvärde

Antalet lästa byte

## BufferedStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) metod

Läser det angivna antalet byte från den underliggande strömmen och skriver dem till den angivna byte-arrayen.

```cpp
virtual int32_t System::IO::BufferedStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Byte-arrayen som de lästa byten ska skrivas till |
| offset | **int32_t** | En 0-baserad position i **buffer** för att börja skriva |
| count | **int32_t** | Antalet byte att läsa |

### Returvärde

Antalet lästa byte

## Se också

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klass [BufferedStream](../)
* Namnrymd [System::IO](../../)
* Bibliotek [Aspose.Slides](../../../)