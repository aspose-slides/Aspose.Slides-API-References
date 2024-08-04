---
title: set_TileAlignment()
second_title: Aspose.Slides for C++ API Reference
description: Sets how the texture is aligned within the shape. This setting controls the starting point of the texture pattern and how it repeats across the shape. Write RectangleAlignment.
type: docs
weight: 391
url: /aspose.slides/picturefillformat/set_tilealignment/
---
## PictureFillFormat::set_TileAlignment(RectangleAlignment) method


Sets how the texture is aligned within the shape. This setting controls the starting point of the texture pattern and how it repeats across the shape. Write [RectangleAlignment](../../rectanglealignment/).

```cpp
void Aspose::Slides::PictureFillFormat::set_TileAlignment(RectangleAlignment value) override
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
* Class [PictureFillFormat](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)