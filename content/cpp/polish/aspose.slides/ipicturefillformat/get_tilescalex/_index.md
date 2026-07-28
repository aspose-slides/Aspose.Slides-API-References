---
title: get_TileScaleX()
second_title: Aspose.Slides dla C++ - referencja API
description: Zwraca skalę poziomą wypełnienia teksturą jako procent. Odczyt float.
type: docs
weight: 326
url: /pl/aspose.slides/ipicturefillformat/get_tilescalex/
---
## IPictureFillFormat::get_TileScaleX() metoda


Zwraca skalę poziomą wypełnienia teksturą jako procent. Odczyt **float**.

```cpp
virtual float Aspose::Slides::IPictureFillFormat::get_TileScaleX()=0
```

## Uwagi



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Pobiera format wypełnienia obrazu kształtu
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Ustawia tryb wypełnienia obrazu na Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Ustawia poziomą skalę tekstury na 120 procent
pictureFillFormat->set_TileScaleX(120.0f);
```

## Zobacz także

* Klasa [IPictureFillFormat](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)