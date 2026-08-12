---
title: get_ZoomImage()
second_title: Aspose.Slides for C++ API संदर्भ
description: Zoom ऑब्जेक्ट के लिए चित्र प्राप्त करता है। IPPImage पढ़ें।
type: docs
weight: 79
url: /hi/aspose.slides/izoomobject/get_zoomimage/
---
## IZoomObject::get_ZoomImage() विधि


Zoom ऑब्जेक्ट के लिए चित्र प्राप्त करता है। पढ़ें [IPPImage](../../ippimage/).

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IZoomObject::get_ZoomImage()=0
```

## टिप्पणी


यह उदाहरण Zoom ऑब्जेक्ट की छवि बदलना दर्शाता है: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slide(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slide(1));
System::SharedPtr<IPPImage> image = pres->get_Images()->AddImage(System::Drawing::Image::FromFile(u"image.png"));
zoomFrame->set_ZoomImage(image);
```

## देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPPImage](../../ippimage/)
* Class [IZoomObject](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)