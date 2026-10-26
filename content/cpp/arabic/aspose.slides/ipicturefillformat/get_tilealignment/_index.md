---
title: get_TileAlignment()
second_title: Aspose.Slides للغة C++ مرجع API
description: تُعيد كيفية محاذاة النسيج داخل الشكل. تتحكم هذه الإعدادات بنقطة بدء نمط النسيج وكيفية تكراره عبر الشكل. اقرأ RectangleAlignment.
type: docs
weight: 378
url: /ar/aspose.slides/ipicturefillformat/get_tilealignment/
---
## IPictureFillFormat::get_TileAlignment() طريقة


إرجاع كيف يتم محاذاة النسيج داخل الشكل. تتحكم هذه الإعدادات بنقطة بدء نمط النسيج وكيفية تكراره عبر الشكل. اقرأ [RectangleAlignment](../../rectanglealignment/).

```cpp
virtual RectangleAlignment Aspose::Slides::IPictureFillFormat::get_TileAlignment()=0
```

## ملاحظات


الافتراضي هو [RectangleAlignment::TopLeft](../../rectanglealignment/). 


```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// يحصل على تنسيق تعبئة الصورة للشكل
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// يضبط وضع تعبئة الصورة إلى Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// يضبط محاذاة التبليط إلى الزاوية السفلية اليمنى
pictureFillFormat->set_TileAlignment(RectangleAlignment::BottomRight);
```

## انظر أيضا

* تعداد [RectangleAlignment](../../rectanglealignment/)
* فئة [IPictureFillFormat](../)
* مساحة الاسم [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)