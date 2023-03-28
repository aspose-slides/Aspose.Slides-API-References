---
title: ByteLength()
second_title: Aspose.Slides for C++ API Reference
description: Determines the number of bytes occupied by all elements of the specified array.
type: docs
weight: 14
url: /cpp/system/buffer/bytelength/
---
## Buffer::ByteLength(const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<T\>\>\&) method


Determines the number of bytes occupied by all elements of the specified array.

```cpp
template<class T> static int System::Buffer::ByteLength(const SharedPtr<Array<T>> &array)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | The type of elements of the array |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| array | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<T\>\>\& | An array |

### Return Value

The number of bytes occupied by all elements of the specified array

## See Also

* Typedef [SharedPtr](../../sharedptr/)
* Class [Array](../../array/)
* Class [Buffer](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
## Buffer::ByteLength(const System::Details::ArrayView\<T\>\&) method


Determines the number of bytes occupied by all elements of the specified array.

```cpp
template<class T> static int System::Buffer::ByteLength(const System::Details::ArrayView<T> &array)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | The type of elements of the array view |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| array | const System::Details::ArrayView\<T\>\& | An array view |

### Return Value

The number of bytes occupied by all elements of the specified array view

## See Also

* Class [Buffer](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
## Buffer::ByteLength(const System::Details::StackArray\<T, N\>\&) method


Determines the number of bytes occupied by all elements of the specified array.

```cpp
template<class T,std::size_t> static int System::Buffer::ByteLength(const System::Details::StackArray<T, N> &array)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | The type of elements of the stack array |
| N | The size of the stack array |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| array | const System::Details::StackArray\<T, N\>\& | An stack array |

### Return Value

The number of bytes occupied by all elements of the specified stack array

## See Also

* Class [Buffer](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
