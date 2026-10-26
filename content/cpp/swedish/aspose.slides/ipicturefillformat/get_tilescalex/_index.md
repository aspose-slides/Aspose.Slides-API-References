---
title: get_TileScaleX()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar den horisontella skalan för texturfyllning som procentandel. Läs float.
type: docs
weight: 326
url: /sv/aspose.slides/ipicturefillformat/get_tilescalex/
---
## IPictureFillFormat::get_TileScaleX() metod


Returnerar den horisontella skalan för texturfyllning som procentandel. Läs **float**.

```cpp
virtual float Aspose::Slides::IPictureFillFormat::get_TileScaleX()=0
```

## Anmärkningar



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Hämtar bildfyllningsformatet för formen
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Ställer in bildfyllnadsläget till Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Ställer in den horisontella skalningen för texturen till 120 procent
pictureFillFormat->set_TileScaleX(120.0f);
```

## Se även

* Klass [IPictureFillFormat](../)
* Namnrymd [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)