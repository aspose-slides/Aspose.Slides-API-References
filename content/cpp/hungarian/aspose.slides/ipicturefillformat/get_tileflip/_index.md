---
title: get_TileFlip()
second_title: Aspose.Slides C++ API referencia
description: "A textúra csempét a vízszintes, függőleges vagy mindkét tengely körül fordítja. Olvassa el Slides::TileFlip."
type: docs
weight: 404
url: /hu/aspose.slides/ipicturefillformat/get_tileflip/
---
## IPictureFillFormat::get_TileFlip() metódus


A textúra csempét a vízszintes, függőleges vagy mindkét tengely körül forgatja. Olvassa el [Slides::TileFlip](../../tileflip/).

```cpp
virtual Aspose::Slides::TileFlip Aspose::Slides::IPictureFillFormat::get_TileFlip()=0
```

## Megjegyzés


Az alapértelmezett [TileFlip::NoFlip](../../tileflip/). 


```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// A forma kép kitöltési formátumát lekéri
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Beállítja a kép kitöltési módját Tile-re
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// A textúra csempét a függőleges tengely körül tükrözi.
pictureFillFormat->set_TileFlip(TileFlip::FlipY);
}
```

## Lásd még

* Enum [TileFlip](../../tileflip/)
* Osztály [IPictureFillFormat](../)
* Névtér [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)