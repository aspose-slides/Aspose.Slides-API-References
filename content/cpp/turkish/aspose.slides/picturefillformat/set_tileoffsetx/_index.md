---
title: set_TileOffsetX()
second_title: Aspose.Slides C++ için API Referansı
description: Doku'nun şeklin orijini noktasından yatay kaydırmasını nokta cinsinden ayarlar. Pozitif bir değer doku'yu sağa, negatif bir değer doku'yu sola taşır. Yaz float.
type: docs
weight: 287
url: /tr/aspose.slides/picturefillformat/set_tileoffsetx/
---
## PictureFillFormat::set_TileOffsetX(float) metod

Doku'nun şeklin orijini noktasından yatay kaydırmasını nokta cinsinden ayarlar. Pozitif bir değer doku'yu sağa, negatif bir değer doku'yu sola taşır. Yaz **float**.

```cpp
void Aspose::Slides::PictureFillFormat::set_TileOffsetX(float value) override
```

## Açıklamalar

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Şeklin resim doldurma biçimini alır
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Resim doldurma modunu Tile olarak ayarlar
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Doku'nun yatay kaydırmasını 20 nokta olarak ayarlar
pictureFillFormat->set_TileOffsetX(20.0f);
```

## İlgili

* Sınıf [PictureFillFormat](../)
* Ad alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)