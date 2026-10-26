---
title: set_TileOffsetX()
second_title: Aspose.Slides C++ API referenciája
description: Beállítja a textúra vízszintes eltolását a forma kiindulási pontjától pontban. A pozitív érték jobbra, a negatív érték balra mozgatja a textúrát. Írja float.
type: docs
weight: 287
url: /hu/aspose.slides/ipicturefillformat/set_tileoffsetx/
---
## IPictureFillFormat::set_TileOffsetX(float) metódus

A textúra vízszintes eltolását állítja be a forma kiindulási pontjától pontban. A pozitív érték jobbra, a negatív érték balra mozgatja a textúrát. Írja **float**.

```cpp
virtual void Aspose::Slides::IPictureFillFormat::set_TileOffsetX(float value)=0
```

## Megjegyzések



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Lekéri a forma kép kitöltésének formátumát
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Beállítja a kép kitöltési módot Tile-re
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Beállítja a textúra vízszintes eltolását 20 pontra
pictureFillFormat->set_TileOffsetX(20.0f);
```

## Lásd még

* Osztály [IPictureFillFormat](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)