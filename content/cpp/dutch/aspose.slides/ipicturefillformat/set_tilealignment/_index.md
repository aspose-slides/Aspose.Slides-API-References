---
title: set_TileAlignment()
second_title: Aspose.Slides voor C++ API-referentie
description: Stelt in hoe de textuur binnen de vorm is uitgelijnd. Deze instelling bepaalt het startpunt van het textuurpatroon en hoe het zich over de vorm herhaalt. Schrijf RectangleAlignment.
type: docs
weight: 391
url: /nl/aspose.slides/ipicturefillformat/set_tilealignment/
---
## IPictureFillFormat::set_TileAlignment(RectangleAlignment) methode


Stelt in hoe de textuur is uitgelijnd binnen de vorm. Deze instelling bepaalt het startpunt van het textuurpatroon en hoe het zich over de vorm herhaalt. Schrijf [RectangleAlignment](../../rectanglealignment/).

```cpp
virtual void Aspose::Slides::IPictureFillFormat::set_TileAlignment(RectangleAlignment value)=0
```

## Opmerkingen


Standaard is [RectangleAlignment::TopLeft](../../rectanglealignment/). 


```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Haalt het picture fill format van de vorm op
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Stelt de picture fill-modus in op Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Stelt de uitlijning voor het betegelen in op rechtsonder
pictureFillFormat->set_TileAlignment(RectangleAlignment::BottomRight);
```

## Zie ook

* Enum [RectangleAlignment](../../rectanglealignment/)
* Klasse [IPictureFillFormat](../)
* Naamruimte [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)