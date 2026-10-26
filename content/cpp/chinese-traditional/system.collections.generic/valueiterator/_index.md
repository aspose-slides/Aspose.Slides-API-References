---
title: ValueIterator
second_title: Aspose.Slides for C++ API 參考
description: 提供值存取的字典迭代器。
type: docs
weight: 625
url: /zh-hant/system.collections.generic/valueiterator/
---
## ValueIterator 類別


[Dictionary](../dictionary/) 迭代器，提供值訪問。

```cpp
template<typename Dict>class ValueIterator : public System::Details::NativeIteratorWrapperBase<Dict::map_t::mapped_type, Dict::map_t::const_iterator>,
                                             private System::Details::IteratorPointerUpdater<Dict::map_t::mapped_type, false>
```


### 範本參數

| 參數 | 說明 |
| --- | --- |
| Dict | [Dictionary](../dictionary/) 類別。 |
## 方法

| 方法 | 說明 |
| --- | --- |
| System::Details::VirtualizedIteratorBase\<typename Dict::map_t::mapped_type\> * [CloneIterator](./cloneiterator/)() const override | 克隆目前的迭代器。 |
| void [DecrementIterator](./decrementiterator/)() override | 將迭代器向後移動一步。 |
| void [IncrementIterator](./incrementiterator/)() override | 將迭代器向前移動一步。 |
| void [ShiftIteratorBy](./shiftiteratorby/)(std::ptrdiff_t) override | 將迭代器按指定的步數移動。 |
|  [ValueIterator](./valueiterator/)(typename Dict::map_t::const_iterator\&&, typename Dict::map_t::const_iterator\&&) | 建構函式。 |
|  [ValueIterator](./valueiterator/)(const typename Dict::map_t::const_iterator\&, const typename Dict::map_t::const_iterator\&) | 建構函式。 |
|  [ValueIterator](./valueiterator/)([ValueIterator](./)\&&) | 移動建構函式。 |
| virtual  [~ValueIterator](./~valueiterator/)() | 解構函式。 |

## 另請參閱

* 命名空間 [System::Collections::Generic](../)
* 函式庫 [Aspose.Slides](../../)