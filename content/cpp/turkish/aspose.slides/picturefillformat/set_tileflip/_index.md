---
title: set_TileFlip()
second_title: Aspose.Slides için C++ API Referansı
description: "Doku döşemesini yatay, dikey veya her iki eksen etrafında çevirir. Slides::TileFlip yazın."
type: docs
weight: 417
url: /tr/aspose.slides/picturefillformat/set_tileflip/
---
## PictureFillFormat::set_TileFlip(Aspose::Slides::TileFlip) method


Doku döşemesini yatay, dikey veya her iki eksen etrafında çevirir. Yazın [Slides::TileFlip](../../tileflip/).

```cpp
void Aspose::Slides::PictureFillFormat::set_TileFlip(Aspose::Slides::TileFlip value) override
```

## Açıklamalar


Varsayılan [TileFlip::NoFlip](../../tileflip/). 


```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Şeklin resim doldurma biçimini alır
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Resim doldurma modunu Döşeme olarak ayarlar
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Doku döşemesini dikey ekseni etrafında çevirir.
pictureFillFormat->set_TileFlip(TileFlip::FlipY);
```

## Ayrıca Bakınız

* Enum [TileFlip](../../tileflip/)
* Class [PictureFillFormat](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)