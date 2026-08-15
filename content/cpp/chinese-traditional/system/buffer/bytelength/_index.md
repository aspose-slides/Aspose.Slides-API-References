---
title: ByteLength()
second_title: Aspose.Slides for C++ API 參考
description: 確定指定陣列中所有元素佔用的位元組數。
type: docs
weight: 14
url: /zh-hant/system/buffer/bytelength/
---
## Buffer::ByteLength(const SharedPtr\<Array\<T\>\>\&) 方法


確定指定陣列中所有元素佔用的位元組數。

```cpp
template<class T> static int System::Buffer::ByteLength(const SharedPtr<Array<T>> &array)
```


### 模板參數

| Parameter | Description |
| --- | --- |
| T | The type of elements of the array |

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| array | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<T\>\>\& | 一個陣列 |

### 返回值

The number of bytes occupied by all elements of the specified array

## Buffer::ByteLength(const System::Details::ArrayView\<T\>\&) 方法


確定指定陣列中所有元素佔用的位元組數。

```cpp
template<class T> static int System::Buffer::ByteLength(const System::Details::ArrayView<T> &array)
```


### 模板參數

| Parameter | Description |
| --- | --- |
| T | The type of elements of the array view |

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| array | const System::Details::ArrayView\<T\>\& | 一個陣列視圖 |

### 返回值

The number of bytes occupied by all elements of the specified array view

## Buffer::ByteLength(const System::Details::StackArray\<T, N\>\&) 方法


確定指定陣列中所有元素佔用的位元組數。

```cpp
template<class T,std::size_t> static int System::Buffer::ByteLength(const System::Details::StackArray<T, N> &array)
```


### 模板參數

| Parameter | Description |
| --- | --- |
| T | The type of elements of the stack array |
| N | The size of the stack array |

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| array | const System::Details::StackArray\<T, N\>\& | 一個堆疊陣列 |

### 返回值

The number of bytes occupied by all elements of the specified stack array

## 另見

* Typedef [SharedPtr](../../sharedptr/)
* 類別 [Array](../../array/)
* 類別 [Buffer](../)
* 命名空間 [System](../../)
* Library [Aspose.Slides](../../../)