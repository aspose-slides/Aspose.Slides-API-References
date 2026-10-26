---
title: BuildObject()
second_title: Aspose.Slides for C++ API संदर्भ
description: साझा स्वामित्व के साथ एक ऑब्जेक्ट बनाएं।
type: docs
weight: 2250
url: /hi/system/buildobject/
---
## System::BuildObject(Args\&&...) फ़ंक्शन

साझा स्वामित्व के साथ एक ऑब्जेक्ट बनाएं।

```cpp
template<typename T,typename...> Details::ObjectBuilder<T, SharedPtr<T>> System::BuildObject(Args &&... args)
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | बनाने के लिए ऑब्जेक्ट का प्रकार |
| Args | ऑब्जेक्ट निर्माण के लिए आर्ग्यूमेंट प्रकार |

### आर्ग्यूमेंट

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| args | Args\&&... | ऑब्जेक्ट कन्स्ट्रक्टर को फॉरवर्ड करने के लिए आर्ग्यूमेंट्स |

### रिटर्न वैल्यू

शेयरड पॉइंटर निर्माण के लिए कॉन्फ़िगर किया गया ObjectBuilder

## टिप्पणी

SharedPtr<T> बनाता है और इसके लिए एक बिल्डर वापस करता है  
[Object](../object/) निर्माण को [Get()](../get/) कॉल के साथ पूरा किया जाना चाहिए  

## देखें

* टाइपडिफ़ [SharedPtr](../sharedptr/)
* नेमस्पेस [System](../)
* लाइब्रेरी [Aspose.Slides](../../)