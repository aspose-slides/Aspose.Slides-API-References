---
title: GetByte()
second_title: Aspose.Slides for C++ API Reference
description: Interprets the specified typed array as a raw byte array and retrieves the byte value at specified byte offset.
type: docs
weight: 27
url: /cpp/system/buffer/getbyte/
---
## Buffer::GetByte(const SharedPtr\<Array\<T\>\>\&, int) method


Interprets the specified typed array as a raw byte array and retrieves the byte value at specified byte offset.

```cpp
template<typename T> static uint8_t System::Buffer::GetByte(const SharedPtr<Array<T>> &array, int index)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | The type of elements of the array |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| array | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<T\>\>\& | The target array |
| index | int | Zero-based offset of the byte to retrieve |

### Return Value

The byte value at the specified index

## Buffer::GetByte(const System::Details::ArrayView\<T\>\&, int) method


Interprets the specified typed array as a raw byte array and retrieves the byte value at specified byte offset.

```cpp
template<typename T> static uint8_t System::Buffer::GetByte(const System::Details::ArrayView<T> &array, int index)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | The type of elements of the array view |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| array | const System::Details::ArrayView\<T\>\& | The target array view |
| index | int | Zero-based offset of the byte to retrieve |

### Return Value

The byte value at the specified index

## Buffer::GetByte(const System::Details::StackArray\<T, N\>\&, int) method


Interprets the specified typed array as a raw byte array and retrieves the byte value at specified byte offset.

```cpp
template<typename T,std::size_t> static uint8_t System::Buffer::GetByte(const System::Details::StackArray<T, N> &array, int index)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | The type of elements of the stack array |
| N | The size of the stack array |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| array | const System::Details::StackArray\<T, N\>\& | The target stack array |
| index | int | Zero-based offset of the byte to retrieve |

### Return Value

The byte value at the specified index

## See Also

* Typedef [SharedPtr](../../sharedptr/)
* Class [Array](../../array/)
* Class [Buffer](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)