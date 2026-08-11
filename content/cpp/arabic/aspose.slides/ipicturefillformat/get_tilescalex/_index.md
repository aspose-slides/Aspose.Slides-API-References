---
title: get_TileScaleX()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: تعيد المقياس الأفقي لتعبئة القوام كنسبة مئوية. قراءة float.
type: docs
weight: 326
url: /ar/aspose.slides/ipicturefillformat/get_tilescalex/
---
## IPictureFillFormat::get_TileScaleX() طريقة

تعيد المقياس الأفقي لتعبئة القوام كنسبة مئوية. قراءة **float**.

```cpp
virtual float Aspose::Slides::IPictureFillFormat::get_TileScaleX()=0
```

## ملاحظات



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// يجلب تنسيق تعبئة الصورة للشكل
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// يضبط وضع تعبئة الصورة إلى Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// يضبط المقياس الأفقي للقوام إلى 120٪
pictureFillFormat->set_TileScaleX(120.0f);
```

## انظر أيضًا

* الفئة [IPictureFillFormat](../)
* النطاق [Aspose::Slides](../../)
* المكتبة [Aspose.Slides](../../../)