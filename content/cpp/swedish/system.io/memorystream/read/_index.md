---
title: Read()
second_title: Aspose.Slides för C++ API-referens
description: Läser det angivna antalet byte från strömmen och skriver dem till den angivna bytearrayen.
type: docs
weight: 79
url: /sv/system.io/memorystream/read/
---
## MemoryStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) metod


Läser det angivna antalet byte från strömmen och skriver dem till den angivna bytearrayen.

```cpp
int32_t System::IO::MemoryStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Bytearrayen att skriva de lästa byten till |
| offset | **int32_t** | En 0-baserad position i **buffer** att börja skriva på |
| count | **int32_t** | Antalet byte att läsa |

### Returvärde

Antalet lästa byte

## MemoryStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) metod


Läser det angivna antalet byte från strömmen och skriver dem till den angivna bytearrayen.

```cpp
int32_t System::IO::MemoryStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Bytearray-vyn att skriva de lästa byten till |
| offset | **int32_t** | En 0-baserad position i **buffer** att börja skriva på |
| count | **int32_t** | Antalet byte att läsa |

### Returvärde

Antalet lästa byte

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klass [MemoryStream](../)
* Namnrymd [System::IO](../../)
* Bibliotek [Aspose.Slides](../../../)