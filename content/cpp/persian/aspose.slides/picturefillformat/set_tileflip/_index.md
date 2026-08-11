---
title: set_TileFlip()
second_title: مرجع API Aspose.Slides برای C++
description: "کاشی بافت را حول محور افقی، عمودی یا هر دو محور می‌چرخاند. بنویسید Slides::TileFlip."
type: docs
weight: 417
url: /fa/aspose.slides/picturefillformat/set_tileflip/
---
## PictureFillFormat::set_TileFlip(Aspose::Slides::TileFlip) متد


کاشی بافت را حول محور افقی، عمودی یا هر دو محور می‌چرخاند. بنویسید [Slides::TileFlip](../../tileflip/).

```cpp
void Aspose::Slides::PictureFillFormat::set_TileFlip(Aspose::Slides::TileFlip value) override
```

## توضیحات


پیش‌فرض [TileFlip::NoFlip](../../tileflip/) است. 


```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// دریافت قالب پر کردن تصویر شکل
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// تنظیم حالت پر کردن تصویر به Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// کاشی بافت را حول محور عمودی می‌چرخاند.
pictureFillFormat->set_TileFlip(TileFlip::FlipY);
```

## مراجع

* enum [TileFlip](../../tileflip/)
* کلاس [PictureFillFormat](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)