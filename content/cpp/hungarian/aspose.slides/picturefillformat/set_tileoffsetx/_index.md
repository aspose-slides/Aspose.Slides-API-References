---
title: set_TileOffsetX()
second_title: Aspose.Slides C++ API Referencia
description: Beállítja a textúra vízszintes eltolását a forma kiindulópontjától pontokban. A pozitív érték a textúrát jobbra mozgatja, a negatív pedig balra. Írja float.
type: docs
weight: 287
url: /hu/aspose.slides/picturefillformat/set_tileoffsetx/
---
## PictureFillFormat::set_TileOffsetX(float) metódus


Beállítja a textúra vízszintes eltolását a forma kiindulópontjától pontokban. A pozitív érték a textúrát jobbra mozgatja, a negatív érték pedig balra. Írja **float**.

```cpp
void Aspose::Slides::PictureFillFormat::set_TileOffsetX(float value) override
```

## Megjegyzések



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Lekéri a forma képti kitöltési formátumát
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Beállítja a picture fill módot Tile-re
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Beállítja a textúra vízszintes eltolását 20 pontra
pictureFillFormat->set_TileOffsetX(20.0f);
```

## Lásd még

* Osztály [PictureFillFormat](../)
* Névtere [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)