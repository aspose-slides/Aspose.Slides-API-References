---
title: get_TileFlip()
second_title: Aspose.Slides for C++ API Reference
description: "Flips the texture tile around its horizontal, vertical or both axis. Read Slides::TileFlip."
type: docs
weight: 404
url: /aspose.slides/ipicturefillformat/get_tileflip/
---
## IPictureFillFormat::get_TileFlip() method


Flips the texture tile around its horizontal, vertical or both axis. Read [Slides::TileFlip](../../tileflip/).

```cpp
virtual Aspose::Slides::TileFlip Aspose::Slides::IPictureFillFormat::get_TileFlip()=0
```

## Remarks


Default is [TileFlip::NoFlip](../../tileflip/). 


```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Gets the picture fill format of the shape
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Sets the picture fill mode to Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Flips the texture tile around its vertical axis.
pictureFillFormat->set_TileFlip(TileFlip::FlipY);
}
```

## See Also

* Enum [TileFlip](../../tileflip/)
* Class [IPictureFillFormat](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)