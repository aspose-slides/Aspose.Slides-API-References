---
title: Write()
second_title: Aspose.Slides for C++ API Reference
description: Writes the specified subrange of bytes from the specified byte array to the stream.
type: docs
weight: 53
url: /system.io/stream/write/
---
## Stream::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) method


Writes the specified subrange of bytes from the specified byte array to the stream.

```cpp
virtual void System::IO::Stream::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | The array containing the bytes to write |
| offset | **int32_t** | A 0-based index of the element in **buffer** at which the subrange to write begins |
| count | **int32_t** | The number of elements in the subrange to write |

## Stream::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) method


Writes the specified subrange of bytes from the specified byte array to the stream.

```cpp
virtual void System::IO::Stream::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | The array view containing the bytes to write |
| offset | **int32_t** | A 0-based index of the element in **buffer** at which the subrange to write begins |
| count | **int32_t** | The number of elements in the subrange to write |

## Stream::Write(const System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t) method


Writes the specified subrange of bytes from the specified byte array to the stream.

```cpp
template<std::size_t> void System::IO::Stream::Write(const System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t count)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| N | The size of the stack array |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const System::Details::StackArray\<**uint8_t**, N\>\& | The stack array containing the bytes to write |
| offset | **int32_t** | A 0-based index of the element in **buffer** at which the subrange to write begins |
| count | **int32_t** | The number of elements in the subrange to write |

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Stream](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)