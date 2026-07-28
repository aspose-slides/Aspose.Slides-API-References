---
title: get_TileOffsetX()
second_title: Aspose.Slides C++ API-referencia
description: Visszaadja a textúra vízszintes eltolását a forma kiindulási pontjából pontokban. A pozitív érték a textúrát jobbra mozgatja, míg a negatív érték balra. Olvas float.
type: docs
weight: 274
url: /hu/aspose.slides/ipicturefillformat/get_tileoffsetx/
---
## IPictureFillFormat::get_TileOffsetX() method


A visszatérési érték a textúra vízszintes eltolása a forma kiindulási pontjából pontban. A pozitív érték a textúrát jobbra, a negatív érték balra mozgatja. Olvas **float**.

```cpp
virtual float Aspose::Slides::IPictureFillFormat::get_TileOffsetX()=0
```

## Megjegyzés



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// A forma kép kitöltési formátumát kapja
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// A kép kitöltési módját Tile-re állítja
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// A textúra vízszintes eltolását 20 pontra állítja
pictureFillFormat->set_TileOffsetX(20.0f);
```

## Lásd még

* Osztály [IPictureFillFormat](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)