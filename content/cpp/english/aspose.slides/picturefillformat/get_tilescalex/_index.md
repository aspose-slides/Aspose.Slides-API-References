---
title: get_TileScaleX()
second_title: Aspose.Slides for C++ API Reference
description: Returns the horizontal scale for the texture fill as a percentage. Read float.
type: docs
weight: 326
url: /aspose.slides/picturefillformat/get_tilescalex/
---
## PictureFillFormat::get_TileScaleX() method


Returns the horizontal scale for the texture fill as a percentage. Read **float**.

```cpp
float Aspose::Slides::PictureFillFormat::get_TileScaleX() override
```

## Remarks



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Gets the picture fill format of the shape
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Sets the picture fill mode to Tile
pictureFillFormat->set_PictureFillMode(Aspose::Slides::PictureFillMode::Tile);

// Sets the horizontal scale for the texture to 120 percents
pictureFillFormat->set_TileScaleX(120.0f);
```

## See Also

* Class [PictureFillFormat](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)