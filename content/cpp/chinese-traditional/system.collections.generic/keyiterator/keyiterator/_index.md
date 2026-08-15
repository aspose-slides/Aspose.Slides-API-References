---
title: KeyIterator()
second_title: Aspose.Slides for C++ API 參考文件
description: 建構子。
type: docs
weight: 1
url: /zh-hant/system.collections.generic/keyiterator/keyiterator/
---
## KeyIterator::KeyIterator(typename Dict::map_t::const_iterator\&&, typename Dict::map_t::const_iterator\&&) 建構子


建構子。

```cpp
System::Collections::Generic::KeyIterator<Dict>::KeyIterator(typename Dict::map_t::const_iterator &&iterator, typename Dict::map_t::const_iterator &&end) noexcept
```


### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| iterator | typename Dict::map_t::const_iterator\&& | 要保存的迭代器。 |
| end | typename Dict::map_t::const_iterator\&& | 指向容器末端的迭代器。 |

## KeyIterator::KeyIterator(const typename Dict::map_t::const_iterator\&, const typename Dict::map_t::const_iterator\&) 建構子


建構子。

```cpp
System::Collections::Generic::KeyIterator<Dict>::KeyIterator(const typename Dict::map_t::const_iterator &iterator, const typename Dict::map_t::const_iterator &end)
```


### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| iterator | const typename Dict::map_t::const_iterator\& | 要保存的迭代器。 |
| end | const typename Dict::map_t::const_iterator\& | 指向容器末端的迭代器。 |

## KeyIterator::KeyIterator(KeyIterator\&&) 建構子


移動建構子。

```cpp
System::Collections::Generic::KeyIterator<Dict>::KeyIterator(KeyIterator &&other) noexcept
```


### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| other | [KeyIterator](../)\&& | 迭代器以移動資料。 |

## 另請參閱

* 類別 [KeyIterator](../)
* 命名空間 [System::Collections::Generic](../../)
* 函式庫 [Aspose.Slides](../../../)