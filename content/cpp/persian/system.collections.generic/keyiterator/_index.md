---
title: KeyIterator
second_title: مرجع API Aspose.Slides برای C++
description: تکرارگر دیکشنری که دسترسی به کلیدها را فراهم می‌کند.
type: docs
weight: 365
url: /fa/system.collections.generic/keyiterator/
---
## KeyIterator کلاس


[Dictionary](../dictionary/) iterator that provides key access.

```cpp
template<typename Dict>class KeyIterator : public System::Details::NativeIteratorWrapperBase<Dict::map_t::key_type, Dict::map_t::const_iterator>,
                                           private System::Details::IteratorPointerUpdater<Dict::map_t::key_type, false>
```


### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| Dict | [Dictionary](../dictionary/) کلاس. |
## متدها

| متد | توضیح |
| --- | --- |
| System::Details::VirtualizedIteratorBase\<typename Dict::map_t::key_type\> * [CloneIterator](./cloneiterator/)() const override | یک کپی از iterator فعلی ایجاد می‌کند. |
| void [DecrementIterator](./decrementiterator/)() override | iterator را یک گام به عقب حرکت می‌دهد. |
| void [IncrementIterator](./incrementiterator/)() override | iterator را یک گام به جلو حرکت می‌دهد. |
|  [KeyIterator](./keyiterator/)(typename Dict::map_t::const_iterator\&&, typename Dict::map_t::const_iterator\&&) | سازنده. |
|  [KeyIterator](./keyiterator/)(const typename Dict::map_t::const_iterator\&, const typename Dict::map_t::const_iterator\&) | سازنده. |
|  [KeyIterator](./keyiterator/)([KeyIterator](./)\&&) | سازنده جابجایی. |
| void [ShiftIteratorBy](./shiftiteratorby/)(std::ptrdiff_t) override | iterator را به تعداد گام‌های مشخص‌شده حرکت می‌دهد. |
| virtual  [~KeyIterator](./~keyiterator/)() | تخریب‌کننده. |

## موارد مرتبط

* فضای‌نام [System::Collections::Generic](../)
* کتابخانه [Aspose.Slides](../../)