---
title: EnumeratorWrapperIterator
second_title: Aspose.Slides for C++ API संदर्भ
description: इटररेटर जो पहले से निर्मित enumerator को लपेटता है और सभी कॉलों को इसमें पुनर्निर्देशित करता है।
type: docs
weight: 196
url: /hi/system.collections.generic/enumeratorwrapperiterator/
---
## EnumeratorWrapperIterator क्लास

एक iterator जो पहले से निर्मित enumerator को लपेटता है और सभी कॉलों को इसमें पुनर्निर्देशित करता है।

```cpp
template<typename Element>class EnumeratorWrapperIterator : public System::Details::VirtualizedIteratorBase<Element>
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| Element | Element प्रकार। |

## विधियाँ

| विधि | विवरण |
| --- | --- |
| System::Details::VirtualizedIteratorBase\<Element\> * [CloneIterator](./cloneiterator/)() const override | वर्तमान इटररेटर की प्रतिलिपि बनाता है। |
| [EnumeratorWrapperIterator](./enumeratorwrapperiterator/)(const [SharedPtr](../../system/sharedptr/)\<[IEnumerator](../ienumerator/)\<Element\>\>\&) |  |
| void [IncrementIterator](./incrementiterator/)() override | इटररेटर को एक कदम आगे ले जाता है। m_is_end और m_pointer को अपडेट करना आवश्यक है। |
| **bool** [IteratorEquals](./iteratorequals/)(System::Details::VirtualizedIteratorBase\<Element\> *) const override | जाँचता है कि दो इटररेटर उसी आइटम की ओर संकेत कर रहे हैं। |
| virtual  [~EnumeratorWrapperIterator](./~enumeratorwrapperiterator/)() | डिस्ट्रक्टर। |

## देखें

* नामस्थान [System::Collections::Generic](../)
* लाइब्रेरी [Aspose.Slides](../../)