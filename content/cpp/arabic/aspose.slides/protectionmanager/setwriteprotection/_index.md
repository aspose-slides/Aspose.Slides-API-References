---
title: SetWriteProtection()
second_title: Aspose.Slides لمرجع API C++
description: تعيين حماية كتابة لهذا العرض التقديمي باستخدام كلمة مرور محددة.
type: docs
weight: 131
url: /ar/aspose.slides/protectionmanager/setwriteprotection/
---
## ProtectionManager::SetWriteProtection(System::String) طريقة

تعيين حماية كتابة لهذا العرض التقديمي باستخدام كلمة المرور المحددة.

```cpp
void Aspose::Slides::ProtectionManager::SetWriteProtection(System::String password) override
```

### المعلمات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| password | [System::String](../../../system/string/) | كلمة المرور |
## ملاحظات

يوضح لك الكود العيني التالي كيفية تعيين حماية كتابة لعرض تقديمي. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"pres.pptx");
presentation->get_ProtectionManager()->SetWriteProtection(u"123123");
presentation->Save(u"write-protected-pres.pptx", SaveFormat::Pptx);
```

## انظر أيضًا

* فئة [String](../../../system/string/)
* فئة [ProtectionManager](../)
* مساحة الاسم [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)