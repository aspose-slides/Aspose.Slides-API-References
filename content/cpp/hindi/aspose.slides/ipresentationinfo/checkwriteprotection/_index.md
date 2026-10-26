---
title: CheckWriteProtection()
second_title: Aspose.Slides for C++ API संदर्भ
description: जाँचता है कि क्या लिखे संरक्षित प्रस्तुति को संशोधित करने के लिए पासवर्ड सही है।
type: docs
weight: 66
url: /hi/aspose.slides/ipresentationinfo/checkwriteprotection/
---
## IPresentationInfo::CheckWriteProtection(System::String) मेथड

जाँचता है कि क्या लिखे संरक्षित प्रस्तुति को संशोधित करने के लिए पासवर्ड सही है।

```cpp
virtual bool Aspose::Slides::IPresentationInfo::CheckWriteProtection(System::String password)=0
```

### तर्क

| Parameter | Type | Description |
| --- | --- | --- |
| password | [System::String](../../../system/string/) | जाँचने के लिए पासवर्ड। |

### वापसी मान

सही यदि प्रस्तुति लिखे संरक्षित है और पासवर्ड सही है। अन्यथा गलत।

## टिप्पणियाँ

```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(presentationFilePath);
if (info->get_IsWriteProtected() == NullableBool::True)
{
    bool isWriteProtectedByPassword = info->CheckWriteProtection(u"my_password");
}
```

1. आपको इस मेथड को कॉल करने से पहले [IPresentationInfo::get_IsWriteProtected](../get_iswriteprotected/) प्रॉपर्टी की जाँच करनी चाहिए।
1. जब पासवर्ड null या empty हो, तो यह मेथड गलत लौटाता है।

## देखें

* क्लास [String](../../../system/string/)
* क्लास [IPresentationInfo](../)
* नामस्थान [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)