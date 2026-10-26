---
title: get_TileOffsetX()
second_title: Aspose.Slides için C++ API Referansı
description: Doku'nun şeklin orijininin yatay ofsetini puan cinsinden döndürür. Pozitif bir değer doku'yu sağa, negatif bir değer doku'yu sola kaydırır. Okunur float.
type: docs
weight: 274
url: /tr/aspose.slides/ipicturefillformat/get_tileoffsetx/
---
## IPictureFillFormat::get_TileOffsetX() yöntemi

Doku'nun şeklin orijininin yatay ofsetini puan cinsinden döndürür. Pozitif bir değer doku'yu sağa, negatif bir değer doku'yu sola kaydırır. Okunur **float**.

```cpp
virtual float Aspose::Slides::IPictureFillFormat::get_TileOffsetX()=0
```

## Açıklamalar

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Şeklin resim doldurma biçimini alır
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Resim doldurma modunu Döşeme olarak ayarlar
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Doku'nun yatay ofsetini 20 puana ayarlar
pictureFillFormat->set_TileOffsetX(20.0f);
```

## Ayrıca Bakınız

* Sınıf [IPictureFillFormat](../)
* Ad Alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)