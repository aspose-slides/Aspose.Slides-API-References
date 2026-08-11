---
title: get_TileFlip()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: "يقلب بلاطة النسيج حول محورها الأفقي أو الرأسي أو كليهما. اقرأ Slides::TileFlip."
type: docs
weight: 404
url: /ar/aspose.slides/picturefillformat/get_tileflip/
---
## PictureFillFormat::get_TileFlip() الطريقة

يقلب بلاطة النسيج حول محورها الأفقي أو الرأسي أو كلاهما. اقرأ [Slides::TileFlip](../../tileflip/).

```cpp
Aspose::Slides::TileFlip Aspose::Slides::PictureFillFormat::get_TileFlip() override
```

## ملاحظات

القيمة الافتراضية هي [TileFlip::NoFlip](../../tileflip/).

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// يحصل على تنسيق ملء الصورة للشكل
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// يضبط وضع ملء الصورة إلى Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// يقلب بلاطة النسيج حول محورها العمودي.
pictureFillFormat->set_TileFlip(TileFlip::FlipY);
```

## انظر أيضاً

* Enum [TileFlip](../../tileflip/)
* Class [PictureFillFormat](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)