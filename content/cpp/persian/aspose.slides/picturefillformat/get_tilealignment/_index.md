---
title: get_TileAlignment()
second_title: Aspose.Slides برای مرجع API C++
description: تعیین می‌کند که بافت چگونه در داخل شکل تراز شود. این تنظیم نقطه شروع الگوی بافت و نحوه تکرار آن در سراسر شکل را کنترل می‌کند. مطالعه کنید RectangleAlignment.
type: docs
weight: 378
url: /fa/aspose.slides/picturefillformat/get_tilealignment/
---
## PictureFillFormat::get_TileAlignment() متد

تعیین می‌کند که بافت چگونه در داخل شکل تراز شود. این تنظیم نقطهٔ شروع الگوی بافت و نحوهٔ تکرار آن در سراسر شکل را کنترل می‌کند. مطالعه کنید [RectangleAlignment](../../rectanglealignment/).

```cpp
RectangleAlignment Aspose::Slides::PictureFillFormat::get_TileAlignment() override
```

## توضیحات

پیش‌فرض [RectangleAlignment::TopLeft](../../rectanglealignment/) است.

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// قالب پر کردن تصویر شکل را دریافت می‌کند
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// حالت پر کردن تصویر را به Tile تنظیم می‌کند
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// تنظیم ترازبندی کاشی‌ها به پایین راست
pictureFillFormat->set_TileAlignment(RectangleAlignment::BottomRight);
```

## موارد دیگر

* enum [RectangleAlignment](../../rectanglealignment/)
* کلاس [PictureFillFormat](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)