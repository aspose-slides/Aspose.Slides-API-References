---
title: get_TileAlignment()
second_title: مرجع API الخاص بـ Aspose.Slides للغة C++
description: يعيد كيفية محاذاة القوام داخل الشكل. تتحكم هذه الإعدادات في نقطة البداية لنمط القوام وكيفية تكراره عبر الشكل. اقرأ RectangleAlignment.
type: docs
weight: 378
url: /ar/aspose.slides/picturefillformat/get_tilealignment/
---
## PictureFillFormat::get_TileAlignment() طريقة

يعيد كيفية محاذاة القوام داخل الشكل. تتحكم هذه الإعدادات في نقطة البداية لنمط القوام وكيفية تكراره عبر الشكل. اقرأ [RectangleAlignment](../../rectanglealignment/).

```cpp
RectangleAlignment Aspose::Slides::PictureFillFormat::get_TileAlignment() override
```

## ملاحظات

الافتراضي هو [RectangleAlignment::TopLeft](../../rectanglealignment/). 

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// يحصل على تنسيق ملء الصورة للشكل
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// يحدد وضع ملء الصورة إلى Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// يحدد محاذاة التكرار إلى الزاوية السفلية اليمنى
pictureFillFormat->set_TileAlignment(RectangleAlignment::BottomRight);
```

## راجع أيضًا

* تعداد [RectangleAlignment](../../rectanglealignment/)
* فئة [PictureFillFormat](../)
* نطاق [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)