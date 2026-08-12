---
title: KeyIterator
second_title: Aspose.Slides for C++ API संदर्भ
description: डिक्शनरी इटररेटर जो कुंजी पहुंच प्रदान करता है।
type: docs
weight: 365
url: /hi/system.collections.generic/keyiterator/
---
## KeyIterator क्लास


[Dictionary](../dictionary/) कुंजी पहुंच प्रदान करने वाला इटररेटर।

```cpp
template<typename Dict>class KeyIterator : public System::Details::NativeIteratorWrapperBase<Dict::map_t::key_type, Dict::map_t::const_iterator>,
                                           private System::Details::IteratorPointerUpdater<Dict::map_t::key_type, false>
```


### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| Dict | [Dictionary](../dictionary/) क्लास। |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| System::Details::VirtualizedIteratorBase\<typename Dict::map_t::key_type\> * [CloneIterator](./cloneiterator/)() const override | वर्तमान इटररेटर को क्लोन करता है। |
| void [DecrementIterator](./decrementiterator/)() override | इटररेटर को एक कदम पीछे ले जाता है। |
| void [IncrementIterator](./incrementiterator/)() override | इटररेटर को एक कदम आगे ले जाता है। |
|  [KeyIterator](./keyiterator/)(typename Dict::map_t::const_iterator\&&, typename Dict::map_t::const_iterator\&&) | कन्स्ट्रक्टर। |
|  [KeyIterator](./keyiterator/)(const typename Dict::map_t::const_iterator\&, const typename Dict::map_t::const_iterator\&) | कन्स्ट्रक्टर। |
|  [KeyIterator](./keyiterator/)([KeyIterator](./)\&&) | मूव कन्स्ट्रक्टर। |
| void [ShiftIteratorBy](./shiftiteratorby/)(std::ptrdiff_t) override | इटररेटर को निर्दिष्ट संख्या में कदमों से ले जाता है। |
| virtual  [~KeyIterator](./~keyiterator/)() | डिस्ट्रक्टर। |

## देखें

* नेमस्पेस [System::Collections::Generic](../)
* लाइब्रेरी [Aspose.Slides](../../)