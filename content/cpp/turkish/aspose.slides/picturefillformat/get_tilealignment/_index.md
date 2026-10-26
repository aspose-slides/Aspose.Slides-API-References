---
title: get_TileAlignment()
second_title: Aspose.Slides for C++ API Referansı
description: Doku şekil içinde nasıl hizalandığını döndürür. Bu ayar, doku deseninin başlangıç noktasını ve şekil boyunca nasıl tekrar ettiğini kontrol eder. Oku RectangleAlignment.
type: docs
weight: 378
url: /tr/aspose.slides/picturefillformat/get_tilealignment/
---
## PictureFillFormat::get_TileAlignment() metot


Doku şekil içinde nasıl hizalandığını döndürür. Bu ayar, doku deseninin başlangıç noktasını ve şekil boyunca nasıl tekrar ettiğini kontrol eder. Oku [RectangleAlignment](../../rectanglealignment/).

```cpp
RectangleAlignment Aspose::Slides::PictureFillFormat::get_TileAlignment() override
```

## Açıklamalar


Varsayılan [RectangleAlignment::TopLeft](../../rectanglealignment/). 


```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Şeklin resim doldurma formatını alır
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Resim doldurma modunu Tile olarak ayarlar
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Döşemenin hizalamasını sağ alt olarak ayarlar
pictureFillFormat->set_TileAlignment(RectangleAlignment::BottomRight);
```

## Ayrıca Bakınız

* Enum [RectangleAlignment](../../rectanglealignment/)
* Sınıf [PictureFillFormat](../)
* AdAlanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)