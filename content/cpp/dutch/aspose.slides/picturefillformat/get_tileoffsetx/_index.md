---
title: get_TileOffsetX()
second_title: Aspose.Slides voor C++ API Referentie
description: Retourneert de horizontale offset van de textuur vanaf de oorsprong van de vorm in punten. Een positieve waarde verschuift de textuur naar rechts, terwijl een negatieve waarde deze naar links verschuift. Lees float.
type: docs
weight: 274
url: /nl/aspose.slides/picturefillformat/get_tileoffsetx/
---
## PictureFillFormat::get_TileOffsetX() methode

Retourneert de horizontale offset van de textuur vanaf de oorsprong van de vorm in punten. Een positieve waarde verschuift de textuur naar rechts, terwijl een negatieve waarde deze naar links verschuift. Lezen **float**.

```cpp
float Aspose::Slides::PictureFillFormat::get_TileOffsetX() override
```

## Opmerkingen



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Haalt het picture fill-formaat van de vorm op
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Stelt de picture fill-modus in op Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Stelt de horizontale offset van de textuur in op 20 punten
pictureFillFormat->set_TileOffsetX(20.0f);
```

## Zie ook

* Klasse [PictureFillFormat](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)