---
title: Ref()
second_title: Aspose.Slides for C++ API संदर्भ
description: DynamicWeakPtr ऑब्जेक्ट का रेफ़रेंस बनाता है। ट्रांसलेटर द्वारा फ़ंक्शन आर्ग्युमेंट्स को रेफ़रेंस द्वारा पास करने पर उपयोग किया जाता है।
type: docs
weight: 2458
url: /hi/system/ref/
---
## System::Ref(DynamicWeakPtr\<T, trunkMode, weakLeafs...\>\&) फ़ंक्शन


[DynamicWeakPtr](../dynamicweakptr/) ऑब्जेक्ट के लिए रेफ़रेंस बनाता है। ट्रांसलेटर द्वारा फ़ंक्शन आर्ग्युमेंट्स को रेफ़रेंस द्वारा पास करने पर उपयोग किया जाता है।

```cpp
template<typename T,SmartPtrMode,unsigned int ...> DynamicWeakPtr<T, trunkMode, weakLeafs...>::Reference System::Ref(DynamicWeakPtr<T, trunkMode, weakLeafs...> &ptr)
```


### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | पॉइंट किया गया प्रकार। |
| trunkMode | स्मार्ट पॉइंटर स्वयं का मोड। |
| weakLeafs | उन टेम्प्लेट आर्ग्युमेंट्स के इंडेक्स जिनके लिए SetTemplateWeakPtr मेथड को कॉल करना आवश्यक है। |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| ptr | [DynamicWeakPtr](../dynamicweakptr/)\<T, trunkMode, weakLeafs...\>\& | वह स्मार्ट पॉइंटर जिसे रेफ़रेंस में परिवर्तित किया जाना है। |

### रिटर्न मान

स्मार्ट पॉइंटर रेफ़रेंस।

## System::Ref(T\&) फ़ंक्शन


ऑब्जेक्ट्स के रेफ़रेंस प्राप्त करने के लिए हेल्पर फ़ंक्शन। यह सुनिश्चित करता है कि [System::DynamicWeakPtr](../dynamicweakptr/) असाइनमेंट के बाद रेफ़रेंस किए गए ऑब्जेक्ट को अपडेट करता है।

```cpp
template<typename T> T & System::Ref(T &value)
```


### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | वह प्रकार जिससे रेफ़रेंस बनाया जाना है। |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | T\& | वह वैल्यू जिससे रेफ़रेंस बनाया जाना है। |

### रिटर्न मान

इस फ़ंक्शन को पास किए गए वैल्यू का रेफ़रेंस।

## सम्बन्धित देखें

* Class [DynamicWeakPtr](../dynamicweakptr/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)