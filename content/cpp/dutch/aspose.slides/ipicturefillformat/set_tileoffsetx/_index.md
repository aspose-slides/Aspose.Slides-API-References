---
title: set_TileOffsetX()
second_title: Aspose.Slides voor C++ API-referentie
description: Stelt de horizontale offset van de textuur vanaf de oorsprong van de vorm in punten in. Een positieve waarde verplaatst de textuur naar rechts, terwijl een negatieve waarde deze naar links verplaatst. Schrijf float.
type: docs
weight: 287
url: /nl/aspose.slides/ipicturefillformat/set_tileoffsetx/
---
## IPictureFillFormat::set_TileOffsetX(float) methode

Stelt de horizontale offset van de textuur ten opzichte van de oorsprong van de vorm in punten in. Een positieve waarde verplaatst de textuur naar rechts, terwijl een negatieve waarde deze naar links verplaatst. Schrijf **float**.

```cpp
virtual void Aspose::Slides::IPictureFillFormat::set_TileOffsetX(float value)=0
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
* Library [Aspose.Slides](../../../)