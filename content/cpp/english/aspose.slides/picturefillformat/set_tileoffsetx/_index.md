---
title: set_TileOffsetX()
second_title: Aspose.Slides for C++ API Reference
description: Sets the horizontal offset of the texture from the shape's origin in points. A positive value moves the texture to the right, while a negative value moves it to the left. Write float.
type: docs
weight: 287
url: /aspose.slides/picturefillformat/set_tileoffsetx/
---
## PictureFillFormat::set_TileOffsetX(float) method


Sets the horizontal offset of the texture from the shape's origin in points. A positive value moves the texture to the right, while a negative value moves it to the left. Write **float**.

```cpp
void Aspose::Slides::PictureFillFormat::set_TileOffsetX(float value) override
```

## Remarks



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Gets the picture fill format of the shape
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Sets the picture fill mode to Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Sets the horizontal offset of the texture to 20 points
pictureFillFormat->set_TileOffsetX(20.0f);
```

## See Also

* Class [PictureFillFormat](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)