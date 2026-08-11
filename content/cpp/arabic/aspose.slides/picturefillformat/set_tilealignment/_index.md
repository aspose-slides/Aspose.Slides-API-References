---
title: set_TileAlignment()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: تحدد كيفية محاذاة النسيج داخل الشكل. تتحكم هذه الإعدادات في نقطة البداية لنمط النسيج وكيفية تكراره عبر الشكل. اكتب RectangleAlignment.
type: docs
weight: 391
url: /ar/aspose.slides/picturefillformat/set_tilealignment/
---
## PictureFillFormat::set_TileAlignment(RectangleAlignment) طريقة

تحدد كيفية محاذاة النسيج داخل الشكل. تتحكم هذه الإعدادات في نقطة البداية لنمط النسيج وكيفية تكراره عبر الشكل. اكتب [RectangleAlignment](../../rectanglealignment/).

```cpp
void Aspose::Slides::PictureFillFormat::set_TileAlignment(RectangleAlignment value) override
```

## ملاحظات

القيمة الافتراضية هي [RectangleAlignment::TopLeft](../../rectanglealignment/). 

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// يحصل على تنسيق تعبئة الصورة للشكل
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// يعيّن وضع تعبئة الصورة إلى Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// يضبط محاذاة التكرار إلى الزاوية اليمنى السفلية
pictureFillFormat->set_TileAlignment(RectangleAlignment::BottomRight);
```

## انظر أيضًا

* تعدد [RectangleAlignment](../../rectanglealignment/)
* فئة [PictureFillFormat](../)
* مساحة الاسم [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)