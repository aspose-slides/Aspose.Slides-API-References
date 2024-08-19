---
title: set_TileAlignment()
second_title: Aspose.Slides for C++ API Reference
description: Sets how the texture is aligned within the shape. This setting controls the starting point of the texture pattern and how it repeats across the shape. Write RectangleAlignment.
type: docs
weight: 391
url: /aspose.slides/ipicturefillformat/set_tilealignment/
---
## IPictureFillFormat::set_TileAlignment(RectangleAlignment) method


Sets how the texture is aligned within the shape. This setting controls the starting point of the texture pattern and how it repeats across the shape. Write [RectangleAlignment](../../rectanglealignment/).

```cpp
virtual void Aspose::Slides::IPictureFillFormat::set_TileAlignment(RectangleAlignment value)=0
```

## Remarks


Default is [RectangleAlignment::TopLeft](../../rectanglealignment/). 


```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Gets the picture fill format of the shape
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Sets the picture fill mode to Tile
pictureFillFormat->set_PictureFillMode(Aspose::Slides::PictureFillMode::Tile);

// Sets the alignment for the tiling to the right bottom
pictureFillFormat->set_TileAlignment(Aspose::Slides::RectangleAlignment::BottomRight);
```

## See Also

* Enum [RectangleAlignment](../../rectanglealignment/)
* Class [IPictureFillFormat](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)