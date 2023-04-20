---
title: KeyIterator
second_title: Aspose.Slides for C++ API Reference
description: Dictionary iterator that provides key access.
type: docs
weight: 339
url: /cpp/system.collections.generic/keyiterator/
---
## KeyIterator class


[Dictionary](../dictionary/) iterator that provides key access.

```cpp
template<typename Dict>class KeyIterator : public System::Details::NativeIteratorWrapperBase<Dict::map_t::key_type, Dict::map_t::const_iterator>,
                                           private System::Details::IteratorPointerUpdater<Dict::map_t::key_type, false>
```


### Template parameters

| Parameter | Description |
| --- | --- |
| Dict | [Dictionary](../dictionary/) class. |
## Methods

| Method | Description |
| --- | --- |
| System::Details::VirtualizedIteratorBase\<typename Dict::map_t::key_type\> * [CloneIterator](./cloneiterator/)() const override | Clones current iterator. |
| void [DecrementIterator](./decrementiterator/)() override | Moves the iterator step back. |
| void [IncrementIterator](./incrementiterator/)() override | Moves the iterator step forward. |
|  [KeyIterator](./keyiterator/)(typename Dict::map_t::const_iterator\&&, typename Dict::map_t::const_iterator\&&) | Constructor. |
|  [KeyIterator](./keyiterator/)(const typename Dict::map_t::const_iterator\&, const typename Dict::map_t::const_iterator\&) | Constructor. |
|  [KeyIterator](./keyiterator/)([KeyIterator](./)\&&) | Move constructor. |
| void [ShiftIteratorBy](./shiftiteratorby/)(std::ptrdiff_t) override | Moves the iterator by the specified number of steps. |
| virtual  [~KeyIterator](./~keyiterator/)() | Destructor. |

## See Also

* Namespace [System::Collections::Generic](../)
* Library [Aspose.Slides](../../)