---
title: set_ReadOnlyRecommended()
second_title: Aspose.Slides for C++ API संदर्भ
description: पढ़ने-केवल अनुशंसा सेट करता है। लिखें bool.
type: docs
weight: 92
url: /hi/aspose.slides/iprotectionmanager/set_readonlyrecommended/
---
## IProtectionManager::set_ReadOnlyRecommended(bool) विधि


पढ़ने-केवल अनुशंसा सेट करता है। लिखें **bool**.

```cpp
virtual void Aspose::Slides::IProtectionManager::set_ReadOnlyRecommended(bool value)=0
```

## टिप्पणी



```cpp
auto pres = System::MakeObject<Presentation>();
pres->get_ProtectionManager()->set_ReadOnlyRecommended(true);
pres->Save(u"ReadOnlyPresentation.pptx", SaveFormat::Pptx);
```

## देखें

* क्लास [IProtectionManager](../)
* नामस्थान [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)