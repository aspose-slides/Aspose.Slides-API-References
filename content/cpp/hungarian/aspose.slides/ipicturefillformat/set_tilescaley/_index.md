---
title: set_TileScaleY()
second_title: Aspose.Slides C++ API hivatkozás
description: Beállítja a textúra kitöltés függőleges méretarányát százalékban. Írja float.
type: docs
weight: 365
url: /hu/aspose.slides/ipicturefillformat/set_tilescaley/
---
## IPictureFillFormat::set_TileScaleY(float) metódus


Beállítja a textúra kitöltés függőleges méretarányát százalékban. Írja **float**.

```cpp
virtual void Aspose::Slides::IPictureFillFormat::set_TileScaleY(float value)=0
```

## Megjegyzések



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Lekérdezi a forma kép kitöltési formátumát
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Beállítja a kép kitöltési módot Tile-re
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Beállítja a textúra függőleges skáláját 120 százalékra
pictureFillFormat->set_TileScaleY(120.0f);
```

## Lásd még

* Osztály [IPictureFillFormat](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)