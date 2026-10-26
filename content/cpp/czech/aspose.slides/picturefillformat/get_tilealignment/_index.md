---
title: get_TileAlignment()
second_title: Aspose.Slides pro C++ – reference API
description: Vrací, jak je textura zarovnána uvnitř tvaru. Toto nastavení řídí počáteční bod vzoru textury a to, jak se opakuje po celém tvaru. Přečtěte si RectangleAlignment.
type: docs
weight: 378
url: /cs/aspose.slides/picturefillformat/get_tilealignment/
---
## PictureFillFormat::get_TileAlignment() metoda


Vrací, jak je textura zarovnána uvnitř tvaru. Toto nastavení řídí počáteční bod vzoru textury a to, jak se opakuje po celém tvaru. Přečtěte si [RectangleAlignment](../../rectanglealignment/).

```cpp
RectangleAlignment Aspose::Slides::PictureFillFormat::get_TileAlignment() override
```

## Poznámky


Výchozí je [RectangleAlignment::TopLeft](../../rectanglealignment/). 


```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Získá formát výplně obrázkem tvaru
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Nastaví režim výplně obrázkem na Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Nastaví zarovnání dlaždic na pravý dolní roh
pictureFillFormat->set_TileAlignment(RectangleAlignment::BottomRight);
```

## Viz také

* Enum [RectangleAlignment](../../rectanglealignment/)
* třída [PictureFillFormat](../)
* jmenný prostor [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)