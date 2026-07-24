---
title: set_TileScaleY()
second_title: Aspose.Slides için C++ API Referansı
description: Doku dolgusunun dikey ölçeğini yüzde olarak ayarlar. float yazın.
type: docs
weight: 365
url: /tr/aspose.slides/picturefillformat/set_tilescaley/
---
## PictureFillFormat::set_TileScaleY(float) metod


Doku dolgusunun dikey ölçeğini yüzde olarak ayarlar. **float** yazın.

```cpp
void Aspose::Slides::PictureFillFormat::set_TileScaleY(float value) override
```

## Açıklamalar



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Şeklin resim dolgu formatını alır
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Resim dolgu modunu Tile olarak ayarlar
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Doku için dikey ölçeği yüzde 120 olarak ayarlar
pictureFillFormat->set_TileScaleY(120.0f);
```

## Ayrıca Bakınız

* Sınıf [PictureFillFormat](../)
* İsim Alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)