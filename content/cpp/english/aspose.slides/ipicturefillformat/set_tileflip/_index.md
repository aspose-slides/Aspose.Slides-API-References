---
title: set_TileFlip()
second_title: Aspose.Slides for C++ API Reference
description: Flips the texture tile around its horizontal, vertical or both axis. Write TileFlip.
type: docs
weight: 417
url: /aspose.slides/ipicturefillformat/set_tileflip/
---
## IPictureFillFormat::set_TileFlip(Aspose::Slides::TileFlip) method


Flips the texture tile around its horizontal, vertical or both axis. Write [TileFlip](../../tileflip/).

```cpp
virtual void Aspose::Slides::IPictureFillFormat::set_TileFlip(Aspose::Slides::TileFlip value)=0
```

## Remarks


Default is [TileFlip::NoFlip](../../tileflip/). 


```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Gets the picture fill format of the shape
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Sets the picture fill mode to Tile
pictureFillFormat->set_PictureFillMode(Aspose::Slides::PictureFillMode::Tile);

// Flips the texture tile around its vertical axis.
pictureFillFormat->set_TileFlip(Aspose::Slides::TileFlip::FlipY);
}
```

## See Also

* Enum [TileFlip](../../tileflip/)
* Class [IPictureFillFormat](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)