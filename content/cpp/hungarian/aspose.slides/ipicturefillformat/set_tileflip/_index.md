---
title: set_TileFlip()
second_title: Aspose.Slides C++ API hivatkozás
description: "A textúra csempét a vízszintes, függőleges vagy mindkét tengely körül fordítja. Írja Slides::TileFlip."
type: docs
weight: 417
url: /hu/aspose.slides/ipicturefillformat/set_tileflip/
---
## IPictureFillFormat::set_TileFlip(Aspose::Slides::TileFlip) metódus


A textúra csempét a vízszintes, függőleges vagy mindkét tengely körül fordítja. Írja [Slides::TileFlip](../../tileflip/).

```cpp
virtual void Aspose::Slides::IPictureFillFormat::set_TileFlip(Aspose::Slides::TileFlip value)=0
```

## Megjegyzések


Az alapértelmezett [TileFlip::NoFlip](../../tileflip/). 


```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Lekéri a forma kép kitöltési formátumát
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Beállítja a kép kitöltési módot Tile-re
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Megfordítja a textúra csempét a függőleges tengelye körül.
pictureFillFormat->set_TileFlip(TileFlip::FlipY);
}
```

## Lásd még

* Enum [TileFlip](../../tileflip/)
* Osztály [IPictureFillFormat](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)