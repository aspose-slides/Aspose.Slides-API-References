---
title: get_TileOffsetY()
second_title: Aspose.Slides C++ API referencia
description: Visszaadja a textúra függőleges eltolását a forma kiindulópontjától pontban. A pozitív érték lefelé, a negatív érték felfelé mozgatja a textúrát. Olvas float.
type: docs
weight: 300
url: /hu/aspose.slides/picturefillformat/get_tileoffsety/
---
## PictureFillFormat::get_TileOffsetY() módszer


Visszaadja a textúra függőleges eltolását a forma kiindulópontjából pontban. A pozitív érték lefelé, a negatív érték felfelé mozgatja a textúrát. Olvas **float**.

```cpp
float Aspose::Slides::PictureFillFormat::get_TileOffsetY() override
```

## Megjegyzések



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Lekéri a forma kép kitöltési formátumát
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Beállítja a kép kitöltési módot Tile-re
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Beállítja a textúra függőleges eltolását -50 pontban
pictureFillFormat->set_TileOffsetY(-50.0f);
```

## Lásd még

* Osztály [PictureFillFormat](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)