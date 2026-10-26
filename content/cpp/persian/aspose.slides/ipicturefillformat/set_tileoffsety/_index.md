---
title: set_TileOffsetY()
second_title: مرجع API Aspose.Slides برای C++
description: انحراف عمودی بافت نسبت به مبدأ شکل را بر حسب نقطه تنظیم می‌کند. مقدار مثبت بافت را به سمت پایین می‌برد، در حالی که مقدار منفی آن را به سمت بالا می‌برد. بنویسید float.
type: docs
weight: 313
url: /fa/aspose.slides/ipicturefillformat/set_tileoffsety/
---
## IPictureFillFormat::set_TileOffsetY(float) متد

انحراف عمودی بافت نسبت به مبدأ شکل را بر حسب نقطه تنظیم می‌کند. مقدار مثبت بافت را به سمت پایین می‌برد، در حالی که مقدار منفی آن را به سمت بالا می‌برد. بنویسید **float**.

```cpp
virtual void Aspose::Slides::IPictureFillFormat::set_TileOffsetY(float value)=0
```

## توضیحات



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// قالب پر کردن تصویر شکل را دریافت می‌کند
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// حالت پر کردن تصویر را به Tile تنظیم می‌کند
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// انحراف عمودی بافت را به -50 نقطه تنظیم می‌کند
pictureFillFormat->set_TileOffsetY(-50.0f);
```

## مراجع

* کلاس [IPictureFillFormat](../)
* فضای نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)