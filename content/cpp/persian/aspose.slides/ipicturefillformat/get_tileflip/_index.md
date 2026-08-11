---
title: get_TileFlip()
second_title: Aspose.Slides برای C++ مرجع API
description: "کاشی بافت را حول محور افقی، عمودی یا هر دو محور می‌چرخاند. خواندن Slides::TileFlip."
type: docs
weight: 404
url: /fa/aspose.slides/ipicturefillformat/get_tileflip/
---
## IPictureFillFormat::get_TileFlip() متد


کاشی بافت را حول محور افقی، عمودی یا هر دو محور می‌چرخاند. خواندن [Slides::TileFlip](../../tileflip/).

```cpp
virtual Aspose::Slides::TileFlip Aspose::Slides::IPictureFillFormat::get_TileFlip()=0
```

## ملاحظات


پیش‌فرض [TileFlip::NoFlip](../../tileflip/) است. 


```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// فرمت پر کردن تصویر شکل را دریافت می‌کند
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// حالت پر کردن تصویر را به Tile تنظیم می‌کند
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// کاشی بافت را حول محور عمودی می‌چرخاند.
pictureFillFormat->set_TileFlip(TileFlip::FlipY);
}
```

## مراجع

* Enum [TileFlip](../../tileflip/)
* Class [IPictureFillFormat](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)