---
title: set_TileOffsetX()
second_title: Referencja API Aspose.Slides dla C++
description: Ustawia poziomy offset tekstury względem pochodzenia kształtu w punktach. Dodatnia wartość przesuwa teksturę w prawo, natomiast ujemna wartość przesuwa ją w lewo. Zapisz float.
type: docs
weight: 287
url: /pl/aspose.slides/ipicturefillformat/set_tileoffsetx/
---
## IPictureFillFormat::set_TileOffsetX(float) metoda


Ustawia poziomy offset tekstury względem pochodzenia kształtu w punktach. Dodatnia wartość przesuwa teksturę w prawo, natomiast ujemna wartość przesuwa ją w lewo. Zapisz **float**.

```cpp
virtual void Aspose::Slides::IPictureFillFormat::set_TileOffsetX(float value)=0
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

* Klasa [IPictureFillFormat](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)