---
title: get_TileOffsetX()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يرجع الإزاحة الأفقية للنقش من أصل الشكل بالنقاط. القيمة الموجبة تحرك النقش إلى اليمين، بينما القيمة السالبة تحركه إلى اليسار. قراءة float.
type: docs
weight: 274
url: /ar/aspose.slides/ipicturefillformat/get_tileoffsetx/
---
## IPictureFillFormat::get_TileOffsetX() طريقة

يرجع الإزاحة الأفقية للنقش من أصل الشكل بالنقاط. القيمة الموجبة تحرك النقش إلى اليمين، بينما القيمة السالبة تحركه إلى اليسار. قراءة **float**.

```cpp
virtual float Aspose::Slides::IPictureFillFormat::get_TileOffsetX()=0
```

## ملاحظات

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// يحصل على تنسيق تعبئة الصورة للشكل
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// يضبط وضع تعبئة الصورة إلى Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// يضبط الإزاحة الأفقية للنقش إلى 20 نقطة
pictureFillFormat->set_TileOffsetX(20.0f);
```

## انظر أيضًا

* الفئة [IPictureFillFormat](../)
* النطاق [Aspose::Slides](../../)
* المكتبة [Aspose.Slides](../../../)