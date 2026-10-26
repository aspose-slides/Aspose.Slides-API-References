---
title: BasicSystemIOStreamWrapper
second_title: Aspose.Slides for C++ API संदर्भ
description: "एक std::iostream जैसे रैपर को दर्शाता है जो BasicSystemIOStreamBuf को आंतरिक बफ़र के रूप में उपयोग करता है।"
type: docs
weight: 53
url: /hi/system.io/basicsystemiostreamwrapper/
---
## BasicSystemIOStreamWrapper क्लास

एक std::iostream जैसा रैपर दर्शाता है जो [BasicSystemIOStreamBuf](../basicsystemiostreambuf/) को आंतरिक बफ़र के रूप में उपयोग करता है।

```cpp
template<typename Elem,typename Traits>class BasicSystemIOStreamWrapper : public std::basic_iostream<Elem, std::char_traits<Elem>>
```

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| void [AssignRV](./assignrv/)([BasicSystemIOStreamWrapper](./)\&&) | मूव कन्स्ट्रक्टर और मूव असाइनमेंट ऑपरेटर में पॉइंटर्स को रीसेट करने और [swap()](./swap/) को कॉल करने के लिये उपयोग किया जाता है। |
| [BasicSystemIOStreamWrapper](./basicsystemiostreamwrapper/)([SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>, [SystemIOStreamWrappingMode](../systemiostreamwrappingmode/)) | [BasicSystemIOStreamWrapper](./) का नया इंस्टेंस बनाता है। |
| [BasicSystemIOStreamWrapper](./basicsystemiostreamwrapper/)(const [BasicSystemIOStreamWrapper](./)\&) | कॉपी कन्स्ट्रक्टर। हटाया गया। |
| [BasicSystemIOStreamWrapper](./basicsystemiostreamwrapper/)([BasicSystemIOStreamWrapper](./)\&&) | मूव कन्स्ट्रक्टर। |
| [BasicSystemIOStreamWrapper](./)\& [operator=](./operator_equal/)(const [BasicSystemIOStreamWrapper](./)\&) | कॉपी असाइनमेंट ऑपरेटर। हटाया गया। |
| [BasicSystemIOStreamWrapper](./)\& [operator=](./operator_equal/)([BasicSystemIOStreamWrapper](./)\&&) | मूव असाइनमेंट ऑपरेटर। |
| void [swap](./swap/)([BasicSystemIOStreamWrapper](./)\&) | यदि वे बराबर न हों, तो *this और **right** को स्वैप करने के लिए कॉल किया जाता है। |

## टाइपडिफ़

| टाइपडिफ़ | विवरण |
| --- | --- |
| [char_type](./char_type/) |  |
| [traits_type](./traits_type/) |  |
| [Mybase](./mybase/) |  |
| [Mysb](./mysb/) |  |

## संबंधित देखें

* नामस्थान [System::IO](../)
* लाइब्रेरी [Aspose.Slides](../../)