---
title: set_TileOffsetY()
second_title: Aspose.Slides للـ C++ مرجع API
description: يحدد الإزاحة العمودية للملمس من أصل الشكل بالنقاط. القيمة الموجبة تحرك الملمس إلى الأسفل، بينما القيمة السالبة تحركه إلى الأعلى. اكتب float.
type: docs
weight: 313
url: /ar/aspose.slides/picturefillformat/set_tileoffsety/
---
## PictureFillFormat::set_TileOffsetY(float) طريقة

يحدد الإزاحة العمودية للملمس من أصل الشكل بالنقاط. القيمة الموجبة تحرك الملمس إلى الأسفل، بينما القيمة السالبة تحركه إلى الأعلى. اكتب **float**.

```cpp
void Aspose::Slides::PictureFillFormat::set_TileOffsetY(float value) override
```

## ملاحظات



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// يحصل على تنسيق تعبئة الصورة للشكل
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// يضبط وضع تعبئة الصورة إلى Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// يضبط الإزاحة العمودية للملمس إلى -50 نقطة
pictureFillFormat->set_TileOffsetY(-50.0f);
```

## انظر أيضًا

* الفئة [PictureFillFormat](../)
* النطاق [Aspose::Slides](../../)
* المكتبة [Aspose.Slides](../../../)