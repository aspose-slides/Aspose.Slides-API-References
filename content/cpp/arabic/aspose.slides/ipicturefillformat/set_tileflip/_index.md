---
title: set_TileFlip()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: "يقلب بلاطة النسيج حول محورها الأفقي أو العمودي أو كليهما. اكتب Slides::TileFlip."
type: docs
weight: 417
url: /ar/aspose.slides/ipicturefillformat/set_tileflip/
---
## IPictureFillFormat::set_TileFlip(Aspose::Slides::TileFlip) طريقة

يقلب بلاطة النسيج حول محورها الأفقي أو العمودي أو كليهما. اكتب [Slides::TileFlip](../../tileflip/).

```cpp
virtual void Aspose::Slides::IPictureFillFormat::set_TileFlip(Aspose::Slides::TileFlip value)=0
```

## ملاحظات

القيمة الافتراضية هي [TileFlip::NoFlip](../../tileflip/). 


```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// يحصل على تنسيق تعبئة الصورة للشكل
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// يضبط وضع تعبئة الصورة إلى نمط التكرار
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// يقلب بلاطة القوام حول محورها العمودي.
pictureFillFormat->set_TileFlip(TileFlip::FlipY);
}
```

## انظر أيضاً

* تعداد [TileFlip](../../tileflip/)
* فئة [IPictureFillFormat](../)
* نطاق اسم [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)