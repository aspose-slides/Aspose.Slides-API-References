---
title: setter_post_decrement_wrap()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: अनुवादक C# के पोस्ट-डिक्रीमेंट अभिव्यक्तियों को, जो ऐसी class' property को लक्षित करती हैं जहाँ setter और getter परिभाषित है, इस फ़ंक्शन के कॉल में अनुवादित करता है।
type: docs
weight: 2874
url: /hi/system/setter_post_decrement_wrap/
---
## System::setter_post_decrement_wrap(T(*)(), void(*)(T)) फ़ंक्शन

अनुवादक C# के पोस्ट-डिक्रीमेंट अभिव्यक्तियों को, जो क्लास की प्रॉपर्टी को लक्षित करती हैं और जिनमें setter और getter परिभाषित है, इस फ़ंक्शन के कॉल में अनुवादित करता है।

```cpp
template<typename T> T System::setter_post_decrement_wrap(T(*pGetter)(), void(*pSetter)(T))
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | प्रॉपर्टी का प्रकार |

### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pGetter | T(*)() | प्रॉपर्टी के getter फ्री फ़ंक्शन की ओर इशारा करने वाला फ़ंक्शन पॉइंटर |
| pSetter | void(*)(T) | प्रॉपर्टी के setter फ्री फ़ंक्शन की ओर इशारा करने वाला फ़ंक्शन पॉइंटर |

### रिटर्न मान

इन्क्रीमेंट से पहले प्रॉपर्टी का मान

## System::setter_post_decrement_wrap(Host *const, T(HostGet::*)(), void(HostSet::*)(T)) फ़ंक्शन

अनुवादक C# के पोस्ट-डिक्रीमेंट अभिव्यक्तियों को, जो इंस्टेंस की प्रॉपर्टी को लक्षित करती हैं और जिनमें setter और getter परिभाषित है, इस फ़ंक्शन (overload for non-const getter) के कॉल में अनुवादित करता है।

```cpp
template<typename T,typename Host,typename HostGet,typename HostSet> std::enable_if<std::is_base_of<HostGet, Host>::value &&std::is_base_of<HostSet, Host>::value, T>::type System::setter_post_decrement_wrap(Host *const host, T(HostGet::*pGetter)(), void(HostSet::*pSetter)(T))
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | प्रॉपर्टी का प्रकार। |
| Host | - संशोधित करने के लिये इंस्टेंस की क्लास |
| HostGet | - Host स्वयं, या उसका बेस टाइप जहाँ प्रॉपर्टी का getter परिभाषित है |
| HostSet | - Host स्वयं, या उसका बेस टाइप जहाँ प्रॉपर्टी का setter परिभाषित है |

### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| host | Host *const | जिस इंस्टेंस के लिए getter और setter को कॉल किया जायेगा। |
| pGetter | T(HostGet::*)() | प्रॉपर्टी के getter फ़ंक्शन की ओर इशारा करने वाला फ़ंक्शन पॉइंटर |
| pSetter | void(HostSet::*)(T) | प्रॉपर्टी के setter फ़ंक्शन की ओर इशारा करने वाला फ़ंक्शन पॉइंटर |

### रिटर्न मान

इन्क्रीमेंट से पहले प्रॉपर्टी का मान

## System::setter_post_decrement_wrap(Host *const, T(HostConstGet::*)() const, void(HostSet::*)(T)) फ़ंक्शन

अनुवादक C# के पोस्ट-डिक्रीमेंट अभिव्यक्तियों को, जो इंस्टेंस की प्रॉपर्टी को लक्षित करती हैं और जिनमें setter और getter परिभाषित है, इस फ़ंक्शन (overload for const getter) के कॉल में अनुवादित करता है।

```cpp
template<typename T,typename Host,typename HostConstGet,typename HostSet> std::enable_if<std::is_base_of<HostConstGet, Host>::value &&std::is_base_of<HostSet, Host>::value, T>::type System::setter_post_decrement_wrap(Host *const host, T(HostConstGet::*pGetter)() const, void(HostSet::*pSetter)(T))
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | प्रॉपर्टी का प्रकार। |
| Host | - संशोधित करने के लिये इंस्टेंस की क्लास |
| HostConstGet | - Host स्वयं, या उसका बेस टाइप जहाँ प्रॉपर्टी का getter परिभाषित है |
| HostSet | - Host स्वयं, या उसका बेस टाइप जहाँ प्रॉपर्टी का setter परिभाषित है |

### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| host | Host *const | जिस इंस्टेंस के लिए getter और setter को कॉल किया जायेगा। |
| pGetter | T(HostConstGet::*)() const | प्रॉपर्टी के getter फ़ंक्शन की ओर इशारा करने वाला फ़ंक्शन पॉइंटर |
| pSetter | void(HostSet::*)(T) | प्रॉपर्टी के setter फ़ंक्शन की ओर इशारा करने वाला फ़ंक्शन पॉइंटर |

### रिटर्न मान

इन्क्रीमेंट से पहले प्रॉपर्टी का मान

## संबंधित देखें

* नेमस्पेस [System](../)
* लाइब्रेरी [Aspose.Slides](../../)