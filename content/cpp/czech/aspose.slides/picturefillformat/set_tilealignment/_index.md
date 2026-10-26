---
title: set_TileAlignment()
second_title: Aspose.Slides pro C++ - referenční příručka API
description: Nastavuje, jak je textura zarovnána uvnitř tvaru. Toto nastavení určuje výchozí bod vzoru textury a jak se opakuje po celém tvaru. Zapište RectangleAlignment.
type: docs
weight: 391
url: /cs/aspose.slides/picturefillformat/set_tilealignment/
---
## PictureFillFormat::set_TileAlignment(RectangleAlignment) metoda

Nastavuje, jak je textura zarovnána uvnitř tvaru. Toto nastavení určuje výchozí bod vzoru textury a jak se opakuje po celém tvaru. Zapište [RectangleAlignment](../../rectanglealignment/).

```cpp
void Aspose::Slides::PictureFillFormat::set_TileAlignment(RectangleAlignment value) override
```

## Poznámky

Výchozí hodnota je [RectangleAlignment::TopLeft](../../rectanglealignment/). 

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Získá formát vyplnění obrázkem tvaru
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Nastaví režim vyplnění obrázkem na Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Nastaví zarovnání pro dlaždicování na pravý dolní roh
pictureFillFormat->set_TileAlignment(RectangleAlignment::BottomRight);
```

## Viz také

* Enum [RectangleAlignment](../../rectanglealignment/)
* Třída [PictureFillFormat](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)