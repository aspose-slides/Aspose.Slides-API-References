---
title: get_IsWriteProtected()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: एक मान प्राप्त करता है जो यह दर्शाता है कि बंधी हुई प्रस्तुति लिखने से सुरक्षित है।
type: docs
weight: 27
url: /hi/aspose.slides/presentationinfo/get_iswriteprotected/
---
## PresentationInfo::get_IsWriteProtected() मेथड


एक मान प्राप्त करता है जो यह दर्शाता है कि बंधी हुई प्रस्तुति लिखने से सुरक्षित है।

```cpp
NullableBool Aspose::Slides::PresentationInfo::get_IsWriteProtected() override
```

## टिप्पणियाँ



```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(presentationFilePath);
if (info->get_IsWriteProtected() == NullableBool::True)
{
    System::Console::WriteLine(System::String(u"The presentation '") + presentationFilePath + u"' is write protected by a password.");
}
```


यदि प्रस्तुति को खोलने के लिए पासवर्ड द्वारा सुरक्षित किया गया है, तो प्रॉपर्टी मान NotDefined के बराबर होता है। 
## संबंधित देखें

* Enum [NullableBool](../../nullablebool/)
* क्लास [PresentationInfo](../)
* नामस्थान [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)