---
title: set_TileOffsetY()
second_title: Aspose.Slides برای مرجع API C++
description: جهت‌گیری عمودی بافت نسبت به مبدأ شکل بر حسب نقطه تنظیم می‌کند. مقدار مثبت بافت را به سمت پایین حرکت می‌دهد، در حالی که مقدار منفی آن را به سمت بالا می‌برد. بنویسید float.
type: docs
weight: 313
url: /fa/aspose.slides/picturefillformat/set_tileoffsety/
---
## PictureFillFormat::set_TileOffsetY(float) متد

جهت‌گیری عمودی بافت نسبت به مبدأ شکل را به واحد نقطه تنظیم می‌کند. مقدار مثبت بافت را به سمت پایین حرکت می‌دهد، در حالی که مقدار منفی آن را به سمت بالا می‌برد. بنویسید **float**.

```cpp
void Aspose::Slides::PictureFillFormat::set_TileOffsetY(float value) override
```

## توضیحات

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// فرمت پر کردن تصویر شکل را دریافت می‌کند
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// حالت پر کردن تصویر را به Tile تنظیم می‌کند
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// افست عمودی بافت را به -50 نقطه تنظیم می‌کند
pictureFillFormat->set_TileOffsetY(-50.0f);
```

## مطالب مرتبط

* کلاس [PictureFillFormat](../)
* فضای نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)