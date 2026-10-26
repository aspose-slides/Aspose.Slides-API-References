---
title: get_TileScaleX()
second_title: Aspose.Slides C++ API referencia
description: Visszaadja a textúra kitöltés vízszintes méretarányát százalékban. Olvasás float.
type: docs
weight: 326
url: /hu/aspose.slides/ipicturefillformat/get_tilescalex/
---
## IPictureFillFormat::get_TileScaleX() metódus

Visszaadja a textúra kitöltés vízszintes méretarányát százalékban. Olvasás **float**.

```cpp
virtual float Aspose::Slides::IPictureFillFormat::get_TileScaleX()=0
```

## Megjegyzések



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Lekéri a alakzat kép kitöltés formátumát
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Beállítja a kép kitöltés módját Tile-re
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Beállítja a textúra vízszintes méretarányát 120 százalékra
pictureFillFormat->set_TileScaleX(120.0f);
```

## Lásd még

* Osztály [IPictureFillFormat](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)