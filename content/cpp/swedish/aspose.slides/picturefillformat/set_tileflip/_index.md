---
title: set_TileFlip()
second_title: Aspose.Slides för C++ API-referens
description: "Vänder texturplattan kring dess horisontella, vertikala eller båda axlarna. Skriv Slides::TileFlip."
type: docs
weight: 417
url: /sv/aspose.slides/picturefillformat/set_tileflip/
---
## PictureFillFormat::set_TileFlip(Aspose::Slides::TileFlip) metod


Vänder texturplattan kring dess horisontella, vertikala eller båda axlarna. Skriv [Slides::TileFlip](../../tileflip/).

```cpp
void Aspose::Slides::PictureFillFormat::set_TileFlip(Aspose::Slides::TileFlip value) override
```

## Anmärkningar


Standard är [TileFlip::NoFlip](../../tileflip/). 


```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Hämtar bildfyllnadsformatet för formen
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Ställer in bildfyllnadsläget till Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Vänder texturplattan kring dess vertikala axel.
pictureFillFormat->set_TileFlip(TileFlip::FlipY);
```

## Se även

* Enum [TileFlip](../../tileflip/)
* Klass [PictureFillFormat](../)
* Namnrymd [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)