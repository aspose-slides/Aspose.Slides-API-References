---
title: set_TileScaleX()
second_title: Aspose.Slides C++ API referencia
description: Beállítja a textúra kitöltés vízszintes skáláját százalékban. Írja float.
type: docs
weight: 339
url: /hu/aspose.slides/picturefillformat/set_tilescalex/
---
## PictureFillFormat::set_TileScaleX(float) metódus


Beállítja a textúra kitöltés vízszintes skáláját százalékban. Írja **float**.

```cpp
void Aspose::Slides::PictureFillFormat::set_TileScaleX(float value) override
```

## Megjegyzés



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Lekéri a alakzat kép kitöltési formátumát
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Beállítja a kép kitöltési módot Tile-re
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Beállítja a textúra vízszintes skáláját 120 százalékra
pictureFillFormat->set_TileScaleX(120.0f);
```

## Lásd még

* Osztály [PictureFillFormat](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)