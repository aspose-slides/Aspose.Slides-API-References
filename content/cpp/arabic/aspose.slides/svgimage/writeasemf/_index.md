---
title: WriteAsEmf()
second_title: مرجع API Aspose.Slides للغة C++
description: يحفظ صورة SVG كملف EMF.
type: docs
weight: 66
url: /ar/aspose.slides/svgimage/writeasemf/
---
## SvgImage::WriteAsEmf(System::SharedPtr\<System::IO::Stream\>) طريقة

يحفظ صورة SVG كملف EMF.

```cpp
void Aspose::Slides::SvgImage::WriteAsEmf(System::SharedPtr<System::IO::Stream> stream) override
```

### المعامل

| المعامل | النوع | الوصف |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | تيار الهدف |
## ملاحظات

يوضح المثال التالي كيفية حفظ صورة SVG في ملف تعريف. 
```cpp
// ينشئ صورة SVG جديدة
System::SharedPtr<ISvgImage> svgImage = System::MakeObject<SvgImage>(System::IO::File::ReadAllText(u"content.svg"));

// يحفظ صورة SVG كملف تعريف
auto fileStream = System::IO::File::OpenWrite(u"SvgAsEmf.emf");
svgImage->WriteAsEmf(fileStream);
```
 هذا المثال يوضح كيفية إضافة صورة SVG كملف تعريف إلى مجموعة صور العرض. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// ينشئ صورة SVG جديدة
System::SharedPtr<ISvgImage> svgImage = System::MakeObject<SvgImage>(System::IO::File::ReadAllText(u"content.svg"));
auto memStream = System::MakeObject<System::IO::MemoryStream>();

// يحفظ صورة SVG كملف تعريف
svgImage->WriteAsEmf(memStream);
// يضيف ملف التعريف إلى مجموعة الصور
pres->get_Images()->AddImage(memStream->ToArray());
```

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* صنف [Stream](../../../system.io/stream/)
* صنف [SvgImage](../)
* مساحة الأسماء [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)