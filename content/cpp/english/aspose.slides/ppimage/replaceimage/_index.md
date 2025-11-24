---
title: ReplaceImage()
second_title: Aspose.Slides for C++ API Reference
description: Replaces image data.
type: docs
weight: 118
url: /aspose.slides/ppimage/replaceimage/
---
## PPImage::ReplaceImage(System::ArrayPtr\<uint8_t\>) method


Replaces image data.

```cpp
void Aspose::Slides::PPImage::ReplaceImage(System::ArrayPtr<uint8_t> newImageData) override
```

## PPImage::ReplaceImage(System::SharedPtr\<Aspose::Slides::IImage\>) method


Replaces image data. Attention: when Image is metafile - it will be rasterized. Use ReplaceImage(byte[]) instead

```cpp
void Aspose::Slides::PPImage::ReplaceImage(System::SharedPtr<Aspose::Slides::IImage> newImage) override
```




## PPImage::ReplaceImage(System::SharedPtr\<Aspose::Slides::IPPImage\>) method


Replaces image data.

```cpp
void Aspose::Slides::PPImage::ReplaceImage(System::SharedPtr<Aspose::Slides::IPPImage> newImage) override
```

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [PPImage](../)
* Class [IImage](../../iimage/)
* Class [IPPImage](../../ippimage/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)