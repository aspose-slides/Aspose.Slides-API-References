---
title: get_TileOffsetY()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Zwraca pionowe przesunięcie tekstury względem pochodzenia kształtu w punktach. Dodatnia wartość przesuwa teksturę w dół, natomiast ujemna przesuwa ją w górę. Odczyt float.
type: docs
weight: 300
url: /pl/aspose.slides/ipicturefillformat/get_tileoffsety/
---
## IPictureFillFormat::get_TileOffsetY() metoda


Zwraca pionowe przesunięcie tekstury względem pochodzenia kształtu w punktach. Dodatnia wartość przesuwa teksturę w dół, natomiast ujemna przesuwa ją w górę. Odczyt **float**.

```cpp
virtual float Aspose::Slides::IPictureFillFormat::get_TileOffsetY()=0
```

## Uwagi



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Pobiera format wypełnienia obrazem kształtu
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Ustawia tryb wypełnienia obrazem na Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Ustawia pionowe przesunięcie tekstury na -50 punktów
pictureFillFormat->set_TileOffsetY(-50.0f);
```

## Zobacz także

* Klasa [IPictureFillFormat](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)