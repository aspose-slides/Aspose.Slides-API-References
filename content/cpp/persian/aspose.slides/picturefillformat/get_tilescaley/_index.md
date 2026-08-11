---
title: get_TileScaleY()
second_title: Aspose.Slides برای مرجع API C++
description: مقیاس عمودی برای پر کردن بافت را به صورت درصد برمی‌گرداند. قابل خواندن float.
type: docs
weight: 352
url: /fa/aspose.slides/picturefillformat/get_tilescaley/
---
## PictureFillFormat::get_TileScaleY() متد

مقیاس عمودی برای پر کردن بافت را به صورت درصد برمی‌گرداند. قابل خواندن **float**.

```cpp
float Aspose::Slides::PictureFillFormat::get_TileScaleY() override
```

## ملاحظات

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// دریافت فرمت پر کردن تصویر شکل
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// تنظیم حالت پر کردن تصویر به Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// مقیاس عمودی بافت را به 120 درصد تنظیم می‌کند
pictureFillFormat->set_TileScaleY(120.0f);
```

## موارد مرتبط

* کلاس [PictureFillFormat](../)
* فضای نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)