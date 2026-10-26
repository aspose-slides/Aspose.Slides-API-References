---
title: KeyIterator()
second_title: Aspose.Slides for C++ API 参考
description: 构造函数。
type: docs
weight: 1
url: /zh/system.collections.generic/keyiterator/keyiterator/
---
## KeyIterator::KeyIterator(typename Dict::map_t::const_iterator\&&, typename Dict::map_t::const_iterator\&&) 构造函数

构造函数。

```cpp
System::Collections::Generic::KeyIterator<Dict>::KeyIterator(typename Dict::map_t::const_iterator &&iterator, typename Dict::map_t::const_iterator &&end) noexcept
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| iterator | typename Dict::map_t::const_iterator\&& | 用于保存的迭代器。 |
| end | typename Dict::map_t::const_iterator\&& | 指向容器末尾的迭代器。 |

## KeyIterator::KeyIterator(const typename Dict::map_t::const_iterator\&, const typename Dict::map_t::const_iterator\&) 构造函数

构造函数。

```cpp
System::Collections::Generic::KeyIterator<Dict>::KeyIterator(const typename Dict::map_t::const_iterator &iterator, const typename Dict::map_t::const_iterator &end)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| iterator | const typename Dict::map_t::const_iterator\& | 用于保存的迭代器。 |
| end | const typename Dict::map_t::const_iterator\& | 指向容器末尾的迭代器。 |

## KeyIterator::KeyIterator(KeyIterator\&&) 构造函数

移动构造函数。

```cpp
System::Collections::Generic::KeyIterator<Dict>::KeyIterator(KeyIterator &&other) noexcept
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| other | [KeyIterator](../)\&& | 要移动数据的迭代器。 |

## 另见

* 类 [KeyIterator](../)
* 命名空间 [System::Collections::Generic](../../)
* 库 [Aspose.Slides](../../../)