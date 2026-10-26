---
title: set_TileScaleY()
second_title: Aspose.Slides برای مرجع API C++
description: مقیاس عمودی پر کردن بافت را به‌صورت درصد تنظیم می‌کند. مقدار float را بنویسید.
type: docs
weight: 365
url: /fa/aspose.slides/ipicturefillformat/set_tilescaley/
---
## IPictureFillFormat::set_TileScaleY(float) متد

مقیاس عمودی پر کردن بافت را به‌صورت درصد تنظیم می‌کند. مقدار **float** را بنویسید.

```cpp
virtual void Aspose::Slides::IPictureFillFormat::set_TileScaleY(float value)=0
```

## توضیحات

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// فرمت پر کردن تصویر شکل را دریافت می‌کند
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// حالت پر کردن تصویر را به Tile تنظیم می‌کند
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// مقیاس عمودی بافت را به 120 درصد تنظیم می‌کند
pictureFillFormat->set_TileScaleY(120.0f);
```

## نگاه کنید به

* کلاس [IPictureFillFormat](../)
* فضای نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)