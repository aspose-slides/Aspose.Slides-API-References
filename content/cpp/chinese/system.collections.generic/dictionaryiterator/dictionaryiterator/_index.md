---
title: DictionaryIterator()
second_title: Aspose.Slides C++ API 参考
description: 构造函数。
type: docs
weight: 1
url: /zh/system.collections.generic/dictionaryiterator/dictionaryiterator/
---
## DictionaryIterator::DictionaryIterator(typename Dict::map_t::const_iterator\&&, typename Dict::map_t::const_iterator\&&) constructor


构造函数.

```cpp
System::Collections::Generic::DictionaryIterator<Dict>::DictionaryIterator(typename Dict::map_t::const_iterator &&iterator, typename Dict::map_t::const_iterator &&end) noexcept
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| iterator | typename Dict::map_t::const_iterator\&& | 要保存的迭代器。 |
| end | typename Dict::map_t::const_iterator\&& | 容器末尾的迭代器。 |

## DictionaryIterator::DictionaryIterator(const typename Dict::map_t::const_iterator\&, const typename Dict::map_t::const_iterator\&) constructor


构造函数.

```cpp
System::Collections::Generic::DictionaryIterator<Dict>::DictionaryIterator(const typename Dict::map_t::const_iterator &iterator, const typename Dict::map_t::const_iterator &end)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| iterator | const typename Dict::map_t::const_iterator\& | 要保存的迭代器。 |
| end | const typename Dict::map_t::const_iterator\& | 容器末尾的迭代器。 |

## DictionaryIterator::DictionaryIterator(DictionaryIterator\&&) constructor


移动构造函数.

```cpp
System::Collections::Generic::DictionaryIterator<Dict>::DictionaryIterator(DictionaryIterator &&other) noexcept
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| other | [DictionaryIterator](../)\&& | 要从中移动数据的迭代器。 |

## 另见

* 类 [DictionaryIterator](../)
* 命名空间 [System::Collections::Generic](../../)
* 库 [Aspose.Slides](../../../)