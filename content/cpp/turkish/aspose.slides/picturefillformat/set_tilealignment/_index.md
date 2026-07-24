---
title: set_TileAlignment()
second_title: Aspose.Slides için C++ API Referansı
description: Doku şekil içinde nasıl hizalanacağını ayarlar. Bu ayar, doku deseninin başlangıç noktasını ve şekil boyunca nasıl tekrar ettiğini kontrol eder. RectangleAlignment yazın.
type: docs
weight: 391
url: /tr/aspose.slides/picturefillformat/set_tilealignment/
---
## PictureFillFormat::set_TileAlignment(RectangleAlignment) yöntemi

Doku şekil içinde nasıl hizalanacağını ayarlar. Bu ayar, doku deseninin başlangıç noktasını ve şekil boyunca nasıl tekrar ettiğini kontrol eder. Yaz [RectangleAlignment](../../rectanglealignment/).

```cpp
void Aspose::Slides::PictureFillFormat::set_TileAlignment(RectangleAlignment value) override
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

// Döşemenin hizalamasını sağ alt köşeye ayarlar
pictureFillFormat->set_TileAlignment(RectangleAlignment::BottomRight);
```

## Ayrıca Bakınız

* Enum [RectangleAlignment](../../rectanglealignment/)
* Sınıf [PictureFillFormat](../)
* Ad alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)