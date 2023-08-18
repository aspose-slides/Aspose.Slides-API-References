---
title: SetByte()
second_title: Aspose.Slides for C++ API Reference
description: Interprets the specified typed array as a raw byte array and sets the specified byte value at specified byte offset.
type: docs
weight: 40
url: /system/buffer/setbyte/
---
## Buffer::SetByte(const SharedPtr\<Array\<T\>\>\&, int, uint8_t) method


Interprets the specified typed array as a raw byte array and sets the specified byte value at specified byte offset.

```cpp
template<typename T> static void System::Buffer::SetByte(const SharedPtr<Array<T>> &array, int index, uint8_t value)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | The type of elements of the array |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| array | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<T\>\>\& | The target array |
| index | int | Zero-based offset of the byte to set |
| value | **uint8_t** | The byte value to set |

## Buffer::SetByte(const System::Details::ArrayView\<T\>\&, int, uint8_t) method


Interprets the specified typed array as a raw byte array and sets the specified byte value at specified byte offset.

```cpp
template<typename T> static void System::Buffer::SetByte(const System::Details::ArrayView<T> &array, int index, uint8_t value)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | The type of elements of the array |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| array | const System::Details::ArrayView\<T\>\& | The target array view |
| index | int | Zero-based offset of the byte to set |
| value | **uint8_t** | The byte value to set |

## Buffer::SetByte(const System::Details::StackArray\<T, N\>\&, int, uint8_t) method


Interprets the specified typed array as a raw byte array and sets the specified byte value at specified byte offset.

```cpp
template<typename T,std::size_t> static void System::Buffer::SetByte(const System::Details::StackArray<T, N> &array, int index, uint8_t value)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | The type of elements of the array |
| N | The size of the stack array |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| array | const System::Details::StackArray\<T, N\>\& | The target stack array |
| index | int | Zero-based offset of the byte to set |
| value | **uint8_t** | The byte value to set |

## See Also

* Typedef [SharedPtr](../../sharedptr/)
* Class [Array](../../array/)
* Class [Buffer](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)