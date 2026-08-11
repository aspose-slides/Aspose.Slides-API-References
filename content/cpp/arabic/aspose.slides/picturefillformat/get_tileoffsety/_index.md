---
title: get_TileOffsetY()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يعيد الإزاحة الرأسية للملمس من أصل الشكل بالنقاط. القيمة الموجبة تحرك الملمس إلى الأسفل، بينما القيمة السالبة تحركه إلى الأعلى. قراءة float.
type: docs
weight: 300
url: /ar/aspose.slides/picturefillformat/get_tileoffsety/
---
## PictureFillFormat::get_TileOffsetY() طريقة

يعيد الإزاحة الرأسية للملمس من أصل الشكل بالنقاط. القيمة الموجبة تحرك الملمس إلى الأسفل، بينما القيمة السالبة تحركه إلى الأعلى. قراءة **float**.

```cpp
float Aspose::Slides::PictureFillFormat::get_TileOffsetY() override
```

## ملاحظات

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// يحصل على تنسيق تعبئة الصورة للشكل
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// يضبط وضع تعبئة الصورة إلى Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// يضبط الإزاحة الرأسية للملمس إلى -50 نقطة
pictureFillFormat->set_TileOffsetY(-50.0f);
```

## انظر أيضًا

* الفئة [PictureFillFormat](../)
* النطاق [Aspose::Slides](../../)
* المكتبة [Aspose.Slides](../../../)