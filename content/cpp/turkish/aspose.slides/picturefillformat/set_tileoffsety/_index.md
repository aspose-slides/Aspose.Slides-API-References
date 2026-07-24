---
title: set_TileOffsetY()
second_title: Aspose.Slides for C++ API Referansı
description: Doku'nun şeklin kökeninden nokta biriminde düşey offset'ini ayarlar. Pozitif bir değer dokuyu aşağı kaydırırken, negatif bir değer yukarı kaydırır. float yazın.
type: docs
weight: 313
url: /tr/aspose.slides/picturefillformat/set_tileoffsety/
---
## PictureFillFormat::set_TileOffsetY(float) metodu


Doku'nun şeklin kökeninden düşey offset'ini nokta biriminde ayarlar. Pozitif bir değer dokuyu aşağı kaydırırken, negatif bir değer yukarı kaydırır. **float** yazın.

```cpp
void Aspose::Slides::PictureFillFormat::set_TileOffsetY(float value) override
```

## Açıklamalar



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Şeklin resim doldurma biçimini alır
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Resim doldurma modunu Tile olarak ayarlar
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Doku'nun düşey offset'ini -50 nokta olarak ayarlar
pictureFillFormat->set_TileOffsetY(-50.0f);
```

## Diğer Bağlantılar

* Sınıf [PictureFillFormat](../)
* Ad alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)