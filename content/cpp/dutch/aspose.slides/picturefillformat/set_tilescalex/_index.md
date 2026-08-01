---
title: set_TileScaleX()
second_title: Aspose.Slides voor C++ API-referentie
description: Stelt de horizontale schaal voor de textuurvulling in als een percentage. Schrijf float.
type: docs
weight: 339
url: /nl/aspose.slides/picturefillformat/set_tilescalex/
---
## PictureFillFormat::set_TileScaleX(float) methode


Stelt de horizontale schaal voor de textuurvulling in als een percentage. Schrijf **float**.

```cpp
void Aspose::Slides::PictureFillFormat::set_TileScaleX(float value) override
```

## Opmerkingen



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Haalt het picture fill format van de shape op
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Stelt de picture fill modus in op Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Stelt de horizontale schaal voor de texture in op 120 procent
pictureFillFormat->set_TileScaleX(120.0f);
```

## Zie ook

* Klasse [PictureFillFormat](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)