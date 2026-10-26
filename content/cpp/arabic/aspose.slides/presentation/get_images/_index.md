---
title: get_Images()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يعيد مجموعة جميع الصور في العرض التقديمي. IImageCollection للقراءة فقط.
type: docs
weight: 209
url: /ar/aspose.slides/presentation/get_images/
---
## Presentation::get_Images() طريقة

يعيد مجموعة جميع الصور في العرض التقديمي. للقراءة فقط [IImageCollection](../../iimagecollection/).

```cpp
System::SharedPtr<IImageCollection> Aspose::Slides::Presentation::get_Images() override
```

## ملاحظات

تظهر الأمثلة التالية كيفية إضافة صورة كـ BLOB في PowerPoint [Presentation](../).
```cpp
System::String pathToLargeImage = u"large_image.jpg";
// ينشئ عرض تقديمي جديد ستتم إضافة الصورة إليه.
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);

auto fileStream = System::MakeObject<System::IO::FileStream>(pathToLargeImage, System::IO::FileMode::Open);

// لنضيف الصورة إلى العرض التقديمي - نختار سلوك KeepLocked لأننا
// لا ننويا الوصول إلى ملف "largeImage.png".
auto img = pres->get_Images()->AddImage(fileStream, LoadingStreamBehavior::KeepLocked);
slide->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 0.0f, 0.0f, 300.0f, 200.0f, img);
// يحفظ العرض التقديمي. بينما يتم إخراج عرض تقديمي كبير، يظل استهلاك الذاكرة
// منخفضًا طوال دورة حياة كائن pres
pres->Save(u"presentationWithLargeImage.pptx", SaveFormat::Pptx);
```
تضيف الأمثلة التالية ارتباطًا تشعبيًا إلى صورة في PowerPoint [Presentation](../).
```cpp
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);

// يضيف الصورة إلى العرض التقديمي
auto image = pres->get_Images()->AddImage(System::IO::File::ReadAllBytes(u"image.png"));
// ينشئ إطار صورة على الشريحة 1 بناءً على الصورة التي تمت إضافتها مسبقًا
auto pictureFrame = slide->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 10.0f, 10.0f, 100.0f, 100.0f, image);
pictureFrame->set_HyperlinkClick(System::MakeObject<Hyperlink>(u"https://www.aspose.com/"));
pictureFrame->get_HyperlinkClick()->set_Tooltip(u"More than 70% Fortune 100 companies trust Aspose APIs");
pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IImageCollection](../../iimagecollection/)
* فئة [Presentation](../)
* النطاق [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)