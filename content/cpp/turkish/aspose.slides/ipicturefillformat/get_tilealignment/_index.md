---
title: get_TileAlignment()
second_title: Aspose.Slides C++ için API Referansı
description: Doku şekil içinde nasıl hizalandığını döndürür. Bu ayar, doku deseninin başlangıç noktasını ve şekil boyunca nasıl tekrar ettiğini kontrol eder. RectangleAlignment'ı okuyun.
type: docs
weight: 378
url: /tr/aspose.slides/ipicturefillformat/get_tilealignment/
---
## IPictureFillFormat::get_TileAlignment() yöntemi

Doku şekil içinde nasıl hizalandığını döndürür. Bu ayar, doku deseninin başlangıç noktasını ve şekil boyunca nasıl tekrar ettiğini kontrol eder. Okuyun [RectangleAlignment](../../rectanglealignment/).

```cpp
virtual RectangleAlignment Aspose::Slides::IPictureFillFormat::get_TileAlignment()=0
```

## Açıklamalar

Varsayılan [RectangleAlignment::TopLeft](../../rectanglealignment/). 

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Şeklin resim doldurma biçimini alır
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Resim doldurma modunu Tile olarak ayarlar
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Döşemenin hizalamasını sağ alt olarak ayarlar
pictureFillFormat->set_TileAlignment(RectangleAlignment::BottomRight);
```

## Ayrıca

* Enum [RectangleAlignment](../../rectanglealignment/)
* Sınıf [IPictureFillFormat](../)
* AdAlanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)