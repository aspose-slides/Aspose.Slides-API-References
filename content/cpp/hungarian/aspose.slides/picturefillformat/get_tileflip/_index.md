---
title: get_TileFlip()
second_title: Aspose.Slides C++ API hivatkozás
description: "Megfordítja a textúra csempét a vízszintes, függőleges vagy mindkét tengely körül. Olvassa el a Slides::TileFlip-et."
type: docs
weight: 404
url: /hu/aspose.slides/picturefillformat/get_tileflip/
---
## PictureFillFormat::get_TileFlip() metódus


Megfordítja a textúra csempét a vízszintes, függőleges vagy mindkét tengely körül. Olvassa el [Slides::TileFlip](../../tileflip/).

```cpp
Aspose::Slides::TileFlip Aspose::Slides::PictureFillFormat::get_TileFlip() override
```

## Megjegyzések


Az alapértelmezett érték [TileFlip::NoFlip](../../tileflip/). 


```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Lekéri a forma képkitöltési formátumát
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Beállítja a képkitöltési módot Tile-re
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Megfordítja a textúra csempét a függőleges tengely körül.
pictureFillFormat->set_TileFlip(TileFlip::FlipY);
```

## Lásd még

* Enum [TileFlip](../../tileflip/)
* Osztály [PictureFillFormat](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)