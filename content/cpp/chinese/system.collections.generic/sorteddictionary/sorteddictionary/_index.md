---
title: SortedDictionary()
second_title: Aspose.Slides for C++ API 参考
description: 构造空字典。
type: docs
weight: 14
url: /zh/system.collections.generic/sorteddictionary/sorteddictionary/
---
## SortedDictionary::SortedDictionary() 构造函数

构造空字典。

```cpp
System::Collections::Generic::SortedDictionary<TKey, TValue>::SortedDictionary()
```

## SortedDictionary::SortedDictionary(const SharedPtr\<IComparer\<typename BasePointerType\<TKey\>::type\>\>\&) 构造函数

构造空字典。

```cpp
System::Collections::Generic::SortedDictionary<TKey, TValue>::SortedDictionary(const SharedPtr<IComparer<typename BasePointerType<TKey>::type>> &comparer)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[IComparer](../../icomparer/)\<typename BasePointerType\<TKey\>::type\>\>\& | 要使用的[Comparer](../../comparer/)。 |

## SortedDictionary::SortedDictionary(const SharedPtr\<IDictionary\<TKey, TValue\>\>\&) 构造函数

复制构造函数。

```cpp
System::Collections::Generic::SortedDictionary<TKey, TValue>::SortedDictionary(const SharedPtr<IDictionary<TKey, TValue>> &src)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| src | const [SharedPtr](../../../system/sharedptr/)\<[IDictionary](../../idictionary/)\<TKey, TValue\>\>\& | 要从中复制数据的源字典。 |

## SortedDictionary::SortedDictionary(const SharedPtr\<IDictionary\<TKey, TValue\>\>\&, const SharedPtr\<IComparer\<typename BasePointerType\<TKey\>::type\>\>\&) 构造函数

复制构造函数。

```cpp
System::Collections::Generic::SortedDictionary<TKey, TValue>::SortedDictionary(const SharedPtr<IDictionary<TKey, TValue>> &src, const SharedPtr<IComparer<typename BasePointerType<TKey>::type>> &comparer)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| src | const [SharedPtr](../../../system/sharedptr/)\<[IDictionary](../../idictionary/)\<TKey, TValue\>\>\& | 要从中复制数据的源字典。 |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[IComparer](../../icomparer/)\<typename BasePointerType\<TKey\>::type\>\>\& | 要使用的[Comparer](../../comparer/)。 |

## 另请参阅

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [SortedDictionary](../)
* 类 [IComparer](../../icomparer/)
* 类 [IDictionary](../../idictionary/)
* 命名空间 [System::Collections::Generic](../../)
* 库 [Aspose.Slides](../../../)