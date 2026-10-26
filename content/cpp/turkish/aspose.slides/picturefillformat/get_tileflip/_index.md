---
title: get_TileFlip()
second_title: Aspose.Slides C++ API Referansı
description: "Doku karoselini yatay, dikey veya her iki eksen etrafında çevirir. Slides::TileFlip okuyun."
type: docs
weight: 404
url: /tr/aspose.slides/picturefillformat/get_tileflip/
---
## PictureFillFormat::get_TileFlip() metot

Doku karoselini yatay, dikey veya her iki eksen etrafında çevirir. Oku [Slides::TileFlip](../../tileflip/).

```cpp
Aspose::Slides::TileFlip Aspose::Slides::PictureFillFormat::get_TileFlip() override
```

## Açıklamalar


Varsayılan [TileFlip::NoFlip](../../tileflip/).

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Şeklin resim doldurma biçimini alır
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Resim doldurma modunu Karo olarak ayarlar
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Doku karoselini dikey eksen etrafında çevirir.
pictureFillFormat->set_TileFlip(TileFlip::FlipY);
```

## İlgili

* Enum [TileFlip](../../tileflip/)
* Sınıf [PictureFillFormat](../)
* Ad Alanı [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)