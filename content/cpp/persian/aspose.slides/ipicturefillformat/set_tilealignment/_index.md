---
title: set_TileAlignment()
second_title: Aspose.Slides برای مرجع API C++
description: تنظیم می‌کند بافت چگونه درون شکل هم‌ترازی شود. این تنظیم نقطه شروع الگوی بافت و نحوهٔ تکرار آن در سراسر شکل را کنترل می‌کند. RectangleAlignment را بنویسید.
type: docs
weight: 391
url: /fa/aspose.slides/ipicturefillformat/set_tilealignment/
---
## IPictureFillFormat::set_TileAlignment(RectangleAlignment) متد


تنظیم می‌کند که بافت چگونه درون شکل هم‌ترازی شود. این تنظیم نقطه شروع الگوی بافت و نحوهٔ تکرار آن در سراسر شکل را کنترل می‌کند. [RectangleAlignment](../../rectanglealignment/) را بنویسید.

```cpp
virtual void Aspose::Slides::IPictureFillFormat::set_TileAlignment(RectangleAlignment value)=0
```

## توضیحات


پیش‌فرض [RectangleAlignment::TopLeft](../../rectanglealignment/) است. 


```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// دریافت قالب پر کردن تصویر شکل
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// تنظیم حالت پر کردن تصویر به کاشی
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// تنظیم هم‌ترازی کاشی به پایین راست
pictureFillFormat->set_TileAlignment(RectangleAlignment::BottomRight);
```

## موارد مرتبط

* شمارشی [RectangleAlignment](../../rectanglealignment/)
* کلاس [IPictureFillFormat](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)