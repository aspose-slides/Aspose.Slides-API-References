---
title: get_Password()
second_title: مرجع واجهة برمجة التطبيقات Aspose.Slides لـ C++
description: "يحصل على كلمة المرور. اقرأ System::String."
type: docs
weight: 105
url: /ar/aspose.slides/loadoptions/get_password/
---
## LoadOptions::get_Password() طريقة

يحصل على كلمة المرور. اقرأ [System::String](../../../system/string/).

```cpp
System::String Aspose::Slides::LoadOptions::get_Password() override
```

## ملاحظات

كلمة المرور.

يعرض الكود المثال التالي كيفية فتح PowerPoint محمي بكلمة مرور [Presentation](../../presentation/).
```cpp
System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>();
loadOptions->set_Password(u"YOUR_PASSWORD");
auto presentation = System::MakeObject<Presentation>(u"pres.pptx", loadOptions);
// work with decrypted presentation
```

## انظر أيضًا

* فئة [String](../../../system/string/)
* فئة [LoadOptions](../)
* مساحة الاسم [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)