---
title: get_ReadOnlyRecommended()
second_title: Aspose.Slides للغة C++ مرجع API
description: يحصل على توصية للقراءة-فقط. قراءة bool.
type: docs
weight: 79
url: /ar/aspose.slides/iprotectionmanager/get_readonlyrecommended/
---
## IProtectionManager::get_ReadOnlyRecommended() طريقة


يحصل على توصية للقراءة-فقط. قراءة **bool**.

```cpp
virtual bool Aspose::Slides::IProtectionManager::get_ReadOnlyRecommended()=0
```

## ملاحظات



```cpp
auto pres = System::MakeObject<Presentation>();
pres->get_ProtectionManager()->set_ReadOnlyRecommended(true);
pres->Save(u"ReadOnlyPresentation.pptx", SaveFormat::Pptx);
```

## انظر أيضاً

* الفئة [IProtectionManager](../)
* مساحة الاسم [Aspose::Slides](../../)
* المكتبة [Aspose.Slides](../../../)