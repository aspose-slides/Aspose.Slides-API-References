---
title: Encrypt()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: निर्दिष्ट पासवर्ड के साथ प्रस्तुति को एन्क्रिप्ट करता है।
type: docs
weight: 105
url: /hi/aspose.slides/protectionmanager/encrypt/
---
## ProtectionManager::Encrypt(System::String) मेथड

[Presentation](../../presentation/) को निर्दिष्ट पासवर्ड के साथ एन्क्रिप्ट करता है।

```cpp
void Aspose::Slides::ProtectionManager::Encrypt(System::String encryptionPassword) override
```

### आर्ग्युमेंट्स

| परिमाण | प्रकार | विवरण |
| --- | --- | --- |
| encryptionPassword | [System::String](../../../system/string/) | पासवर्ड। |
## टिप्पणियाँ



निम्नलिखित नमूना कोड दिखाता है कि आप PowerPoint [Presentation](../../presentation/) को कैसे एन्क्रिप्ट कर सकते हैं। 
```cpp
auto presentation = System::MakeObject<Presentation>(u"pres.pptx");
presentation->get_ProtectionManager()->Encrypt(u"123123");
presentation->Save(u"encrypted-pres.pptx", SaveFormat::Pptx);
```

## देखें

* क्लास [String](../../../system/string/)
* क्लास [ProtectionManager](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)