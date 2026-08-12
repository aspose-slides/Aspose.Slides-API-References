---
title: GetImage()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: "आकार थंबनेल लौटाता है। ShapeThumbnailBounds::Shape आकार थंबनेल बाउंड्स प्रकार डिफ़ॉल्ट रूप से उपयोग किया जाता है।"
type: docs
weight: 547
url: /hi/aspose.slides/ishape/getimage/
---
## IShape::GetImage() मेथड


आकार थंबनेल लौटाता है। [ShapeThumbnailBounds::Shape](../../shapethumbnailbounds/) shape thumbnail bounds type डिफ़ॉल्ट रूप से उपयोग किया जाता है।

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::IShape::GetImage()=0
```


### रिटर्न वैल्यू

[Shape](../../shape/) थंबनेल।

## IShape::GetImage(ShapeThumbnailBounds, float, float) मेथड


आकार थंबनेल लौटाता है।

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::IShape::GetImage(ShapeThumbnailBounds bounds, float scaleX, float scaleY)=0
```


### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| bounds | [ShapeThumbnailBounds](../../shapethumbnailbounds/) | [Shape](../../shape/) थंबनेल बाउंड्स टाइप। |
| scaleX | **float** | X स्केल |
| scaleY | **float** | Y स्केल |

### रिटर्न वैल्यू

[Shape](../../shape/) थंबनेल या null जब [ShapeThumbnailBounds::Appearance](../../shapethumbnailbounds/) उपयोग किया जाता है और एक आकार में दृश्यमान तत्व नहीं होते हैं।

## देखें

* एनम [ShapeThumbnailBounds](../../shapethumbnailbounds/)
* टाइपडेफ़ [SharedPtr](../../../system/sharedptr/)
* क्लास [IImage](../../iimage/)
* क्लास [IShape](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)