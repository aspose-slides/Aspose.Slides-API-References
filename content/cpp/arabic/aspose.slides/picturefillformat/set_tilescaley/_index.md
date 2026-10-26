---
title: set_TileScaleY()
second_title: Aspose.Slides لواجهة برمجة التطبيقات لـ C++
description: يضبط المقياس العمودي لملء القوام كنسبة مئوية. اكتب float.
type: docs
weight: 365
url: /ar/aspose.slides/picturefillformat/set_tilescaley/
---
## PictureFillFormat::set_TileScaleY(float) طريقة


يضبط المقياس العمودي لملء القوام كنسبة مئوية. اكتب **float**.

```cpp
void Aspose::Slides::PictureFillFormat::set_TileScaleY(float value) override
```

## ملاحظات



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// يحصل على تنسيق ملء الصورة لل形
// يضبط وضع ملء الصورة إلى Tile
// يضبط المقياس العمودي للقوام إلى 120٪
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Sets the picture fill mode to Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Sets the vertical scale for the texture to 120 percents
pictureFillFormat->set_TileScaleY(120.0f);
```

## انظر أيضًا

* الفئة [PictureFillFormat](../)
* النطاق [Aspose::Slides](../../)
* المكتبة [Aspose.Slides](../../../)