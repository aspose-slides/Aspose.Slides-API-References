---
title: KeyValuePair
second_title: Aspose.Slides के लिए C++ API रेफरेंस
description: "कुंजी और मान की जोड़ी। इस प्रकार को स्टैक पर आवंटित किया जाना चाहिए और फ़ंक्शनों में मान या संदर्भ द्वारा पास किया जाना चाहिए। इस प्रकार की वस्तुओं का प्रबंधन करने के लिए कभी भी System::SmartPtr क्लास का उपयोग न करें।"
type: docs
weight: 378
url: /hi/system.collections.generic/keyvaluepair/
---
## KeyValuePair क्लास

कुंजी और मान की जोड़ी। इस प्रकार को स्टैक पर आवंटित किया जाना चाहिए और फ़ंक्शनों में मान या संदर्भ द्वारा पास किया जाना चाहिए। इस प्रकार की वस्तुओं का प्रबंधन करने के लिए कभी भी [System::SmartPtr](../../system/smartptr/) क्लास का उपयोग न करें।

```cpp
template<typename TKey,typename TValue>class KeyValuePair
```

## विधियाँ

| मेथड | विवरण |
| --- | --- |
| const TKey\& [get_Key](./get_key/)() const | कुंजी प्राप्त करता है। |
| const TValue\& [get_Value](./get_value/)() const | मान प्राप्त करता है। |
| int [GetHashCode](./gethashcode/)() const | कुंजी-मान जोड़ी का हैश गणना करता है, कुंजी और मान के हैश को XOR करके। |
| **bool** [IsNull](./isnull/)() const | हमेशा false लौटाता है। |
| [KeyValuePair](./keyvaluepair/)() | शून्य कुंजी-मान जोड़ी प्रारंभकर्ता। |
| [KeyValuePair](./keyvaluepair/)(const TKey\&, const TValue\&) | कन्स्ट्रक्टर। |
| [KeyValuePair](./keyvaluepair/)(const std::pair\<OtherK, OtherV\>\&) | टाइप परिवर्तन कन्स्ट्रक्टर। |
| **bool** [operator<](./operator_less/)(const [KeyValuePair](./)\&) const | IComparer<KeyValuePair<TKey, TValue>> से विरासत में मिली क्लासों के लिए पैच, कुछ भी तुलना नहीं करता। |
| [String](../../system/string/) [ToString](./tostring/)() const | कुंजी-मान जोड़ी को स्ट्रिंग में परिवर्तित करता है। |

## संबंधित देखें

* नेमस्पेस [System::Collections::Generic](../)
* लाइब्रेरी [Aspose.Slides](../../)