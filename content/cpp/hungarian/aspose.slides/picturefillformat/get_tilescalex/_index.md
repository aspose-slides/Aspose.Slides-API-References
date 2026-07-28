---
title: get_TileScaleX()
second_title: Aspose.Slides C++ API Referencia
description: Visszaadja a textúra kitöltés vízszintes skáláját százalékban. Olvasható float.
type: docs
weight: 326
url: /hu/aspose.slides/picturefillformat/get_tilescalex/
---
## PictureFillFormat::get_TileScaleX() metódus


Visszaadja a textúra kitöltés vízszintes skáláját százalékban. Olvasható **float**.

```cpp
float Aspose::Slides::PictureFillFormat::get_TileScaleX() override
```

## Megjegyzések



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Lekérdezi az alakzat képkitöltés formátumát
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Beállítja a képkitöltés módot Csempe-re
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Beállítja a textúra vízszintes skáláját 120 százalékra
pictureFillFormat->set_TileScaleX(120.0f);
```

## Lásd még

* Osztály [PictureFillFormat](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)