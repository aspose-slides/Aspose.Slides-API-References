---
title: set_TileAlignment()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Ustawia sposób wyrównania tekstury wewnątrz kształtu. To ustawienie kontroluje punkt początkowy wzoru tekstury oraz sposób jej powtarzania się w obrębie kształtu. Zapisz RectangleAlignment.
type: docs
weight: 391
url: /pl/aspose.slides/picturefillformat/set_tilealignment/
---
## PictureFillFormat::set_TileAlignment(RectangleAlignment) metoda


Ustawia sposób wyrównania tekstury wewnątrz kształtu. To ustawienie kontroluje punkt początkowy wzoru tekstury oraz sposób jej powtarzania się w obrębie kształtu. Zapisz [RectangleAlignment](../../rectanglealignment/).

```cpp
void Aspose::Slides::PictureFillFormat::set_TileAlignment(RectangleAlignment value) override
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
* Klasa [PictureFillFormat](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)