---
title: MemoryStream()
second_title: Aspose.Slides for C++ API Reference
description: Constructs a new instance of the MemoryStream class with initial capacity equal to 0.
type: docs
weight: 1
url: /system.io/memorystream/memorystream/
---
## MemoryStream::MemoryStream() constructor


Constructs a new instance of the [MemoryStream](../) class with initial capacity equal to 0.

```cpp
System::IO::MemoryStream::MemoryStream()
```

## MemoryStream::MemoryStream(int) constructor


Constructs a new instance of the [MemoryStream](../) class that represents a stream based on a memory buffer of the specified size.

```cpp
System::IO::MemoryStream::MemoryStream(int capacity_)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| capacity_ | int | The size in bytes of a memory buffer associated with the stream represented by the object being created |

## MemoryStream::MemoryStream(const ArrayPtr\<uint8_t\>\&, bool) constructor


Constructs a new instance of the [MemoryStream](../) class that represents a memory stream which is connected to the specified memory buffer. A parameter specifies if the stream is writable.

```cpp
System::IO::MemoryStream::MemoryStream(const ArrayPtr<uint8_t> &content, bool writable=1)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| content | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | A byte array to be used as a memory buffer on which the stream represented by the object being created will be based |
| writable | **bool** | Specifies if the stream should be writable |

## MemoryStream::MemoryStream(const ArrayPtr\<uint8_t\>\&, int, int, bool, bool) constructor


Constructs a new instance of the [MemoryStream](../) class that represents a memory stream which is connected to a segment of the specified memory buffer starting at the specified index and including the specified number of elements. Parameters specifies if the stream is writable and if method GetBytes() can be called.

```cpp
System::IO::MemoryStream::MemoryStream(const ArrayPtr<uint8_t> &content, int index, int count, bool writable=1, bool publiclyVisible=false)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| content | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | A byte array a segment of which is to be used as a memory buffer on which the stream represented by the object being created will be based |
| index | int | A 0-based index of the element in **content** at which the segment begins |
| count | int | The number of elements of **content** included in the segment |
| writable | **bool** | Specifies if the stream should be writable |
| publiclyVisible | **bool** | Specifies if the underlying memory buffer should be made available to the caller of method GetByte() |

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [MemoryStream](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)