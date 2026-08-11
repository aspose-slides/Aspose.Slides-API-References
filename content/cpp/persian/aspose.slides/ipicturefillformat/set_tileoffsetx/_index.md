---
title: set_TileOffsetX()
second_title: مرجع API Aspose.Slides برای C++
description: آفست افقی بافت را نسبت به مبدأ شکل بر حسب نقطه تنظیم می‌کند. مقدار مثبت بافت را به سمت راست منتقل می‌کند، در حالی که مقدار منفی آن را به سمت چپ می‌برد. بنویسید float.
type: docs
weight: 287
url: /fa/aspose.slides/ipicturefillformat/set_tileoffsetx/
---
## IPictureFillFormat::set_TileOffsetX(float) متد


آفست افقی بافت را نسبت به مبدأ شکل بر حسب نقطه تنظیم می‌کند. مقدار مثبت بافت را به سمت راست منتقل می‌کند، در حالی که مقدار منفی آن را به سمت چپ می‌برد. بنویسید **float**.

```cpp
virtual void Aspose::Slides::IPictureFillFormat::set_TileOffsetX(float value)=0
```

## توضیحات



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// دریافت فرمت پر کردن تصویر شکل
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// تنظیم حالت پر کردن تصویر به تایل
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// تنظیم آفست افقی بافت به 20 نقطه
pictureFillFormat->set_TileOffsetX(20.0f);
```

## مراجع

* کلاس [IPictureFillFormat](../)
* فضای نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)