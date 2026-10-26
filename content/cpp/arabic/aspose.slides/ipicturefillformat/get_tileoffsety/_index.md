---
title: get_TileOffsetY()
second_title: Aspose.Slides لـ C++ مرجع API
description: يقوم بإرجاع الإزاحة العمودية للملمس من أصل الشكل بوحدات النقاط. القيمة الموجبة تحرك الملمس إلى الأسفل، بينما القيمة السلبية تحركه إلى الأعلى. قراءة float.
type: docs
weight: 300
url: /ar/aspose.slides/ipicturefillformat/get_tileoffsety/
---
## IPictureFillFormat::get_TileOffsetY() طريقة

يعيد الإزاحة العمودية للملمس من أصل الشكل بوحدات النقاط. القيمة الموجبة تحرك الملمس إلى الأسفل، بينما القيمة السلبية تحركه إلى الأعلى. قراءة **float**.

```cpp
virtual float Aspose::Slides::IPictureFillFormat::get_TileOffsetY()=0
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

* فئة [IPictureFillFormat](../)
* نطاق [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)