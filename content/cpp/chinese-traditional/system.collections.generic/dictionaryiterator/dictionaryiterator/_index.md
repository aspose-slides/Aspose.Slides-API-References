---
title: DictionaryIterator()
second_title: Aspose.Slides for C++ API 參考文件
description: 建構函式。
type: docs
weight: 1
url: /zh-hant/system.collections.generic/dictionaryiterator/dictionaryiterator/
---
## DictionaryIterator::DictionaryIterator(typename Dict::map_t::const_iterator\&&, typename Dict::map_t::const_iterator\&&) 建構函式


建構函式。

```cpp
System::Collections::Generic::DictionaryIterator<Dict>::DictionaryIterator(typename Dict::map_t::const_iterator &&iterator, typename Dict::map_t::const_iterator &&end) noexcept
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| iterator | typename Dict::map_t::const_iterator\&& | 要保存的迭代器。 |
| end | typename Dict::map_t::const_iterator\&& | 指向容器末端的迭代器。 |

## DictionaryIterator::DictionaryIterator(const typename Dict::map_t::const_iterator\&, const typename Dict::map_t::const_iterator\&) 建構函式


建構函式。

```cpp
System::Collections::Generic::DictionaryIterator<Dict>::DictionaryIterator(const typename Dict::map_t::const_iterator &iterator, const typename Dict::map_t::const_iterator &end)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| iterator | const typename Dict::map_t::const_iterator\& | 要保存的迭代器。 |
| end | const typename Dict::map_t::const_iterator\& | 指向容器末端的迭代器。 |

## DictionaryIterator::DictionaryIterator(DictionaryIterator\&&) 建構函式


移動建構函式。

```cpp
System::Collections::Generic::DictionaryIterator<Dict>::DictionaryIterator(DictionaryIterator &&other) noexcept
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| other | [DictionaryIterator](../)\&& | 要移動資料的迭代器。 |

## 另請參閱

* 類別 [DictionaryIterator](../)
* 命名空間 [System::Collections::Generic](../../)
* 程式庫 [Aspose.Slides](../../../)