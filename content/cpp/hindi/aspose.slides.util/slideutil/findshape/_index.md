---
title: FindShape()
second_title: Aspose.Slides for C++ API संदर्भ
description: PPTX प्रस्तुति में वैकल्पिक टेक्स्ट द्वारा आकार खोजें।
type: docs
weight: 1
url: /hi/aspose.slides.util/slideutil/findshape/
---
## SlideUtil::FindShape(System::SharedPtr\<IPresentation\>, System::String) method


PPTX प्रस्तुति में वैकल्पिक टेक्स्ट द्वारा आकार खोजें।

```cpp
static System::SharedPtr<IShape> Aspose::Slides::Util::SlideUtil::FindShape(System::SharedPtr<IPresentation> pres, System::String altText)
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[IPresentation](../../../aspose.slides/ipresentation/)\> | स्कैन किया गया प्रस्तुतीकरण। |
| altText | [System::String](../../../system/string/) | आकार का वैकल्पिक टेक्स्ट। |

### रिटर्न वैल्यू

[Shape](../../../aspose.slides/shape/) या null।

## SlideUtil::FindShape(System::SharedPtr\<IBaseSlide\>, System::String) method


PPTX प्रस्तुति में स्लाइड पर वैकल्पिक टेक्स्ट द्वारा आकार खोजें।

```cpp
static System::SharedPtr<IShape> Aspose::Slides::Util::SlideUtil::FindShape(System::SharedPtr<IBaseSlide> slide, System::String altText)
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[IBaseSlide](../../../aspose.slides/ibaseslide/)\> | स्कैन किया गया स्लाइड। |
| altText | [System::String](../../../system/string/) | आकार का वैकल्पिक टेक्स्ट। |

### रिटर्न वैल्यू

[Shape](../../../aspose.slides/shape/) या null।

## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [IShape](../../../aspose.slides/ishape/)
* क्लास [IPresentation](../../../aspose.slides/ipresentation/)
* क्लास [String](../../../system/string/)
* क्लास [SlideUtil](../)
* क्लास [IBaseSlide](../../../aspose.slides/ibaseslide/)
* नामस्थान [Aspose::Slides::Util](../../)
* लाइब्रेरी [Aspose.Slides](../../../)