---
title: set_TileOffsetX()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يضبط الإزاحة الأفقية للملمس من أصل الشكل بالنقاط. القيمة الموجبة تحرك الملمس إلى اليمين، بينما القيمة السالبة تحركه إلى اليسار. اكتب float.
type: docs
weight: 287
url: /ar/aspose.slides/ipicturefillformat/set_tileoffsetx/
---
## IPictureFillFormat::set_TileOffsetX(float) method


يضبط الإزاحة الأفقية للملمس من أصل الشكل بالنقاط. القيمة الموجبة تحرك الملمس إلى اليمين، بينما القيمة السالبة تحركه إلى اليسار. اكتب **float**.

```cpp
virtual void Aspose::Slides::IPictureFillFormat::set_TileOffsetX(float value)=0
```

## ملاحظات



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// يحصل على تنسيق تعبئة الصورة للشكل
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// يضبط وضع تعبئة الصورة إلى نمط البلاط
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// يضبط الإزاحة الأفقية للملمس إلى 20 نقطة
pictureFillFormat->set_TileOffsetX(20.0f);
```

## انظر أيضًا

* فئة [IPictureFillFormat](../)
* مساحة اسم [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)