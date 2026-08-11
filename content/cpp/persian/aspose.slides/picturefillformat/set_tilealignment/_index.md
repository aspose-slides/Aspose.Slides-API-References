---
title: set_TileAlignment()
second_title: Aspose.Slides برای مرجع API C++
description: نحوه تراز بافت درون شکل را تعیین می‌کند. این تنظیم نقطه شروع الگوی بافت و نحوه تکرار آن در سراسر شکل را کنترل می‌کند. RectangleAlignment را بنویسید.
type: docs
weight: 391
url: /fa/aspose.slides/picturefillformat/set_tilealignment/
---
## PictureFillFormat::set_TileAlignment(RectangleAlignment) متد

نحوه‌ی تنظیم تراز بافت درون شکل را تعیین می‌کند. این تنظیم نقطه شروع الگوی بافت و نحوهٔ تکرار آن در سراسر شکل را کنترل می‌کند. [RectangleAlignment](../../rectanglealignment/) را بنویسید.

```cpp
void Aspose::Slides::PictureFillFormat::set_TileAlignment(RectangleAlignment value) override
```

## توضیحات

پیش‌فرض [RectangleAlignment::TopLeft](../../rectanglealignment/) است.

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// دریافت فرمت پر کردن تصویر شکل
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// تنظیم حالت پر کردن تصویر به Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// تنظیم تراز کاشی‌ها به پایین راست
pictureFillFormat->set_TileAlignment(RectangleAlignment::BottomRight);
```

## موارد مرتبط

* Enum [RectangleAlignment](../../rectanglealignment/)
* کلاس [PictureFillFormat](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)