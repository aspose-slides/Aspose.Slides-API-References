---
title: get_TileFlip()
second_title: Aspose.Slides för C++ API-referens
description: "Vänder texturbrickan runt dess horisontella, vertikala eller båda axlarna. Läs Slides::TileFlip."
type: docs
weight: 404
url: /sv/aspose.slides/picturefillformat/get_tileflip/
---
## PictureFillFormat::get_TileFlip() metod


Vänder texturbrickan runt dess horisontella, vertikala eller båda axlarna. Läs [Slides::TileFlip](../../tileflip/).

```cpp
Aspose::Slides::TileFlip Aspose::Slides::PictureFillFormat::get_TileFlip() override
```

## Anmärkningar


Standard är [TileFlip::NoFlip](../../tileflip/). 


```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Hämtar bildfyllningsformatet för formen
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Ställer in picture fill-läget till Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Vänder texturbrickan runt dess vertikala axel.
pictureFillFormat->set_TileFlip(TileFlip::FlipY);
```

## Se även

* Enum [TileFlip](../../tileflip/)
* Klass [PictureFillFormat](../)
* Namnrymd [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)