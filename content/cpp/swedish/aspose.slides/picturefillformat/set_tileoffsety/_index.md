---
title: set_TileOffsetY()
second_title: Aspose.Slides för C++ API-referens
description: Ställer in den vertikala förskjutningen av texturen från figurens ursprung i punkter. Ett positivt värde flyttar texturen nedåt, medan ett negativt värde flyttar den uppåt. Skriv float.
type: docs
weight: 313
url: /sv/aspose.slides/picturefillformat/set_tileoffsety/
---
## PictureFillFormat::set_TileOffsetY(float) metod


Ställer in den vertikala förskjutningen av texturen från figurens ursprung i punkter. Ett positivt värde flyttar texturen nedåt, medan ett negativt värde flyttar den uppåt. Skriv **float**.

```cpp
void Aspose::Slides::PictureFillFormat::set_TileOffsetY(float value) override
```

## Anmärkningar



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Hämtar bildfyllningsformatet för formen
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Ställer in bildfyllningsläget till Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Ställer in den vertikala förskjutningen av texturen till -50 punkter
pictureFillFormat->set_TileOffsetY(-50.0f);
```

## Se även

* Klass [PictureFillFormat](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)