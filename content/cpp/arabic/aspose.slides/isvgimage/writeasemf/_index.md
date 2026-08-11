---
title: WriteAsEmf()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يحفظ صورة SVG كملف EMF.
type: docs
weight: 53
url: /ar/aspose.slides/isvgimage/writeasemf/
---
## ISvgImage::WriteAsEmf(System::SharedPtr\<System::IO::Stream\>) method

يحفظ صورة SVG كملف EMF.

```cpp
virtual void Aspose::Slides::ISvgImage::WriteAsEmf(System::SharedPtr<System::IO::Stream> stream)=0
```

### الوسائط

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | دفق الهدف |

## ملاحظات

يوضح المثال التالي كيفية حفظ صورة SVG في ملف ميتا. 
```cpp
// ينشئ صورة SVG الجديدة
System::SharedPtr<ISvgImage> svgImage = System::MakeObject<SvgImage>(System::IO::File::ReadAllText(u"content.svg"));

// يحفظ صورة SVG كملف ميتا
auto fileStream = System::IO::File::OpenWrite(u"SvgAsEmf.emf");
svgImage->WriteAsEmf(fileStream);
```
 يعرض هذا المثال كيفية إضافة صورة SVG كملف ميتا إلى مجموعة صور العرض التقديمي. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// ينشئ صورة SVG الجديدة
System::SharedPtr<ISvgImage> svgImage = System::MakeObject<SvgImage>(System::IO::File::ReadAllText(u"content.svg"));
auto memStream = System::MakeObject<System::IO::MemoryStream>();

// يحفظ صورة SVG كملف ميتا
svgImage->WriteAsEmf(memStream);
// يضيف ملف الميتا إلى مجموعة الصور
pres->get_Images()->AddImage(memStream->ToArray());
```

## أنظر أيضاً

* تعريف النوع [SharedPtr](../../../system/sharedptr/)
* فئة [Stream](../../../system.io/stream/)
* فئة [ISvgImage](../)
* مساحة الاسم [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)