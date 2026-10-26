---
title: set_TileFlip()
second_title: Aspose.Slides C++ API Referenciája
description: "Megfordítja a textúra csempét a vízszintes, függőleges vagy mindkét tengely mentén. Írja Slides::TileFlip."
type: docs
weight: 417
url: /hu/aspose.slides/picturefillformat/set_tileflip/
---
## PictureFillFormat::set_TileFlip(Aspose::Slides::TileFlip) metódus


Megfordítja a textúra csempét a vízszintes, függőleges vagy mindkét tengely mentén. Írja [Slides::TileFlip](../../tileflip/).

```cpp
void Aspose::Slides::PictureFillFormat::set_TileFlip(Aspose::Slides::TileFlip value) override
```

## Megjegyzések


Az alapértelmezett [TileFlip::NoFlip](../../tileflip/). 


```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Lekéri a forma kép kitöltési formátumát
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Beállítja a kép kitöltési módot Csempe
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Megfordítja a textúra csempét a függőleges tengely körül.
pictureFillFormat->set_TileFlip(TileFlip::FlipY);
```

## Lásd még

* Enum [TileFlip](../../tileflip/)
* Osztály [PictureFillFormat](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)