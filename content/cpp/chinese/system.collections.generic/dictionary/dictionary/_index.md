---
title: Dictionary()
second_title: Aspose.Slides for C++ API 参考
description: 创建空字典。
type: docs
weight: 1
url: /zh/system.collections.generic/dictionary/dictionary/
---
## Dictionary::Dictionary() 构造函数

创建空字典。

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary()
```

## Dictionary::Dictionary(const map_t\&) 构造函数

从 map 复制数据。

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary(const map_t &map)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| map | const [map_t](../map_t/)\& | 要从中复制数据的 map。 |

## Dictionary::Dictionary(int) 构造函数

对应创建预分配字典的重载；实际上不进行分配。

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary(int capacity)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| capacity | int | 要分配的容量；已忽略。 |

## Dictionary::Dictionary(const SharedPtr\<IDictionary\<TKey, TValue\>\>\&) 构造函数

复制构造函数。

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary(const SharedPtr<IDictionary<TKey, TValue>> &src)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| src | const [SharedPtr](../../../system/sharedptr/)\<[IDictionary](../../idictionary/)\<TKey, TValue\>\>\& | [Dictionary](../) 用于复制数据。 |

## Dictionary::Dictionary(const SharedPtr\<IDictionary\<TKey, TValue\>\>\&, const SharedPtr\<IEqualityComparer\<TKey\>\>\&) 构造函数

复制构造函数。

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary(const SharedPtr<IDictionary<TKey, TValue>> &src, const SharedPtr<IEqualityComparer<TKey>> &comparer)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| src | const [SharedPtr](../../../system/sharedptr/)\<[IDictionary](../../idictionary/)\<TKey, TValue\>\>\& | 源字典。 |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[IEqualityComparer](../../iequalitycomparer/)\<TKey\>\>\& | [Comparer](../../comparer/) 要使用的对象。 |

## Dictionary::Dictionary(const SharedPtr\<IEqualityComparer\<TKey\>\>\&) 构造函数

创建空字典。

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary(const SharedPtr<IEqualityComparer<TKey>> &comparer)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[IEqualityComparer](../../iequalitycomparer/)\<TKey\>\>\& | [Comparer](../../comparer/) 要使用。 |

## Dictionary::Dictionary(int, const SharedPtr\<IEqualityComparer\<TKey\>\>\&) 构造函数

创建空字典。

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary(int capacity, const SharedPtr<IEqualityComparer<TKey>> &comparer)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| capacity | int | [Dictionary](../) 创建后的容量；已忽略。 |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[IEqualityComparer](../../iequalitycomparer/)\<TKey\>\>\& | [Comparer](../../comparer/) 要使用。 |

## 另请参见

* Typedef [map_t](../map_t/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Dictionary](../)
* Class [IDictionary](../../idictionary/)
* Class [IEqualityComparer](../../iequalitycomparer/)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)