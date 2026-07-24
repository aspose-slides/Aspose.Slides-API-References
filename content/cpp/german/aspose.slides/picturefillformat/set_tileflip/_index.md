---
title: set_TileFlip()
second_title: Aspose.Slides für C++ API Referenz
description: "Dreht die Texturkachel um ihre horizontale, vertikale oder beide Achsen. Schreiben Sie Slides::TileFlip."
type: docs
weight: 417
url: /de/aspose.slides/picturefillformat/set_tileflip/
---
## PictureFillFormat::set_TileFlip(Aspose::Slides::TileFlip) Methode

Dreht die Texturkachel um ihre horizontale, vertikale oder beide Achsen. Schreiben Sie [Slides::TileFlip](../../tileflip/).

```cpp
void Aspose::Slides::PictureFillFormat::set_TileFlip(Aspose::Slides::TileFlip value) override
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

// Dreht die Texturkachel um ihre vertikale Achse.
pictureFillFormat->set_TileFlip(TileFlip::FlipY);
```

## Siehe auch

* Enum [TileFlip](../../tileflip/)
* Klasse [PictureFillFormat](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)