---
title: get_TileOffsetX()
second_title: مرجع API Aspose.Slides برای C++
description: افست افقی بافت نسبت به مبدأ شکل را بر حسب نقطه برمی‌گرداند. مقدار مثبت بافت را به سمت راست حرکت می‌دهد، در حالی که مقدار منفی آن را به سمت چپ حرکت می‌دهد. خواندن float.
type: docs
weight: 274
url: /fa/aspose.slides/ipicturefillformat/get_tileoffsetx/
---
## IPictureFillFormat::get_TileOffsetX() متد

افست افقی بافت نسبت به مبدا شکل را بر حسب نقطه برمی‌گرداند. مقدار مثبت بافت را به سمت راست حرکت می‌دهد، در حالی که مقدار منفی آن را به سمت چپ حرکت می‌دهد. خواندن **float**.

```cpp
virtual float Aspose::Slides::IPictureFillFormat::get_TileOffsetX()=0
```

## توضیحات



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// قالب پر کردن تصویر شکل را دریافت می‌کند
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// حالت پر کردن تصویر را به Tile تنظیم می‌کند
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// افست افقی بافت را به 20 نقطه تنظیم می‌کند
pictureFillFormat->set_TileOffsetX(20.0f);
```

## مراجعه

* کلاس [IPictureFillFormat](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)