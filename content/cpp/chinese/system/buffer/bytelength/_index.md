---
title: ByteLength()
second_title: Aspose.Slides for C++ API 参考
description: 确定指定数组中所有元素占用的字节数。
type: docs
weight: 14
url: /zh/system/buffer/bytelength/
---
## Buffer::ByteLength(const SharedPtr\<Array\<T\>\>\&) 方法


确定指定数组中所有元素占用的字节数。

```cpp
template<class T> static int System::Buffer::ByteLength(const SharedPtr<Array<T>> &array)
```


### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | The type of elements of the array |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| array | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<T\>\>\& | An array |

### 返回值

The number of bytes occupied by all elements of the specified array

## Buffer::ByteLength(const System::Details::ArrayView\<T\>\&) 方法


确定指定数组中所有元素占用的字节数。

```cpp
template<class T> static int System::Buffer::ByteLength(const System::Details::ArrayView<T> &array)
```


### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | The type of elements of the array view |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| array | const System::Details::ArrayView\<T\>\& | An array view |

### 返回值

The number of bytes occupied by all elements of the specified array view

## Buffer::ByteLength(const System::Details::StackArray\<T, N\>\&) 方法


确定指定数组中所有元素占用的字节数。

```cpp
template<class T,std::size_t> static int System::Buffer::ByteLength(const System::Details::StackArray<T, N> &array)
```


### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | The type of elements of the stack array |
| N | The size of the stack array |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| array | const System::Details::StackArray\<T, N\>\& | An stack array |

### 返回值

The number of bytes occupied by all elements of the specified stack array

## 参见

* Typedef [SharedPtr](../../sharedptr/)
* 类 [Array](../../array/)
* 类 [Buffer](../)
* 命名空间 [System](../../)
* Library [Aspose.Slides](../../../)