---
title: get_ZoomImage()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: Zoom ऑब्जेक्ट के लिए छवि प्राप्त करता है। पढ़ें IPPImage.
type: docs
weight: 79
url: /hi/aspose.slides/zoomobject/get_zoomimage/
---
## ZoomObject::get_ZoomImage() विधि


Zoom ऑब्जेक्ट के लिए छवि प्राप्त करता है। पढ़ें [IPPImage](../../ippimage/).

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ZoomObject::get_ZoomImage() override
```

## टिप्पणी


उदाहरण दिखाता है कि कैसे Zoom ऑब्जेक्ट की छवि को बदलते हैं:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slide(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slide(1));
System::SharedPtr<IPPImage> image = pres->get_Images()->AddImage(System::Drawing::Image::FromFile(u"image.png"));
zoomFrame->set_ZoomImage(image);
```

## देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [IPPImage](../../ippimage/)
* क्लास [ZoomObject](../)
* नामस्थान [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)