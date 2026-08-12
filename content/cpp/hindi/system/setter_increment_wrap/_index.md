---
title: setter_increment_wrap()
second_title: Aspose.Slides for C++ API संदर्भ
description: अनुवादक C# की increment अभिव्यक्तियों को जो क्लास की प्रॉपर्टी को लक्ष्य बनाती हैं, जहाँ setter और getter परिभाषित हैं, इस फ़ंक्शन के आह्वान में बदलता है।
type: docs
weight: 2835
url: /hi/system/setter_increment_wrap/
---
## System::setter_increment_wrap(T(*)(), void(*)(T)) फ़ंक्शन

अनुवादक C# की increment अभिव्यक्तियों को जो class की property को लक्ष्य बनाती हैं जिनमें setter और getter परिभाषित है, इस फ़ंक्शन के आह्वान में बदलता है।

```cpp
template<typename T> T System::setter_increment_wrap(T(*pGetter)(), void(*pSetter)(T))
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | प्रॉपर्टी का प्रकार |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pGetter | T(*)() | फ़ंक्शन पॉइंटर जो प्रॉपर्टी के getter फ्री फ़ंक्शन की ओर संकेत करता है |
| pSetter | void(*)(T) | फ़ंक्शन पॉइंटर जो प्रॉपर्टी के setter फ्री फ़ंक्शन की ओर संकेत करता है |

### रिटर्न वैल्यू

प्रॉपर्टी का बढ़ाया हुआ मान

## System::setter_increment_wrap(Host *const, T(HostGet::*)(), void(HostSet::*)(T)) फ़ंक्शन

अनुवादक C# की increment अभिव्यक्तियों को जो class की property को लक्ष्य बनाती हैं जिनमें setter और getter परिभाषित है, इस फ़ंक्शन के आह्वान में बदलता है।

```cpp
template<typename T,typename Host,typename HostGet,typename HostSet> std::enable_if<std::is_base_of<HostGet, Host>::value &&std::is_base_of<HostSet, Host>::value, T>::type System::setter_increment_wrap(Host *const host, T(HostGet::*pGetter)(), void(HostSet::*pSetter)(T))
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | प्रॉपर्टी का प्रकार |
| Host | - संशोधित किए जाने वाले इंस्टेंस का class |
| HostGet | - Host स्वयं, या उसका बेस टाइप, जहाँ प्रॉपर्टी का getter परिभाषित है |
| HostSet | - Host स्वयं, या उसका बेस टाइप, जहाँ प्रॉपर्टी का setter परिभाषित है |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| host | Host *const | वह पॉइंटर जो उस ऑब्जेक्ट की ओर है जिसकी प्रॉपर्टी बढ़ाने योग्य है |
| pGetter | T(HostGet::*)() | फ़ंक्शन पॉइंटर जो प्रॉपर्टी के getter मेथड की ओर संकेत करता है |
| pSetter | void(HostSet::*)(T) | फ़ंक्शन पॉइंटर जो प्रॉपर्टी के setter मेथड की ओर संकेत करता है |

### रिटर्न वैल्यू

प्रॉपर्टी का बढ़ाया हुआ मान

## संबंधित देखें

* नामस्थान [System](../)
* लाइब्रेरी [Aspose.Slides](../../)