---
title: GetHashCode()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट स्केलर मान के लिए एक हैश कोड लौटाता है।
type: docs
weight: 2484
url: /hi/system/gethashcode/
---
## System::GetHashCode(const T\&) फ़ंक्शन

निर्दिष्ट स्केलर मान के लिए एक हैश कोड लौटाता है।

```cpp
template<typename T> std::enable_if<std::is_scalar<T>::value, int>::type System::GetHashCode(const T &obj)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | फ़ंक्शन द्वारा हैश कोड उत्पन्न करने वाले मान का प्रकार |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | const T\& | हैश कोड उत्पन्न करने के लिए मान |

### रिटर्न मान

निर्दिष्ट मान के लिए उत्पन्न किया गया हैश कोड

## System::GetHashCode(const T\&) फ़ंक्शन

निर्दिष्ट ऑब्जेक्ट के लिए एक हैश कोड लौटाता है।

```cpp
template<typename T> std::enable_if<!std::is_scalar<T>::value &&System::IsSmartPtr<T>::value, int>::type System::GetHashCode(const T &obj)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | फ़ंक्शन द्वारा हैश कोड उत्पन्न करने वाले ऑब्जेक्ट का प्रकार |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | const T\& | हैश कोड उत्पन्न करने वाले ऑब्जेक्ट की ओर संकेत करने वाला [SmartPtr](../smartptr/) |

### रिटर्न मान

निर्दिष्ट ऑब्जेक्ट के लिए उत्पन्न किया गया हैश कोड

## System::GetHashCode(const T\&) फ़ंक्शन

निर्दिष्ट ऑब्जेक्ट जो एक अपवाद है, के लिए एक हैश कोड लौटाता है।

```cpp
template<typename T> std::enable_if<System::IsExceptionWrapper<T>::value, int>::type System::GetHashCode(const T &obj)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | फ़ंक्शन द्वारा हैश कोड उत्पन्न करने वाले ऑब्जेक्ट का प्रकार |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | const T\& | हैश कोड उत्पन्न करने वाले ऑब्जेक्ट को सम्मिलित करने वाला Exception Wrapper |

### रिटर्न मान

निर्दिष्ट ऑब्जेक्ट के लिए उत्पन्न किया गया हैश कोड

## System::GetHashCode(const T\&) फ़ंक्शन

निर्दिष्ट ऑब्जेक्ट जो स्मार्ट पॉइंटर या अपवाद नहीं है, के लिए एक हैश कोड लौटाता है।

```cpp
template<typename T> std::enable_if<!std::is_scalar<T>::value &&!System::IsSmartPtr<T>::value &&!System::IsExceptionWrapper<T>::value, int>::type System::GetHashCode(const T &obj)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | फ़ंक्शन द्वारा हैश कोड उत्पन्न करने वाले ऑब्जेक्ट का प्रकार |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | const T\& | हैश कोड उत्पन्न करने वाले ऑब्जेक्ट का const रेफ़रेंस |

### रिटर्न मान

निर्दिष्ट ऑब्जेक्ट के लिए उत्पन्न किया गया हैश कोड

## System::GetHashCode(const std::thread::id\&) फ़ंक्शन

std::thread::id के लिए विशेषीकरण; निर्दिष्ट थ्रेड ऑब्जेक्ट के लिए हैश कोड लौटाता है।

```cpp
int System::GetHashCode(const std::thread::id &id)
```

## देखें

* Struct [IsSmartPtr](../issmartptr/)
* Struct [IsExceptionWrapper](../isexceptionwrapper/)
* नेमस्पेस [System](../)
* Library [Aspose.Slides](../../)