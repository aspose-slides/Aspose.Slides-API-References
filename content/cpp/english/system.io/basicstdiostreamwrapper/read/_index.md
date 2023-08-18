---
title: Read()
second_title: Aspose.Slides for C++ API Reference
description: If wrapping mode is binary, reads the specified number of bytes from the stream, otherwise read the specified number of characters and converts them to uint8_t type. Writes result of the reading to the specified byte array.
type: docs
weight: 66
url: /system.io/basicstdiostreamwrapper/read/
---
## BasicSTDIOStreamWrapper::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) method


If wrapping mode is binary, reads the specified number of bytes from the stream, otherwise read the specified number of characters and converts them to **uint8_t** type. Writes result of the reading to the specified byte array.

```cpp
virtual int32_t System::IO::BasicSTDIOStreamWrapper<T, typename>::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | The byte array to write the read bytes to |
| offset | **int32_t** | A 0-based position in **buffer** to start writing at |
| count | **int32_t** | The number of bytes to read |

### Return Value

Number of bytes or characters read

## BasicSTDIOStreamWrapper::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) method


Reads the specified number of bytes from the stream and writes them to the specified byte array.

```cpp
virtual int32_t System::IO::BasicSTDIOStreamWrapper<T, typename>::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | The byte array view to write the read bytes to |
| offset | **int32_t** | A 0-based position in **buffer** to start writing at |
| count | **int32_t** | The number of bytes to read |

### Return Value

The number of bytes read

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [BasicSTDIOStreamWrapper](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)