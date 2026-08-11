---
title: get_ReadOnlyRecommended()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يحصل على توصية القراءة-الذاتية. قراءة bool.
type: docs
weight: 79
url: /ar/aspose.slides/protectionmanager/get_readonlyrecommended/
---
## ProtectionManager::get_ReadOnlyRecommended() طريقة


يحصل على توصية للقراءة-الذاتية. القراءة **bool**.

```cpp
bool Aspose::Slides::ProtectionManager::get_ReadOnlyRecommended() override
```

## ملاحظات


الكود النموذجي التالي يوضح لك كيفية ضبط PowerPoint [Presentation](../../presentation/) على وضع القراءة-الذاتية في C# باستخدام [Aspose.Slides](../../). 
```cpp
auto pres = System::MakeObject<Presentation>();
pres->get_ProtectionManager()->set_ReadOnlyRecommended(true);
pres->Save(u"ReadOnlyPresentation.pptx", SaveFormat::Pptx);
```

## انظر أيضاً

* فئة [ProtectionManager](../)
* نطاق [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)