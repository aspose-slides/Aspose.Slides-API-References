---
title: get_TileOffsetY()
second_title: مرجع API Aspose.Slides برای C++
description: افست عمودی بافت نسبت به مبدأ شکل بر حسب نقطه بر می‌گرداند. مقدار مثبت بافت را به سمت پایین می‌برد، در حالی که مقدار منفی آن را به سمت بالا حرکت می‌دهد. خواندن float.
type: docs
weight: 300
url: /fa/aspose.slides/ipicturefillformat/get_tileoffsety/
---
## IPictureFillFormat::get_TileOffsetY() متد

Returns the vertical offset of the texture from the shape's origin in points. A positive value moves the texture down, while a negative value moves it up. Read **float**.

```cpp
virtual float Aspose::Slides::IPictureFillFormat::get_TileOffsetY()=0
```

## توضیحات



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// دریافت قالب پر کردن تصویر شکل
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// تنظیم حالت پر کردن تصویر به Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// تنظیم افست عمودی بافت به -50 نقطه
pictureFillFormat->set_TileOffsetY(-50.0f);
```

## مراجع

* کلاس [IPictureFillFormat](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)