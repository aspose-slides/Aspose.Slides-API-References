---
title: Sort()
second_title: Aspose.Slides for C++ API 参考
description: 使用自定义比较器对 Span 进行排序。
type: docs
weight: 339
url: /zh/system.memoryextensions/sort/
---
## System::MemoryExtensions::Sort(const Span\<T\>\&, const SharedPtr\<TComparer\>\&) 函数

使用自定义比较器对 [Span](../../system/span/) 进行排序。

```cpp
template<typename T,typename TComparer> void System::MemoryExtensions::Sort(const Span<T> &span, const SharedPtr<TComparer> &comparer)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 元素的类型 |
| TComparer | 比较器对象的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 要排序的跨度 |
| comparer | const [SharedPtr](../../system/sharedptr/)\<TComparer\>\& | 用于元素比较的比较器对象的智能指针 |

## System::MemoryExtensions::Sort(Span\<T\>\&) 函数

使用默认比较对 [Span](../../system/span/) 进行排序。

```cpp
template<typename T> void System::MemoryExtensions::Sort(Span<T> &span)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 元素的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | 要排序的跨度 |

## System::MemoryExtensions::Sort(Span\<TKey\>\&, Span\<TValue\>\&, const SharedPtr\<TComparer\>\&) 函数

使用自定义比较器对键值对进行排序（键和值一起排序）

```cpp
template<typename TKey,typename TValue,typename TComparer> void System::MemoryExtensions::Sort(Span<TKey> &keys, Span<TValue> &values, const SharedPtr<TComparer> &comparer)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| TKey | 键的类型 |
| TValue | 值的类型 |
| TComparer | 比较器对象的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | 要排序的键的跨度 |
| values | [Span](../../system/span/)\<TValue\>\& | 要排序的值的跨度（保持与键的对应关系） |
| comparer | const [SharedPtr](../../system/sharedptr/)\<TComparer\>\& | 用于键比较的比较器对象的智能指针 |

## System::MemoryExtensions::Sort(Span\<TKey\>\&, Span\<TValue\>\&, System::Comparison\<TKey\>) 函数

使用比较委托对键值对进行排序。

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Sort(Span<TKey> &keys, Span<TValue> &values, System::Comparison<TKey> comparer)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| TKey | 键的类型 |
| TValue | 值的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | 要排序的键的跨度 |
| values | [Span](../../system/span/)\<TValue\>\& | 要排序的值的跨度 |
| comparer | [System::Comparison](../../system/comparison/)\<TKey\> | [Comparison](../../system/comparison/) 委托用于键比较 |

## System::MemoryExtensions::Sort(Span\<TKey\>\&, Span\<TValue\>\&) 函数

使用默认比较对键值对进行排序。

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Sort(Span<TKey> &keys, Span<TValue> &values)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| TKey | 键的类型 |
| TValue | 值的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | 要排序的键的跨度 |
| values | [Span](../../system/span/)\<TValue\>\& | 要排序的值的跨度 |

## 另见

* 类型定义 [SharedPtr](../../system/sharedptr/)
* 类 [Span](../../system/span/)
* 类 [Comparison](../../system/comparison/)
* 命名空间 [System::MemoryExtensions](../)
* 库 [Aspose.Slides](../../)