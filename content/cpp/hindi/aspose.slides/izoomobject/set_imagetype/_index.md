---
title: set_ImageType()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: "एक ज़ूम ऑब्जेक्ट का इमेज टाइप सेट करता है। लिखें ZoomImageType। डिफ़ॉल्ट मान: Preview"
type: docs
weight: 14
url: /hi/aspose.slides/izoomobject/set_imagetype/
---
## IZoomObject::set_ImageType(ZoomImageType) विधि

एक ज़ूम ऑब्जेक्ट का इमेज टाइप सेट करता है। लिखें [ZoomImageType](../../zoomimagetype/)। डिफ़ॉल्ट मान: Preview

```cpp
virtual void Aspose::Slides::IZoomObject::set_ImageType(ZoomImageType value)=0
```

## टिप्पणी

निर्दिष्ट करता है कि ज़ूम ऑब्जेक्ट स्लाइड प्रीव्यू या कवर इमेज का उपयोग कर रहा है।

यह उदाहरण इमेज टाइप को Preview मान में बदलने को दर्शाता है। इस स्थिति में ज़ूम ऑब्जेक्ट की वर्तमान इमेज स्लाइड इमेज में बदल जाती है:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto image = pres->get_Images()->AddImage(Image::FromFile(u"image.png"));
auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1), image);
zoomFrame->set_ImageType(ZoomImageType::Preview);
```

## देखें

* एनम [ZoomImageType](../../zoomimagetype/)
* क्लास [IZoomObject](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)