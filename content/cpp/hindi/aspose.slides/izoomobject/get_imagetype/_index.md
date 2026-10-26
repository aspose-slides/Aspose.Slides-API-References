---
title: get_ImageType()
second_title: Aspose.Slides C++ के लिए API संदर्भ
description: "Zoom ऑब्जेक्ट का इमेज प्रकार प्राप्त करता है। ZoomImageType पढ़ें। डिफ़ॉल्ट मान: Preview"
type: docs
weight: 1
url: /hi/aspose.slides/izoomobject/get_imagetype/
---
## IZoomObject::get_ImageType() method


Zoom ऑब्जेक्ट का इमेज प्रकार प्राप्त करता है। पढ़ें [ZoomImageType](../../zoomimagetype/)। डिफ़ॉल्ट मान: Preview

```cpp
virtual ZoomImageType Aspose::Slides::IZoomObject::get_ImageType()=0
```

## टिप्पणियाँ


निर्दिष्ट करता है कि Zoom ऑब्जेक्ट स्लाइड प्रीव्यू या कवर इमेज का उपयोग कर रहा है।

यह उदाहरण Image Type को Preview मान में बदलने को दर्शाता है। इस मामले में Zoom ऑब्जेक्ट की वर्तमान इमेज स्लाइड इमेज में बदल जाती है: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto image = pres->get_Images()->AddImage(Image::FromFile(u"image.png"));
auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1), image);
zoomFrame->set_ImageType(ZoomImageType::Preview);
```

## संबंधित

* एन्यूम [ZoomImageType](../../zoomimagetype/)
* क्लास [IZoomObject](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)