---
title: set_TileOffsetY()
second_title: Aspose.Slides for C++ API Reference
description: Sets the vertical offset of the texture from the shape's origin in points. A positive value moves the texture down, while a negative value moves it up. Write float.
type: docs
weight: 313
url: /aspose.slides/ipicturefillformat/set_tileoffsety/
---
## IPictureFillFormat::set_TileOffsetY(float) method


Sets the vertical offset of the texture from the shape's origin in points. A positive value moves the texture down, while a negative value moves it up. Write **float**.

```cpp
virtual void Aspose::Slides::IPictureFillFormat::set_TileOffsetY(float value)=0
```

## Remarks



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Gets the picture fill format of the shape
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Sets the picture fill mode to Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Sets the vertical offset of the texture to -50 points
pictureFillFormat->set_TileOffsetY(-50.0f);
```

## See Also

* Class [IPictureFillFormat](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)