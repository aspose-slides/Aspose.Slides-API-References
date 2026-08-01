---
title: set_TileScaleX()
second_title: Aspose.Slides voor C++ API-referentie
description: Stelt de horizontale schaal voor de textuurvulling in als een percentage. Schrijf float.
type: docs
weight: 339
url: /nl/aspose.slides/ipicturefillformat/set_tilescalex/
---
## IPictureFillFormat::set_TileScaleX(float) methode


Stelt de horizontale schaal voor de textuurvulling in als een percentage. Schrijf **float**.

```cpp
virtual void Aspose::Slides::IPictureFillFormat::set_TileScaleX(float value)=0
```

## Opmerkingen



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Haalt het picture fill format van de vorm op
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Stelt de picture fill mode in op Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Stelt de horizontale schaal voor de texture in op 120 procent
pictureFillFormat->set_TileScaleX(120.0f);
```

## Zie ook

* Klasse [IPictureFillFormat](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)