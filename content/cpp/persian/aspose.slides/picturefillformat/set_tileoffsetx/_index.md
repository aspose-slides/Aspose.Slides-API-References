---
title: set_TileOffsetX()
second_title: مرجع API Aspose.Slides برای C++
description: افست افقی بافت نسبت به مبدأ شکل را بر حسب نقطه تعیین می‌کند. مقدار مثبت بافت را به سمت راست جابه‌جا می‌کند، در حالی که مقدار منفی آن را به سمت چپ می‌برد. بنویسید float.
type: docs
weight: 287
url: /fa/aspose.slides/picturefillformat/set_tileoffsetx/
---
## PictureFillFormat::set_TileOffsetX(float) متد


افست افقی بافت نسبت به مبدأ شکل را بر حسب نقطه تعیین می‌کند. مقدار مثبت بافت را به سمت راست جابه‌جا می‌کند، در حالی که مقدار منفی آن را به سمت چپ می‌برد. بنویسید **float**.

```cpp
void Aspose::Slides::PictureFillFormat::set_TileOffsetX(float value) override
```

## ملاحظات



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// دریافت فرمت پر کردن تصویر شکل
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// تنظیم حالت پر کردن تصویر به Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// تنظیم افست افقی بافت به 20 نقطه
pictureFillFormat->set_TileOffsetX(20.0f);
```

## موارد مرتبط

* کلاس [PictureFillFormat](../)
* فضای نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)