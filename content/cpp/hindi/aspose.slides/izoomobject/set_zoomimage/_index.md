---
title: set_ZoomImage()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: ज़ूम ऑब्जेक्ट के लिए छवि सेट करता है। लिखें IPPImage.
type: docs
weight: 92
url: /hi/aspose.slides/izoomobject/set_zoomimage/
---
## IZoomObject::set_ZoomImage(System::SharedPtr\<IPPImage\>) method

ज़ूम ऑब्जेक्ट के लिए छवि सेट करता है। लिखें [IPPImage](../../ippimage/).

```cpp
virtual void Aspose::Slides::IZoomObject::set_ZoomImage(System::SharedPtr<IPPImage> value)=0
```

## टिप्पणी

यह उदाहरण ज़ूम ऑब्जेक्ट की छवि बदलने का प्रदर्शन करता है:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slide(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slide(1));
System::SharedPtr<IPPImage> image = pres->get_Images()->AddImage(System::Drawing::Image::FromFile(u"image.png"));
zoomFrame->set_ZoomImage(image);
```

## देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [IPPImage](../../ippimage/)
* क्लास [IZoomObject](../)
* नामस्थान [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)