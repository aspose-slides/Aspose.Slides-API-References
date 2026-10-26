---
title: get_TileOffsetY()
second_title: Aspose.Slides for C++ API Referansı
description: Dokuun şeklin orijinden dikey ofsetini puan cinsinden döndürür. Pozitif bir değer dokuyu aşağı kaydırırken, negatif bir değer yukarı kaydırır. Okunur float.
type: docs
weight: 300
url: /tr/aspose.slides/ipicturefillformat/get_tileoffsety/
---
## IPictureFillFormat::get_TileOffsetY() metodu

Şeklin kökeninden dokuya olan dikey ofseti puan cinsinden döndürür. Pozitif bir değer dokuyu aşağı kaydırırken, negatif bir değer yukarı kaydırır. Okunur **float**.

```cpp
virtual float Aspose::Slides::IPictureFillFormat::get_TileOffsetY()=0
```

## Açıklamalar

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Şeklin resim doldurma formatını alır
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Resim doldurma modunu Tile olarak ayarlar
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Dokunun dikey ofsetini -50 puana ayarlar
pictureFillFormat->set_TileOffsetY(-50.0f);
```

## Ayrıca Bakınız

* Sınıf [IPictureFillFormat](../)
* İsim Alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)