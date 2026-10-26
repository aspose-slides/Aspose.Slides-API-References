---
title: IndexOf()
second_title: Aspose.Slides for C++ API 參考文件
description: 確定陣列中指定項目第一次出現的索引。
type: docs
weight: 131
url: /zh-hant/system/array/indexof/
---
## Array::IndexOf(const T\&) const 方法

判斷陣列中指定項目第一次出現的索引。

```cpp
virtual int System::Array<T>::IndexOf(const T &item) const override
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| item | const T\& | 要確定其索引的項目 |

### 回傳值

[Index](../../index/) 首次出現指定項目的索引，如果找到項目，否則返回 -1

## Array::IndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&) 方法

判斷陣列中指定項目第一次出現的索引。

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::IndexOf(const ArrayPtr<ArrayType> &arr, const ValueType &value)
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| ArrayType | 目標陣列中元素的型別 |
| ValueType | 在陣列中搜尋的項目型別 |

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<ArrayType\>\& | [Array](../) 用於搜尋指定的項目 |
| value | const [ValueType](../valuetype/)\& | 要確定其索引的項目 |

### 回傳值

[Index](../../index/) 首次出現指定項目的索引，如果找到項目，否則返回 -1

## Array::IndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&, int) 方法

判斷從指定索引開始，陣列中指定項目第一次出現的索引。

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::IndexOf(const ArrayPtr<ArrayType> &arr, const ValueType &value, int startIndex)
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| ArrayType | 目標陣列中元素的型別 |
| ValueType | 在陣列中搜尋的項目型別 |

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<ArrayType\>\& | [Array](../) 用於搜尋指定的項目 |
| value | const [ValueType](../valuetype/)\& | 要確定其索引的項目 |
| startIndex | int | [Index](../../index/) 搜尋開始的索引 |

### 回傳值

[Index](../../index/) 首次出現指定項目的索引，如果找到項目，否則返回 -1

## Array::IndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&, int, int) 方法

判斷在由起始索引和範圍內元素數量指定的陣列項目範圍中，指定項目第一次出現的索引。

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::IndexOf(const ArrayPtr<ArrayType> &arr, const ValueType &value, int startIndex, int count)
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| ArrayType | 目標陣列中元素的型別 |
| ValueType | 在陣列中搜尋的項目型別 |

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<ArrayType\>\& | [Array](../) 用於搜尋指定的項目 |
| value | const [ValueType](../valuetype/)\& | 要確定其索引的項目 |
| startIndex | int | [Index](../../index/) 搜尋開始的索引 |
| count | int | 要搜尋的範圍內元素的數量 |

### 回傳值

[Index](../../index/) 首次出現指定項目的索引，如果找到項目，否則返回 -1

## 另見

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [ValueType](../valuetype/)
* 類別 [Array](../)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)