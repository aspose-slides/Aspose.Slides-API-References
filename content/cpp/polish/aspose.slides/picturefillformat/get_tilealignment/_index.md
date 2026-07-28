---
title: get_TileAlignment()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Zwraca, jak tekstura jest wyrównana w obrębie kształtu. To ustawienie kontroluje punkt początkowy wzoru tekstury i sposób, w jaki powtarza się w obrębie kształtu. Zobacz RectangleAlignment.
type: docs
weight: 378
url: /pl/aspose.slides/picturefillformat/get_tilealignment/
---
## PictureFillFormat::get_TileAlignment() metoda

Zwraca, jak tekstura jest wyrównana w obrębie kształtu. To ustawienie kontroluje punkt początkowy wzoru tekstury i sposób, w jaki powtarza się w obrębie kształtu. Zobacz [RectangleAlignment](../../rectanglealignment/).

```cpp
RectangleAlignment Aspose::Slides::PictureFillFormat::get_TileAlignment() override
```

## Uwagi

Domyślna wartość to [RectangleAlignment::TopLeft](../../rectanglealignment/).

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Pobiera format wypełnienia obrazu kształtu
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Ustawia tryb wypełnienia obrazu na Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Ustawia wyrównanie kafelkowania na prawy dolny
pictureFillFormat->set_TileAlignment(RectangleAlignment::BottomRight);
```

## Zobacz także

* Wyliczenie [RectangleAlignment](../../rectanglealignment/)
* Klasa [PictureFillFormat](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)