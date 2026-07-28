---
title: set_TileOffsetY()
second_title: Aspose.Slides a C++ API hivatkozáshoz
description: Beállítja a textúra függőleges eltolását a forma kiindulási pontjától pontban. A pozitív érték lefelé mozgatja a textúrát, míg a negatív érték felfelé mozgatja. Írja float.
type: docs
weight: 313
url: /hu/aspose.slides/ipicturefillformat/set_tileoffsety/
---
## IPictureFillFormat::set_TileOffsetY(float) metódus


Beállítja a textúra függőleges eltolását a forma kiindulási pontjától pontban. A pozitív érték lefelé mozgatja a textúrát, míg a negatív érték felfelé mozgatja. Írja **float**.

```cpp
virtual void Aspose::Slides::IPictureFillFormat::set_TileOffsetY(float value)=0
```

## Megjegyzések



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Lekéri a forma képkitöltési formátumát
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Beállítja a képkitöltési módot Tile-re
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Beállítja a textúra függőleges eltolását -50 pontra
pictureFillFormat->set_TileOffsetY(-50.0f);
```

## Lásd még

* Osztály [IPictureFillFormat](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)