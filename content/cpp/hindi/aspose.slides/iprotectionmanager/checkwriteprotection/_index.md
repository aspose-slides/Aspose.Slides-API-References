---
title: CheckWriteProtection()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: निर्धारित करता है कि क्या प्रस्तुति संशोधित करने के लिए पासवर्ड-सुरक्षित है।
type: docs
weight: 157
url: /hi/aspose.slides/iprotectionmanager/checkwriteprotection/
---
## IProtectionManager::CheckWriteProtection(System::String) विधि


निर्धारित करता है कि प्रस्तुतिकरण संशोधित करने के लिए पासवर्ड द्वारा संरक्षित है या नहीं।

```cpp
virtual bool Aspose::Slides::IProtectionManager::CheckWriteProtection(System::String password)=0
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| password | [System::String](../../../system/string/) | जाँच के लिए पासवर्ड। |

### वापसी मान

यदि पासवर्ड मान्य है तो True; अन्यथा false।

## टिप्पणी



```cpp
auto presentation = System::MakeObject<Presentation>(presentationFilePath);
bool isWriteProtected = presentation->get_ProtectionManager()->CheckWriteProtection(u"my_password");
```



1. आपको इस विधि को कॉल करने से पहले [IProtectionManager::get_IsWriteProtected](../get_iswriteprotected/) प्रॉपर्टी जांचनी चाहिए।
1. जब पासवर्ड null या empty हो, यह विधि false लौटाती है।


## देखें

* क्लास [String](../../../system/string/)
* क्लास [IProtectionManager](../)
* नामस्थान [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)