---
title: set_ReadOnlyRecommended()
second_title: Aspose.Slides لـ C++ مرجع API
description: يضبط توصية القراءة-فقط. اكتب bool.
type: docs
weight: 92
url: /ar/aspose.slides/iprotectionmanager/set_readonlyrecommended/
---
## IProtectionManager::set_ReadOnlyRecommended(bool) طريقة


يضبط توصية القراءة-فقط. اكتب **bool**.

```cpp
virtual void Aspose::Slides::IProtectionManager::set_ReadOnlyRecommended(bool value)=0
```

## ملاحظات



```cpp
auto pres = System::MakeObject<Presentation>();
pres->get_ProtectionManager()->set_ReadOnlyRecommended(true);
pres->Save(u"ReadOnlyPresentation.pptx", SaveFormat::Pptx);
```

## انظر أيضًا

* فئة [IProtectionManager](../)
* نطاق [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)