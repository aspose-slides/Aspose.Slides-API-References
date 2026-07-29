---
title: set_TileAlignment()
second_title: Aspose.Slides för C++ API-referens
description: Ställer in hur texturen är placerad inom formen. Denna inställning styr startpunkten för texturmönstret och hur det upprepas över formen. Skriv RectangleAlignment.
type: docs
weight: 391
url: /sv/aspose.slides/ipicturefillformat/set_tilealignment/
---
## IPictureFillFormat::set_TileAlignment(RectangleAlignment) metod


Ställer in hur texturen är justerad inom formen. Denna inställning styr startpunkten för texturmönstret och hur det upprepas över formen. Skriv [RectangleAlignment](../../rectanglealignment/).

```cpp
virtual void Aspose::Slides::IPictureFillFormat::set_TileAlignment(RectangleAlignment value)=0
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

// Ställer in justeringen för brickning till nedre högra
pictureFillFormat->set_TileAlignment(RectangleAlignment::BottomRight);
```

## Se även

* Enum [RectangleAlignment](../../rectanglealignment/)
* Klass [IPictureFillFormat](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)