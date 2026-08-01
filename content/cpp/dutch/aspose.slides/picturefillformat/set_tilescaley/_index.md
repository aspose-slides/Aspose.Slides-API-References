---
title: set_TileScaleY()
second_title: Aspose.Slides voor C++ API-referentie
description: Stelt de verticale schaal van de textuurvulling in als een percentage. Schrijf float.
type: docs
weight: 365
url: /nl/aspose.slides/picturefillformat/set_tilescaley/
---
## PictureFillFormat::set_TileScaleY(float) methode


Stelt de verticale schaal van de textuurvulling in als een percentage. Schrijf **float**.

```cpp
void Aspose::Slides::PictureFillFormat::set_TileScaleY(float value) override
```

## Opmerkingen



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Haalt het picture fill-formaat van de shape op
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