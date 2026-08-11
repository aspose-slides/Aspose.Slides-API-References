---
title: get_TileAlignment()
second_title: Aspose.Slides برای C++ مرجع API
description: مشخص می‌کند که بافت چگونه درون شکل تراز شده است. این تنظیم نقطه شروع الگوی بافت و نحوه تکرار آن در سراسر شکل را کنترل می‌کند. مطالعه کنید RectangleAlignment.
type: docs
weight: 378
url: /fa/aspose.slides/ipicturefillformat/get_tilealignment/
---
## IPictureFillFormat::get_TileAlignment() متد


باز می‌گرداند که بافت چگونه درون شکل تراز شده است. این تنظیم نقطه شروع الگوی بافت و نحوه تکرار آن در سراسر شکل را کنترل می‌کند. مطالعه کنید [RectangleAlignment](../../rectanglealignment/).

```cpp
virtual RectangleAlignment Aspose::Slides::IPictureFillFormat::get_TileAlignment()=0
```

## توضیحات


پیش‌فرض [RectangleAlignment::TopLeft](../../rectanglealignment/) است. 


```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// فرمت پر کردن تصویر شکل را دریافت می‌کند
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// حالت پر شدن تصویر را به Tile تنظیم می‌کند
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// ترازبندی کاشی‌ها را به پایین راست تنظیم می‌کند
pictureFillFormat->set_TileAlignment(RectangleAlignment::BottomRight);
```

## موارد مرتبط

* نوع شمارشی [RectangleAlignment](../../rectanglealignment/)
* کلاس [IPictureFillFormat](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)