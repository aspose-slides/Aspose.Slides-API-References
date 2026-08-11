---
title: get_TileScaleY()
second_title: Aspose.Slides برای C++ مرجع API
description: مقیاس عمودی پر بافت را به‌صورت درصد برمی‌گرداند. خواندنی float.
type: docs
weight: 352
url: /fa/aspose.slides/ipicturefillformat/get_tilescaley/
---
## IPictureFillFormat::get_TileScaleY() متد


مقیاس عمودی پر بافت را به‌صورت درصد برمی‌گرداند. خواندنی **float**.

```cpp
virtual float Aspose::Slides::IPictureFillFormat::get_TileScaleY()=0
```

## توضیحات



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// قالب پر تصویر شکل را دریافت می‌کند
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// حالت پر تصویر را روی Tile تنظیم می‌کند
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// مقیاس عمودی بافت را به 120 درصد تنظیم می‌کند
pictureFillFormat->set_TileScaleY(120.0f);
```

## موارد مرتبط

* کلاس [IPictureFillFormat](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)