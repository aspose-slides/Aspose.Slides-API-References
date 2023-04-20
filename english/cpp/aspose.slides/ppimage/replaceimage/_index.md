---
title: ReplaceImage()
second_title: Aspose.Slides for C++ API Reference
description: Replaces image data.
type: docs
weight: 118
url: /cpp/aspose.slides/ppimage/replaceimage/
---
## PPImage::ReplaceImage(System::ArrayPtr\<uint8_t\>) method


Replaces image data.

```cpp
void Aspose::Slides::PPImage::ReplaceImage(System::ArrayPtr<uint8_t> newImageData) override
```

## PPImage::ReplaceImage(System::SharedPtr\<System::Drawing::Image\>) method


Replaces image data. Attention: when Image is metafile - it will be rasterized due to restrictions of GDI+. Use ReplaceImage(byte[]) instead

```cpp
void Aspose::Slides::PPImage::ReplaceImage(System::SharedPtr<System::Drawing::Image> newImage) override
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
* Class [Image](../../../system.drawing/image/)
* Class [IPPImage](../../ippimage/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)