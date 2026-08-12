---
title: ExceptionWrapper
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: टेम्प्लेट जो उन अपवादों का रैपर दर्शाता है जो Exception क्लास से व्युत्पन्न होते हैं।
type: docs
weight: 833
url: /hi/system/exceptionwrapper/
---
## ExceptionWrapper क्लास

Template जो उन Exception क्लास से व्युत्पन्न अपवादों के रैपर का प्रतिनिधित्व करता है।

```cpp
template<typename T>class ExceptionWrapper
```

## विधियाँ

| मेथड | विवरण |
| --- | --- |
|  [ExceptionWrapper](./exceptionwrapper/)(std::nullptr_t) | एक null-instance बनाता है [ExceptionWrapper](./) क्लास का जो किसी भी अपवाद का प्रतिनिधित्व नहीं करता। |
|  [ExceptionWrapper](./exceptionwrapper/)(const [ExceptionPtr](../exceptionptr/)\&) | एक instance बनाता है [ExceptionWrapper](./) क्लास का जो पास किए गए पॉइंटर को रखता है। |
|  [ExceptionWrapper](./exceptionwrapper/)(const [ExceptionWrapper](./)\&) | कॉपी कंस्ट्रक्टर। |
|  [ExceptionWrapper](./exceptionwrapper/)([ExceptionWrapper](./)\&&) | मूव कंस्ट्रक्टर। |
| explicit  [ExceptionWrapper](./exceptionwrapper/)(Args\&&...) | कंस्ट्रक्टर जो पैरामीटर को Exception क्लास कंस्ट्रक्टर्स तक फ़ॉरवर्ड करता है और एक स्मार्ट पॉइंटर बनाता है जो नए Exception क्लास instance को रखता है। |
| static void * [operator new](./operator_new/)(std::size_t) |  |
| static void * [operator new[]](./operator_new[]/)(std::size_t) |  |
|  [operator SharedPtr< Object >](./operator_sharedptr_less_object__greater/)() | SharedPtr<Object> के लिए इम्प्लिसिट कास्ट ऑपरेटर |
| T * [operator->](./operator_minus_greater/)() const | Exception ऑब्जेक्ट के सदस्यों तक पहुंच की अनुमति देता है। |
| [ExceptionWrapper](./)\& [operator=](./operator_equal/)(const [ExceptionWrapper](./)\&) | असाइनमेंट ऑपरेटर। |
| [ExceptionWrapper](./)\& [operator=](./operator_equal/)([ExceptionWrapper](./)\&&) | मूव असाइनमेंट ऑपरेटर। |
| static const [System::TypeInfo](../typeinfo/)\& [Type](./type/)() | Exception टाइप के लिए [System::TypeInfo](../typeinfo/) ऑब्जेक्ट प्राप्त करने की शॉर्टकट। |

## टाइपडिफ़

| टाइपडिफ़ | विवरण |
| --- | --- |
| [ExceptionType](./exceptiontype/) | कास्टिंग फ़ंक्शन्स के लिए उपयोग किया जाता है। |

## देखें

* नेमस्पेस [System](../)
* लाइब्रेरी [Aspose.Slides](../../)