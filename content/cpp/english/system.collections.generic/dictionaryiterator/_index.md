---
title: DictionaryIterator
second_title: Aspose.Slides for C++ API Reference
description: Dictionary iterator that provides KeyValuePair notation.
type: docs
weight: 144
url: /system.collections.generic/dictionaryiterator/
---
## DictionaryIterator class


[Dictionary](../dictionary/) iterator that provides [KeyValuePair](../keyvaluepair/) notation.

```cpp
template<typename Dict>class DictionaryIterator : public System::Details::NativeIteratorWrapperBase<Dict::KeyValuePairType, Dict::map_t::const_iterator>,
                                                  private System::Details::IteratorPointerUpdater<Dict::KeyValuePairType, false>
```


### Template parameters

| Parameter | Description |
| --- | --- |
| Dict | [Dictionary](../dictionary/) class. |
## Methods

| Method | Description |
| --- | --- |
| System::Details::VirtualizedIteratorBase\<typename Dict::KeyValuePairType\> * [CloneIterator](./cloneiterator/)() const override | Clones current iterator. |
| void [DecrementIterator](./decrementiterator/)() override | Moves the iterator step back. |
|  [DictionaryIterator](./dictionaryiterator/)(typename Dict::map_t::const_iterator\&&, typename Dict::map_t::const_iterator\&&) | Constructor. |
|  [DictionaryIterator](./dictionaryiterator/)(const typename Dict::map_t::const_iterator\&, const typename Dict::map_t::const_iterator\&) | Constructor. |
|  [DictionaryIterator](./dictionaryiterator/)([DictionaryIterator](./)\&&) | Move constructor. |
| void [IncrementIterator](./incrementiterator/)() override | Moves the iterator step forward. |
| void [ShiftIteratorBy](./shiftiteratorby/)(std::ptrdiff_t) override | Moves the iterator by the specified number of steps. |
| virtual  [~DictionaryIterator](./~dictionaryiterator/)() | Destructor. |

## See Also

* Namespace [System::Collections::Generic](../)
* Library [Aspose.Slides](../../)