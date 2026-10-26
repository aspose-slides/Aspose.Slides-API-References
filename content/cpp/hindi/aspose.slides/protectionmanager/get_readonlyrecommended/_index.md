---
title: get_ReadOnlyRecommended()
second_title: Aspose.Slides for C++ API संदर्भ
description: पढ़-केवल अनुशंसा प्राप्त करता है। पढ़ें bool.
type: docs
weight: 79
url: /hi/aspose.slides/protectionmanager/get_readonlyrecommended/
---
## ProtectionManager::get_ReadOnlyRecommended() मेथड

पढ़-केवल अनुशंसा प्राप्त करता है। पढ़ें **bool**।

```cpp
bool Aspose::Slides::ProtectionManager::get_ReadOnlyRecommended() override
```

## टिप्पणी

निम्नलिखित नमूना कोड दिखाता है कि आप PowerPoint [Presentation](../../presentation/) को C# में [Aspose.Slides](../../) का उपयोग करके Read-Only कैसे सेट कर सकते हैं। 
```cpp
auto pres = System::MakeObject<Presentation>();
pres->get_ProtectionManager()->set_ReadOnlyRecommended(true);
pres->Save(u"ReadOnlyPresentation.pptx", SaveFormat::Pptx);
```

## देखें

* क्लास [ProtectionManager](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)