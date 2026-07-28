---
title: set_TileAlignment()
second_title: Aspose.Slides C++ API-referencia
description: Beállítja, hogyan van igazítva a textúra az alakzatban. Ez a beállítás szabályozza a textúraminta kiindulópontját és azt, hogyan ismétlődik az alakzatban. Írja be RectangleAlignment.
type: docs
weight: 391
url: /hu/aspose.slides/ipicturefillformat/set_tilealignment/
---
## IPictureFillFormat::set_TileAlignment(RectangleAlignment) metódus


Beállítja, hogyan van igazítva a textúra az alakzatban. Ez a beállítás a textúraminta kiindulópontját és azt szabályozza, hogy a minta hogyan ismétlődik az alakzatban. Írja be [RectangleAlignment](../../rectanglealignment/).

```cpp
virtual void Aspose::Slides::IPictureFillFormat::set_TileAlignment(RectangleAlignment value)=0
```

## Megjegyzések


Az alapértelmezett [RectangleAlignment::TopLeft](../../rectanglealignment/). 


```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Lekéri az alakzat képkitöltési formátumát
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Beállítja a képkitöltés módját Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Beállítja a csempezés igazítását jobb alsó sarokba
pictureFillFormat->set_TileAlignment(RectangleAlignment::BottomRight);
```

## Lásd még

* Enum [RectangleAlignment](../../rectanglealignment/)
* Osztály [IPictureFillFormat](../)
* Névtere [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)