---
title: set_TileFlip()
second_title: C++ için Aspose.Slides API Referansı
description: "Doku döşemesini yatay, dikey ya da her iki eksen etrafında çevirir. Slides::TileFlip yazın."
type: docs
weight: 417
url: /tr/aspose.slides/ipicturefillformat/set_tileflip/
---
## IPictureFillFormat::set_TileFlip(Aspose::Slides::TileFlip) method


Doku döşemesini yatay, dikey ya da her iki eksen etrafında çevirir. [Slides::TileFlip](../../tileflip/) yazın.

```cpp
virtual void Aspose::Slides::IPictureFillFormat::set_TileFlip(Aspose::Slides::TileFlip value)=0
```

## Açıklamalar


Varsayılan [TileFlip::NoFlip](../../tileflip/)'dir. 


```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Şeklin resim doldurma formatını alır
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Resim doldurma modunu Tile olarak ayarlar
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Doku döşemesini dikey eksen etrafında çevirir.
pictureFillFormat->set_TileFlip(TileFlip::FlipY);
}
```

## Ayrıca Bakınız

* Enum [TileFlip](../../tileflip/)
* Class [IPictureFillFormat](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)