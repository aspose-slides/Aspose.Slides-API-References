---
title: get_TileOffsetX()
second_title: Aspose.Slides برای مرجع API C++
description: افست افقی بافت را نسبت به مبدای شکل به واحد نقطه باز می‌گرداند. مقدار مثبت بافت را به سمت راست می‌برد، در حالی که مقدار منفی آن را به سمت چپ می‌برد. قابل خواندن float.
type: docs
weight: 274
url: /fa/aspose.slides/picturefillformat/get_tileoffsetx/
---
## PictureFillFormat::get_TileOffsetX() متد


باز می‌گرداند افست افقی بافت از مبدای شکل به واحد نقاط. مقدار مثبت بافت را به سمت راست می‌برد، در حالی که مقدار منفی آن را به سمت چپ می‌برد. قابل خواندن **float**.

```cpp
float Aspose::Slides::PictureFillFormat::get_TileOffsetX() override
```

## توضیحات



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// قالب پر کردن تصویر شکل را دریافت می‌کند
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// حالت پر کردن تصویر را روی Tile تنظیم می‌کند
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// افست افقی بافت را به 20 نقطه تنظیم می‌کند
pictureFillFormat->set_TileOffsetX(20.0f);
```

## موارد مرتبط

* کلاس [PictureFillFormat](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)