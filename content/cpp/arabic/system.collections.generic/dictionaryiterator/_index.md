---
title: DictionaryIterator
second_title: مرجع API Aspose.Slides للغة C++
description: متكرر القاموس الذي يوفر ترميز KeyValuePair.
type: docs
weight: 157
url: /ar/system.collections.generic/dictionaryiterator/
---
## DictionaryIterator فئة

[Dictionary](../dictionary/) المتكرر الذي يوفر [KeyValuePair](../keyvaluepair/) ترميز.

```cpp
template<typename Dict>class DictionaryIterator : public System::Details::NativeIteratorWrapperBase<Dict::KeyValuePairType, Dict::map_t::const_iterator>,
                                                  private System::Details::IteratorPointerUpdater<Dict::KeyValuePairType, false>
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| Dict | [Dictionary](../dictionary/) فئة. |

## الطرق

| الطريقة | الوصف |
| --- | --- |
| System::Details::VirtualizedIteratorBase\<typename Dict::KeyValuePairType\> * [CloneIterator](./cloneiterator/)() const override | ينسخ المتكرر الحالي. |
| void [DecrementIterator](./decrementiterator/)() override | يحرك المتكرر خطوة إلى الخلف. |
|  [DictionaryIterator](./dictionaryiterator/)(typename Dict::map_t::const_iterator\&&, typename Dict::map_t::const_iterator\&&) | منشئ. |
|  [DictionaryIterator](./dictionaryiterator/)(const typename Dict::map_t::const_iterator\&, const typename Dict::map_t::const_iterator\&) | منشئ. |
|  [DictionaryIterator](./dictionaryiterator/)([DictionaryIterator](./)\&&) | منشئ النقل. |
| void [IncrementIterator](./incrementiterator/)() override | يحرك المتكرر خطوة إلى الأمام. |
| void [ShiftIteratorBy](./shiftiteratorby/)(std::ptrdiff_t) override | يحرك المتكرر بعدد الخطوات المحدد. |
| virtual  [~DictionaryIterator](./~dictionaryiterator/)() | المدمر. |

## انظر أيضًا

* النطاق [System::Collections::Generic](../)
* المكتبة [Aspose.Slides](../../)