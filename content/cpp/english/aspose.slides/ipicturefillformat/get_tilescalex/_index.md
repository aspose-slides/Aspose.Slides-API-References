---
title: get_TileScaleX()
second_title: Aspose.Slides for C++ API Reference
description: Returns the horizontal scale for the texture fill as a percentage. Read float.
type: docs
weight: 326
url: /aspose.slides/ipicturefillformat/get_tilescalex/
---
## IPictureFillFormat::get_TileScaleX() method


Returns the horizontal scale for the texture fill as a percentage. Read **float**.

```cpp
virtual float Aspose::Slides::IPictureFillFormat::get_TileScaleX()=0
```

## Remarks



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Gets the picture fill format of the shape
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Sets the picture fill mode to Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Sets the horizontal scale for the texture to 120 percents
pictureFillFormat->set_TileScaleX(120.0f);
```

## See Also

* Class [IPictureFillFormat](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)