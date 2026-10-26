---
title: get_TileScaleY()
second_title: مرجع API Aspose.Slides للغة C++
description: يرجع المقياس الرأسي لملء النسيج كنسبة مئوية. قراءة float.
type: docs
weight: 352
url: /ar/aspose.slides/picturefillformat/get_tilescaley/
---
## PictureFillFormat::get_TileScaleY() طريقة

يرجع المقياس الرأسي لملء النسيج كنسبة مئوية. قراءة **float**.

```cpp
float Aspose::Slides::PictureFillFormat::get_TileScaleY() override
```

## ملاحظات



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// يحصل على تنسيق ملء الصورة للشكل
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// يضبط وضع ملء الصورة إلى Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// يضبط المقياس الرأسي للملمس إلى 120 بالمائة
pictureFillFormat->set_TileScaleY(120.0f);
```

## انظر أيضًا

* فئة [PictureFillFormat](../)
* نطاق [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)