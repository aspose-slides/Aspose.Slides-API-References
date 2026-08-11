---
title: set_TileFlip()
second_title: مرجع واجهة برمجة التطبيقات Aspose.Slides للغة C++
description: "يقلب لوحة النسيج حول محورها الأفقي أو الرأسي أو كلاهما. اكتب Slides::TileFlip."
type: docs
weight: 417
url: /ar/aspose.slides/picturefillformat/set_tileflip/
---
## PictureFillFormat::set_TileFlip(Aspose::Slides::TileFlip) طريقة

يقلب لوحة النسيج حول محورها الأفقي أو الرأسي أو كلاهما. اكتب [Slides::TileFlip](../../tileflip/).

```cpp
void Aspose::Slides::PictureFillFormat::set_TileFlip(Aspose::Slides::TileFlip value) override
```

## ملاحظات

الافتراضي هو [TileFlip::NoFlip](../../tileflip/). 

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// يحصل على تنسيق ملء الصورة للشكل
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// يضبط وضع ملء الصورة إلى بلاط
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// يقلب لوحة النسيج حول محورها العمودي.
pictureFillFormat->set_TileFlip(TileFlip::FlipY);
```

## انظر أيضًا

* Enum [TileFlip](../../tileflip/)
* فئة [PictureFillFormat](../)
* نطاق [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)