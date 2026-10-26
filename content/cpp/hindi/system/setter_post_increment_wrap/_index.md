---
title: setter_post_increment_wrap()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: अनुवादक C# की पोस्ट-इन्क्रिमेंट अभिव्यक्तियों को जो सेट्टर और गेटर परिभाषित क्लास की प्रॉपर्टी को लक्षित करती हैं, इस फ़ंक्शन के आह्वान में बदलता है।
type: docs
weight: 2848
url: /hi/system/setter_post_increment_wrap/
---
## System::setter_post_increment_wrap(T(*)(), void(*)(T)) फ़ंक्शन

अनुवादक C# की पोस्ट-इन्क्रिमेंट अभिव्यक्तियों को जो सेट्टर और गेटर परिभाषित क्लास की प्रॉपर्टी को लक्षित करती हैं, इस फ़ंक्शन के आह्वान में बदलता है।

```cpp
template<typename T> T System::setter_post_increment_wrap(T(*pGetter)(), void(*pSetter)(T))
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | प्रॉपर्टी का प्रकार |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pGetter | T(*)() | फ़ंक्शन पॉइंटर जो प्रॉपर्टी के गेटर फ्री फ़ंक्शन की ओर इशारा करता है |
| pSetter | void(*)(T) | फ़ंक्शन पॉइंटर जो प्रॉपर्टी के सेट्टर फ्री फ़ंक्शन की ओर इशारा करता है |

### वापसी मान

इंक्रीमेंट करने से पहले प्रॉपर्टी का मान

## System::setter_post_increment_wrap(Host *const, T(HostGet::*)(), void(HostSet::*)(T)) फ़ंक्शन

अनुवादक C# की पोस्ट-इन्क्रिमेंट अभिव्यक्तियों को जो सेट्टर और गेटर परिभाषित इंस्टेंस की प्रॉपर्टी को लक्षित करती हैं, इस फ़ंक्शन के आह्वान में बदलता है (नॉन-कंस्ट गेटर के लिए ओवरलोड)।

```cpp
template<typename T,typename Host,typename HostGet,typename HostSet> std::enable_if<std::is_base_of<HostGet, Host>::value &&std::is_base_of<HostSet, Host>::value, T>::type System::setter_post_increment_wrap(Host *const host, T(HostGet::*pGetter)(), void(HostSet::*pSetter)(T))
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | प्रॉपर्टी का प्रकार। |
| Host | - संशोधित किए जाने वाले इंस्टेंस का क्लास |
| HostGet | - Host स्वयं, या उसका बेस टाइप, जहाँ प्रॉपर्टी का गेटर परिभाषित है |
| HostSet | - Host स्वयं, या उसका बेस टाइप, जहाँ प्रॉपर्टी का सेट्टर परिभाषित है |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| host | Host *const | गेटर और सेट्टर कॉल करने के लिए इंस्टेंस। |
| pGetter | T(HostGet::*)() | फ़ंक्शन पॉइंटर जो प्रॉपर्टी के गेटर फ़ंक्शन की ओर इशारा करता है |
| pSetter | void(HostSet::*)(T) | फ़ंक्शन पॉइंटर जो प्रॉपर्टी के सेट्टर फ़ंक्शन की ओर इशारा करता है |

### वापसी मान

इंक्रीमेंट करने से पहले प्रॉपर्टी का मान

## System::setter_post_increment_wrap(Host *const, T(HostConstGet::*)() const, void(HostSet::*)(T)) फ़ंक्शन

अनुवादक C# की पोस्ट-इन्क्रिमेंट अभिव्यक्तियों को जो सेट्टर और गेटर परिभाषित इंस्टेंस की प्रॉपर्टी को लक्षित करती हैं, इस फ़ंक्शन के आह्वान में बदलता है (कंस्ट गेटर के लिए ओवरलोड)।

```cpp
template<typename T,typename Host,typename HostConstGet,typename HostSet> std::enable_if<std::is_base_of<HostConstGet, Host>::value &&std::is_base_of<HostSet, Host>::value, T>::type System::setter_post_increment_wrap(Host *const host, T(HostConstGet::*pGetter)() const, void(HostSet::*pSetter)(T))
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | प्रॉपर्टी का प्रकार। |
| Host | - संशोधित किए जाने वाले इंस्टेंस का क्लास |
| HostConstGet | - Host स्वयं, या उसका बेस टाइप, जहाँ प्रॉपर्टी का गेटर परिभाषित है |
| HostSet | - Host स्वयं, या उसका बेस टाइप, जहाँ प्रॉपर्टी का सेट्टर परिभाषित है |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| host | Host *const | गेटर और सेट्टर कॉल करने के लिए इंस्टेंस। |
| pGetter | T(HostConstGet::*)() const | फ़ंक्शन पॉइंटर जो प्रॉपर्टी के गेटर फ़ंक्शन की ओर इशारा करता है |
| pSetter | void(HostSet::*)(T) | फ़ंक्शन पॉइंटर जो प्रॉपर्टी के सेट्टर फ़ंक्शन की ओर इशारा करता है |

### वापसी मान

इंक्रीमेंट करने से पहले प्रॉपर्टी का मान

## संबंधित देखें

* नेमस्पेस [System](../)
* लाइब्रेरी [Aspose.Slides](../../)