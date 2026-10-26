---
title: get_TileOffsetX()
second_title: Aspose.Slides C++ API hivatkozás
description: Visszaadja a textúra vízszintes eltolását a shape eredetétől pontokban. A pozitív érték jobbra mozgatja a textúrát, a negatív érték balra. Olvasás float.
type: docs
weight: 274
url: /hu/aspose.slides/picturefillformat/get_tileoffsetx/
---
## PictureFillFormat::get_TileOffsetX() metódus


Visszaadja a textúra vízszintes eltolását a shape eredetétől pontokban. A pozitív érték jobbra mozgatja a textúrát, a negatív érték balra. Olvasás **float**.

```cpp
float Aspose::Slides::PictureFillFormat::get_TileOffsetX() override
```

## Megjegyzések



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Lekéri a shape kép kitöltési formátumát
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Beállítja a kép kitöltési módot Tile-re
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Beállítja a textúra vízszintes eltolását 20 pontra
pictureFillFormat->set_TileOffsetX(20.0f);
```

## Lásd még

* Osztály [PictureFillFormat](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)