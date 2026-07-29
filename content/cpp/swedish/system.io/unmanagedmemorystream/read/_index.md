---
title: Read()
second_title: Aspose.Slides för C++ API-referens
description: Läser det angivna antalet bytes från strömmen och skriver dem till den angivna byte-arrayen.
type: docs
weight: 144
url: /sv/system.io/unmanagedmemorystream/read/
---
## UnmanagedMemoryStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) method

Läser det angivna antalet bytes från strömmen och skriver dem till den angivna byte-arrayen.

```cpp
virtual int32_t System::IO::UnmanagedMemoryStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Byte-arrayen att skriva de lästa byten till |
| offset | **int32_t** | En 0-baserad position i **buffer** att börja skriva på |
| count | **int32_t** | Antalet bytes att läsa |

### Returvärde

Antalet lästa bytes

## UnmanagedMemoryStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) method

Läser det angivna antalet bytes från strömmen och skriver dem till den angivna byte-arrayen.

```cpp
virtual int32_t System::IO::UnmanagedMemoryStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Byte-array-vyn att skriva de lästa byten till |
| offset | **int32_t** | En 0-baserad position i **buffer** att börja skriva på |
| count | **int32_t** | Antalet bytes att läsa |

### Returvärde

Antalet lästa bytes

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klass [UnmanagedMemoryStream](../)
* Namnrymd [System::IO](../../)
* Library [Aspose.Slides](../../../)