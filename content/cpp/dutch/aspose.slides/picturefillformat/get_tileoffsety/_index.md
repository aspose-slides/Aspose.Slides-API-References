---
title: get_TileOffsetY()
second_title: Aspose.Slides voor C++ API-referentie
description: Retourneert de verticale verschuiving van de textuur ten opzichte van de oorsprong van de vorm in punten. Een positieve waarde verplaatst de textuur naar beneden, terwijl een negatieve waarde deze naar boven verplaatst. Lees float.
type: docs
weight: 300
url: /nl/aspose.slides/picturefillformat/get_tileoffsety/
---
## PictureFillFormat::get_TileOffsetY() methode

Retourneert de verticale verschuiving van de textuur ten opzichte van de oorsprong van de vorm in punten. Een positieve waarde verplaatst de textuur naar beneden, terwijl een negatieve waarde deze naar boven verplaatst. Lees **float**.

```cpp
float Aspose::Slides::PictureFillFormat::get_TileOffsetY() override
```

## Opmerkingen

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Haalt het picture fill-formaat van de vorm op
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Stelt de picture fill-modus in op Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Stelt de verticale verschuiving van de textuur in op -50 punten
pictureFillFormat->set_TileOffsetY(-50.0f);
```

## Zie ook

* Klasse [PictureFillFormat](../)
* Namespace [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)