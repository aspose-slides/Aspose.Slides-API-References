---
title: EqualityComparerAdapter
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: "IEqualityComparer का उपयोग करके STL-शैली के संग्रह और एल्गोरिद्म के साथ इसे संभव बनाने वाला एडेप्टर। यदि सेट किया गया हो तो IEqualityComparer का उपयोग करता है। यदि सेट नहीं है, तो operator ==, Object::Equals या T::Equals का उपयोग करता है, जो भी उपलब्ध हो।"
type: docs
weight: 664
url: /hi/system.collections.generic/equalitycompareradapter/
---
## EqualityComparerAdapter struct

[IEqualityComparer](../iequalitycomparer/) का उपयोग करके STL-शैली के संग्रह और एल्गोरिद्म के साथ इसे संभव बनाने वाला एडेप्टर। यदि सेट किया गया हो तो [IEqualityComparer](../iequalitycomparer/) का उपयोग करता है। यदि सेट नहीं है, तो operator ==, [Object::Equals](../../system/object/equals/) या T::Equals का उपयोग करता है, जो भी उपलब्ध हो।

```cpp
template<class T>class EqualityComparerAdapter
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | तुलना किया जा रहा प्रकार। |

## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  [EqualityComparerAdapter](./equalitycompareradapter/)() | कोई कंपेरेटर उपयोग किए बिना एडेप्टर बनाता है। |
|  [EqualityComparerAdapter](./equalitycompareradapter/)(const [SharedPtr](../../system/sharedptr/)\<[IEqualityComparer](../iequalitycomparer/)\<T\>\>\&) | दिए गए कंपेरेटर के साथ एडेप्टर बनाता है। |
| **bool** [operator()](./operator_call/)(const T\&, const T\&) const | दो ऑब्जेक्ट्स की तुलना करता है। |
| void [set_EqualityComparator](./set_equalitycomparator/)(const [SharedPtr](../../system/sharedptr/)\<[IEqualityComparer](../iequalitycomparer/)\<T\>\>\&) | कंपेरेटर सेट करता है। |

## संबंधित देखें

* नेमस्पेस [System::Collections::Generic](../)
* लाइब्रेरी [Aspose.Slides](../../)