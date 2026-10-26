---
title: ValueIterator
second_title: مرجع API Aspose.Slides برای C++
description: تکرارگر دیکشنری که دسترسی به مقدار را فراهم می‌کند.
type: docs
weight: 625
url: /fa/system.collections.generic/valueiterator/
---
## ValueIterator کلاس

[Dictionary](../dictionary/) iterator که دسترسی به مقدار را فراهم می‌کند.

```cpp
template<typename Dict>class ValueIterator : public System::Details::NativeIteratorWrapperBase<Dict::map_t::mapped_type, Dict::map_t::const_iterator>,
                                             private System::Details::IteratorPointerUpdater<Dict::map_t::mapped_type, false>
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| Dict | [Dictionary](../dictionary/) کلاس. |

## متدها

| متد | توضیح |
| --- | --- |
| System::Details::VirtualizedIteratorBase\<typename Dict::map_t::mapped_type\> * [CloneIterator](./cloneiterator/)() const override | یک کپی از تکرارگر فعلی ایجاد می‌کند. |
| void [DecrementIterator](./decrementiterator/)() override | تکرارگر را یک گام به عقب می‌برد. |
| void [IncrementIterator](./incrementiterator/)() override | تکرارگر را یک گام به جلو می‌برد. |
| void [ShiftIteratorBy](./shiftiteratorby/)(std::ptrdiff_t) override | تکرارگر را به تعداد گام‌های مشخص شده حرکت می‌دهد. |
|  [ValueIterator](./valueiterator/)(typename Dict::map_t::const_iterator\&&, typename Dict::map_t::const_iterator\&&) | سازنده. |
|  [ValueIterator](./valueiterator/)(const typename Dict::map_t::const_iterator\&, const typename Dict::map_t::const_iterator\&) | سازنده. |
|  [ValueIterator](./valueiterator/)([ValueIterator](./)\&&) | سازنده انتقالی. |
| virtual  [~ValueIterator](./~valueiterator/)() | تخریب‌کننده. |

## موارد مرتبط

* فضا نام [System::Collections::Generic](../)
* کتابخانه [Aspose.Slides](../../)