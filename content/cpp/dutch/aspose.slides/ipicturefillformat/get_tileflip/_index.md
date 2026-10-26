---
title: get_TileFlip()
second_title: Aspose.Slides voor C++ API Referentie
description: "Draait de textuurtegel rond zijn horizontale, verticale of beide assen. Lees Slides::TileFlip."
type: docs
weight: 404
url: /nl/aspose.slides/ipicturefillformat/get_tileflip/
---
## IPictureFillFormat::get_TileFlip() methode

Draait de textuurtegel rond zijn horizontale, verticale of beide assen. Lees [Slides::TileFlip](../../tileflip/).

```cpp
virtual Aspose::Slides::TileFlip Aspose::Slides::IPictureFillFormat::get_TileFlip()=0
```

## Opmerkingen

Standaard is [TileFlip::NoFlip](../../tileflip/). 

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Haalt de picture fill format van de shape op
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Stelt de picture fill mode in op Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Draait de textuurtegel rond zijn verticale as.
pictureFillFormat->set_TileFlip(TileFlip::FlipY);
}
```

## Zie ook

* Enum [TileFlip](../../tileflip/)
* Class [IPictureFillFormat](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)