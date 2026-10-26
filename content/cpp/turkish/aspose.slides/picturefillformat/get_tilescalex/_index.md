---
title: get_TileScaleX()
second_title: Aspose.Slides for C++ API Referansı
description: Doku dolgusunun yatay ölçeğini yüzde olarak döndürür. Okunur **float**.
type: docs
weight: 326
url: /tr/aspose.slides/picturefillformat/get_tilescalex/
---
## PictureFillFormat::get_TileScaleX() metodu

Yüzde olarak doku dolgusunun yatay ölçeğini döndürür. Okunur **float**.

```cpp
float Aspose::Slides::PictureFillFormat::get_TileScaleX() override
```

## Açıklamalar


```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Şeklin resim dolgu formatını alır
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Resim dolgu modunu Tile olarak ayarlar
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Doku için yatay ölçeği %120 olarak ayarlar
pictureFillFormat->set_TileScaleX(120.0f);
```

## İlgili

* Sınıf [PictureFillFormat](../)
* Ad alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)