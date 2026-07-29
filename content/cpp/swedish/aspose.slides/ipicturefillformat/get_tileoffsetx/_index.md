---
title: get_TileOffsetX()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar den horisontella förskjutningen av texturen från figurens ursprung i punkter. Ett positivt värde flyttar texturen åt höger, medan ett negativt värde flyttar den åt vänster. Läs float.
type: docs
weight: 274
url: /sv/aspose.slides/ipicturefillformat/get_tileoffsetx/
---
## IPictureFillFormat::get_TileOffsetX() metod


Returnerar den horisontella förskjutningen av texturen från figurens ursprung i punkter. Ett positivt värde flyttar texturen åt höger, medan ett negativt värde flyttar den åt vänster. Läs **float**.

```cpp
virtual float Aspose::Slides::IPictureFillFormat::get_TileOffsetX()=0
```

## Anmärkningar



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Hämtar bildfyllnadsformatet för formen
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Ställer in bildfyllnadsläget till Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Ställer in den horisontella förskjutningen av texturen till 20 punkter
pictureFillFormat->set_TileOffsetX(20.0f);
```

## Se även

* Klass [IPictureFillFormat](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)