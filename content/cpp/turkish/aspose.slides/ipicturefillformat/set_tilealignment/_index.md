---
title: set_TileAlignment()
second_title: Aspose.Slides için C++ API Referansı
description: Doku şekil içinde nasıl hizalanacağını ayarlar. Bu ayar, doku deseninin başlangıç noktasını ve şekil boyunca nasıl tekrarlanacağını kontrol eder. RectangleAlignment yazın.
type: docs
weight: 391
url: /tr/aspose.slides/ipicturefillformat/set_tilealignment/
---
## IPictureFillFormat::set_TileAlignment(RectangleAlignment) method


Desenin içinde dokunun nasıl hizalanacağını ayarlar. Bu ayar, doku deseninin başlangıç noktasını ve şekil boyunca nasıl tekrarlanacağını kontrol eder. [RectangleAlignment](../../rectanglealignment/) yazın.

```cpp
virtual void Aspose::Slides::IPictureFillFormat::set_TileAlignment(RectangleAlignment value)=0
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

## Diğer

* Enum [RectangleAlignment](../../rectanglealignment/)
* Sınıf [IPictureFillFormat](../)
* İsim alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)