---
title: set_TileScaleX()
second_title: Aspose.Slides for C++ API Reference
description: Sets the horizontal scale for the texture fill as a percentage. Write float.
type: docs
weight: 339
url: /aspose.slides/ipicturefillformat/set_tilescalex/
---
## IPictureFillFormat::set_TileScaleX(float) method


Sets the horizontal scale for the texture fill as a percentage. Write **float**.

```cpp
virtual void Aspose::Slides::IPictureFillFormat::set_TileScaleX(float value)=0
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