---
title: get_TileScaleX()
second_title: Aspose.Slides لمرجع API الخاص بـ C++
description: ترجع المقياس الأفقي لتعبئة القوام كنسبة مئوية. قراءة float.
type: docs
weight: 326
url: /ar/aspose.slides/picturefillformat/get_tilescalex/
---
## PictureFillFormat::get_TileScaleX() طريقة


ترجع المقياس الأفقي لتعبئة القوام كنسبة مئوية. قراءة **float**.

```cpp
float Aspose::Slides::PictureFillFormat::get_TileScaleX() override
```

## ملاحظات



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// يحصل على تنسيق تعبئة الصورة للعنصر
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// يضبط وضع تعبئة الصورة إلى Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// يضبط المقياس الأفقي للقوام إلى 120 بالمئة
pictureFillFormat->set_TileScaleX(120.0f);
```

## انظر أيضًا

* فئة [PictureFillFormat](../)
* نطاق الاسم [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)