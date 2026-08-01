---
title: get_TileScaleY()
second_title: Aspose.Slides voor C++ API Referentie
description: Retourneert de verticale schaal voor de textuurvulling als percentage. Lees float.
type: docs
weight: 352
url: /nl/aspose.slides/picturefillformat/get_tilescaley/
---
## PictureFillFormat::get_TileScaleY() methode


Retourneert de verticale schaal voor de textuurvulling als percentage. Lees **float**.

```cpp
float Aspose::Slides::PictureFillFormat::get_TileScaleY() override
```

## Opmerkingen



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Haalt het picture fill formaat van de vorm op
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Stelt de picture fill-modus in op Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Stelt de verticale schaal voor de textuur in op 120 procent
pictureFillFormat->set_TileScaleY(120.0f);
```

## Zie ook

* Klasse [PictureFillFormat](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)