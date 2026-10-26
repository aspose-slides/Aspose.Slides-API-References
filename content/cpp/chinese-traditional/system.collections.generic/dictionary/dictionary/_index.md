---
title: Dictionary()
second_title: Aspose.Slides for C++ API 參考
description: 建立空字典。
type: docs
weight: 1
url: /zh-hant/system.collections.generic/dictionary/dictionary/
---
## Dictionary::Dictionary() 建構函式

建立空字典。

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary()
```

## Dictionary::Dictionary(const map_t\&) 建構函式

從 map 複製資料。

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary(const map_t &map)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| map | const [map_t](../map_t/)\& | 要從中複製資料的映射。 |

## Dictionary::Dictionary(int) 建構函式

此重載對應於建立預先分配的字典；實際上不進行分配。

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary(int capacity)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| capacity | int | 要分配的容量；會被忽略。 |

## Dictionary::Dictionary(const SharedPtr\<IDictionary\<TKey, TValue\>\>\&) 建構函式

複製建構函式。

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary(const SharedPtr<IDictionary<TKey, TValue>> &src)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| src | const [SharedPtr](../../../system/sharedptr/)\<[IDictionary](../../idictionary/)\<TKey, TValue\>\>\& | 用於從中複製資料的 [Dictionary](../)。 |

## Dictionary::Dictionary(const SharedPtr\<IDictionary\<TKey, TValue\>\>\&, const SharedPtr\<IEqualityComparer\<TKey\>\>\&) 建構函式

複製建構函式。

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary(const SharedPtr<IDictionary<TKey, TValue>> &src, const SharedPtr<IEqualityComparer<TKey>> &comparer)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| src | const [SharedPtr](../../../system/sharedptr/)\<[IDictionary](../../idictionary/)\<TKey, TValue\>\>\& | 來源字典。 |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[IEqualityComparer](../../iequalitycomparer/)\<TKey\>\>\& | 要使用的 [Comparer](../../comparer/) 物件。 |

## Dictionary::Dictionary(const SharedPtr\<IEqualityComparer\<TKey\>\>\&) 建構函式

建立空字典。

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary(const SharedPtr<IEqualityComparer<TKey>> &comparer)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[IEqualityComparer](../../iequalitycomparer/)\<TKey\>\>\& | 要使用的 [Comparer](../../comparer/)。 |

## Dictionary::Dictionary(int, const SharedPtr\<IEqualityComparer\<TKey\>\>\&) 建構函式

建立空字典。

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary(int capacity, const SharedPtr<IEqualityComparer<TKey>> &comparer)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| capacity | int | [Dictionary](../) 建立後的容量；會被忽略。 |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[IEqualityComparer](../../iequalitycomparer/)\<TKey\>\>\& | 要使用的 [Comparer](../../comparer/)。 |

## 另請參閱

* 類型別名 [map_t](../map_t/)
* 類型別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [Dictionary](../)
* 類別 [IDictionary](../../idictionary/)
* 類別 [IEqualityComparer](../../iequalitycomparer/)
* 命名空間 [System::Collections::Generic](../../)
* 函式庫 [Aspose.Slides](../../../)