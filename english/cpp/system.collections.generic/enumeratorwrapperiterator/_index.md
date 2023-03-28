---
title: EnumeratorWrapperIterator
second_title: Aspose.Slides for C++ API Reference
description: Iterator that wraps the pre-created enumerator and redirects all calls into it.
type: docs
weight: 170
url: /cpp/system.collections.generic/enumeratorwrapperiterator/
---
## EnumeratorWrapperIterator class


Iterator that wraps the pre-created enumerator and redirects all calls into it.

```cpp
template<typename Element>class EnumeratorWrapperIterator : public System::Details::VirtualizedIteratorBase<Element>
```


### Template parameters

| Parameter | Description |
| --- | --- |
| Element | Element type. |
## Methods

| Method | Description |
| --- | --- |
| System::Details::VirtualizedIteratorBase\<Element\> * [CloneIterator](./cloneiterator/)() const override | Clones current iterator. |
|  [EnumeratorWrapperIterator](./enumeratorwrapperiterator/)(const [SharedPtr](../../system/sharedptr/)\<[IEnumerator](../ienumerator/)\<Element\>\>\&) |  |
| void [IncrementIterator](./incrementiterator/)() override | Moves the iterator step forward. Must update m_is_end and m_pointer. |
| **bool** [IteratorEquals](./iteratorequals/)(System::Details::VirtualizedIteratorBase\<Element\> *) const override | Checks if two iterators point to the same item. |
| virtual  [~EnumeratorWrapperIterator](./~enumeratorwrapperiterator/)() | Destructor. |

## See Also

* Namespace [System::Collections::Generic](../)
* Library [Aspose.Slides](../../)
