---
title: LastIndexOf()
second_title: Aspose.Slides for C++ API 參考文件
description: 搜尋指定的物件，並返回該物件在整個列表中最後一次出現的零基索引。
type: docs
weight: 469
url: /zh-hant/system.collections.generic/list/lastindexof/
---
## List::LastIndexOf(const T\&) const 方法


搜尋指定的物件，並返回該物件在整個列表中最後一次出現的零基索引。

```cpp
int32_t System::Collections::Generic::List<T>::LastIndexOf(const T &item) const
```


### 參數

| 參數 | 型別 | 描述 |
| --- | --- | --- |
| item | const T\& | 要在列表中定位的物件 |

### 返回值

如果找到，則返回項目在整個 [List](../) 中最後一次出現的零基索引；否則返回 -1。

## List::LastIndexOf(const T\&, int32_t) const 方法


搜尋指定的物件，並返回該物件在 [List](../) 中元素範圍內最後一次出現的零基索引，該範圍從第一個元素延伸至指定的索引。

```cpp
int32_t System::Collections::Generic::List<T>::LastIndexOf(const T &item, int32_t index) const
```


### 參數

| 參數 | 型別 | 描述 |
| --- | --- | --- |
| item | const T\& | 要在列表中定位的物件 |
| index | **int32_t** | 向後搜尋的零基起始索引。 |

### 返回值

如果找到，則返回項目在 [List](../) 中元素範圍內最後一次出現的零基索引，該範圍從第一個元素延伸至 index；否則返回 -1。

## List::LastIndexOf(const T\&, int32_t, int32_t) const 方法


搜尋指定的物件，並返回該物件在 [List](../) 中包含指定數量元素且於指定索引結束的元素範圍內最後一次出現的零基索引。

```cpp
int32_t System::Collections::Generic::List<T>::LastIndexOf(const T &item, int32_t index, int32_t count) const
```


### 參數

| 參數 | 型別 | 描述 |
| --- | --- | --- |
| item | const T\& | 要在 [List](../) 中定位的物件 |
| index | **int32_t** | 向後搜尋的零基起始索引。 |
| count | **int32_t** | 要搜尋之區段中的元素數量。 |

### 返回值

如果找到，則返回項目在 [List](../) 中包含 count 數量元素且於 index 結束的元素範圍內最後一次出現的零基索引；否則返回 -1。

## 另見

* 類別 [List](../)
* 命名空間 [System::Collections::Generic](../../)
* 函式庫 [Aspose.Slides](../../../)