---
title: get_TileAlignment()
second_title: Aspose.Slides dla C++ – referencja API
description: Zwraca sposób, w jaki tekstura jest wyrównana w kształcie. To ustawienie kontroluje punkt początkowy wzoru tekstury oraz sposób, w jaki powtarza się ona w kształcie. Przeczytaj RectangleAlignment.
type: docs
weight: 378
url: /pl/aspose.slides/ipicturefillformat/get_tilealignment/
---
## IPictureFillFormat::get_TileAlignment() metoda

Zwraca sposób, w jaki tekstura jest wyrównana w kształcie. To ustawienie kontroluje punkt początkowy wzoru tekstury oraz sposób, w jaki powtarza się ona w kształcie. Zobacz [RectangleAlignment](../../rectanglealignment/).

```cpp
virtual RectangleAlignment Aspose::Slides::IPictureFillFormat::get_TileAlignment()=0
```

## Uwagi

Domyślne jest [RectangleAlignment::TopLeft](../../rectanglealignment/). 

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

* Enum [RectangleAlignment](../../rectanglealignment/)
* Class [IPictureFillFormat](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)