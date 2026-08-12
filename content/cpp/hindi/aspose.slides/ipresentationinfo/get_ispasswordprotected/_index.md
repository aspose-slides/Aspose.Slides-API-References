---
title: get_IsPasswordProtected()
second_title: Aspose.Slides for C++ API संदर्भ
description: एक मान प्राप्त करता है जो यह संकेत देता है कि बंधी हुई प्रस्तुति को खोलने के लिए पासवर्ड द्वारा संरक्षित किया गया है।
type: docs
weight: 14
url: /hi/aspose.slides/ipresentationinfo/get_ispasswordprotected/
---
## IPresentationInfo::get_IsPasswordProtected() विधि


एक मान प्राप्त करता है जो संकेत देता है कि बाइंडेड प्रस्तुति को खोलने के लिए पासवर्ड द्वारा संरक्षित किया गया है।

```cpp
virtual bool Aspose::Slides::IPresentationInfo::get_IsPasswordProtected()=0
```

## टिप्पणी



```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(presentationFilePath);
if (info->get_IsPasswordProtected())
{
    System::Console::WriteLine(System::String(u"The presentation '") + presentationFilePath + u"' is protected by a password to open.");
}
```

## देखें भी

* क्लास [IPresentationInfo](../)
* नामस्थान [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)