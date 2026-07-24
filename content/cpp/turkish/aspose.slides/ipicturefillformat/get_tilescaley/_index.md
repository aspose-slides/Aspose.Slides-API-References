---
title: get_TileScaleY()
second_title: Aspose.Slides için C++ API Referansı
description: Doku doldurması için dikey ölçeği yüzde olarak döndürür. Okunur float.
type: docs
weight: 352
url: /tr/aspose.slides/ipicturefillformat/get_tilescaley/
---
## IPictureFillFormat::get_TileScaleY() metod


Doku doldurması için dikey ölçeği yüzde olarak döndürür. Okunur **float**.

```cpp
virtual float Aspose::Slides::IPictureFillFormat::get_TileScaleY()=0
```

## Açıklama



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Şeklin resim doldurma biçimini alır
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Resim doldurma modunu Döşeme olarak ayarlar
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Doku için dikey ölçeği %120 olarak ayarlar
pictureFillFormat->set_TileScaleY(120.0f);
```

## Ayrıca Bakınız

* Sınıf [IPictureFillFormat](../)
* Ad alanı [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)