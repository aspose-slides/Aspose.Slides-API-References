---
title: get_TileOffsetY()
second_title: مرجع API Aspose.Slides برای C++
description: مختصات عمودی بافت نسبت به مبدأ شکل را بر حسب نقاط برمی‌گرداند. مقدار مثبت بافت را به سمت پایین حرکت می‌دهد، در حالی که مقدار منفی آن را به سمت بالا می‌برد. خواندن float.
type: docs
weight: 300
url: /fa/aspose.slides/picturefillformat/get_tileoffsety/
---
## PictureFillFormat::get_TileOffsetY() متد

مختصات عمودی بافت نسبت به مبدأ شکل را بر حسب نقاط برمی‌گرداند. مقدار مثبت بافت را به سمت پایین حرکت می‌دهد، در حالی که مقدار منفی آن را به سمت بالا می‌برد. خواندن **float**.

```cpp
float Aspose::Slides::PictureFillFormat::get_TileOffsetY() override
```

## توضیحات

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// قالب پر کردن تصویر شکل را دریافت می‌کند
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// حالت پر کردن تصویر را به Tile تنظیم می‌کند
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// افست عمودی بافت را به -50 نقطه تنظیم می‌کند
pictureFillFormat->set_TileOffsetY(-50.0f);
```

## موارد مرتبط

* کلاس [PictureFillFormat](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)