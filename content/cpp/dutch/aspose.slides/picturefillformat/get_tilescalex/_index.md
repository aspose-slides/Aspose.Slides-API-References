---
title: get_TileScaleX()
second_title: Aspose.Slides voor C++ API-referentie
description: Retourneert de horizontale schaal voor de textuurvulling als een percentage. Lezen float.
type: docs
weight: 326
url: /nl/aspose.slides/picturefillformat/get_tilescalex/
---
## PictureFillFormat::get_TileScaleX() methode


Retourneert de horizontale schaal voor de textuurvulling als een percentage. Lezen **float**.

```cpp
float Aspose::Slides::PictureFillFormat::get_TileScaleX() override
```

## Opmerkingen



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Haalt de picture fill format van de shape op
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Stelt de picture fill mode in op Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Stelt de horizontale schaal voor de textuur in op 120 procent
pictureFillFormat->set_TileScaleX(120.0f);
```

## Zie ook

* Klasse [PictureFillFormat](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)