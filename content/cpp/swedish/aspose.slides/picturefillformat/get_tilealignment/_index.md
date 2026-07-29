---
title: get_TileAlignment()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar hur texturen är justerad inom formen. Denna inställning styr startpunkten för texturmönstret och hur det upprepas över formen. Läs RectangleAlignment.
type: docs
weight: 378
url: /sv/aspose.slides/picturefillformat/get_tilealignment/
---
## PictureFillFormat::get_TileAlignment() metod


Returnerar hur texturen är justerad inom formen. Denna inställning styr startpunkten för texturmönstret och hur det upprepas över formen. Läs [RectangleAlignment](../../rectanglealignment/).

```cpp
RectangleAlignment Aspose::Slides::PictureFillFormat::get_TileAlignment() override
```

## Anmärkningar


Standard är [RectangleAlignment::TopLeft](../../rectanglealignment/). 


```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Hämtar bildfyllningsformatet för formen
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Ställer in bildfyllningsläget till Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Ställer in justeringen för mönstret till BottomRight
pictureFillFormat->set_TileAlignment(RectangleAlignment::BottomRight);
```

## Se även

* Enum [RectangleAlignment](../../rectanglealignment/)
* Klass [PictureFillFormat](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)