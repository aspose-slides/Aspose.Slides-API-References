---
title: set_TileScaleY()
second_title: Aspose.Slides for C++ API Referansı
description: Doku dolgusunun dikey ölçeğini yüzde olarak ayarlar. float yazın.
type: docs
weight: 365
url: /tr/aspose.slides/ipicturefillformat/set_tilescaley/
---
## IPictureFillFormat::set_TileScaleY(float) metodu


Doku dolgusunun dikey ölçeğini yüzde olarak ayarlar. **float** yazın.

```cpp
virtual void Aspose::Slides::IPictureFillFormat::set_TileScaleY(float value)=0
```

## Açıklamalar



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Şeklin resim dolgu biçimini alır
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Resim dolgu modunu Tile olarak ayarlar
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Doku için dikey ölçeği %120 olarak ayarlar
pictureFillFormat->set_TileScaleY(120.0f);
```

## Ayrıca Bakınız

* Sınıf [IPictureFillFormat](../)
* AdAlanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)