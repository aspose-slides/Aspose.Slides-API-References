---
title: get_TileScaleY()
second_title: Aspose.Slides dla C++ Referencja API
description: Zwraca pionową skalę wypełnienia teksturą jako procent. Odczyt float.
type: docs
weight: 352
url: /pl/aspose.slides/picturefillformat/get_tilescaley/
---
## PictureFillFormat::get_TileScaleY() metoda

Zwraca pionową skalę wypełnienia teksturą jako procent. Odczyt **float**.

```cpp
float Aspose::Slides::PictureFillFormat::get_TileScaleY() override
```

## Uwagi

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Pobiera format wypełnienia obrazu kształtu
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Ustawia tryb wypełnienia obrazu na Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Ustawia pionową skalę tekstury na 120 procent
pictureFillFormat->set_TileScaleY(120.0f);
```

## Zobacz także

* Klasa [PictureFillFormat](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)