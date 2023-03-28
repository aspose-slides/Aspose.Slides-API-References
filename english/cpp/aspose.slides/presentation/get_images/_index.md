---
title: get_Images()
second_title: Aspose.Slides for C++ API Reference
description: Returns the collection of all images in the presentation. Read-only IImageCollection.
type: docs
weight: 209
url: /cpp/aspose.slides/presentation/get_images/
---
## Presentation::get_Images() method


Returns the collection of all images in the presentation. Read-only [IImageCollection](../../iimagecollection/).

```cpp
System::SharedPtr<IImageCollection> Aspose::Slides::Presentation::get_Images() override
```

## Remarks


The following examples shows how to add image as BLOB in PowerPoint [Presentation](../). 
```cpp
System::String pathToLargeImage = u"large_image.jpg";
// creates a new presentation to which the image will be added.
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);

auto fileStream = System::MakeObject<System::IO::FileStream>(pathToLargeImage, System::IO::FileMode::Open);

// Let's add the image to the presentation - we choose KeepLocked behavior because we do
// NOT intend to access the "largeImage.png" file.
auto img = pres->get_Images()->AddImage(fileStream, LoadingStreamBehavior::KeepLocked);
slide->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 0.0f, 0.0f, 300.0f, 200.0f, img);
// Saves the presentation. While a large presentation gets outputted, the memory consumption
// stays low through the pres object's lifecycle
pres->Save(u"presentationWithLargeImage.pptx", SaveFormat::Pptx);
```
 The following examples add a hyperlink to an image in a PowerPoint [Presentation](../). 
```cpp
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);

// Adds image to presentation
auto image = pres->get_Images()->AddImage(System::IO::File::ReadAllBytes(u"image.png"));
// Creates picture frame on slide 1 based on previously added image
auto pictureFrame = slide->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 10.0f, 10.0f, 100.0f, 100.0f, image);
pictureFrame->set_HyperlinkClick(System::MakeObject<Hyperlink>(u"https://www.aspose.com/"));
pictureFrame->get_HyperlinkClick()->set_Tooltip(u"More than 70% Fortune 100 companies trust Aspose APIs");
pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IImageCollection](../../iimagecollection/)
* Class [Presentation](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
