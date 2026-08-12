---
title: ValueIterator
second_title: Aspose.Slides for C++ API संदर्भ
description: डिक्शनरी इटररेटर जो वैल्यू एक्सेस प्रदान करता है।
type: docs
weight: 625
url: /hi/system.collections.generic/valueiterator/
---
## ValueIterator क्लास

[Dictionary](../dictionary/) वैल्यू एक्सेस प्रदान करने वाला इटररेटर.

```cpp
template<typename Dict>class ValueIterator : public System::Details::NativeIteratorWrapperBase<Dict::map_t::mapped_type, Dict::map_t::const_iterator>,
                                             private System::Details::IteratorPointerUpdater<Dict::map_t::mapped_type, false>
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| Dict | [Dictionary](../dictionary/) क्लास। |
## विधियाँ

| मेथड | विवरण |
| --- | --- |
| System::Details::VirtualizedIteratorBase\<typename Dict::map_t::mapped_type\> * [CloneIterator](./cloneiterator/)() const override | वर्तमान इटररेटर को क्लोन करता है। |
| void [DecrementIterator](./decrementiterator/)() override | इटररेटर को एक कदम पीछे ले जाता है। |
| void [IncrementIterator](./incrementiterator/)() override | इटररेटर को एक कदम आगे ले जाता है। |
| void [ShiftIteratorBy](./shiftiteratorby/)(std::ptrdiff_t) override | इटररेटर को निर्दिष्ट कदम संख्या द्वारा ले जाता है। |
|  [ValueIterator](./valueiterator/)(typename Dict::map_t::const_iterator\&&, typename Dict::map_t::const_iterator\&&) | कन्स्ट्रक्टर। |
|  [ValueIterator](./valueiterator/)(const typename Dict::map_t::const_iterator\&, const typename Dict::map_t::const_iterator\&) | कन्स्ट्रक्टर। |
|  [ValueIterator](./valueiterator/)([ValueIterator](./)\&&) | मूव कन्स्ट्रक्टर। |
| virtual  [~ValueIterator](./~valueiterator/)() | डिस्ट्रक्टर। |

## देखें भी

* नेमस्पेस [System::Collections::Generic](../)
* लाइब्रेरी [Aspose.Slides](../../)