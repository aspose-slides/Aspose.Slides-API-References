---
title: set_TileScaleX()
second_title: Aspose.Slides için C++ API Referansı
description: Doku dolgusunun yatay ölçeğini yüzde olarak ayarlar. float yazın.
type: docs
weight: 339
url: /tr/aspose.slides/picturefillformat/set_tilescalex/
---
## PictureFillFormat::set_TileScaleX(float) yöntemi


Doku dolgusunun yatay ölçeğini yüzde olarak ayarlar. **float** yazın.

```cpp
void Aspose::Slides::PictureFillFormat::set_TileScaleX(float value) override
```

## Açıklamalar



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Şeklin resim dolgu biçimini alır
// Resim dolgu modunu Döşeme olarak ayarlar
// Doku için yatay ölçeği %120 olarak ayarlar
pictureFillFormat->set_TileScaleX(120.0f);
```

## Ayrıca Bakınız

* Sınıf [PictureFillFormat](../)
* Ad alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)