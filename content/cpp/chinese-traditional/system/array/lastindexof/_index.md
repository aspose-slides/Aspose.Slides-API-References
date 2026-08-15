---
title: LastIndexOf()
second_title: Aspose.Slides for C++ API 參考
description: 確定由起始索引與範圍內元素數量所指定之陣列項目範圍中，指定項目最後一次出現的索引。
type: docs
weight: 703
url: /zh-hant/system/array/lastindexof/
---
## Array::LastIndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&, int, int) 方法

確定指定項目在陣列中由起始索引和範圍內元素數量所限定的項目範圍內最後一次出現的索引。

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::LastIndexOf(const ArrayPtr<ArrayType> &arr, const ValueType &value, int startIndex, int count)
```

### 範本參數

| 參數 | 說明 |
| --- | --- |
| ArrayType | 目標陣列中元素的類型 |
| ValueType | 於陣列中搜尋之項目的類型 |

### 引數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<ArrayType\>\& | [Array](../) 用於搜尋指定的項目 |
| value | const [ValueType](../valuetype/)\& | 要確定其索引的項目 |
| startIndex | int | [Index](../../index/) 開始搜尋的索引 |
| count | int | 要搜尋之範圍的元素數量 |

### 回傳值

[Index](../../index/) 若找到指定項目則為最後一次出現的索引，否則為 -1

## Array::LastIndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&, int) 方法

確定指定項目在陣列中自指定索引起最後一次出現的索引。

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::LastIndexOf(const ArrayPtr<ArrayType> &items, const ValueType &value, int startIndex)
```

### 範本參數

| 參數 | 說明 |
| --- | --- |
| ArrayType | 目標陣列中元素的類型 |
| ValueType | 於陣列中搜尋之項目的類型 |

### 引數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| items | const [ArrayPtr](../../arrayptr/)\<ArrayType\>\& | [Array](../) 用於搜尋指定的項目 |
| value | const [ValueType](../valuetype/)\& | 要確定其索引的項目 |
| startIndex | int | [Index](../../index/) 開始搜尋的索引 |

### 回傳值

[Index](../../index/) 若找到指定項目則為最後一次出現的索引，否則為 -1

## Array::LastIndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&) 方法

確定指定項目在陣列中最後一次出現的索引。

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::LastIndexOf(const ArrayPtr<ArrayType> &items, const ValueType &value)
```

### 範本參數

| 參數 | 說明 |
| --- | --- |
| ArrayType | 目標陣列中元素的類型 |
| ValueType | 於陣列中搜尋之項目的類型 |

### 引數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| items | const [ArrayPtr](../../arrayptr/)\<ArrayType\>\& | [Array](../) 用於搜尋指定的項目 |
| value | const [ValueType](../valuetype/)\& | 要確定其索引的項目 |

### 回傳值

[Index](../../index/) 若找到指定項目則為最後一次出現的索引，否則為 -1

## 另請參閱

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [ValueType](../valuetype/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)