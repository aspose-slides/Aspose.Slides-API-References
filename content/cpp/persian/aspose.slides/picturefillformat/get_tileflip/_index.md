---
title: get_TileFlip()
second_title: Aspose.Slides برای C++ مرجع API
description: "کاشی بافت را حول محور افقی، عمودی یا هر دو محور می‌چرخاند. Slides::TileFlip را بخوانید."
type: docs
weight: 404
url: /fa/aspose.slides/picturefillformat/get_tileflip/
---
## PictureFillFormat::get_TileFlip() متد


کاشی بافت را حول محور افقی، عمودی یا هر دو محور می‌چرخاند. مطالعه کنید [Slides::TileFlip](../../tileflip/).

```cpp
Aspose::Slides::TileFlip Aspose::Slides::PictureFillFormat::get_TileFlip() override
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

// چرخاندن کاشی بافت حول محور عمودی
pictureFillFormat->set_TileFlip(TileFlip::FlipY);
```

## مطالب مرتبط

* Enum [TileFlip](../../tileflip/)
* کلاس [PictureFillFormat](../)
* فضای نام [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)