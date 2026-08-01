---
title: get_TileAlignment()
second_title: Aspose.Slides voor C++ API Referentie
description: Geeft terug hoe de textuur is uitgelijnd binnen de vorm. Deze instelling bepaalt het startpunt van het textuurpatroon en hoe het zich herhaalt over de vorm. Lees RectangleAlignment.
type: docs
weight: 378
url: /nl/aspose.slides/picturefillformat/get_tilealignment/
---
## PictureFillFormat::get_TileAlignment() methode


Geeft terug hoe de textuur is uitgelijnd binnen de vorm. Deze instelling bepaalt het startpunt van het textuurpatroon en hoe het zich herhaalt over de vorm. Lees [RectangleAlignment](../../rectanglealignment/).

```cpp
RectangleAlignment Aspose::Slides::PictureFillFormat::get_TileAlignment() override
```

## Opmerkingen


Standaard is [RectangleAlignment::TopLeft](../../rectanglealignment/). 


```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Haalt het picture fill format van de vorm op
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Stelt de picture fill mode in op Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Stelt de uitlijning voor de tiling in op rechtsonder
pictureFillFormat->set_TileAlignment(RectangleAlignment::BottomRight);
```

## Zie ook

* Enum [RectangleAlignment](../../rectanglealignment/)
* Klasse [PictureFillFormat](../)
* Naamruimte [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)