---
title: CompressImage()
second_title: Aspose.Slides for C++ API Reference
description: Compresses the image by reducing its size based on the shape size and specified resolution. Optionally, it also deletes cropped areas.
type: docs
weight: 443
url: /aspose.slides/picturefillformat/compressimage/
---
## PictureFillFormat::CompressImage(bool, float) method


Compresses the image by reducing its size based on the shape size and specified resolution. Optionally, it also deletes cropped areas.

```cpp
bool Aspose::Slides::PictureFillFormat::CompressImage(bool deleteCroppedAreasOfImage, float resolution) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| deleteCroppedAreasOfImage | **bool** | If true, the method will remove the cropped areas of the image, potentially further reducing its size. |
| resolution | **float** | The target resolution in DPI. This value must be positive and defines how the image will be resized. |

### Return Value

A **bool** indicating whether the image was successfully compressed. Returns ****true****
## Remarks


This method changes the image's size and resolution similar to PowerPoint's \"Picture Format -> Compress Pictures\" feature.


if the image was resized or cropped, otherwise ****false****

. 


The following example demonstrates how to use the **CompressImage** method to reduce the size of an image in a presentation by setting a target resolution and removing cropped areas: 
```cpp
[C#]
using (Presentation presentation = new Presentation("demo.pptx"))
{
    ISlide slide = presentation.Slides[0];

    // Gets the PictureFrame
    IPictureFrame picFrame = slide.Shapes[0] as IPictureFrame;

    // Compress the image with a target resolution of 150 DPI (Web resolution) and remove cropped areas
    bool result=picFrame.PictureFormat.CompressImage(true, 150f); // Web resolution
}
```

## See Also

* Class [PictureFillFormat](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)