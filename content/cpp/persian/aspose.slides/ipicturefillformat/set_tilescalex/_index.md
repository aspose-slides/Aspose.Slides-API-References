---
title: set_TileScaleX()
second_title: مرجع API Aspose.Slides برای C++
description: مقیاس افقی پر کردن بافت را به صورت درصد تنظیم می‌کند. مقدار float را بنویسید.
type: docs
weight: 339
url: /fa/aspose.slides/ipicturefillformat/set_tilescalex/
---
## IPictureFillFormat::set_TileScaleX(float) متد


مقیاس افقی برای پر کردن بافت را به صورت درصد تنظیم می‌کند. مقدار **float** را بنویسید.

```cpp
virtual void Aspose::Slides::IPictureFillFormat::set_TileScaleX(float value)=0
```

## توضیحات



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// قالب پر کردن تصویر شکل را دریافت می‌کند
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// حالت پر کردن تصویر را به Tile تنظیم می‌کند
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// مقیاس افقی بافت را به 120 درصد تنظیم می‌کند
pictureFillFormat->set_TileScaleX(120.0f);
```

## موارد مرتبط

* کلاس [IPictureFillFormat](../)
* فضای نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)