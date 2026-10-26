---
title: set_TileOffsetY()
second_title: Aspose.Slides voor C++ API-referentie
description: Stelt de verticale offset van de textuur ten opzichte van de oorsprong van de vorm in punten in. Een positieve waarde verplaatst de textuur naar beneden, terwijl een negatieve waarde hem omhoog verplaatst. Schrijf float.
type: docs
weight: 313
url: /nl/aspose.slides/ipicturefillformat/set_tileoffsety/
---
## IPictureFillFormat::set_TileOffsetY(float) methode

Stelt de verticale offset van de textuur ten opzichte van de oorsprong van de vorm in punten in. Een positieve waarde verplaatst de textuur naar beneden, terwijl een negatieve waarde hem omhoog verplaatst. Schrijf **float**.

```cpp
virtual void Aspose::Slides::IPictureFillFormat::set_TileOffsetY(float value)=0
```

## Opmerkingen



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Haalt het picture fill format van de shape op
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Stelt de picture fill mode in op Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Stelt de verticale offset van de texture in op -50 punten
pictureFillFormat->set_TileOffsetY(-50.0f);
```

## Zie ook

* Klasse [IPictureFillFormat](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)