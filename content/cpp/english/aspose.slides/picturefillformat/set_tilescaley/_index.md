---
title: set_TileScaleY()
second_title: Aspose.Slides for C++ API Reference
description: Sets the vertical scale for the texture fill as a percentage. Write float.
type: docs
weight: 365
url: /aspose.slides/picturefillformat/set_tilescaley/
---
## PictureFillFormat::set_TileScaleY(float) method


Sets the vertical scale for the texture fill as a percentage. Write **float**.

```cpp
void Aspose::Slides::PictureFillFormat::set_TileScaleY(float value) override
```

## Remarks



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Gets the picture fill format of the shape
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Sets the picture fill mode to Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Sets the vertical scale for the texture to 120 percents
pictureFillFormat->set_TileScaleY(120.0f);
```

## See Also

* Class [PictureFillFormat](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)