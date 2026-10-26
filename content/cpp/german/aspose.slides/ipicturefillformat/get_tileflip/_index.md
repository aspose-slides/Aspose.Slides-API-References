---
title: get_TileFlip()
second_title: Aspose.Slides für C++ API-Referenz
description: "Spiegelt die Texturkachel um ihre horizontale, vertikale oder beide Achsen. Lesen Sie Slides::TileFlip."
type: docs
weight: 404
url: /de/aspose.slides/ipicturefillformat/get_tileflip/
---
## IPictureFillFormat::get_TileFlip() Methode


Spiegelt die Texturkachel um ihre horizontale, vertikale oder beide Achsen. Lesen Sie [Slides::TileFlip](../../tileflip/).

```cpp
virtual Aspose::Slides::TileFlip Aspose::Slides::IPictureFillFormat::get_TileFlip()=0
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

// Spiegelt die Texturkachel um die vertikale Achse.
pictureFillFormat->set_TileFlip(TileFlip::FlipY);
}
```

## Siehe auch

* Enum [TileFlip](../../tileflip/)
* Klasse [IPictureFillFormat](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)