---
title: get_TileOffsetY()
second_title: Aspose.Slides C++ API-referencia
description: Visszaadja a textúra függőleges eltolását a forma kiindulási pontjától pontban. A pozitív érték lefele mozgatja a textúrát, míg a negatív érték felfelé mozgatja. Olvasható float.
type: docs
weight: 300
url: /hu/aspose.slides/ipicturefillformat/get_tileoffsety/
---
## IPictureFillFormat::get_TileOffsetY() method


Visszaadja a textúra függőleges eltolását a forma kiindulási pontjától pontban megadva. A pozitív érték lefele mozgatja a textúrát, míg a negatív érték felfelé mozgatja. Olvasható **float**.

```cpp
virtual float Aspose::Slides::IPictureFillFormat::get_TileOffsetY()=0
```

## Remarks



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Lekéri a forma kép kitöltési formátumát
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Sets the picture fill mode to Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Sets the vertical offset of the texture to -50 points
pictureFillFormat->set_TileOffsetY(-50.0f);
```

## See Also

* Osztály [IPictureFillFormat](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)