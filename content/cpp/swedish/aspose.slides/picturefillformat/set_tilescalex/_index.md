---
title: set_TileScaleX()
second_title: Aspose.Slides för C++ API-referens
description: Ställer in den horisontella skalan för texturfyllning som en procentsats. Skriv float.
type: docs
weight: 339
url: /sv/aspose.slides/picturefillformat/set_tilescalex/
---
## PictureFillFormat::set_TileScaleX(float) metod


Ställer in den horisontella skalan för texturfyllning som en procentsats. Skriv **float**.

```cpp
void Aspose::Slides::PictureFillFormat::set_TileScaleX(float value) override
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

## Se också

* Klass [PictureFillFormat](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)