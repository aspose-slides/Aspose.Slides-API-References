---
title: WriteAsEmf()
second_title: Aspose.Slides for C++ API Reference
description: Saves the SVG image as an EMF file.
type: docs
weight: 53
url: /aspose.slides/isvgimage/writeasemf/
---
## ISvgImage::WriteAsEmf(System::SharedPtr\<System::IO::Stream\>) method


Saves the SVG image as an EMF file.

```cpp
virtual void Aspose::Slides::ISvgImage::WriteAsEmf(System::SharedPtr<System::IO::Stream> stream)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Target stream |
## Remarks



The following example demonstrates how to save the SVG image into a metafile. 
```cpp
// Creates the new SVG image
System::SharedPtr<ISvgImage> svgImage = System::MakeObject<SvgImage>(System::IO::File::ReadAllText(u"content.svg"));

// Saves the SVG image as a metafille
auto fileStream = System::IO::File::OpenWrite(u"SvgAsEmf.emf");
svgImage->WriteAsEmf(fileStream);
```
 This sample demonstrates how to add the SVG image as a metafile to the presentation image collection. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Creates the new SVG image
System::SharedPtr<ISvgImage> svgImage = System::MakeObject<SvgImage>(System::IO::File::ReadAllText(u"content.svg"));
auto memStream = System::MakeObject<System::IO::MemoryStream>();

// Saves the SVG image as a metafille
svgImage->WriteAsEmf(memStream);
// Adds metafile to the image collection
pres->get_Images()->AddImage(memStream->ToArray());
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [ISvgImage](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)