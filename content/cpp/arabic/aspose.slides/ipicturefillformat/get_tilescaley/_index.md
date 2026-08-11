---
title: get_TileScaleY()
second_title: Aspose.Slides لـ C++ مرجع واجهة برمجة التطبيقات
description: يعيد المقياس العمودي لتعبئة النسيج كنسبة مئوية. اقرأ float.
type: docs
weight: 352
url: /ar/aspose.slides/ipicturefillformat/get_tilescaley/
---
## IPictureFillFormat::get_TileScaleY() طريقة

يُرجع المقياس العمودي لتعبئة النسيج كنسبة مئوية. اقرأ **float**.

```cpp
virtual float Aspose::Slides::IPictureFillFormat::get_TileScaleY()=0
```

## ملاحظات

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// يحصل على تنسيق تعبئة الصورة للشكل
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// يضبط وضع تعبئة الصورة إلى Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// يضبط المقياس العمودي للنسيج إلى 120 بالمئة
pictureFillFormat->set_TileScaleY(120.0f);
```

## انظر أيضًا

* الفئة [IPictureFillFormat](../)
* مساحة الاسم [Aspose::Slides](../../)
* المكتبة [Aspose.Slides](../../../)