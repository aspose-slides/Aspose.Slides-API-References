---
title: set_TileOffsetY()
second_title: Aspose.Slides dla C++ - odniesienie API
description: Ustawia pionowy offset tekstury względem początku kształtu w punktach. Dodatnia wartość przesuwa teksturę w dół, a wartość ujemna przesuwa ją w górę. Zapisz float.
type: docs
weight: 313
url: /pl/aspose.slides/picturefillformat/set_tileoffsety/
---
## PictureFillFormat::set_TileOffsetY(float) metoda

Ustawia pionowy offset tekstury względem początkowego punktu kształtu w punktach. Dodatnia wartość przesuwa teksturę w dół, natomiast ujemna wartość przesuwa ją w górę. Zapisz **float**.

```cpp
void Aspose::Slides::PictureFillFormat::set_TileOffsetY(float value) override
```

## Uwagi

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Pobiera format wypełnienia obrazem kształtu
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Ustawia tryb wypełnienia obrazem na Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Ustawia pionowy offset tekstury na -50 punktów
pictureFillFormat->set_TileOffsetY(-50.0f);
```

## Zobacz także

* Klasa [PictureFillFormat](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)