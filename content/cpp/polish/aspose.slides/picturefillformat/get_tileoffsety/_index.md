---
title: get_TileOffsetY()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Zwraca pionowy offset tekstury względem początku kształtu w punktach. Dodatnia wartość przesuwa teksturę w dół, natomiast ujemna wartość przesuwa ją w górę. Odczyt float.
type: docs
weight: 300
url: /pl/aspose.slides/picturefillformat/get_tileoffsety/
---
## PictureFillFormat::get_TileOffsetY() metoda

Zwraca pionowy offset tekstury względem początku kształtu w punktach. Dodatnia wartość przesuwa teksturę w dół, natomiast ujemna wartość przesuwa ją w górę. Odczyt **float**.

```cpp
float Aspose::Slides::PictureFillFormat::get_TileOffsetY() override
```

## Uwagi

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Pobiera format wypełnienia obrazu kształtu
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Ustawia tryb wypełnienia obrazu na Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Ustawia pionowy offset tekstury na -50 punktów
pictureFillFormat->set_TileOffsetY(-50.0f);
```

## Zobacz także

* Klasa [PictureFillFormat](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)