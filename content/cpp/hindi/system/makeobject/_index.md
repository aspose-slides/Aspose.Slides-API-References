---
title: MakeObject()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: हीप पर ऑब्जेक्ट बनाता है और उसके लिए साझा पॉइंटर लौटाता है।
type: docs
weight: 2887
url: /hi/system/makeobject/
---
## System::MakeObject(Args\&&...) फ़ंक्शन


हीप पर ऑब्जेक्ट बनाता है और उसके लिए साझा पॉइंटर लौटाता है।

```cpp
template<class T,class ...> std::enable_if<!IsSmartPtr<T>::value, SmartPtr<T>>::type System::MakeObject(Args &&... args)
```


### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | इंस्टैंटिएट करने के लिए वर्ग। |
| Args | कंस्ट्रक्टर आर्गुमेंट्स के प्रकार। |

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| args | Args\&&... | कंस्ट्रक्टर आर्गुमेंट्स। |

### रिटर्न वैल्यू

[SmartPtr](../smartptr/) को नए बनाए गए ऑब्जेक्ट की ओर, हमेशा साझा मोड में।

## System::MakeObject(Args\&&...) फ़ंक्शन


हीप पर ऑब्जेक्ट बनाता है और उसके लिए साझा पॉइंटर लौटाता है।

```cpp
template<class T,class ...> std::enable_if<IsSmartPtr<T>::value, T>::type System::MakeObject(Args &&... args)
```


### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | [SmartPtr](../smartptr/) को वर्ग इंस्टैंटिएट करने के लिए। |
| Args | कंस्ट्रक्टर आर्गुमेंट्स के प्रकार। |

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| args | Args\&&... | कंस्ट्रक्टर आर्गुमेंट्स। |

### रिटर्न वैल्यू

[SmartPtr](../smartptr/) को नए बनाए गए ऑब्जेक्ट की ओर, हमेशा साझा मोड में।

## देखें भी

* वर्ग [SmartPtr](../smartptr/)
* संरचना [IsSmartPtr](../issmartptr/)
* नामस्थान [System](../)
* लाइब्रेरी [Aspose.Slides](../../)