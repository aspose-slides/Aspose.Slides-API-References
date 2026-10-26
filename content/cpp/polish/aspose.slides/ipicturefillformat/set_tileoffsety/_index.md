---
title: set_TileOffsetY()
second_title: Aspose.Slides dla C++ - Dokumentacja API
description: Ustawia pionowy offset tekstury względem początku kształtu w punktach. Dodatnia wartość przesuwa teksturę w dół, a ujemna w górę. Zapisz float.
type: docs
weight: 313
url: /pl/aspose.slides/ipicturefillformat/set_tileoffsety/
---
## IPictureFillFormat::set_TileOffsetY(float) metoda


Ustawia pionowy offset tekstury względem początku kształtu w punktach. Dodatnia wartość przesuwa teksturę w dół, a ujemna w górę. Zapisz **float**.

```cpp
virtual void Aspose::Slides::IPictureFillFormat::set_TileOffsetY(float value)=0
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

* Klasa [IPictureFillFormat](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)