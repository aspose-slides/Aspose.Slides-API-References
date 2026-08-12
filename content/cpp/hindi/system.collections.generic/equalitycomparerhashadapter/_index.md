---
title: EqualityComparerHashAdapter
second_title: C++ के लिए Aspose.Slides एपीआई संदर्भ
description: हैशिंग के लिए IEqualityComparer का उपयोग करने वाला एडेप्टर। यदि सेट किया गया हो तो comparator ऑब्जेक्ट का उपयोग करता है; अन्यथा, DictionaryHashSelector struct का उपयोग करके चयनित उपलब्ध हैश मेथड का उपयोग करता है।
type: docs
weight: 677
url: /hi/system.collections.generic/equalitycomparerhashadapter/
---
## EqualityComparerHashAdapter संरचना

हैशिंग के लिए [IEqualityComparer](../iequalitycomparer/) का उपयोग करने हेतु एडेप्टर। यदि सेट किया गया है तो comparator ऑब्जेक्ट का उपयोग करता है; अन्यथा, [DictionaryHashSelector](../dictionaryhashselector/) संरचना का उपयोग करके चयनित उपलब्ध हैश मेथड का उपयोग करता है।

```cpp
template<typename T>class EqualityComparerHashAdapter
```

### टेम्पलेट पैरामीटर

| Parameter | Description |
| --- | --- |
| Hashed | type. |

## मेथड्स

| Method | Description |
| --- | --- |
|  [EqualityComparerHashAdapter](./equalitycomparerhashadapter/)() | बिना comparator के एडेप्टर बनाता है। |
|  [EqualityComparerHashAdapter](./equalitycomparerhashadapter/)(const [SharedPtr](../../system/sharedptr/)\<[IEqualityComparer](../iequalitycomparer/)\<T\>\>\&) | दिए गए comparator के साथ एडेप्टर बनाता है। |
| std::size_t [operator()](./operator_call/)(const T\&) const | हैश मान की गणना करता है। |
| void [set_EqualityComparator](./set_equalitycomparator/)(const [SharedPtr](../../system/sharedptr/)\<[IEqualityComparer](../iequalitycomparer/)\<T\>\>\&) | उपयोग के लिए comparator सेट करता है। |

## संबंधित देखें

* नेमस्पेस [System::Collections::Generic](../)
* लाइब्रेरी [Aspose.Slides](../../)