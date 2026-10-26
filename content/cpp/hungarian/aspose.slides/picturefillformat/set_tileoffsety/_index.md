---
title: set_TileOffsetY()
second_title: Aspose.Slides C++ API Referencia
description: Beállítja a textúra függőleges eltolását az alakzat kiindulópontjától pontokban. A pozitív érték lefelé mozgatja a textúrát, míg a negatív érték felfelé mozgatja. Írja float.
type: docs
weight: 313
url: /hu/aspose.slides/picturefillformat/set_tileoffsety/
---
## PictureFillFormat::set_TileOffsetY(float) metódus

Beállítja a textúra függőleges eltolását az alakzat kiindulópontjából pontokban. A pozitív érték lefelé mozgatja a textúrát, míg a negatív érték felfelé mozgatja. Írja **float**.

```cpp
void Aspose::Slides::PictureFillFormat::set_TileOffsetY(float value) override
```

## Megjegyzések



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Lekéri a forma kép kitöltési formátumát
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// A kép kitöltési módot Tile-re állítja
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// A textúra függőleges eltolását -50 pontra állítja
pictureFillFormat->set_TileOffsetY(-50.0f);
```

## Lásd még

* Osztály [PictureFillFormat](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)