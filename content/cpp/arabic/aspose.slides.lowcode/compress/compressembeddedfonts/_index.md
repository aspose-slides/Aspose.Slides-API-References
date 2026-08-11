---
title: CompressEmbeddedFonts()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يقوم بضغط العرض التقديمي عن طريق إزالة الأحرف غير المستخدمة من الخطوط المضمّنة.
type: docs
weight: 27
url: /ar/aspose.slides.lowcode/compress/compressembeddedfonts/
---
## Compress::CompressEmbeddedFonts(System::SharedPtr\<Presentation\>) طريقة

يقوم بضغط [Presentation](../../../aspose.slides/presentation/) عن طريق إزالة الأحرف غير المستخدمة من الخطوط المضمّنة.

```cpp
static void Aspose::Slides::LowCode::Compress::CompressEmbeddedFonts(System::SharedPtr<Presentation> pres)
```

### المعاملات

| معامل | نوع | وصف |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | مثيل العرض التقديمي |
## ملاحظات

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
LowCode::Compress::CompressEmbeddedFonts(pres);

pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [Presentation](../../../aspose.slides/presentation/)
* فئة [Compress](../)
* مساحة الاسم [Aspose::Slides::LowCode](../../)
* مكتبة [Aspose.Slides](../../../)