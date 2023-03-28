---
title: Write()
second_title: Aspose.Slides for C++ API Reference
description: Writes the specified subrange of bytes from the specified byte array to the stream.
type: docs
weight: 209
url: /cpp/system.net.sockets/networkstream/write/
---
## NetworkStream::Write(const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) method


Writes the specified subrange of bytes from the specified byte array to the stream.

```cpp
void System::Net::Sockets::NetworkStream::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t size) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | The array containing the bytes to write. |
| offset | **int32_t** | The offset in bytes in the specified array. |
| size | **int32_t** | The number of elements in the subrange to write. |

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [NetworkStream](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)
## NetworkStream::Write(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) method


Writes the specified subrange of bytes from the specified byte array to the stream.

```cpp
void System::Net::Sockets::NetworkStream::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t size) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | The array view containing the bytes to write |
| offset | **int32_t** | A 0-based index of the element in **buffer** at which the subrange to write begins |
| size | **int32_t** | The number of elements in the subrange to write |

## See Also

* Class [NetworkStream](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)
