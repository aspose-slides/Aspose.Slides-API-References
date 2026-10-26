---
title: set_TileAlignment()
second_title: Aspose.Slides C++ API hivatkozás
description: Beállítja, hogyan igazodik a textúra az alakzaton belül. Ez a beállítás szabályozza a textúraminta kiindulópontját és hogy hogyan ismétlődik az alakzaton. Írja be RectangleAlignment.
type: docs
weight: 391
url: /hu/aspose.slides/picturefillformat/set_tilealignment/
---
## PictureFillFormat::set_TileAlignment(RectangleAlignment) metódus


Beállítja, hogy a textúra hogyan igazodik az alakzaton belül. Ez a beállítás szabályozza a textúraminta kiindulópontját, és hogy hogyan ismétlődik az alakzaton keresztül. Írja be [RectangleAlignment](../../rectanglealignment/).

```cpp
void Aspose::Slides::PictureFillFormat::set_TileAlignment(RectangleAlignment value) override
```

## Megjegyzések


Az alapértelmezett [RectangleAlignment::TopLeft](../../rectanglealignment/). 


```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Lekéri az alakzat kép kitöltési formátumát
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Beállítja a kép kitöltési módot Csempére
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Beállítja a csempe igazítást jobb alsó sarokra
pictureFillFormat->set_TileAlignment(RectangleAlignment::BottomRight);
```

## Lásd még

* Enum [RectangleAlignment](../../rectanglealignment/)
* Osztály [PictureFillFormat](../)
* Névterület [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)