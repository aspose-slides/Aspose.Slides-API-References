---
title: get_TileScaleY()
second_title: Aspose.Slides C++ API referencia
description: Visszaadja a textúra kitöltés függőleges méretarányát százalékban. Olvasás float.
type: docs
weight: 352
url: /hu/aspose.slides/ipicturefillformat/get_tilescaley/
---
## IPictureFillFormat::get_TileScaleY() metódus


Visszaadja a textúra kitöltés függőleges méretarányát százalékban. Olvasás: **float**.

```cpp
virtual float Aspose::Slides::IPictureFillFormat::get_TileScaleY()=0
```

## Megjegyzések



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Lekéri a shape kép kitöltési formátumát
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Beállítja a kép kitöltés módját Tile-re
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Beállítja a textúra függőleges méretarányát 120 százalékra
pictureFillFormat->set_TileScaleY(120.0f);
```

## Lásd még

* Osztály [IPictureFillFormat](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)