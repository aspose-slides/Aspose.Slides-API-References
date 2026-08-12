---
title: get_ReadOnlyRecommended()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: पढ़े-केवल अनुशंसा प्राप्त करता है। पढ़ें bool.
type: docs
weight: 79
url: /hi/aspose.slides/iprotectionmanager/get_readonlyrecommended/
---
## IProtectionManager::get_ReadOnlyRecommended() मेथड


पढ़े-केवल अनुशंसा प्राप्त करता है। पढ़ें **bool**.

```cpp
virtual bool Aspose::Slides::IProtectionManager::get_ReadOnlyRecommended()=0
```

## टिप्पणियाँ



```cpp
auto pres = System::MakeObject<Presentation>();
pres->get_ProtectionManager()->set_ReadOnlyRecommended(true);
pres->Save(u"ReadOnlyPresentation.pptx", SaveFormat::Pptx);
```

## संबंधित देखें

* क्लास [IProtectionManager](../)
* नामस्थान [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)