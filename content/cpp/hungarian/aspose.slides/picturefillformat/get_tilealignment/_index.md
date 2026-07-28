---
title: get_TileAlignment()
second_title: Aspose.Slides C++ API referencia
description: Visszaadja, hogy a textúra hogyan van igazítva az alakzatban. Ez a beállítás szabályozza a textúramintázat kezdőpontját és hogy hogyan ismétlődik az alakzaton belül. Olvassa el a RectangleAlignment.
type: docs
weight: 378
url: /hu/aspose.slides/picturefillformat/get_tilealignment/
---
## PictureFillFormat::get_TileAlignment() metódus


Visszaadja, hogyan van igazítva a textúra az alakzatban. Ez a beállítás szabályozza a textúramintázat kezdőpontját, és hogy hogyan ismétlődik az alakzatban. Olvassa el [RectangleAlignment](../../rectanglealignment/).

```cpp
RectangleAlignment Aspose::Slides::PictureFillFormat::get_TileAlignment() override
```

## Megjegyzések


Alapértelmezett: [RectangleAlignment::TopLeft](../../rectanglealignment/). 


```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Lekéri az alakzat kép kitöltési formátumát
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Beállítja a kép kitöltési módot Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Beállítja a csempe igazítását jobb alsó sarokba
pictureFillFormat->set_TileAlignment(RectangleAlignment::BottomRight);
```

## Lásd még

* Enum [RectangleAlignment](../../rectanglealignment/)
* Osztály [PictureFillFormat](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)