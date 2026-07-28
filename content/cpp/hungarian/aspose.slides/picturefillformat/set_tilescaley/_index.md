---
title: set_TileScaleY()
second_title: Aspose.Slides C++ API referencia
description: Beállítja a textúra kitöltés függőleges skáláját százalékban. Írja float.
type: docs
weight: 365
url: /hu/aspose.slides/picturefillformat/set_tilescaley/
---
## PictureFillFormat::set_TileScaleY(float) metódus


Beállítja a textúra kitöltés függőleges skáláját százalékban. Írja **float**.

```cpp
void Aspose::Slides::PictureFillFormat::set_TileScaleY(float value) override
```

## Megjegyzés



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Lekéri a forma képkitöltési formátumát
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// A kép kitöltés módját Tile-re állítja be
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// A textúra függőleges skáláját 120 százalékra állítja be
pictureFillFormat->set_TileScaleY(120.0f);
```

## Lásd még

* Osztály [PictureFillFormat](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)