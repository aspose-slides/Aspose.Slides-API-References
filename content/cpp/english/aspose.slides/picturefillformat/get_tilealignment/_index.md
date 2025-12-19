---
title: get_TileAlignment()
second_title: Aspose.Slides for C++ API Reference
description: Returns how the texture is aligned within the shape. This setting controls the starting point of the texture pattern and how it repeats across the shape. Read RectangleAlignment.
type: docs
weight: 378
url: /aspose.slides/picturefillformat/get_tilealignment/
---
## PictureFillFormat::get_TileAlignment() method


Returns how the texture is aligned within the shape. This setting controls the starting point of the texture pattern and how it repeats across the shape. Read [RectangleAlignment](../../rectanglealignment/).

```cpp
RectangleAlignment Aspose::Slides::PictureFillFormat::get_TileAlignment() override
```

## Remarks


Default is [RectangleAlignment::TopLeft](../../rectanglealignment/). 


```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Gets the picture fill format of the shape
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Sets the picture fill mode to Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Sets the alignment for the tiling to the right bottom
pictureFillFormat->set_TileAlignment(RectangleAlignment::BottomRight);
```

## See Also

* Enum [RectangleAlignment](../../rectanglealignment/)
* Class [PictureFillFormat](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)