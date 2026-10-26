---
title: get_TileFlip()
second_title: Aspose.Slides voor C++ API-referentie
description: "Draait de textuurtegel rond zijn horizontale, verticale of beide assen. Lees Slides::TileFlip."
type: docs
weight: 404
url: /nl/aspose.slides/picturefillformat/get_tileflip/
---
## PictureFillFormat::get_TileFlip() methode


Draait de textuurtegel rond zijn horizontale, verticale of beide assen. Lees [Slides::TileFlip](../../tileflip/).

```cpp
Aspose::Slides::TileFlip Aspose::Slides::PictureFillFormat::get_TileFlip() override
```

## Opmerkingen


Standaard is [TileFlip::NoFlip](../../tileflip/). 


```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Haalt het picture fill-formaat van de vorm op.
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Stelt de picture fill-modus in op Tile.
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Draait de textuurtegel rond zijn verticale as.
pictureFillFormat->set_TileFlip(TileFlip::FlipY);
```

## Zie ook

* Enumeratie [TileFlip](../../tileflip/)
* Klasse [PictureFillFormat](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)