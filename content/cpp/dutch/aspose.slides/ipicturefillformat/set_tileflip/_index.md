---
title: set_TileFlip()
second_title: Aspose.Slides voor C++ API-referentie
description: "Draait de textuurtegel rond zijn horizontale, verticale of beide assen. Schrijf Slides::TileFlip."
type: docs
weight: 417
url: /nl/aspose.slides/ipicturefillformat/set_tileflip/
---
## IPictureFillFormat::set_TileFlip(Aspose::Slides::TileFlip) methode

Draait de textuurtegel rond zijn horizontale, verticale of beide assen. Schrijf [Slides::TileFlip](../../tileflip/).

```cpp
virtual void Aspose::Slides::IPictureFillFormat::set_TileFlip(Aspose::Slides::TileFlip value)=0
```

## Opmerkingen

Standaard is [TileFlip::NoFlip](../../tileflip/).

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Haalt het picture fill format van de shape op
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Stelt het picture fill mode in op Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Draait de textuurtegel rond zijn verticale as.
pictureFillFormat->set_TileFlip(TileFlip::FlipY);
}
```

## Zie ook

* Enum [TileFlip](../../tileflip/)
* Klasse [IPictureFillFormat](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)