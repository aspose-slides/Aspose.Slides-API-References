---
title: RemoveWriteProtection()
second_title: Aspose.Slides لـ C++ مرجع API
description: يزيل حماية الكتابة لهذا العرض التقديمي.
type: docs
weight: 144
url: /ar/aspose.slides/protectionmanager/removewriteprotection/
---
## ProtectionManager::RemoveWriteProtection() طريقة

يزيل حماية الكتابة لهذا العرض التقديمي.

```cpp
void Aspose::Slides::ProtectionManager::RemoveWriteProtection() override
```

## ملاحظات

يظهر لك هذا المثال البرمجي كيفية إزالة حماية الكتابة من PowerPoint [Presentation](../../presentation/).
```cpp
auto presentation = System::MakeObject<Presentation>(u"pres.pptx");
presentation->get_ProtectionManager()->RemoveWriteProtection();
presentation->Save(u"write-protection-removed.pptx", SaveFormat::Pptx);
```

## انظر أيضاً

* فئة [ProtectionManager](../)
* مساحة الاسم [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)