---
title: set_DefaultRegularFont()
second_title: Aspose.Slides لـ C++ مرجع API
description: "يحدد الخط العادي المستخدم في حالة عدم العثور على الخط المصدر. اكتب System::String."
type: docs
weight: 40
url: /ar/aspose.slides/loadoptions/set_defaultregularfont/
---
## LoadOptions::set_DefaultRegularFont(System::String) طريقة

يحدد الخط العادي المستخدم في حالة عدم العثور على الخط المصدر. اكتب [System::String](../../../system/string/).

```cpp
void Aspose::Slides::LoadOptions::set_DefaultRegularFont(System::String value) override
```

## ملاحظات

يوضح المثال التالي كيفية تعيين الخطوط الافتراضية لتصميم PowerPoint [Presentation](../../presentation/).
```cpp
// استخدم خيارات التحميل لتحديد الخطوط العادية والآسيوية الافتراضية
System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>(LoadFormat::Auto);
loadOptions->set_DefaultRegularFont(u"Wingdings");
loadOptions->set_DefaultAsianFont(u"Wingdings");

// حمّل العرض التقديمي
auto pptx = System::MakeObject<Presentation>(u"DefaultFonts.pptx", loadOptions);
// إنشاء مصغّر الشريحة
auto slide = pptx->get_Slides()->idx_get(0);
slide->GetThumbnail(1.0f, 1.0f)->Save(u"output_out.png", System::Drawing::Imaging::ImageFormat::get_Png());

// إنشاء PDF
pptx->Save(u"output_out.pdf", SaveFormat::Pdf);
// إنشاء XPS
pptx->Save(u"output_out.xps", SaveFormat::Xps);
```

## انظر أيضًا

* الفئة [String](../../../system/string/)
* الفئة [LoadOptions](../)
* النطاق [Aspose::Slides](../../)
* المكتبة [Aspose.Slides](../../../)