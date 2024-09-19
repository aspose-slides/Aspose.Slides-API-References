---
title: CompressImage()
second_title: Aspose.Slides for C++ API Reference
description: Compresses the image by reducing its size based on the shape size and specified resolution. Optionally, it also deletes cropped areas.
type: docs
weight: 443
url: /aspose.slides/ipicturefillformat/compressimage/
---
## IPictureFillFormat::CompressImage(bool, float) method


Compresses the image by reducing its size based on the shape size and specified resolution. Optionally, it also deletes cropped areas.

```cpp
virtual bool Aspose::Slides::IPictureFillFormat::CompressImage(bool deleteCroppedAreasOfImage, float resolution)=0
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
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Gets the PictureFrame
System::SharedPtr<IPictureFrame> picFrame = System::AsCast<IPictureFrame>(slide->get_Shape(0));

// Compress the image with a target resolution of 150 DPI (Web resolution) and remove cropped areas
bool result = picFrame->get_PictureFormat()->CompressImage(true, 150.0f); // Web resolution
```

## See Also

* Class [IPictureFillFormat](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)