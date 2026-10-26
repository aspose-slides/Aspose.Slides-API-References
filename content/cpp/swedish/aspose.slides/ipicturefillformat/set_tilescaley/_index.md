---
title: set_TileScaleY()
second_title: Aspose.Slides för C++ API-referens
description: Sätter den vertikala skalan för texturfyllning som en procentsats. Skriv float.
type: docs
weight: 365
url: /sv/aspose.slides/ipicturefillformat/set_tilescaley/
---
## IPictureFillFormat::set_TileScaleY(float) metod


Sätter den vertikala skalan för texturfyllning som en procentsats. Skriv **float**.

```cpp
virtual void Aspose::Slides::IPictureFillFormat::set_TileScaleY(float value)=0
```

## Anmärkningar



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Hämtar bildfyllningsformatet för formen
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Ställer in bildfyllningsläget till Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Ställer in den vertikala skalan för texturen till 120 procent
pictureFillFormat->set_TileScaleY(120.0f);
```

## Se också

* Klass [IPictureFillFormat](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)