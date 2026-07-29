---
title: get_TileOffsetY()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar det vertikala offsetet för texturen från figurens ursprung i punkter. Ett positivt värde flyttar texturen nedåt, medan ett negativt värde flyttar den uppåt. Läs float.
type: docs
weight: 300
url: /sv/aspose.slides/ipicturefillformat/get_tileoffsety/
---
## IPictureFillFormat::get_TileOffsetY() metod

Returnerar det vertikala offsetet för texturen från figurens ursprung i punkter. Ett positivt värde flyttar texturen nedåt, medan ett negativt värde flyttar den uppåt. Läs **float**.

```cpp
virtual float Aspose::Slides::IPictureFillFormat::get_TileOffsetY()=0
```

## Anmärkningar



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Hämtar bildfyllnadsformatet för formen
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Ställer in bildfyllnadsläget till Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Ställer in det vertikala offsetet för texturen till -50 punkter
pictureFillFormat->set_TileOffsetY(-50.0f);
```

## Se även

* Klass [IPictureFillFormat](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)