---
title: get_TileOffsetX()
second_title: Aspose.Slides for C++ API Referansı
description: Doku, şeklin orijinaliyle arasındaki yatay kaydırmayı nokta cinsinden döndürür. Pozitif bir değer dokuyu sağa, negatif bir değer ise sola kaydırır. Okunur float.
type: docs
weight: 274
url: /tr/aspose.slides/picturefillformat/get_tileoffsetx/
---
## PictureFillFormat::get_TileOffsetX() metod


Şeklin orijinalinden dokunun yatay kaydırması noktalar cinsinden döndürülür. Pozitif bir değer dokuyu sağa, negatif bir değer ise sola kaydırır. Okunur **float**.

```cpp
float Aspose::Slides::PictureFillFormat::get_TileOffsetX() override
```

## Açıklamalar



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Şeklin resim doldurma biçimini alır
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Resim doldurma modunu Tile olarak ayarlar
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Dokunun yatay kaydırmasını 20 nokta olarak ayarlar
pictureFillFormat->set_TileOffsetX(20.0f);
```

## Ayrıca bakınız

* Sınıf [PictureFillFormat](../)
* Ad alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)