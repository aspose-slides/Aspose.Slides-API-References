---
title: get_TileScaleX()
second_title: Aspose.Slides için C++ API Referansı
description: Doku dolgusunun yatay ölçeğini yüzde olarak döndürür. Okunan float.
type: docs
weight: 326
url: /tr/aspose.slides/ipicturefillformat/get_tilescalex/
---
## IPictureFillFormat::get_TileScaleX() metod


Yatay ölçeği yüzde olarak döndürür. Okunan **float**.

```cpp
virtual float Aspose::Slides::IPictureFillFormat::get_TileScaleX()=0
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

* Sınıf [IPictureFillFormat](../)
* İsim Uzayı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)