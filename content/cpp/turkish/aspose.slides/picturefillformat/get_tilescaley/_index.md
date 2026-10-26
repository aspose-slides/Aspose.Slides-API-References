---
title: get_TileScaleY()
second_title: Aspose.Slides için C++ API Referansı
description: Doku dolgusunun dikey ölçeğini yüzde olarak döndürür. Okunan float.
type: docs
weight: 352
url: /tr/aspose.slides/picturefillformat/get_tilescaley/
---
## PictureFillFormat::get_TileScaleY() metodu


Doku dolgusunun dikey ölçeğini yüzde olarak döndürür. Okunan **float**.

```cpp
float Aspose::Slides::PictureFillFormat::get_TileScaleY() override
```

## Açıklamalar



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

* Sınıf [PictureFillFormat](../)
* Ad alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)