---
title: get_TileScaleX()
second_title: Aspose.Slides برای C++ مرجع API
description: مقدار مقیاس افقی برای پر کردن بافت را به صورت درصد برمی‌گرداند. خواندن float.
type: docs
weight: 326
url: /fa/aspose.slides/picturefillformat/get_tilescalex/
---
## PictureFillFormat::get_TileScaleX() متد

مقدار مقیاس افقی برای بافت پر کردن را به صورت درصد برمی‌گرداند. خواندنی **float**.

```cpp
float Aspose::Slides::PictureFillFormat::get_TileScaleX() override
```

## توضیحات



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// فرمت پر کردن تصویر شکل را دریافت می‌کند
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// حالت پر کردن تصویر را به Tile تنظیم می‌کند
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// مقیاس افقی بافت را به 120 درصد تنظیم می‌کند
pictureFillFormat->set_TileScaleX(120.0f);
```

## موارد مرتبط

* کلاس [PictureFillFormat](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)