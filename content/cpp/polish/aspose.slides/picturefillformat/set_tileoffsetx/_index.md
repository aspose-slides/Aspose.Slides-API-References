---
title: set_TileOffsetX()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Ustawia poziome przesunięcie tekstury względem początku kształtu w punktach. Wartość dodatnia przesuwa teksturę w prawo, natomiast wartość ujemna przesuwa ją w lewo. Zapisz float.
type: docs
weight: 287
url: /pl/aspose.slides/picturefillformat/set_tileoffsetx/
---
## PictureFillFormat::set_TileOffsetX(float) metoda

Ustawia poziome przesunięcie tekstury względem początku kształtu w punktach. Wartość dodatnia przesuwa teksturę w prawo, natomiast wartość ujemna przesuwa ją w lewo. Zapisz **float**.

```cpp
void Aspose::Slides::PictureFillFormat::set_TileOffsetX(float value) override
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

* Klasa [PictureFillFormat](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)