---
title: set_TileAlignment()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Ustawia sposób wyrównania tekstury w kształcie. To ustawienie kontroluje punkt początkowy wzoru tekstury oraz sposób, w jaki powtarza się ona na kształcie. Zapisz RectangleAlignment.
type: docs
weight: 391
url: /pl/aspose.slides/ipicturefillformat/set_tilealignment/
---
## IPictureFillFormat::set_TileAlignment(RectangleAlignment) method

Ustawia sposób wyrównania tekstury w kształcie. To ustawienie kontroluje punkt początkowy wzoru tekstury oraz sposób, w jaki powtarza się ona na kształcie. Write [RectangleAlignment](../../rectanglealignment/).

```cpp
virtual void Aspose::Slides::IPictureFillFormat::set_TileAlignment(RectangleAlignment value)=0
```

## Uwagi

Domyślnie jest [RectangleAlignment::TopLeft](../../rectanglealignment/).

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Pobiera format wypełnienia obrazem kształtu
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Ustawia tryb wypełnienia obrazem na Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Ustawia wyrównanie kafelkowania na prawy dolny
pictureFillFormat->set_TileAlignment(RectangleAlignment::BottomRight);
```

## Zobacz także

* Wyliczenie [RectangleAlignment](../../rectanglealignment/)
* Klasa [IPictureFillFormat](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)