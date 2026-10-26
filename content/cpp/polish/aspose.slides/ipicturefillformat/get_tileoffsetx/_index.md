---
title: get_TileOffsetX()
second_title: Aspose.Slides for C++ – odniesienie API
description: Zwraca poziome przesunięcie tekstury względem pochodzenia kształtu w punktach. Dodatnia wartość przesuwa teksturę w prawo, natomiast ujemna wartość przesuwa ją w lewo. Odczyt float.
type: docs
weight: 274
url: /pl/aspose.slides/ipicturefillformat/get_tileoffsetx/
---
## IPictureFillFormat::get_TileOffsetX() metoda

Zwraca poziome przesunięcie tekstury względem pochodzenia kształtu w punktach. Dodatnia wartość przesuwa teksturę w prawo, natomiast ujemna wartość przesuwa ją w lewo. Odczyt **float**.

```cpp
virtual float Aspose::Slides::IPictureFillFormat::get_TileOffsetX()=0
```

## Uwagi



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Pobiera format wypełnienia obrazu kształtu
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Ustawia tryb wypełnienia obrazu na Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Ustawia poziome przesunięcie tekstury na 20 punktów
pictureFillFormat->set_TileOffsetX(20.0f);
```

## Zobacz także

* Klasa [IPictureFillFormat](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)