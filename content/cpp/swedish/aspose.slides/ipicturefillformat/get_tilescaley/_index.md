---
title: get_TileScaleY()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar den vertikala skalan för texturfyllning som en procentsats. Läs float.
type: docs
weight: 352
url: /sv/aspose.slides/ipicturefillformat/get_tilescaley/
---
## IPictureFillFormat::get_TileScaleY() metod


Returnera den vertikala skalan för texturfyllning som en procentsats. Läs **float**.

```cpp
virtual float Aspose::Slides::IPictureFillFormat::get_TileScaleY()=0
```

## Anmärkningar



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Hämtar bildfyllningsformatet för formen
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Ställer in bildfyllningsläge till Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Ställer in den vertikala skalan för texturen till 120 procent
pictureFillFormat->set_TileScaleY(120.0f);
```

## Se även

* Klass [IPictureFillFormat](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)