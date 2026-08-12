---
title: operator==()
second_title: Aspose.Slides for C++ API संदर्भ
description: दो कुंजी-मान जोड़ों की तुलना 'equals' सिद्धान्त का उपयोग करके करता है। दोनों कुंजियों और मानों के लिए operator == या EqualsTo मेथड का उपयोग करता है, जो भी परिभाषित हो।
type: docs
weight: 690
url: /hi/system.collections.generic/operator_equal_equal/
---
## System::Collections::Generic::operator==(const KeyValuePair\<TKey, TValue\>\&, const KeyValuePair\<TKey, TValue\>\&) function

दो कुंजी-मान जोड़े की तुलना 'equals' सिमेंटिक का उपयोग करके करता है। दोनों कुंजियों और मानों के लिए operator == या EqualsTo मेथड का उपयोग करता है, जो भी परिभाषित हो।

```cpp
template<typename TKey,typename TValue> bool System::Collections::Generic::operator==(const KeyValuePair<TKey, TValue> &left, const KeyValuePair<TKey, TValue> &right)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| TKey | कुंजी प्रकार। |
| TValue | मान प्रकार। |

### आर्ग्यूमेंट

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| left | const [KeyValuePair](../keyvaluepair/)\<TKey, TValue\>\& | बाएँ हाथ का ऑपेंड। |
| right | const [KeyValuePair](../keyvaluepair/)\<TKey, TValue\>\& | दाएँ हाथ का ऑपेंड। |

### वापसी मान

यदि दोनों कुंजियाँ और मान मेल खाते हैं तो सत्य, अन्यथा असत्य।

## संबंधित देखें

* क्लास [KeyValuePair](../keyvaluepair/)
* नामस्थान [System::Collections::Generic](../)
* लाइब्रेरी [Aspose.Slides](../../)