---
title: set_TileOffsetY()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يضبط الإزاحة العمودية للنقش من أصل الشكل بالنقاط. القيمة الموجبة تحرك النقش إلى الأسفل، بينما القيمة السالبة تحركه إلى الأعلى. اكتب float.
type: docs
weight: 313
url: /ar/aspose.slides/ipicturefillformat/set_tileoffsety/
---
## IPictureFillFormat::set_TileOffsetY(float) طريقة

يضبط الإزاحة العمودية للنقش من أصل الشكل بالنقاط. القيمة الموجبة تحرك النقش إلى الأسفل، بينما القيمة السالبة تحركه إلى الأعلى. اكتب **float**.

```cpp
virtual void Aspose::Slides::IPictureFillFormat::set_TileOffsetY(float value)=0
```

## ملاحظات



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// يحصل على تنسيق تعبئة الصورة للشكلة
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// يحدد وضع تعبئة الصورة إلى بلاط
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// يحدد الإزاحة العمودية للنقش إلى -50 نقطة
pictureFillFormat->set_TileOffsetY(-50.0f);
```

## انظر أيضًا

* فئة [IPictureFillFormat](../)
* نطاق الاسم [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)