---
title: WriteAsSvg()
second_title: Aspose.Slides لتوثيق API لـ C++
description: يحفظ محتوى الشريحة كملف SVG.
type: docs
weight: 157
url: /ar/aspose.slides/slide/writeassvg/
---
## Slide::WriteAsSvg(System::SharedPtr\<System::IO::Stream\>) طريقة

يحفظ محتوى الشريحة كملف SVG.

```cpp
void Aspose::Slides::Slide::WriteAsSvg(System::SharedPtr<System::IO::Stream> stream) override
```

### المعاملات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | التدفق الهدف |
## ملاحظات

يعرض المثال البرمجي التالي كيفية تحويل الشريحة الأولى من عرض تقديمي PowerPoint إلى ملف SVG.

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<System::IO::Stream> fileStream = System::IO::File::Create(u"slide_1.svg");

// يحفظ الشريحة الأولى كملف SVG
pres->get_Slide(0)->WriteAsSvg(fileStream);
```

## Slide::WriteAsSvg(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Export::ISVGOptions\>) طريقة

يحفظ محتوى الشريحة كملف SVG.

```cpp
void Aspose::Slides::Slide::WriteAsSvg(System::SharedPtr<System::IO::Stream> stream, System::SharedPtr<Export::ISVGOptions> svgOptions) override
```

### المعاملات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | التدفق الهدف |
| svgOptions | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ISVGOptions](../../../aspose.slides.export/isvgoptions/)\> | خيارات توليد SVG |
## ملاحظات

يعرض المثال البرمجي التالي كيفية تحويل الشريحة الأولى من عرض تقديمي PowerPoint إلى ملف SVG مع خيارات.

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<System::IO::Stream> fileStream = System::IO::File::Create(u"slide_1.svg");

auto options = System::MakeObject<SVGOptions>();
options->set_VectorizeText(true);

// يحفظ الشريحة الأولى كملف SVG
pres->get_Slide(0)->WriteAsSvg(fileStream, options);
```

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [Stream](../../../system.io/stream/)
* فئة [Slide](../)
* فئة [ISVGOptions](../../../aspose.slides.export/isvgoptions/)
* نطاق [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)