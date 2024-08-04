---
title: get_TileOffsetY()
second_title: Aspose.Slides for C++ API Reference
description: Returns the vertical offset of the texture from the shape's origin in points. A positive value moves the texture down, while a negative value moves it up. Read float.
type: docs
weight: 300
url: /aspose.slides/picturefillformat/get_tileoffsety/
---
## PictureFillFormat::get_TileOffsetY() method


Returns the vertical offset of the texture from the shape's origin in points. A positive value moves the texture down, while a negative value moves it up. Read **float**.

```cpp
float Aspose::Slides::PictureFillFormat::get_TileOffsetY() override
```

## Remarks



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Gets the picture fill format of the shape
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Sets the picture fill mode to Tile
pictureFillFormat->set_PictureFillMode(Aspose::Slides::PictureFillMode::Tile);

// Sets the vertical offset of the texture to -50 points
pictureFillFormat->set_TileOffsetY(-50.0f);
```

## See Also

* Class [PictureFillFormat](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)