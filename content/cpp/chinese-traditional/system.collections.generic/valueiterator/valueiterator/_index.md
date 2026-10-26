---
title: ValueIterator()
second_title: Aspose.Slides for C++ API 參考
description: 建構函式。
type: docs
weight: 1
url: /zh-hant/system.collections.generic/valueiterator/valueiterator/
---
## ValueIterator::ValueIterator(typename Dict::map_t::const_iterator\&&, typename Dict::map_t::const_iterator\&&) 建構函式


建構函式。

```cpp
System::Collections::Generic::ValueIterator<Dict>::ValueIterator(typename Dict::map_t::const_iterator &&iterator, typename Dict::map_t::const_iterator &&end) noexcept
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| iterator | typename Dict::map_t::const_iterator\&& | 要保留的迭代器。 |
| end | typename Dict::map_t::const_iterator\&& | 容器結尾的迭代器。 |

## ValueIterator::ValueIterator(const typename Dict::map_t::const_iterator\&, const typename Dict::map_t::const_iterator\&) 建構函式


建構函式。

```cpp
System::Collections::Generic::ValueIterator<Dict>::ValueIterator(const typename Dict::map_t::const_iterator &iterator, const typename Dict::map_t::const_iterator &end)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| iterator | const typename Dict::map_t::const_iterator\& | 要保留的迭代器。 |
| end | const typename Dict::map_t::const_iterator\& | 容器結尾的迭代器。 |

## ValueIterator::ValueIterator(ValueIterator\&&) 建構函式


移動建構函式。

```cpp
System::Collections::Generic::ValueIterator<Dict>::ValueIterator(ValueIterator &&other) noexcept
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| other | [ValueIterator](../)\&& | 要從中移動資料的迭代器。 |

## 另請參閱

* 類別 [ValueIterator](../)
* 命名空間 [System::Collections::Generic](../../)
* 函式庫 [Aspose.Slides](../../../)