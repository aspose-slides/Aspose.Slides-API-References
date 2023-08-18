---
title: Write()
second_title: Aspose.Slides for C++ API Reference
description: Writes the specified subrange of bytes from the specified byte array to the stream.
type: docs
weight: 92
url: /system.io/memorystream/write/
---
## MemoryStream::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) method


Writes the specified subrange of bytes from the specified byte array to the stream.

```cpp
void System::IO::MemoryStream::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | The array containing the bytes to write |
| offset | **int32_t** | A 0-based index of the elemnet in **buffer** at which the subrange to write begins |
| count | **int32_t** | The number of elements in the subrange to write |

## MemoryStream::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) method


Writes the specified subrange of bytes from the specified byte array to the stream.

```cpp
void System::IO::MemoryStream::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | The array view containing the bytes to write |
| offset | **int32_t** | A 0-based index of the elemnet in **buffer** at which the subrange to write begins |
| count | **int32_t** | The number of elements in the subrange to write |

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [MemoryStream](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)