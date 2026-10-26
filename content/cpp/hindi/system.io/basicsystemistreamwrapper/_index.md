---
title: BasicSystemIStreamWrapper
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: "एक std::istream-के समान रैपर दर्शाता है जो BasicSystemIOStreamBuf को आंतरिक बफ़र के रूप में उपयोग करता है।"
type: docs
weight: 66
url: /hi/system.io/basicsystemistreamwrapper/
---
## BasicSystemIStreamWrapper क्लास

एक std::istream-जैसा रैपर दर्शाता है जो [BasicSystemIOStreamBuf](../basicsystemiostreambuf/) को आंतरिक बफ़र के रूप में उपयोग करता है।

```cpp
template<typename Elem,typename Traits>class BasicSystemIStreamWrapper : public std::basic_istream<Elem, std::char_traits<Elem>>
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| void [AssignRV](./assignrv/)([BasicSystemIStreamWrapper](./)\&&) | मूव कन्स्ट्रक्टर और मूव असाइनमेंट ऑपरेटर में पॉइंटर्स को रीसेट करने और [swap()](./swap/) को कॉल करने के लिए उपयोग किया जाता है। |
|  [BasicSystemIStreamWrapper](./basicsystemistreamwrapper/)([SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>, [SystemIOStreamWrappingMode](../systemiostreamwrappingmode/)) | [BasicSystemIStreamWrapper](./) का नया उदाहरण बनाता है। |
|  [BasicSystemIStreamWrapper](./basicsystemistreamwrapper/)(const [BasicSystemIStreamWrapper](./)\&) | कॉपी कन्स्ट्रक्टर। हटाया गया। |
|  [BasicSystemIStreamWrapper](./basicsystemistreamwrapper/)([BasicSystemIStreamWrapper](./)\&&) | मूव कन्स्ट्रक्टर। |
| [BasicSystemIStreamWrapper](./)\& [operator=](./operator_equal/)(const [BasicSystemIStreamWrapper](./)\&) | कॉपी असाइनमेंट ऑपरेटर। हटाया गया। |
| [BasicSystemIStreamWrapper](./)\& [operator=](./operator_equal/)([BasicSystemIStreamWrapper](./)\&&) | मूव असाइनमेंट ऑपरेटर। |
| void [swap](./swap/)([BasicSystemIStreamWrapper](./)\&) | यदि वे समान नहीं हैं तो *this और **right** को स्वैप करने के लिए कॉल। |
## टाइपडिफ़

| टाइपडिफ़ | विवरण |
| --- | --- |
| [char_type](./char_type/) |  |
| [traits_type](./traits_type/) |  |
| [Mybase](./mybase/) |  |
| [Mysb](./mysb/) |  |
## संबंधित देखें

* नामस्थान [System::IO](../)
* पुस्तकालय [Aspose.Slides](../../)