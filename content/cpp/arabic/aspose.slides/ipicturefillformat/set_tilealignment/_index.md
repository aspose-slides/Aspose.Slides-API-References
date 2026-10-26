---
title: set_TileAlignment()
second_title: Aspose.Slides لواجهة برمجة تطبيقات C++
description: يضبط كيفية محاذاة القوام داخل الشكل. يتحكم هذا الإعداد في نقطة بداية نمط القوام وكيفية تكراره عبر الشكل. اكتب RectangleAlignment.
type: docs
weight: 391
url: /ar/aspose.slides/ipicturefillformat/set_tilealignment/
---
## IPictureFillFormat::set_TileAlignment(RectangleAlignment) طريقة

يضبط كيفية محاذاة القوام داخل الشكل. يتحكم هذا الإعداد في نقطة البداية لنمط القوام وكيفية تكراره عبر الشكل. اكتب [RectangleAlignment](../../rectanglealignment/).

```cpp
virtual void Aspose::Slides::IPictureFillFormat::set_TileAlignment(RectangleAlignment value)=0
```

## ملاحظات

القيمة الافتراضية هي [RectangleAlignment::TopLeft](../../rectanglealignment/).

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// يحصل على تنسيق تعبئة الصورة للشكل
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// يضبط وضع تعبئة الصورة إلى Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// يضبط محاذاة التبليط إلى BottomRight
pictureFillFormat->set_TileAlignment(RectangleAlignment::BottomRight);
```

## انظر أيضًا

* تعداد [RectangleAlignment](../../rectanglealignment/)
* فئة [IPictureFillFormat](../)
* نطاق الاسم [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)