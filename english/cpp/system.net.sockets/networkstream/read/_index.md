---
title: Read()
second_title: Aspose.Slides for C++ API Reference
description: Reads the specified number of bytes from the stream and writes them to the specified byte array.
type: docs
weight: 196
url: /cpp/system.net.sockets/networkstream/read/
---
## NetworkStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) method


Reads the specified number of bytes from the stream and writes them to the specified byte array.

```cpp
int32_t System::Net::Sockets::NetworkStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t size) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | The byte array where the read bytes will be written. |
| offset | **int32_t** | The offset in bytes in the specified array. |
| size | **int32_t** | The number of bytes to read. |

### Return Value

The number of read bytes.

## NetworkStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) method


Reads the specified number of bytes from the stream and writes them to the specified byte array.

```cpp
int32_t System::Net::Sockets::NetworkStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t size) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | The byte array view to write the read bytes to |
| offset | **int32_t** | A 0-based position in **buffer** to start writing at |
| size | **int32_t** | The number of bytes to read |

### Return Value

The number of bytes read

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [NetworkStream](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)