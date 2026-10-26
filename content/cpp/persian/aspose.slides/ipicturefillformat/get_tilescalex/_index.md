---
title: get_TileScaleX()
second_title: Aspose.Slides برای C++ مرجع API
description: مقیاس افقی پر کردن بافت را به‌صورت درصد برمی‌گرداند. خواندنی float.
type: docs
weight: 326
url: /fa/aspose.slides/ipicturefillformat/get_tilescalex/
---
## IPictureFillFormat::get_TileScaleX() متد


مقیاس افقی پر کردن بافت را به‌صورت درصد برمی‌گرداند. خواندنی **float**.

```cpp
virtual float Aspose::Slides::IPictureFillFormat::get_TileScaleX()=0
```

## توضیحات



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// فرمت پر کردن تصویر شکل را دریافت می‌کند
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// حالت پر کردن تصویر را روی Tile تنظیم می‌کند
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// مقیاس افقی بافت را به 120 درصد تنظیم می‌کند
pictureFillFormat->set_TileScaleX(120.0f);
```

## موارد مرتبط

* کلاس [IPictureFillFormat](../)
* فضای نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)