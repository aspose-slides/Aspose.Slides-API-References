---
title: ValueIterator()
second_title: Aspose.Slides C++ API 参考
description: 构造函数。
type: docs
weight: 1
url: /zh/system.collections.generic/valueiterator/valueiterator/
---
## ValueIterator::ValueIterator(typename Dict::map_t::const_iterator\&&, typename Dict::map_t::const_iterator\&&) 构造函数

构造函数。

```cpp
System::Collections::Generic::ValueIterator<Dict>::ValueIterator(typename Dict::map_t::const_iterator &&iterator, typename Dict::map_t::const_iterator &&end) noexcept
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| iterator | typename Dict::map_t::const_iterator\&& | 要保持的迭代器。 |
| end | typename Dict::map_t::const_iterator\&& | 指向容器末尾的迭代器。 |

## ValueIterator::ValueIterator(const typename Dict::map_t::const_iterator\&, const typename Dict::map_t::const_iterator\&) 构造函数

构造函数。

```cpp
System::Collections::Generic::ValueIterator<Dict>::ValueIterator(const typename Dict::map_t::const_iterator &iterator, const typename Dict::map_t::const_iterator &end)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| iterator | const typename Dict::map_t::const_iterator\& | 要保持的迭代器。 |
| end | const typename Dict::map_t::const_iterator\& | 指向容器末尾的迭代器。 |

## ValueIterator::ValueIterator(ValueIterator\&&) 构造函数

移动构造函数。

```cpp
System::Collections::Generic::ValueIterator<Dict>::ValueIterator(ValueIterator &&other) noexcept
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| other | [ValueIterator](../)\&& | 要从中移动数据的迭代器。 |

## 另请参见

* 类 [ValueIterator](../)
* 命名空间 [System::Collections::Generic](../../)
* 库 [Aspose.Slides](../../../)