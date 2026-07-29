---
title: get_TileFlip()
second_title: Aspose.Slides för C++ API-referens
description: "Vänder texturplattan runt dess horisontella, vertikala eller båda axlar. Läs Slides::TileFlip."
type: docs
weight: 404
url: /sv/aspose.slides/ipicturefillformat/get_tileflip/
---
## IPictureFillFormat::get_TileFlip() metod

Vänder texturplattan runt dess horisontella, vertikala eller båda axlarna. Läs [Slides::TileFlip](../../tileflip/).

```cpp
virtual Aspose::Slides::TileFlip Aspose::Slides::IPictureFillFormat::get_TileFlip()=0
```

## Anmärkningar

Standard är [TileFlip::NoFlip](../../tileflip/).

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Hämtar bildfyllnadsformatet för formen
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Sätter bildfyllnadsläget till Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Vänder texturplattan runt dess vertikala axel.
pictureFillFormat->set_TileFlip(TileFlip::FlipY);
}
```

## Se även

* Enum [TileFlip](../../tileflip/)
* Klass [IPictureFillFormat](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)