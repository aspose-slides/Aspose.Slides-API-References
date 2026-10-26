---
title: set_TileScaleX()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: يضبط المقياس الأفقي لملء النسيج كنسبة مئوية. اكتب float.
type: docs
weight: 339
url: /ar/aspose.slides/picturefillformat/set_tilescalex/
---
## PictureFillFormat::set_TileScaleX(float) طريقة

يضبط المقياس الأفقي للملء بالنسيج كنسبة مئوية. اكتب **float**.

```cpp
void Aspose::Slides::PictureFillFormat::set_TileScaleX(float value) override
```

## ملاحظات

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// يحصل على تنسيق ملء الصورة للشكل
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// يضبط وضع ملء الصورة إلى Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// يضبط المقياس الأفقي للنسيج إلى 120 بالمئة
pictureFillFormat->set_TileScaleX(120.0f);
```

## انظر أيضًا

* فئة [PictureFillFormat](../)
* النطاق [Aspose::Slides](../../)
* المكتبة [Aspose.Slides](../../../)