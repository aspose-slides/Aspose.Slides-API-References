---
title: set_TileFlip()
second_title: Aspose.Slides برای مرجع API C++
description: "کاشی بافت را حول محور افقی، عمودی یا هر دو محور می‌چرخاند. بنویسید Slides::TileFlip."
type: docs
weight: 417
url: /fa/aspose.slides/ipicturefillformat/set_tileflip/
---
## IPictureFillFormat::set_TileFlip(Aspose::Slides::TileFlip) متد

کاشی بافت را در محور افقی، عمودی یا هر دو محور می‌چرخاند. بنویسید [Slides::TileFlip](../../tileflip/).

```cpp
virtual void Aspose::Slides::IPictureFillFormat::set_TileFlip(Aspose::Slides::TileFlip value)=0
```

## توضیحات

پیش‌فرض [TileFlip::NoFlip](../../tileflip/) است.

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// فرمت پر کردن تصویر شکل را دریافت می‌کند
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// حالت پر کردن تصویر را به کاشی تنظیم می‌کند
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// کاشی بافت را حول محور عمودی می‌چرخاند.
pictureFillFormat->set_TileFlip(TileFlip::FlipY);
}
```

## موارد مرتبط

* Enum [TileFlip](../../tileflip/)
* Class [IPictureFillFormat](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)