---
title: CheckWriteProtection()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: निर्धारित करता है कि क्या प्रस्तुति को संशोधित करने के लिए पासवर्ड से सुरक्षित है।
type: docs
weight: 157
url: /hi/aspose.slides/protectionmanager/checkwriteprotection/
---
## ProtectionManager::CheckWriteProtection(System::String) मेथड


प्रेजेंटेशन को संशोधित करने के लिए पासवर्ड से सुरक्षित है या नहीं, यह निर्धारित करता है।

```cpp
bool Aspose::Slides::ProtectionManager::CheckWriteProtection(System::String password) override
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| password | [System::String](../../../system/string/) | जाँच के लिए पासवर्ड। |

### रिटर्न वैल्यू

True यदि पासवर्ड वैध है; अन्यथा false।

## टिप्पणी



```cpp
auto presentation = System::MakeObject<Presentation>(presentationFilePath);
bool isWriteProtected = presentation->get_ProtectionManager()->CheckWriteProtection(u"my_password");
```



1. आपको इस मेथड को कॉल करने से पहले [ProtectionManager::get_IsWriteProtected](../get_iswriteprotected/) प्रॉपर्टी की जाँच करनी चाहिए।
1. जब पासवर्ड null या खाली हो, यह मेथड false लौटाता है।


## देखें

* Class [String](../../../system/string/)
* Class [ProtectionManager](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)