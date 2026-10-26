---
title: set_Password()
second_title: مرجع Aspose.Slides للـ C++ API
description: "يضبط كلمة المرور. اكتب System::String."
type: docs
weight: 118
url: /ar/aspose.slides/loadoptions/set_password/
---
## LoadOptions::set_Password(System::String) طريقة

يضبط كلمة المرور. اكتب [System::String](../../../system/string/).

```cpp
void Aspose::Slides::LoadOptions::set_Password(System::String value) override
```

## ملاحظات

كلمة المرور.

يوضح الشيفرة النموذجية التالية كيفية فتح ملف PowerPoint محمي بكلمة مرور [Presentation](../../presentation/).

```cpp
System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>();
loadOptions->set_Password(u"YOUR_PASSWORD");
auto presentation = System::MakeObject<Presentation>(u"pres.pptx", loadOptions);
// work with decrypted presentation
```

## انظر أيضاً

* فئة [String](../../../system/string/)
* فئة [LoadOptions](../)
* نطاق [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)