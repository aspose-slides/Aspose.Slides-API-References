---
title: setter_decrement_wrap()
second_title: Aspose.Slides for C++ API संदर्भ
description: ट्रांसलेटर C# के प्री-डिक्रीमेंट अभिव्यक्तियों को जो क्लास की प्रॉपर्टी को लक्षित करती हैं और जिनके लिए सेट्टर और गेट्टर परिभाषित हैं, इस फ़ंक्शन को कॉल करने में परिवर्तित करता है।
type: docs
weight: 2861
url: /hi/system/setter_decrement_wrap/
---
## System::setter_decrement_wrap(T(*)(), void(*)(T)) function


ट्रांसलेटर C# की प्री-डिक्रीमेंट अभिव्यक्तियों को जो क्लास की प्रॉपर्टी को लक्षित करती हैं और जिनके लिए सेट्टर और गेट्टर परिभाषित हैं, इस फ़ंक्शन को कॉल करने में परिवर्तित करता है।

```cpp
template<typename T> T System::setter_decrement_wrap(T(*pGetter)(), void(*pSetter)(T))
```


### टेम्प्लेट पैरामीटर

| Parameter | Description |
| --- | --- |
| T | प्रॉपर्टी का प्रकार |

### आर्ग्यूमेंट्स

| Parameter | Type | Description |
| --- | --- | --- |
| pGetter | T(*)() | फ़ंक्शन पॉइंटर जो प्रॉपर्टी के getter फ़्री फ़ंक्शन की ओर संकेत करता है |
| pSetter | void(*)(T) | फ़ंक्शन पॉइंटर जो प्रॉपर्टी के setter फ़्री फ़ंक्शन की ओर संकेत करता है |

### वापसी मान

इन्क्रीमेंट से पहले प्रॉपर्टी का मान

## System::setter_decrement_wrap(Host *const, T(HostGet::*)(), void(HostSet::*)(T)) function


ट्रांसलेटर C# की प्री-डिक्रीमेंट अभिव्यक्तियों को जो इंस्टेंस की प्रॉपर्टी को लक्षित करती हैं और जिनके लिए सेट्टर और गेट्टर परिभाषित हैं, इस फ़ंक्शन को कॉल करने में परिवर्तित करता है (नॉन-कॉन्ट गेट्टर के लिए ओवरलोड)।

```cpp
template<typename T,typename Host,typename HostGet,typename HostSet> std::enable_if<std::is_base_of<HostGet, Host>::value &&std::is_base_of<HostSet, Host>::value, T>::type System::setter_decrement_wrap(Host *const host, T(HostGet::*pGetter)(), void(HostSet::*pSetter)(T))
```


### टेम्प्लेट पैरामीटर

| Parameter | Description |
| --- | --- |
| T | प्रॉपर्टी का प्रकार। |
| Host | - संशोधित किए जाने वाले इंस्टेंस की क्लास |
| HostGet | - होस्ट स्वयं, या उसका बेस टाइप जहाँ प्रॉपर्टी का getter परिभाषित है |
| HostSet | - होस्ट स्वयं, या उसका बेस टाइप जहाँ प्रॉपर्टी का setter परिभाषित है |

### आर्ग्यूमेंट्स

| Parameter | Type | Description |
| --- | --- | --- |
| host | Host *const | वह इंस्टेंस जिसके लिए getter और setter को कॉल किया जाता है। |
| pGetter | T(HostGet::*)() | फ़ंक्शन पॉइंटर जो प्रॉपर्टी के getter फ़ंक्शन की ओर संकेत करता है |
| pSetter | void(HostSet::*)(T) | फ़ंक्शन पॉइंटर जो प्रॉपर्टी के setter फ़ंक्शन की ओर संकेत करता है |

### वापसी मान

इन्क्रीमेंट से पहले प्रॉपर्टी का मान

## System::setter_decrement_wrap(Host *const, T(HostConstGet::*)() const, void(HostSet::*)(T)) function


ट्रांसलेटर C# की प्री-डिक्रीमेंट अभिव्यक्तियों को जो इंस्टेंस की प्रॉपर्टी को लक्षित करती हैं और जिनके लिए सेट्टर और गेट्टर परिभाषित हैं, इस फ़ंक्शन को कॉल करने में परिवर्तित करता है (कॉन्ट गेट्टर के लिए ओवरलोड)।

```cpp
template<typename T,typename Host,typename HostConstGet,typename HostSet> std::enable_if<std::is_base_of<HostConstGet, Host>::value &&std::is_base_of<HostSet, Host>::value, T>::type System::setter_decrement_wrap(Host *const host, T(HostConstGet::*pGetter)() const, void(HostSet::*pSetter)(T))
```


### टेम्प्लेट पैरामीटर

| Parameter | Description |
| --- | --- |
| T | प्रॉपर्टी का प्रकार। |
| Host | - संशोधित किए जाने वाले इंस्टेंस की क्लास |
| HostConstGet | - होस्ट स्वयं, या उसका बेस टाइप जहाँ प्रॉपर्टी का getter परिभाषित है |
| HostSet | - होस्ट स्वयं, या उसका बेस टाइप जहाँ प्रॉपर्टी का setter परिभाषित है |

### आर्ग्यूमेंट्स

| Parameter | Type | Description |
| --- | --- | --- |
| host | Host *const | वह इंस्टेंस जिसके लिए getter और setter को कॉल किया जाता है। |
| pGetter | T(HostConstGet::*)() const | फ़ंक्शन पॉइंटर जो प्रॉपर्टी के getter फ़ंक्शन की ओर संकेत करता है |
| pSetter | void(HostSet::*)(T) | फ़ंक्शन पॉइंटर जो प्रॉपर्टी के setter फ़ंक्शन की ओर संकेत करता है |

### वापसी मान

इन्क्रीमेंट से पहले प्रॉपर्टी का मान

## See Also

* Namespace [System](../)
* Library [Aspose.Slides](../../)