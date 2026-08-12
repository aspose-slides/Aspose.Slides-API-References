---
title: DictionaryIterator
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: डिक्शनरी इटरेटर जो KeyValuePair नोटेशन प्रदान करता है।
type: docs
weight: 157
url: /hi/system.collections.generic/dictionaryiterator/
---
## DictionaryIterator क्लास

[Dictionary](../dictionary/) इटरेटर जो [KeyValuePair](../keyvaluepair/) नोटेशन प्रदान करता है।

```cpp
template<typename Dict>class DictionaryIterator : public System::Details::NativeIteratorWrapperBase<Dict::KeyValuePairType, Dict::map_t::const_iterator>,
                                                  private System::Details::IteratorPointerUpdater<Dict::KeyValuePairType, false>
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| Dict | [Dictionary](../dictionary/) क्लास। |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| System::Details::VirtualizedIteratorBase\<typename Dict::KeyValuePairType\> * [CloneIterator](./cloneiterator/)() const override | वर्तमान इटरेटर की क्लोन बनाता है। |
| void [DecrementIterator](./decrementiterator/)() override | इटरेटर को एक कदम पीछे ले जाता है। |
|  [DictionaryIterator](./dictionaryiterator/)(typename Dict::map_t::const_iterator\&&, typename Dict::map_t::const_iterator\&&) | कन्स्ट्रक्टर। |
|  [DictionaryIterator](./dictionaryiterator/)(const typename Dict::map_t::const_iterator\&, const typename Dict::map_t::const_iterator\&) | कन्स्ट्रक्टर। |
|  [DictionaryIterator](./dictionaryiterator/)([DictionaryIterator](./)\&&) | मूव कन्स्ट्रक्टर। |
| void [IncrementIterator](./incrementiterator/)() override | इटरेटर को एक कदम आगे ले जाता है। |
| void [ShiftIteratorBy](./shiftiteratorby/)(std::ptrdiff_t) override | इटरेटर को निर्दिष्ट संख्या में कदम द्वारा ले जाता है। |
| virtual  [~DictionaryIterator](./~dictionaryiterator/)() | डिस्ट्रक्टर। |

## संबंधित देखें

* Namespace [System::Collections::Generic](../)
* Library [Aspose.Slides](../../)