---
title: Read()
second_title: Aspose.Slides for C++ API Reference
description: Reads the specified number of bytes from the stream and writes them to the specified byte array.
type: docs
weight: 27
url: /cpp/system.io/stream/read/
---
## Stream::Read(const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) method


Reads the specified number of bytes from the stream and writes them to the specified byte array.

```cpp
virtual int32_t System::IO::Stream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | The byte array to write the read bytes to |
| offset | **int32_t** | A 0-based position in **buffer** to start writing at |
| count | **int32_t** | The number of bytes to read |

### Return Value

The number of bytes read

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Stream](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)
## Stream::Read(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) method


Reads the specified number of bytes from the stream and writes them to the specified byte array.

```cpp
virtual int32_t System::IO::Stream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count)
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

* Class [Stream](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)
## Stream::Read(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) method


Reads the specified number of bytes from the stream and writes them to the specified byte array.

```cpp
template<std::size_t> int32_t System::IO::Stream::Read(const System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t count)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| N | The size of the stack array |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const System::Details::StackArray\<**uint8_t**, N\>\& | The byte stack array to write the read bytes to |
| offset | **int32_t** | A 0-based position in **buffer** to start writing at |
| count | **int32_t** | The number of bytes to read |

### Return Value

The number of bytes read

## See Also

* Class [Stream](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)
