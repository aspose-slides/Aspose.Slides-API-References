---
title: DictionaryIterator
second_title: Aspose.Slides for C++ API 參考
description: 提供 KeyValuePair 表記法的字典疊代器。
type: docs
weight: 157
url: /zh-hant/system.collections.generic/dictionaryiterator/
---
## DictionaryIterator 類別


[Dictionary](../dictionary/) 提供 [KeyValuePair](../keyvaluepair/) 表記法的疊代器。

```cpp
template<typename Dict>class DictionaryIterator : public System::Details::NativeIteratorWrapperBase<Dict::KeyValuePairType, Dict::map_t::const_iterator>,
                                                  private System::Details::IteratorPointerUpdater<Dict::KeyValuePairType, false>
```


### 範本參數

| 參數 | 說明 |
| --- | --- |
| Dict | [Dictionary](../dictionary/) 類別。 |
## 方法

| 方法 | 說明 |
| --- | --- |
| System::Details::VirtualizedIteratorBase\<typename Dict::KeyValuePairType\> * [CloneIterator](./cloneiterator/)() const override | 複製目前的疊代器。 |
| void [DecrementIterator](./decrementiterator/)() override | 將疊代器往回移動一步。 |
|  [DictionaryIterator](./dictionaryiterator/)(typename Dict::map_t::const_iterator\&&, typename Dict::map_t::const_iterator\&&) | 建構函式。 |
|  [DictionaryIterator](./dictionaryiterator/)(const typename Dict::map_t::const_iterator\&, const typename Dict::map_t::const_iterator\&) | 建構函式。 |
|  [DictionaryIterator](./dictionaryiterator/)([DictionaryIterator](./)\&&) | 移動建構函式。 |
| void [IncrementIterator](./incrementiterator/)() override | 將疊代器向前移動一步。 |
| void [ShiftIteratorBy](./shiftiteratorby/)(std::ptrdiff_t) override | 將疊代器依指定的步數移動。 |
| virtual  [~DictionaryIterator](./~dictionaryiterator/)() | 解構子。 |

## 另請參閱

* 命名空間 [System::Collections::Generic](../)
* 函式庫 [Aspose.Slides](../../)