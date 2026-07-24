---
title: get_TileFlip()
second_title: Aspose.Slides için C++ API Referansı
description: "Doku karonunu yatay, dikey veya her iki eksen etrafında çevirir. Slides::TileFlip öğesini okuyun."
type: docs
weight: 404
url: /tr/aspose.slides/ipicturefillformat/get_tileflip/
---
## IPictureFillFormat::get_TileFlip() metot

Doku karonunu yatay, dikey veya her iki eksen etrafında çevirir. [Slides::TileFlip](../../tileflip/)'i okuyun.

```cpp
virtual Aspose::Slides::TileFlip Aspose::Slides::IPictureFillFormat::get_TileFlip()=0
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

// Doku karonunu dikey ekseni etrafında çevirir.
pictureFillFormat->set_TileFlip(TileFlip::FlipY);
}
```

## İlgili Bağlantılar

* Enum [TileFlip](../../tileflip/)
* Sınıf [IPictureFillFormat](../)
* İsim Uzayı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)