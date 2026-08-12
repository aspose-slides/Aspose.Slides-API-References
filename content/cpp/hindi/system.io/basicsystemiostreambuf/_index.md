---
title: BasicSystemIOStreamBuf
second_title: Aspose.Slides for C++ API संदर्भ
description: "एक बफ़र का प्रतिनिधित्व करता है जो System::IO::Stream-जैसे स्ट्रीम को लपेटता है और उन्हें std::iostream-जैसे स्ट्रीम के आंतरिक बफ़र के रूप में उपयोग करने की अनुमति देता है।"
type: docs
weight: 40
url: /hi/system.io/basicsystemiostreambuf/
---
## BasicSystemIOStreamBuf क्लास

एक बफ़र का प्रतिनिधित्व करता है जो [System::IO::Stream](../stream/)-like streams को लपेटता है और उन्हें std::iostream-like streams के आंतरिक बफ़र के रूप में उपयोग करने की अनुमति देता है।

```cpp
template<typename Elem,typename Traits>class BasicSystemIOStreamBuf : public std::basic_streambuf<Elem, std::char_traits<Elem>>
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| void [AssignRV](./assignrv/)([BasicSystemIOStreamBuf](./)\&&) | मूव कन्स्ट्रक्टर और मूव असाइनमेंट ऑपरेटर में प्वाइंटर्स रीसेट करने और [swap()](./swap/) को कॉल करने के लिए उपयोग किया जाता है। |
| explicit  [BasicSystemIOStreamBuf](./basicsystemiostreambuf/)() | [BasicSystemIOStreamBuf](./) का नया उदाहरण बनाता है। |
| explicit  [BasicSystemIOStreamBuf](./basicsystemiostreambuf/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, [SystemIOStreamWrappingMode](../systemiostreamwrappingmode/), const std::locale\&) | [BasicSystemIOStreamBuf](./) का नया उदाहरण बनाता है। |
|  [BasicSystemIOStreamBuf](./basicsystemiostreambuf/)(const [BasicSystemIOStreamBuf](./)\&) | कॉपी कन्स्ट्रक्टर। हटाया गया। |
|  [BasicSystemIOStreamBuf](./basicsystemiostreambuf/)([BasicSystemIOStreamBuf](./)\&&) | मूव कन्स्ट्रक्टर। |
| [BasicSystemIOStreamBuf](./)\& [operator=](./operator_equal/)(const [BasicSystemIOStreamBuf](./)\&) | कॉपी असाइनमेंट ऑपरेटर। हटाया गया। |
| [BasicSystemIOStreamBuf](./)\& [operator=](./operator_equal/)([BasicSystemIOStreamBuf](./)\&&) | मूव असाइनमेंट ऑपरेटर। |
| void [swap](./swap/)([BasicSystemIOStreamBuf](./)\&) | *this और right को स्वैप करने के लिए कॉल, यदि वे समान नहीं हैं। |
|  [~BasicSystemIOStreamBuf](./~basicsystemiostreambuf/)() override | डेस्ट्रक्टर। |

## टाइपडिफ़्स

| टाइपडेफ़ | विवरण |
| --- | --- |
| [char_type](./char_type/) |  |
| [traits_type](./traits_type/) |  |
| [Mysb](./mysb/) |  |
| [int_type](./int_type/) |  |
| [pos_type](./pos_type/) |  |
| [off_type](./off_type/) |  |

## देखें

* नेमस्पेस [System::IO](../)
* लाइब्रेरी [Aspose.Slides](../../)