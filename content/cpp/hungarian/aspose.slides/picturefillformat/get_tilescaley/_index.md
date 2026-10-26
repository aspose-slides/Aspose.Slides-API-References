---
title: get_TileScaleY()
second_title: Aspose.Slides C++ API referencia
description: Visszaadja a függőleges skálát a textúra kitöltéshez százalékban. Olvasás float.
type: docs
weight: 352
url: /hu/aspose.slides/picturefillformat/get_tilescaley/
---
## PictureFillFormat::get_TileScaleY() metódus


Visszaadja a függőleges méretet a textúra kitöltéshez százalékban. Olvasás **float**.

```cpp
float Aspose::Slides::PictureFillFormat::get_TileScaleY() override
```

## Megjegyzések



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// A forma kép kitöltési formátumát lekéri
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// A kép kitöltési módot csempére állítja
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// A textúra függőleges méretét 120 százalékra állítja
pictureFillFormat->set_TileScaleY(120.0f);
```

## Lásd még

* Osztály [PictureFillFormat](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)