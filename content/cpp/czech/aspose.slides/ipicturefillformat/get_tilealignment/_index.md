---
title: get_TileAlignment()
second_title: Aspose.Slides pro C++ API Reference
description: Vrací, jak je textura zarovnaná uvnitř tvaru. Toto nastavení určuje počáteční bod vzoru textury a jak se opakuje po celém tvaru. Přečtěte si RectangleAlignment.
type: docs
weight: 378
url: /cs/aspose.slides/ipicturefillformat/get_tilealignment/
---
## IPictureFillFormat::get_TileAlignment() metoda

Vrací, jak je textura zarovnaná uvnitř tvaru. Toto nastavení určuje počáteční bod vzoru textury a jak se opakuje po celém tvaru. Přečtěte si [RectangleAlignment](../../rectanglealignment/).

```cpp
virtual RectangleAlignment Aspose::Slides::IPictureFillFormat::get_TileAlignment()=0
```

## Poznámky

Výchozí hodnota je [RectangleAlignment::TopLeft](../../rectanglealignment/). 

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Získá formát výplně obrázkem tvaru
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Nastaví režim výplně obrázkem na Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Nastaví zarovnání pro dlaždicování na pravý dolní roh
pictureFillFormat->set_TileAlignment(RectangleAlignment::BottomRight);
```

## Viz také

* Enum [RectangleAlignment](../../rectanglealignment/)
* Třída [IPictureFillFormat](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)