---
title: get_DocumentLevelFontSources()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يحدد مصادر الخطوط الخارجية التي سيتم استخدامها في العرض التقديمي. تكون هذه الخطوط متاحة للعرض طوال مدة حياته ولا يتم مشاركتها مع عروض تقديمية أخرى
type: docs
weight: 209
url: /ar/aspose.slides/loadoptions/get_documentlevelfontsources/
---
## LoadOptions::get_DocumentLevelFontSources() طريقة

يحدد المصادر للخطوط الخارجية التي سيتم استخدامها في العرض التقديمي. تكون هذه الخطوط متاحة للعرض طوال مدة حياته ولا يتم مشاركتها مع عروض تقديمية أخرى

```cpp
System::SharedPtr<IFontSources> Aspose::Slides::LoadOptions::get_DocumentLevelFontSources() override
```

## ملاحظات

يوضح المثال التالي كيفية تحديد الخطوط المخصصة المستخدمة مع PowerPoint [Presentation](../../presentation/).

```cpp
System::ArrayPtr<uint8_t> memoryFont1 = System::IO::File::ReadAllBytes(u"customfonts\\CustomFont1.ttf");
System::ArrayPtr<uint8_t> memoryFont2 = System::IO::File::ReadAllBytes(u"customfonts\\CustomFont2.ttf");

System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>();
loadOptions->get_DocumentLevelFontSources()->set_FontFolders(System::MakeArray<System::String>({u"assets\\fonts", u"global\\fonts"}));
loadOptions->get_DocumentLevelFontSources()->set_MemoryFonts(System::MakeArray<System::ArrayPtr<uint8_t>>({memoryFont1, memoryFont2}));

auto presentation = System::MakeObject<Presentation>(u"MyPresentation.pptx", loadOptions);
// العمل مع العرض التقديمي
// CustomFont1, CustomFont2 وكذلك الخطوط من مجلد assets\fonts & global\fonts ومجلداتهما الفرعية متاحة للعرض التقديمي
```

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IFontSources](../../ifontsources/)
* فئة [LoadOptions](../)
* مساحة الاسم [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)