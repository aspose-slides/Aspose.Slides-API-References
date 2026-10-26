---
title: get_TileAlignment()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar hur texturen är justerad inom formen. Denna inställning styr startpunkten för texturmönstret och hur det upprepas över formen. Läs RectangleAlignment.
type: docs
weight: 378
url: /sv/aspose.slides/ipicturefillformat/get_tilealignment/
---
## IPictureFillFormat::get_TileAlignment() metod

Returnerar hur texturen är justerad inom formen. Denna inställning styr startpunkten för texturmönstret och hur det upprepas över formen. Läs [RectangleAlignment](../../rectanglealignment/).

```cpp
virtual RectangleAlignment Aspose::Slides::IPictureFillFormat::get_TileAlignment()=0
```

## Anmärkningar

Standard är [RectangleAlignment::TopLeft](../../rectanglealignment/). 

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Hämtar bildfyllningsformatet för formen
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Ställer in bildfyllningsläge till Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Ställer in justeringen för mosaiken till höger nedre
pictureFillFormat->set_TileAlignment(RectangleAlignment::BottomRight);
```

## Se även

* Enum [RectangleAlignment](../../rectanglealignment/)
* Klass [IPictureFillFormat](../)
* namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)