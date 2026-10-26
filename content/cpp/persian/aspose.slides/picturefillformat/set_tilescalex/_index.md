---
title: set_TileScaleX()
second_title: مرجع API Aspose.Slides برای C++
description: مقیاس افقی را برای پر کردن با بافت به صورت درصد تنظیم می‌کند. مقدار float را بنویسید.
type: docs
weight: 339
url: /fa/aspose.slides/picturefillformat/set_tilescalex/
---
## PictureFillFormat::set_TileScaleX(float) متد


مقیاس افقی را برای پر کردن با بافت به صورت درصد تنظیم می‌کند. مقدار **float** را بنویسید.

```cpp
void Aspose::Slides::PictureFillFormat::set_TileScaleX(float value) override
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

## همچنین ببینید

* کلاس [PictureFillFormat](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)