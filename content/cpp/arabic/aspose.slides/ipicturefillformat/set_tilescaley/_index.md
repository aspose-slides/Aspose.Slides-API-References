---
title: set_TileScaleY()
second_title: Aspose.Slides للـ C++ مرجع API
description: يضبط المقياس العمودي لتعبئة النسيج كنسبة مئوية. اكتب float.
type: docs
weight: 365
url: /ar/aspose.slides/ipicturefillformat/set_tilescaley/
---
## IPictureFillFormat::set_TileScaleY(float) method


يضبط المقياس العمودي لتعبئة النسيج كنسبة مئوية. اكتب **float**.

```cpp
virtual void Aspose::Slides::IPictureFillFormat::set_TileScaleY(float value)=0
```

## ملاحظات



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// يحصل على تنسيق تعبئة الصورة للشكل
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// يضبط وضع تعبئة الصورة إلى Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// يضبط المقياس العمودي للنسيج إلى 120٪
pictureFillFormat->set_TileScaleY(120.0f);
```

## انظر أيضًا

* الفئة [IPictureFillFormat](../)
* نطاق الاسم [Aspose::Slides](../../)
* المكتبة [Aspose.Slides](../../../)