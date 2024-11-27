---
title: ValueIterator
second_title: Aspose.Slides for C++ API Reference
description: Dictionary iterator that provides value access.
type: docs
weight: 625
url: /system.collections.generic/valueiterator/
---
## ValueIterator class


[Dictionary](../dictionary/) iterator that provides value access.

```cpp
template<typename Dict>class ValueIterator : public System::Details::NativeIteratorWrapperBase<Dict::map_t::mapped_type, Dict::map_t::const_iterator>,
                                             private System::Details::IteratorPointerUpdater<Dict::map_t::mapped_type, false>
```


### Template parameters

| Parameter | Description |
| --- | --- |
| Dict | [Dictionary](../dictionary/) class. |
## Methods

| Method | Description |
| --- | --- |
| System::Details::VirtualizedIteratorBase\<typename Dict::map_t::mapped_type\> * [CloneIterator](./cloneiterator/)() const override | Clones current iterator. |
| void [DecrementIterator](./decrementiterator/)() override | Moves the iterator step back. |
| void [IncrementIterator](./incrementiterator/)() override | Moves the iterator step forward. |
| void [ShiftIteratorBy](./shiftiteratorby/)(std::ptrdiff_t) override | Moves the iterator by the specified number of steps. |
|  [ValueIterator](./valueiterator/)(typename Dict::map_t::const_iterator\&&, typename Dict::map_t::const_iterator\&&) | Constructor. |
|  [ValueIterator](./valueiterator/)(const typename Dict::map_t::const_iterator\&, const typename Dict::map_t::const_iterator\&) | Constructor. |
|  [ValueIterator](./valueiterator/)([ValueIterator](./)\&&) | Move constructor. |
| virtual  [~ValueIterator](./~valueiterator/)() | Destructor. |

## See Also

* Namespace [System::Collections::Generic](../)
* Library [Aspose.Slides](../../)