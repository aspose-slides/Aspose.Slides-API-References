---
title: ValueIterator
second_title: مرجع API Aspose.Slides للغة C++
description: مؤشّر القاموس الذي يوفّر الوصول إلى القيمة.
type: docs
weight: 625
url: /ar/system.collections.generic/valueiterator/
---
## ValueIterator فئة


[Dictionary](../dictionary/) المؤشر الذي يوفّر الوصول إلى القيمة.

```cpp
template<typename Dict>class ValueIterator : public System::Details::NativeIteratorWrapperBase<Dict::map_t::mapped_type, Dict::map_t::const_iterator>,
                                             private System::Details::IteratorPointerUpdater<Dict::map_t::mapped_type, false>
```


### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| Dict | [Dictionary](../dictionary/) فئة. |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| System::Details::VirtualizedIteratorBase\<typename Dict::map_t::mapped_type\> * [CloneIterator](./cloneiterator/)() const override | ينسخ المؤشر الحالي. |
| void [DecrementIterator](./decrementiterator/)() override | يحرك المؤشر خطوة إلى الوراء. |
| void [IncrementIterator](./incrementiterator/)() override | يحرك المؤشر خطوة إلى الأمام. |
| void [ShiftIteratorBy](./shiftiteratorby/)(std::ptrdiff_t) override | يحرك المؤشر بعدد الخطوات المحدد. |
|  [ValueIterator](./valueiterator/)(typename Dict::map_t::const_iterator\&&, typename Dict::map_t::const_iterator\&&) | منشئ. |
|  [ValueIterator](./valueiterator/)(const typename Dict::map_t::const_iterator\&, const typename Dict::map_t::const_iterator\&) | منشئ. |
|  [ValueIterator](./valueiterator/)([ValueIterator](./)\&&) | منشئ النقل. |
| virtual  [~ValueIterator](./~valueiterator/)() | المدمر. |

## انظر أيضًا

* نطاق [System::Collections::Generic](../)
* مكتبة [Aspose.Slides](../../)