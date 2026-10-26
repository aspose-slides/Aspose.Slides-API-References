---
title: Sort()
second_title: Aspose.Slides for C++ API 參考文件
description: 使用自訂比較器對 Span 進行排序。
type: docs
weight: 339
url: /zh-hant/system.memoryextensions/sort/
---
## System::MemoryExtensions::Sort(const Span\<T\>\&, const SharedPtr\<TComparer\>\&) 函式

使用自訂比較器對 [Span](../../system/span/) 進行排序。

```cpp
template<typename T,typename TComparer> void System::MemoryExtensions::Sort(const Span<T> &span, const SharedPtr<TComparer> &comparer)
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | Span 中元素的類型 |
| TComparer | 比較器物件的類型 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 要排序的 span |
| comparer | const [SharedPtr](../../system/sharedptr/)\<TComparer\>\& | 用於元素比較的 comparer 智慧指標 |

## System::MemoryExtensions::Sort(Span\<T\>\&) 函式

使用預設比較方式對 [Span](../../system/span/) 進行排序。

```cpp
template<typename T> void System::MemoryExtensions::Sort(Span<T> &span)
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | Span 中元素的類型 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | 要排序的 span |

## System::MemoryExtensions::Sort(Span\<TKey\>\&, Span\<TValue\>\&, const SharedPtr\<TComparer\>\&) 函式

使用自訂比較器對鍵值對進行排序（鍵和值一起排序）

```cpp
template<typename TKey,typename TValue,typename TComparer> void System::MemoryExtensions::Sort(Span<TKey> &keys, Span<TValue> &values, const SharedPtr<TComparer> &comparer)
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| TKey | 鍵的類型 |
| TValue | 值的類型 |
| TComparer | 比較器物件的類型 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | 要排序的 keys |
| values | [Span](../../system/span/)\<TValue\>\& | 要排序的 values（與 keys 保持對應） |
| comparer | const [SharedPtr](../../system/sharedptr/)\<TComparer\>\& | 用於鍵比較的 comparer 智慧指標 |

## System::MemoryExtensions::Sort(Span\<TKey\>\&, Span\<TValue\>\&, System::Comparison\<TKey\>) 函式

使用比較委派對鍵值對進行排序。

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Sort(Span<TKey> &keys, Span<TValue> &values, System::Comparison<TKey> comparer)
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| TKey | 鍵的類型 |
| TValue | 值的類型 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | 要排序的 keys |
| values | [Span](../../system/span/)\<TValue\>\& | 要排序的 values |
| comparer | [System::Comparison](../../system/comparison/)\<TKey\> | [Comparison](../../system/comparison/) 委派用於鍵比較 |

## System::MemoryExtensions::Sort(Span\<TKey\>\&, Span\<TValue\>\&) 函式

使用預設比較方式對鍵值對進行排序。

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Sort(Span<TKey> &keys, Span<TValue> &values)
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| TKey | 鍵的類型 |
| TValue | 值的類型 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | 要排序的 keys |
| values | [Span](../../system/span/)\<TValue\>\& | 要排序的 values |

## 參見

* 型別別名 [SharedPtr](../../system/sharedptr/)
* 類別 [Span](../../system/span/)
* 類別 [Comparison](../../system/comparison/)
* 命名空間 [System::MemoryExtensions](../)
* 函式庫 [Aspose.Slides](../../)