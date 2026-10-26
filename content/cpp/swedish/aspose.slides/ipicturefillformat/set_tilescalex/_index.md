---
title: set_TileScaleX()
second_title: Aspose.Slides för C++ API-referens
description: Ställer in den horisontella skalan för texturfyllningen som en procentsats. Skriv float.
type: docs
weight: 339
url: /sv/aspose.slides/ipicturefillformat/set_tilescalex/
---
## IPictureFillFormat::set_TileScaleX(float) metod


Ställer in den horisontella skalan för texturfyllningen som en procentsats. Skriv **float**.

```cpp
virtual void Aspose::Slides::IPictureFillFormat::set_TileScaleX(float value)=0
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

* Klass [IPictureFillFormat](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)