---
title: set_TileScaleY()
second_title: Aspose.Slides för C++ API-referens
description: Ställer in den vertikala skalan för texturfyllning som en procentsats. Skriver float.
type: docs
weight: 365
url: /sv/aspose.slides/picturefillformat/set_tilescaley/
---
## PictureFillFormat::set_TileScaleY(float) metod


Ställer in den vertikala skalan för texturfyllning som en procentsats. Skriver **float**.

```cpp
void Aspose::Slides::PictureFillFormat::set_TileScaleY(float value) override
```

## Anmärkningar



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Hämtar bildfyllnadsformatet för formen
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Ställer in bildfyllnadsläget till Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Ställer in den vertikala skalan för texturen till 120 procent
pictureFillFormat->set_TileScaleY(120.0f);
```

## Se även

* Klass [PictureFillFormat](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)