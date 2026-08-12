---
title: set_ReadOnlyRecommended()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: पढ़ने-के-लिए-केवल अनुशंसा सेट करता है। bool लिखें।
type: docs
weight: 92
url: /hi/aspose.slides/protectionmanager/set_readonlyrecommended/
---
## ProtectionManager::set_ReadOnlyRecommended(bool) मेथड

पढ़ने-के-लिए-केवल अनुशंसा सेट करता है। लिखें **bool**।

```cpp
void Aspose::Slides::ProtectionManager::set_ReadOnlyRecommended(bool value) override
```

## टिप्पणियाँ

निम्नलिखित नमूना कोड दर्शाता है कि आप PowerPoint [Presentation](../../presentation/) को C# में [Aspose.Slides](../../) का उपयोग करके केवल-पढ़ने-योग्य कैसे सेट कर सकते हैं।

```cpp
auto pres = System::MakeObject<Presentation>();
pres->get_ProtectionManager()->set_ReadOnlyRecommended(true);
pres->Save(u"ReadOnlyPresentation.pptx", SaveFormat::Pptx);
```

## देखें

* क्लास [ProtectionManager](../)
* नामस्थान [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)