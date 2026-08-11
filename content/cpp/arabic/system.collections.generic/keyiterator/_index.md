---
title: KeyIterator
second_title: واجهة برمجة تطبيقات Aspose.Slides للغة C++
description: مكرّر القاموس الذي يوفر الوصول إلى المفتاح.
type: docs
weight: 365
url: /ar/system.collections.generic/keyiterator/
---
## KeyIterator فئة

[Dictionary](../dictionary/) مُكرِّر يوفر الوصول إلى المفتاح.

```cpp
template<typename Dict>class KeyIterator : public System::Details::NativeIteratorWrapperBase<Dict::map_t::key_type, Dict::map_t::const_iterator>,
                                           private System::Details::IteratorPointerUpdater<Dict::map_t::key_type, false>
```

### معلمات القالب

| المعلمة | الوصف |
| --- | --- |
| Dict | [Dictionary](../dictionary/) فئة. |

## الطرق

| الطريقة | الوصف |
| --- | --- |
| System::Details::VirtualizedIteratorBase\<typename Dict::map_t::key_type\> * [CloneIterator](./cloneiterator/)() const override | ينسخ المُكرِّر الحالي. |
| void [DecrementIterator](./decrementiterator/)() override | يحرك المُكرِّر خطوة إلى الوراء. |
| void [IncrementIterator](./incrementiterator/)() override | يحرك المُكرِّر خطوة إلى الأمام. |
|  [KeyIterator](./keyiterator/)(typename Dict::map_t::const_iterator\&&, typename Dict::map_t::const_iterator\&&) | منشئ. |
|  [KeyIterator](./keyiterator/)(const typename Dict::map_t::const_iterator\&, const typename Dict::map_t::const_iterator\&) | منشئ. |
|  [KeyIterator](./keyiterator/)([KeyIterator](./)\&&) | منشئ النقل. |
| void [ShiftIteratorBy](./shiftiteratorby/)(std::ptrdiff_t) override | يحرك المُكرِّر بالعدد المحدد من الخطوات. |
| virtual  [~KeyIterator](./~keyiterator/)() | المدمر. |

## انظر أيضًا

* نطاق [System::Collections::Generic](../)
* مكتبة [Aspose.Slides](../../)