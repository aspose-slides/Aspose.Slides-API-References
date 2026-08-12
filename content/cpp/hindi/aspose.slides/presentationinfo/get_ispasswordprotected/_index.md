---
title: get_IsPasswordProtected()
second_title: Aspose.Slides C++ API संदर्भ के लिए
description: एक मान प्राप्त करता है जो यह दर्शाता है कि बाइंडेड प्रस्तुति खोलने के लिए पासवर्ड द्वारा सुरक्षित है या नहीं।
type: docs
weight: 14
url: /hi/aspose.slides/presentationinfo/get_ispasswordprotected/
---
## PresentationInfo::get_IsPasswordProtected() मेथड


एक मान प्राप्त करता है जो यह दर्शाता है कि बाइंडेड प्रस्तुति पासवर्ड द्वारा खोलने के लिए सुरक्षित है या नहीं।

```cpp
bool Aspose::Slides::PresentationInfo::get_IsPasswordProtected() override
```

## टिप्पणियाँ



```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(presentationFilePath);
if (info->get_IsPasswordProtected())
{
    System::Console::WriteLine(System::String(u"The presentation '") + presentationFilePath + u"' is protected by password to open.");
}
```

## संबंधित देखें

* क्लास [PresentationInfo](../)
* नामस्थान [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)