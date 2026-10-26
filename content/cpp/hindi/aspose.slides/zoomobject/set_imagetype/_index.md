---
title: set_ImageType()
second_title: Aspose.Slides for C++ API संदर्भ
description: "ज़ूम ऑब्जेक्ट का इमेज टाइप सेट करता है। लिखें ZoomImageType. Default value: Preview"
type: docs
weight: 14
url: /hi/aspose.slides/zoomobject/set_imagetype/
---
## ZoomObject::set_ImageType(ZoomImageType) विधि


ज़ूम ऑब्जेक्ट का इमेज टाइप सेट करता है। लिखें [ZoomImageType](../../zoomimagetype/)। डिफ़ॉल्ट मान: Preview

```cpp
void Aspose::Slides::ZoomObject::set_ImageType(ZoomImageType value) override
```

## टिप्पणियाँ


निर्दिष्ट करता है कि Zoom ऑब्जेक्ट स्लाइड प्रीव्यू का उपयोग कर रहा है या कवर इमेज। 

अगला उदाहरण Image Type को Preview मान में बदलना दर्शाता है। इस मामले में Zoom ऑब्जेक्ट की वर्तमान इमेज स्लाइड इमेज में बदल जाती है: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto image = pres->get_Images()->AddImage(Image::FromFile(u"image.png"));
auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1), image);
zoomFrame->set_ImageType(ZoomImageType::Preview);
```

## संबंधित देखें

* Enum [ZoomImageType](../../zoomimagetype/)
* क्लास [ZoomObject](../)
* नामस्थान [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)