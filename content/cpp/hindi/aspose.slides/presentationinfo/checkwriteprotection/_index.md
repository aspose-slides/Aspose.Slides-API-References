---
title: CheckWriteProtection()
second_title: Aspose.Slides for C++ API संदर्भ
description: जांच करता है कि लिखने से संरक्षित प्रस्तुति के लिए संशोधन पासवर्ड सही है या नहीं।
type: docs
weight: 66
url: /hi/aspose.slides/presentationinfo/checkwriteprotection/
---
## PresentationInfo::CheckWriteProtection(System::String) मेथड

प्रेज़ेंटेशन को लिखने से सुरक्षित रखने के लिए संशोधन पासवर्ड सही है या नहीं, इसकी जांच करता है।

```cpp
bool Aspose::Slides::PresentationInfo::CheckWriteProtection(System::String password) override
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| password | [System::String](../../../system/string/) | जांच करने के लिए पासवर्ड। |

### रिटर्न वैल्यू

यदि प्रस्तुति लिखने से संरक्षित है और पासवर्ड सही है तो True। अन्यथा False।

## टिप्पणियाँ

```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(presentationFilePath);
if (info->get_IsWriteProtected() == NullableBool::True)
{
    bool isWriteProtectedByPassword = info->CheckWriteProtection(u"my_password");
}
```

1. इस मेथड को कॉल करने से पहले आपको [PresentationInfo::get_IsWriteProtected](../get_iswriteprotected/) प्रॉपर्टी की जाँच करनी चाहिए।
1. जब पासवर्ड null या खाली हो, तो यह मेथड false लौटाता है।

## संबंधित देखें

* क्लास [String](../../../system/string/)
* क्लास [PresentationInfo](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)