---
title: set_TileOffsetX()
second_title: Aspose.Slides for C++ API Referansı
description: Dokunun şeklin orijinal noktasından yatay offsetini puan cinsinden ayarlar. Pozitif bir değer dokuyu sağa, negatif bir değer ise sola kaydırır. Float yazın.
type: docs
weight: 287
url: /tr/aspose.slides/ipicturefillformat/set_tileoffsetx/
---
## IPictureFillFormat::set_TileOffsetX(float) metodu


Desenin orijinal noktasından dokuya yatay offseti puan cinsinden ayarlar. Pozitif bir değer dokuyu sağa, negatif bir değer dokuyu sola kaydırır. **float** yazın.

```cpp
virtual void Aspose::Slides::IPictureFillFormat::set_TileOffsetX(float value)=0
```

## Açıklamalar



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Şeklin resim doldurma formatını alır
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Resim doldurma modunu Tile olarak ayarlar
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Dokunun yatay offsetini 20 puana ayarlar
pictureFillFormat->set_TileOffsetX(20.0f);
```

## Diğer Bağlantılar

* Sınıf [IPictureFillFormat](../)
* Ad alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)