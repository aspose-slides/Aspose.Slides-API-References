---
title: Compress
second_title: Aspose.Slides للـ C++ مرجع API
description: يمثل مجموعة من الطرق المصممة لضغط العرض التقديمي.
type: docs
weight: 14
url: /ar/aspose.slides.lowcode/compress/
---
## فئة Compress

يمثل مجموعة من الطرق المصممة لضغط [Presentation](../../aspose.slides/presentation/).

```cpp
class Compress
```

## الطرق

| طريقة | الوصف |
| --- | --- |
|  [Compress](./compress/)() |  |
| static void [CompressEmbeddedFonts](./compressembeddedfonts/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>) | يقوم بضغط [Presentation](../../aspose.slides/presentation/) عن طريق إزالة الأحرف غير المستخدمة من الخطوط المضمنة. |
| static void [RemoveUnusedLayoutSlides](./removeunusedlayoutslides/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>) | يقوم بضغط [Presentation](../../aspose.slides/presentation/) عن طريق إزالة الشرائح التخطيطية غير المستخدمة. |
| static void [RemoveUnusedMasterSlides](./removeunusedmasterslides/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>) | يقوم بضغط [Presentation](../../aspose.slides/presentation/) عن طريق إزالة الشرائح الرئيسة غير المستخدمة. |

## ملاحظات



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
LowCode::Compress::RemoveUnusedMasterSlides(pres);
pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```

## انظر أيضًا

* نطاق اسم [Aspose::Slides::LowCode](../)
* مكتبة [Aspose.Slides](../../)