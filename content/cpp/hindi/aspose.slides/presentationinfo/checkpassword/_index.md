---
title: CheckPassword()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: जाँचता है कि क्या ओपन पासवर्ड से संरक्षित प्रस्तुति के लिए पासवर्ड सही है।
type: docs
weight: 53
url: /hi/aspose.slides/presentationinfo/checkpassword/
---
## PresentationInfo::CheckPassword(System::String) मेथड

जाँचता है कि क्या पासवर्ड वह प्रस्तुति के लिए सही है जो ओपन पासवर्ड से संरक्षित है।

```cpp
bool Aspose::Slides::PresentationInfo::CheckPassword(System::String password) override
```

### आर्ग्यूमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| password | [System::String](../../../system/string/) | जांचने के लिए पासवर्ड। |

### वापसी मान

यदि प्रस्तुति ओपन पासवर्ड से संरक्षित है और पासवर्ड सही है तो true, अन्यथा false।

## टिप्पणियाँ

```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(u"pres.pptx");
bool isPasswordCorrect = info->CheckPassword(u"my_password");
```

जब पासवर्ड null या empty हो, यह मेथड false लौटाता है। 

## देखें

* क्लास [String](../../../system/string/)
* क्लास [PresentationInfo](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)