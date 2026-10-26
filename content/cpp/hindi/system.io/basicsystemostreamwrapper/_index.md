---
title: BasicSystemOStreamWrapper
second_title: Aspose.Slides for C++ API संदर्भ
description: "एक std::ostream जैसी रैपर का प्रतिनिधित्व करता है जो BasicSystemIOStreamBuf को आंतरिक बफ़र के रूप में उपयोग करता है।"
type: docs
weight: 79
url: /hi/system.io/basicsystemostreamwrapper/
---
## BasicSystemOStreamWrapper क्लास

एक std::ostream-like रैपर का प्रतिनिधित्व करता है जो [BasicSystemIOStreamBuf](../basicsystemiostreambuf/) को आंतरिक बफ़र के रूप में उपयोग करता है।

```cpp
template<typename Elem,typename Traits>class BasicSystemOStreamWrapper : public std::basic_ostream<Elem, std::char_traits<Elem>>
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| void [AssignRV](./assignrv/)([BasicSystemOStreamWrapper](./)\&&) | मूव कन्स्ट्रक्टर और मूव असाइनमेंट ऑपरेटर में पॉइंटर्स को रीसेट करने और [swap()](./swap/) को कॉल करने के लिए उपयोग किया जाता है। |
| [BasicSystemOStreamWrapper](./basicsystemostreamwrapper/)([SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>, [SystemIOStreamWrappingMode](../systemiostreamwrappingmode/)) | [BasicSystemOStreamWrapper](./) का एक नया उदाहरण बनाता है। |
| [BasicSystemOStreamWrapper](./basicsystemostreamwrapper/)(const [BasicSystemOStreamWrapper](./)\&) | कॉपी कन्स्ट्रक्टर। हटाया गया। |
| [BasicSystemOStreamWrapper](./basicsystemostreamwrapper/)([BasicSystemOStreamWrapper](./)\&&) | मूव कन्स्ट्रक्टर। |
| [BasicSystemOStreamWrapper](./)\& [operator=](./operator_equal/)(const [BasicSystemOStreamWrapper](./)\&) | कॉपी असाइनमेंट ऑपरेटर। हटाया गया। |
| [BasicSystemOStreamWrapper](./)\& [operator=](./operator_equal/)([BasicSystemOStreamWrapper](./)\&&) | मूव असाइनमेंट ऑपरेटर। |
| void [swap](./swap/)([BasicSystemOStreamWrapper](./)\&) | यदि वे समान नहीं हैं तो *this और **right** को स्वैप करने के लिए कॉल। |

## टाइपडिफ़

| टाइपडिफ़ | विवरण |
| --- | --- |
| [char_type](./char_type/) |  |
| [traits_type](./traits_type/) |  |
| [Mybase](./mybase/) |  |
| [Mysb](./mysb/) |  |

## देखें

* नेमस्पेस [System::IO](../)
* लाइब्रेरी [Aspose.Slides](../../)