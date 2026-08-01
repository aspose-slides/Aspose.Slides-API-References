---
title: get_TileAlignment()
second_title: Aspose.Slides voor C++ API-referentie
description: Retourneert hoe de textuur is uitgelijnd binnen de vorm. Deze instelling regelt het startpunt van het textuurpatroon en hoe het zich herhaalt over de vorm. Lees RectangleAlignment.
type: docs
weight: 378
url: /nl/aspose.slides/ipicturefillformat/get_tilealignment/
---
## IPictureFillFormat::get_TileAlignment() methode


Retourneert hoe de textuur is uitgelijnd binnen de vorm. Deze instelling regelt het startpunt van het textuurpatroon en hoe het zich herhaalt over de vorm. Lees [RectangleAlignment](../../rectanglealignment/).

```cpp
virtual RectangleAlignment Aspose::Slides::IPictureFillFormat::get_TileAlignment()=0
```

## Opmerkingen


Standaard is [RectangleAlignment::TopLeft](../../rectanglealignment/). 


```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Haalt het picture fill-formaat van de vorm op
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Stelt de picture fill-modus in op Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Stelt de uitlijning voor de tegelzetting in op rechtsonder
pictureFillFormat->set_TileAlignment(RectangleAlignment::BottomRight);
```

## Zie ook

* Enum [RectangleAlignment](../../rectanglealignment/)
* Klasse [IPictureFillFormat](../)
* Namespace [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)