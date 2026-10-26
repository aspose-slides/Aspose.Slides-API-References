---
title: get_TileOffsetX()
second_title: Aspose.Slides voor C++ API-referentie
description: Retourneert de horizontale offset van de textuur ten opzichte van de oorsprong van de vorm in punten. Een positieve waarde verplaatst de textuur naar rechts, terwijl een negatieve waarde deze naar links verplaatst. Lees float.
type: docs
weight: 274
url: /nl/aspose.slides/ipicturefillformat/get_tileoffsetx/
---
## IPictureFillFormat::get_TileOffsetX() methode


Retourneert de horizontale offset van de textuur ten opzichte van de oorsprong van de vorm in punten. Een positieve waarde verplaatst de textuur naar rechts, terwijl een negatieve waarde deze naar links verplaatst. Lezen **float**.

```cpp
virtual float Aspose::Slides::IPictureFillFormat::get_TileOffsetX()=0
```

## Opmerkingen


```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Haalt het picture fill format van de shape op
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Stelt de picture fill mode in op Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Stelt de horizontale offset van de textuur in op 20 punten
pictureFillFormat->set_TileOffsetX(20.0f);
```

## Zie ook
* Klasse [IPictureFillFormat](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)