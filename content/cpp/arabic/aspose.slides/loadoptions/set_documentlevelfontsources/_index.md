---
title: set_DocumentLevelFontSources()
second_title: مرجع API Aspose.Slides للغة C++
description: يحدد المصادر للخطوط الخارجية التي سيتم استخدامها في العرض التقديمي. هذه الخطوط متاحة للعرض التقديمي طوال مدة حياته ولا يتم مشاركتها مع عروض تقديمية أخرى
type: docs
weight: 222
url: /ar/aspose.slides/loadoptions/set_documentlevelfontsources/
---
## LoadOptions::set_DocumentLevelFontSources(System::SharedPtr\<IFontSources\>) الطريقة

يحدد المصادر للخطوط الخارجية التي ستُستخدم في العرض التقديمي. هذه الخطوط متاحة للعرض التقديمي طوال مدة تشغيله ولا يتم مشاركتها مع عروض تقديمية أخرى

```cpp
void Aspose::Slides::LoadOptions::set_DocumentLevelFontSources(System::SharedPtr<IFontSources> value) override
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
// CustomFont1, CustomFont2 وكذلك الخطوط من مجلدي assets\fonts & global\fonts ومجلداتهما الفرعية متاحة للعرض التقديمي
```

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IFontSources](../../ifontsources/)
* فئة [LoadOptions](../)
* نطاق [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)