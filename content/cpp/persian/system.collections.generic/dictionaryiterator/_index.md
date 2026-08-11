---
title: DictionaryIterator
second_title: مستندات مرجع API Aspose.Slides برای C++
description: تکرارگر دیکشنری که نماد KeyValuePair را فراهم می‌کند.
type: docs
weight: 157
url: /fa/system.collections.generic/dictionaryiterator/
---
## DictionaryIterator کلاس

[Dictionary](../dictionary/) تکرارگری که [KeyValuePair](../keyvaluepair/) نماد را فراهم می‌کند.

```cpp
template<typename Dict>class DictionaryIterator : public System::Details::NativeIteratorWrapperBase<Dict::KeyValuePairType, Dict::map_t::const_iterator>,
                                                  private System::Details::IteratorPointerUpdater<Dict::KeyValuePairType, false>
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| Dict | [Dictionary](../dictionary/) کلاس. |
## متدها

| متد | توضیح |
| --- | --- |
| System::Details::VirtualizedIteratorBase\<typename Dict::KeyValuePairType\> * [CloneIterator](./cloneiterator/)() const override | تکرارگر فعلی را کلون می‌کند. |
| void [DecrementIterator](./decrementiterator/)() override | تکرارگر را یک قدم به عقب می‌برد. |
|  [DictionaryIterator](./dictionaryiterator/)(typename Dict::map_t::const_iterator\&&, typename Dict::map_t::const_iterator\&&) | سازنده. |
|  [DictionaryIterator](./dictionaryiterator/)(const typename Dict::map_t::const_iterator\&, const typename Dict::map_t::const_iterator\&) | سازنده. |
|  [DictionaryIterator](./dictionaryiterator/)([DictionaryIterator](./)\&&) | سازندهٔ جابجایی. |
| void [IncrementIterator](./incrementiterator/)() override | تکرارگر را یک قدم به جلو می‌برد. |
| void [ShiftIteratorBy](./shiftiteratorby/)(std::ptrdiff_t) override | تکرارگر را به تعداد قدم‌های مشخص حرکت می‌دهد. |
| virtual  [~DictionaryIterator](./~dictionaryiterator/)() | تخریب‌کننده. |

## دربارهٔ بیشتر

* Namespace [System::Collections::Generic](../)
* Library [Aspose.Slides](../../)