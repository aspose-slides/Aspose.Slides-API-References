---
title: KeyIterator
second_title: Aspose.Slides for C++ API 參考
description: 提供鍵存取的字典迭代器。
type: docs
weight: 365
url: /zh-hant/system.collections.generic/keyiterator/
---
## KeyIterator 類別


[Dictionary](../dictionary/) 提供鍵存取的迭代器。

```cpp
template<typename Dict>class KeyIterator : public System::Details::NativeIteratorWrapperBase<Dict::map_t::key_type, Dict::map_t::const_iterator>,
                                           private System::Details::IteratorPointerUpdater<Dict::map_t::key_type, false>
```


### 模板參數

| 參數 | 描述 |
| --- | --- |
| Dict | [Dictionary](../dictionary/) 類別。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| System::Details::VirtualizedIteratorBase\<typename Dict::map_t::key_type\> * [CloneIterator](./cloneiterator/)() const override | 複製目前的迭代器。 |
| void [DecrementIterator](./decrementiterator/)() override | 將迭代器向後移動一步。 |
| void [IncrementIterator](./incrementiterator/)() override | 將迭代器向前移動一步。 |
|  [KeyIterator](./keyiterator/)(typename Dict::map_t::const_iterator\&&, typename Dict::map_t::const_iterator\&&) | 建構子。 |
|  [KeyIterator](./keyiterator/)(const typename Dict::map_t::const_iterator\&, const typename Dict::map_t::const_iterator\&) | 建構子。 |
|  [KeyIterator](./keyiterator/)([KeyIterator](./)\&&) | 移動建構子。 |
| void [ShiftIteratorBy](./shiftiteratorby/)(std::ptrdiff_t) override | 依指定的步數移動迭代器。 |
| virtual  [~KeyIterator](./~keyiterator/)() | 解構子。 |

## 參見

* 命名空間 [System::Collections::Generic](../)
* 程式庫 [Aspose.Slides](../../)