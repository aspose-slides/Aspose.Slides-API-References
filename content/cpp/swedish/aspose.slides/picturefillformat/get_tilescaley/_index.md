---
title: get_TileScaleY()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar den vertikala skalan för texturfyllningen som en procentsats. Läs float.
type: docs
weight: 352
url: /sv/aspose.slides/picturefillformat/get_tilescaley/
---
## PictureFillFormat::get_TileScaleY() metod


Returnerar den vertikala skalan för texturfyllningen som en procentsats. Läs **float**.

```cpp
float Aspose::Slides::PictureFillFormat::get_TileScaleY() override
```

## Anmärkningar



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Hämtar bildfyllningsformatet för formen
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Ställer in bildfyllningsläget till Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Ställer in vertikal skala för texturen till 120 procent
pictureFillFormat->set_TileScaleY(120.0f);
```

## Se även

* Klass [PictureFillFormat](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)