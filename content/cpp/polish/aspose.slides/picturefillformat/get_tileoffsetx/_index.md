---
title: get_TileOffsetX()
second_title: Aspose.Slides dla C++ Dokumentacja API
description: Zwraca poziomy offset tekstury względem początku kształtu w punktach. Dodatnia wartość przesuwa teksturę w prawo, natomiast ujemna przesuwa ją w lewo. Odczyt float.
type: docs
weight: 274
url: /pl/aspose.slides/picturefillformat/get_tileoffsetx/
---
## PictureFillFormat::get_TileOffsetX() metoda

Zwraca poziomy offset tekstury względem początku kształtu w punktach. Dodatnia wartość przesuwa teksturę w prawo, natomiast ujemna przesuwa ją w lewo. Odczyt **float**.

```cpp
float Aspose::Slides::PictureFillFormat::get_TileOffsetX() override
```

## Uwagi



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Pobiera format wypełnienia obrazu kształtu
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Ustawia tryb wypełnienia obrazu na Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Ustawia poziomy offset tekstury na 20 punktów
pictureFillFormat->set_TileOffsetX(20.0f);
```

## Zobacz także

* Klasa [PictureFillFormat](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)