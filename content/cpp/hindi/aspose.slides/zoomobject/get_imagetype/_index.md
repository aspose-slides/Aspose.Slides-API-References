---
title: get_ImageType()
second_title: Aspose.Slides for C++ API संदर्भ
description: "Zoom ऑब्जेक्ट का छवि प्रकार प्राप्त करता है। पढ़ें ZoomImageType। डिफ़ॉल्ट मान: Preview"
type: docs
weight: 1
url: /hi/aspose.slides/zoomobject/get_imagetype/
---
## ZoomObject::get_ImageType() विधि

Zoom ऑब्जेक्ट के छवि प्रकार को प्राप्त करता है। पढ़ें [ZoomImageType](../../zoomimagetype/)। डिफ़ॉल्ट मान: Preview

```cpp
ZoomImageType Aspose::Slides::ZoomObject::get_ImageType() override
```

## टिप्पणियाँ

निर्दिष्ट करता है कि Zoom ऑब्जेक्ट स्लाइड प्रीव्यू या कवर छवि का उपयोग कर रहा है।

अगला उदाहरण छवि प्रकार को Preview मान में बदलने को दर्शाता है। इस मामले में Zoom ऑब्जेक्ट की वर्तमान छवि स्लाइड छवि में बदल जाती है:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto image = pres->get_Images()->AddImage(Image::FromFile(u"image.png"));
auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1), image);
zoomFrame->set_ImageType(ZoomImageType::Preview);
```

## देखें

* एनम [ZoomImageType](../../zoomimagetype/)
* क्लास [ZoomObject](../)
* नामस्थान [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)