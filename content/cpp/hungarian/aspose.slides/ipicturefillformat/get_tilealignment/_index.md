---
title: get_TileAlignment()
second_title: Aspose.Slides C++ API Referencia
description: Visszaadja, hogy a textúra hogyan van igazítva az alakzatban. Ez a beállítás szabályozza a textúra minta kiindulópontját, és hogy hogyan ismétlődik az alakzatban. Olvassa el RectangleAlignment.
type: docs
weight: 378
url: /hu/aspose.slides/ipicturefillformat/get_tilealignment/
---
## IPictureFillFormat::get_TileAlignment() metódus


Visszaadja, hogy a textúra hogyan van igazítva az alakzatban. Ez a beállítás szabályozza a textúra minta kiindulópontját, és azt, hogy hogyan ismétlődik az alakzatban. Olvassa el [RectangleAlignment](../../rectanglealignment/).

```cpp
virtual RectangleAlignment Aspose::Slides::IPictureFillFormat::get_TileAlignment()=0
```

## Megjegyzés


Az alapértelmezett érték [RectangleAlignment::TopLeft](../../rectanglealignment/). 


```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Lekéri az alakzat kép kitöltési formátumát
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Beállítja a kép kitöltési módot Tile-re
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Beállítja a csempézés igazítását jobbra alul
pictureFillFormat->set_TileAlignment(RectangleAlignment::BottomRight);
```

## Lásd még

* Enum [RectangleAlignment](../../rectanglealignment/)
* Osztály [IPictureFillFormat](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)