---
title: CheckPassword()
second_title: Aspose.Slides for C++ API संदर्भ
description: जाँचता है कि ओपन पासवर्ड से सुरक्षित प्रस्तुति के लिए पासवर्ड सही है या नहीं।
type: docs
weight: 53
url: /hi/aspose.slides/ipresentationinfo/checkpassword/
---
## IPresentationInfo::CheckPassword(System::String) मेथड

जाँचता है कि ओपन पासवर्ड से सुरक्षित प्रस्तुति के लिए पासवर्ड सही है या नहीं।

```cpp
virtual bool Aspose::Slides::IPresentationInfo::CheckPassword(System::String password)=0
```

### आर्ग्युमेंट्स

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| password | [System::String](../../../system/string/) | जाँचने के लिए पासवर्ड। |

### रिटर्न वैल्यू

यदि प्रस्तुति ओपन पासवर्ड से सुरक्षित है और पासवर्ड सही है तो true लौटाता है, अन्यथा false।

## टिप्पणियाँ

```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(u"pres.pptx");
bool isPasswordCorrect = info->CheckPassword(u"my_password");
```

जब पासवर्ड null या खाली हो, यह मेथड false लौटाता है। 

## संबंधित देखें

* क्लास [String](../../../system/string/)
* क्लास [IPresentationInfo](../)
* नामस्थान [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)