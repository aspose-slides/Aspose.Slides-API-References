---
title: set_TileScaleX()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Ustawia poziomą skalę wypełnienia teksturą w procentach. Zapisz float.
type: docs
weight: 339
url: /pl/aspose.slides/picturefillformat/set_tilescalex/
---
## PictureFillFormat::set_TileScaleX(float) metoda


Ustawia poziomą skalę wypełnienia teksturą w procentach. Zapisz **float**.

```cpp
void Aspose::Slides::PictureFillFormat::set_TileScaleX(float value) override
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

* Klasa [PictureFillFormat](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)