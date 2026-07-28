---
title: set_TileScaleX()
second_title: Aspose.Slides for C++ API referencia
description: Beállítja a textúra kitöltés vízszintes skáláját százalékban. Írja be a float.
type: docs
weight: 339
url: /hu/aspose.slides/ipicturefillformat/set_tilescalex/
---
## IPictureFillFormat::set_TileScaleX(float) metódus


Beállítja a textúra kitöltés vízszintes skáláját százalékban. Írja be a **float** értéket.

```cpp
virtual void Aspose::Slides::IPictureFillFormat::set_TileScaleX(float value)=0
```

## Megjegyzés



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Lekéri az alakzat képtöltési formátumát
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Beállítja a képtöltési módot Tile-re
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Beállítja a textúra vízszintes skáláját 120 százalékra
pictureFillFormat->set_TileScaleX(120.0f);
```

## Lásd még

* Osztály [IPictureFillFormat](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)