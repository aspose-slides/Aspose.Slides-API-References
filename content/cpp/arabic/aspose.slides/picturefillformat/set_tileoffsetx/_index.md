---
title: set_TileOffsetX()
second_title: المرجع البرمجي لـ Aspose.Slides للغة C++
description: يضبط الإزاحة الأفقية للنقش من أصل الشكل بالنقاط. القيمة الموجبة تنقل النقش إلى اليمين، بينما القيمة السالبة تنقله إلى اليسار. اكتب float.
type: docs
weight: 287
url: /ar/aspose.slides/picturefillformat/set_tileoffsetx/
---
## PictureFillFormat::set_TileOffsetX(float) طريقة


يضبط الإزاحة الأفقية للنقش من أصل الشكل بالنقاط. القيمة الموجبة تنقل النقش إلى اليمين، بينما القيمة السالبة تنقله إلى اليسار. اكتب **float**.

```cpp
void Aspose::Slides::PictureFillFormat::set_TileOffsetX(float value) override
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

* الفئة [PictureFillFormat](../)
* مساحة الاسم [Aspose::Slides](../../)
* المكتبة [Aspose.Slides](../../../)