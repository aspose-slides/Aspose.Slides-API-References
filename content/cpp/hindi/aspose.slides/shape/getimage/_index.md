---
title: GetImage()
second_title: Aspose.Slides for C++ API संदर्भ
description: "shape थंबनेल लौटाता है। ShapeThumbnailBounds::Shape shape थंबनेल बाउंड्स प्रकार डिफ़ॉल्ट रूप से उपयोग किया जाता है।"
type: docs
weight: 651
url: /hi/aspose.slides/shape/getimage/
---
## Shape::GetImage() विधि

shape थंबनेल लौटाता है। [ShapeThumbnailBounds::Shape](../../shapethumbnailbounds/) shape thumbnail bounds type डिफ़ॉल्ट रूप से उपयोग किया जाता है।

```cpp
System::SharedPtr<IImage> Aspose::Slides::Shape::GetImage() override
```


### रिटर्न वैल्यू

[Shape](../) थंबनेल।

## Shape::GetImage(ShapeThumbnailBounds, float, float) विधि

shape थंबनेल लौटाता है।

```cpp
System::SharedPtr<IImage> Aspose::Slides::Shape::GetImage(ShapeThumbnailBounds bounds, float scaleX, float scaleY) override
```


### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| bounds | [ShapeThumbnailBounds](../../shapethumbnailbounds/) | [Shape](../) थंबनेल बाउंड्स प्रकार। |
| scaleX | **float** | X स्केल |
| scaleY | **float** | Y स्केल |

### रिटर्न वैल्यू

[Shape](../) थंबनेल या null जब [ShapeThumbnailBounds::Appearance](../../shapethumbnailbounds/) उपयोग किया जाता है और एक shape में दृश्यमान तत्व नहीं होते हैं।

## देखें

* Enum [ShapeThumbnailBounds](../../shapethumbnailbounds/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IImage](../../iimage/)
* Class [Shape](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)