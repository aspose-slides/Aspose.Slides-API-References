---
title: set_TileScaleX()
second_title: Aspose.Slides için C++ API Referansı
description: Doku doldurması için yatay ölçeği yüzde olarak ayarlar. float yazın.
type: docs
weight: 339
url: /tr/aspose.slides/ipicturefillformat/set_tilescalex/
---
## IPictureFillFormat::set_TileScaleX(float) metod


Doku doldurması için yatay ölçeği yüzde olarak ayarlar. **float** yazın.

```cpp
virtual void Aspose::Slides::IPictureFillFormat::set_TileScaleX(float value)=0
```

## Açıklamalar



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Şeklin resim doldurma formatını alır
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Resim doldurma modunu Tile olarak ayarlar
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Doku için yatay ölçeği yüzde 120 olarak ayarlar
pictureFillFormat->set_TileScaleX(120.0f);
```

## İlgili

* Sınıf [IPictureFillFormat](../)
* İsim Alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)