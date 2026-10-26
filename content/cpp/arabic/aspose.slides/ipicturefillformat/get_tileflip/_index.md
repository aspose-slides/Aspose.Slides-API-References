---
title: get_TileFlip()
second_title: مرجع API Aspose.Slides للـ C++
description: "يقلب بلاط النسيج حول محوره الأفقي أو الرأسي أو كليهما. اقرأ Slides::TileFlip."
type: docs
weight: 404
url: /ar/aspose.slides/ipicturefillformat/get_tileflip/
---
## IPictureFillFormat::get_TileFlip() طريقة

يقلب بلاط النسيج حول محوره الأفقي أو الرأسي أو كليهما. اقرأ [Slides::TileFlip](../../tileflip/).

```cpp
virtual Aspose::Slides::TileFlip Aspose::Slides::IPictureFillFormat::get_TileFlip()=0
```

## ملاحظات

الافتراضي هو [TileFlip::NoFlip](../../tileflip/).

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// يحصل على تنسيق تعبئة الصورة للشكل
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// يضبط وضع تعبئة الصورة إلى Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// يقلب بلاط النسيج حول محوره الرأسي.
pictureFillFormat->set_TileFlip(TileFlip::FlipY);
}
```

## انظر أيضًا

* تعداد [TileFlip](../../tileflip/)
* فئة [IPictureFillFormat](../)
* نطاق [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)