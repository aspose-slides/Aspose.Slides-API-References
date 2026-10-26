---
title: set_TileOffsetY()
second_title: Aspose.Slides for C++ API Referansı
description: Dokunun şeklinin orijinal noktasından düşey kaymasını puan cinsinden ayarlar. Pozitif bir değer dokuyu aşağı kaydırırken, negatif bir değer yukarı kaydırır. float yazın.
type: docs
weight: 313
url: /tr/aspose.slides/ipicturefillformat/set_tileoffsety/
---
## IPictureFillFormat::set_TileOffsetY(float) yöntemi

Dokunun şeklinin orijinal noktasından düşey kaymasını puan cinsinden ayarlar. Pozitif bir değer dokuyu aşağı kaydırırken, negatif bir değer yukarı kaydırır. **float** yazın.

```cpp
virtual void Aspose::Slides::IPictureFillFormat::set_TileOffsetY(float value)=0
```

## Açıklamalar



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Şeklin resim doldurma biçimini alır
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Resim doldurma modunu Döşeme olarak ayarlar
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Dokunun düşey ofsetini -50 puan olarak ayarlar
pictureFillFormat->set_TileOffsetY(-50.0f);
```

## İlgili

* Sınıf [IPictureFillFormat](../)
* Ad alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)