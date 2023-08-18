---
title: Read()
second_title: Aspose.Slides for C++ API Reference
description: Reads the specified number of bytes from the underlying stream and writes them to the specified byte array.
type: docs
weight: 53
url: /system.io/bufferedstream/read/
---
## BufferedStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) method


Reads the specified number of bytes from the underlying stream and writes them to the specified byte array.

```cpp
virtual int32_t System::IO::BufferedStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | The byte array to write the read bytes to |
| offset | **int32_t** | A 0-based position in **buffer** to start writing at |
| count | **int32_t** | The number of bytes to read |

### Return Value

The number of bytes read

## BufferedStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) method


Reads the specified number of bytes from the underlying stream and writes them to the specified byte array.

```cpp
virtual int32_t System::IO::BufferedStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | The byte array to write the read bytes to |
| offset | **int32_t** | A 0-based position in **buffer** to start writing at |
| count | **int32_t** | The number of bytes to read |

### Return Value

The number of bytes read

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [BufferedStream](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)