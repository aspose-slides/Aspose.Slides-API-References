---
title: set_TileScaleX()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: يضبط المقياس الأفقي لتعبئة النسيج كنسبة مئوية. اكتب float.
type: docs
weight: 339
url: /ar/aspose.slides/ipicturefillformat/set_tilescalex/
---
## IPictureFillFormat::set_TileScaleX(float) طريقة

يضبط مقياس الأفقى للتعبئة بالنسيج كنسبة مئوية. اكتب **float**.

```cpp
virtual void Aspose::Slides::IPictureFillFormat::set_TileScaleX(float value)=0
```

## ملاحظات



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// يحصل على تنسيق تعبئة الصورة للشكل
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// يضبط وضع تعبئة الصورة إلى Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// يضبط المقياس الأفقي للنسيج إلى 120 بالمئة
pictureFillFormat->set_TileScaleX(120.0f);
```

## انظر أيضاً

* الفئة [IPictureFillFormat](../)
* مساحة الاسم [Aspose::Slides](../../)
* المكتبة [Aspose.Slides](../../../)