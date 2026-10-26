---
title: get_DefaultRegularFont()
second_title: مرجع واجهة برمجة تطبيقات Aspose.Slides للغة C++
description: "يعيد الخط العادي المستخدم في حال عدم العثور على الخط الأصلي. اقرأ System::String."
type: docs
weight: 27
url: /ar/aspose.slides/loadoptions/get_defaultregularfont/
---
## LoadOptions::get_DefaultRegularFont() طريقة


يعيد الخط العادي المستخدم في حال عدم العثور على الخط الأصلي. اقرأ [System::String](../../../system/string/).

```cpp
System::String Aspose::Slides::LoadOptions::get_DefaultRegularFont() override
```

## ملاحظات


يوضح المثال التالي كيفية تعيين الخطوط الافتراضية لتصيير PowerPoint [Presentation](../../presentation/). 
```cpp
// استخدم خيارات التحميل لتحديد الخطوط العادية والآسيوية الافتراضية
System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>(LoadFormat::Auto);
loadOptions->set_DefaultRegularFont(u"Wingdings");
loadOptions->set_DefaultAsianFont(u"Wingdings");

// تحميل العرض التقديمي
auto pptx = System::MakeObject<Presentation>(u"DefaultFonts.pptx", loadOptions);
// إنشاء صورة مصغرة لل شريحة
auto slide = pptx->get_Slides()->idx_get(0);
slide->GetThumbnail(1.0f, 1.0f)->Save(u"output_out.png", System::Drawing::Imaging::ImageFormat::get_Png());

// إنشاء PDF
pptx->Save(u"output_out.pdf", SaveFormat::Pdf);
// إنشاء XPS
pptx->Save(u"output_out.xps", SaveFormat::Xps);
```

## انظر أيضًا

* فئة [String](../../../system/string/)
* فئة [LoadOptions](../)
* مساحة اسم [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)