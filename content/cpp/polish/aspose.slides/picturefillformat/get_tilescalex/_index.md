---
title: get_TileScaleX()
second_title: Aspose.Slides dla interfejsu API C++
description: Zwraca poziomą skalę wypełnienia teksturą jako procent. Odczyt float.
type: docs
weight: 326
url: /pl/aspose.slides/picturefillformat/get_tilescalex/
---
## PictureFillFormat::get_TileScaleX() metoda


Zwraca poziomą skalę wypełnienia teksturą jako procent. Odczyt **float**.

```cpp
float Aspose::Slides::PictureFillFormat::get_TileScaleX() override
```

## Uwagi



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Pobiera format wypełnienia obrazem kształtu
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Ustawia tryb wypełnienia obrazem na Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Ustawia poziomą skalę tekstury na 120 procent
pictureFillFormat->set_TileScaleX(120.0f);
```

## Zobacz także

* Klasa [PictureFillFormat](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)