---
title: GetByte()
second_title: Aspose.Slides for C++ API 參考文件
description: 將指定的具型別陣列視為原始位元組陣列，並在指定的位元組偏移量取得位元組值。
type: docs
weight: 27
url: /zh-hant/system/buffer/getbyte/
---
## Buffer::GetByte(const SharedPtr\<Array\<T\>\>\&, int) method

將指定的具型別陣列視為原始位元組陣列，並在指定的位元組偏移量取得位元組值。

```cpp
template<typename T> static uint8_t System::Buffer::GetByte(const SharedPtr<Array<T>> &array, int index)
```

### 模板參數

| Parameter | Description |
| --- | --- |
| T | 陣列中元素的型別 |

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| array | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<T\>\>\& | 目標陣列 |
| index | int | 要取得的位元組之零基偏移量 |

### 傳回值

指定索引處的位元組值

## Buffer::GetByte(const System::Details::ArrayView\<T\>\&, int) method

將指定的具型別陣列視為原始位元組陣列，並在指定的位元組偏移量取得位元組值。

```cpp
template<typename T> static uint8_t System::Buffer::GetByte(const System::Details::ArrayView<T> &array, int index)
```

### 模板參數

| Parameter | Description |
| --- | --- |
| T | 陣列檢視中元素的型別 |

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| array | const System::Details::ArrayView\<T\>\& | 目標陣列檢視 |
| index | int | 要取得的位元組之零基偏移量 |

### 傳回值

指定索引處的位元組值

## Buffer::GetByte(const System::Details::StackArray\<T, N\>\&, int) method

將指定的具型別陣列視為原始位元組陣列，並在指定的位元組偏移量取得位元組值。

```cpp
template<typename T,std::size_t> static uint8_t System::Buffer::GetByte(const System::Details::StackArray<T, N> &array, int index)
```

### 模板參數

| Parameter | Description |
| --- | --- |
| T | 堆疊陣列中元素的型別 |
| N | 堆疊陣列的大小 |

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| array | const System::Details::StackArray\<T, N\>\& | 目標堆疊陣列 |
| index | int | 要取得的位元組之零基偏移量 |

### 傳回值

指定索引處的位元組值

## 另請參閱

* 型別定義 [SharedPtr](../../sharedptr/)
* 類別 [Array](../../array/)
* 類別 [Buffer](../)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)