---
title: set_TileScaleY()
second_title: مرجع API Aspose.Slides برای C++
description: مقیاس عمودی پر کردن بافت را به صورت درصد تنظیم می‌کند. مقدار float را بنویسید.
type: docs
weight: 365
url: /fa/aspose.slides/picturefillformat/set_tilescaley/
---
## PictureFillFormat::set_TileScaleY(float) متد


مقیاس عمودی پر کردن بافت را به صورت درصد تنظیم می‌کند. **float** را بنویسید.

```cpp
void Aspose::Slides::PictureFillFormat::set_TileScaleY(float value) override
```

## توضیحات



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// دریافت قالب پر کردن تصویر شکل
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// تنظیم حالت پر کردن تصویر به Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// تنظیم مقیاس عمودی بافت به 120 درصد
pictureFillFormat->set_TileScaleY(120.0f);
```

## مراجع

* کلاس [PictureFillFormat](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)