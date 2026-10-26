---
title: set_TileFlip()
second_title: Aspose.Slides för C++ API-referens
description: "Vänder texturbrickan runt dess horisontella, vertikala eller båda axlar. Skriv Slides::TileFlip."
type: docs
weight: 417
url: /sv/aspose.slides/ipicturefillformat/set_tileflip/
---
## IPictureFillFormat::set_TileFlip(Aspose::Slides::TileFlip) metod


Vänder texturbrickan runt dess horisontella, vertikala eller båda axlarna. Skriv [Slides::TileFlip](../../tileflip/).

```cpp
virtual void Aspose::Slides::IPictureFillFormat::set_TileFlip(Aspose::Slides::TileFlip value)=0
```

## Anmärkningar


Standard är [TileFlip::NoFlip](../../tileflip/). 


```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Hämtar bildfyllningsformatet för formen
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Ställer in bildfyllningsläget till Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Vänder texturbrickan runt dess vertikala axel.
pictureFillFormat->set_TileFlip(TileFlip::FlipY);
}
```

## Se också

* Enum [TileFlip](../../tileflip/)
* Klass [IPictureFillFormat](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)