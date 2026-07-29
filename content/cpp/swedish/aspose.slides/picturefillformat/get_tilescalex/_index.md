---
title: get_TileScaleX()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar den horisontella skalan för texturfyllningen som en procentandel. Läs float.
type: docs
weight: 326
url: /sv/aspose.slides/picturefillformat/get_tilescalex/
---
## PictureFillFormat::get_TileScaleX() metod

Returnerar den horisontella skalan för texturfyllningen som en procentandel. Läs **float**.

```cpp
float Aspose::Slides::PictureFillFormat::get_TileScaleX() override
```

## Anmärkningar


```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Hämtar bildfyllningsformatet för formen
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Ställer in bildfyllningsläget till Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Ställer in den horisontella skalan för texturen till 120 procent
pictureFillFormat->set_TileScaleX(120.0f);
```

## Se även

* Klass [PictureFillFormat](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)