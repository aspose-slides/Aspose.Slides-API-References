---
title: setter_wrap()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: टाइप परिवर्तन के साथ स्थिर setter फ़ंक्शन के लिए ओवरलोड।
type: docs
weight: 2822
url: /hi/system/setter_wrap/
---
## System::setter_wrap(void(*)(T2), T) फ़ंक्शन

टाइप परिवर्तन के साथ स्थिर setter फ़ंक्शनों के लिए ओवरलोड।

```cpp
template<typename T,typename T2> T System::setter_wrap(void(*pSetter)(T2), T value)
```

### टेम्पलेट पैरामीटर्स

| पैरामीटर | विवरण |
| --- | --- |
| T | मान प्रकार। |
| T2 | setter फ़ंक्शन द्वारा अपेक्षित टाइप। |

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| pSetter | void(*)(T2) | स्थिर setter फ़ंक्शन संदर्भ। |
| value | T | सेट करने के लिए मान। |

### रिटर्न मान

सेट किया गया मान।

## System::setter_wrap(Host *const, void(HostSet::*)(T2), T) फ़ंक्शन

टाइप परिवर्तन के साथ इंस्टेंस setter फ़ंक्शनों के लिए ओवरलोड।

```cpp
template<typename T,typename T2,typename Host,typename HostSet> std::enable_if<std::is_base_of<HostSet, Host>::value, T>::type System::setter_wrap(Host *const host, void(HostSet::*pSetter)(T2), T value)
```

### टेम्पलेट पैरामीटर्स

| पैरामीटर | विवरण |
| --- | --- |
| T | मान प्रकार। |
| T2 | setter फ़ंक्शन द्वारा अपेक्षित टाइप। |
| Host | इंस्टेंस प्रकार। |
| HostSet | - Host स्वयं, या उसका बेस टाइप, जहाँ प्रॉपर्टी का setter परिभाषित है। |

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| host | Host *const | [Object](../object/) को setter फ़ंक्शन को कॉल करने के लिए। |
| pSetter | void(HostSet::*)(T2) | सेटर फ़ंक्शन संदर्भ। |
| value | T | सेट करने के लिए मान। |

### रिटर्न मान

सेट किया गया मान।

## संबंधित देखें

* नेमस्पेस [System](../)
* लाइब्रेरी [Aspose.Slides](../../)