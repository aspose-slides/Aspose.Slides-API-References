---
title: get_TileOffsetX()
second_title: مرجع API Aspose.Slides للغة C++
description: ترجع الإزاحة الأفقية للنقش من أصل الشكل بالنقاط. القيمة الموجبة تحرك النقش إلى اليمين، بينما القيمة السالبة تحركه إلى اليسار. قراءة float.
type: docs
weight: 274
url: /ar/aspose.slides/picturefillformat/get_tileoffsetx/
---
## PictureFillFormat::get_TileOffsetX() طريقة

ترجع الإزاحة الأفقية للنقش من أصل الشكل بالنقاط. القيمة الموجبة تحرك النقش إلى اليمين، بينما القيمة السالبة تحركه إلى اليسار. قراءة **float**.

```cpp
float Aspose::Slides::PictureFillFormat::get_TileOffsetX() override
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
## انظر أيضاً

* صنف [PictureFillFormat](../)
* نطاق [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)