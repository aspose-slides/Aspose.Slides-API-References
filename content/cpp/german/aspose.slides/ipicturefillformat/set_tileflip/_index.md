---
title: set_TileFlip()
second_title: Aspose.Slides für C++ API-Referenz
description: "Spiegelt die Texturkachel um ihre horizontale, vertikale oder beide Achsen. Schreiben Slides::TileFlip."
type: docs
weight: 417
url: /de/aspose.slides/ipicturefillformat/set_tileflip/
---
## IPictureFillFormat::set_TileFlip(Aspose::Slides::TileFlip) Methode


Spiegelt die Texturkachel um ihre horizontale, vertikale oder beide Achsen. Schreiben [Slides::TileFlip](../../tileflip/).

```cpp
virtual void Aspose::Slides::IPictureFillFormat::set_TileFlip(Aspose::Slides::TileFlip value)=0
```

## Anmerkungen


Standard ist [TileFlip::NoFlip](../../tileflip/). 


```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Ermittelt das Bildfüllformat der Form
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Setzt den Bildfüllmodus auf Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Spiegelt die Texturkachel um ihre vertikale Achse.
pictureFillFormat->set_TileFlip(TileFlip::FlipY);
}
```

## Siehe auch

* Enum [TileFlip](../../tileflip/)
* Class [IPictureFillFormat](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)