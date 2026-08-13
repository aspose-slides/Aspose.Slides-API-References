---
title: get_ZoomImage()
second_title: Aspose.Slides C++ API 참조
description: 줌 객체에 대한 이미지를 가져옵니다. IPPImage를 읽으십시오.
type: docs
weight: 79
url: /ko/aspose.slides/izoomobject/get_zoomimage/
---
## IZoomObject::get_ZoomImage() 메서드


줌 객체에 대한 이미지를 가져옵니다. 읽으십시오 [IPPImage](../../ippimage/).

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IZoomObject::get_ZoomImage()=0
```

## 비고


예제는 Zoom 객체의 이미지를 변경하는 방법을 보여줍니다: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slide(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slide(1));
System::SharedPtr<IPPImage> image = pres->get_Images()->AddImage(System::Drawing::Image::FromFile(u"image.png"));
zoomFrame->set_ZoomImage(image);
```

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IPPImage](../../ippimage/)
* 클래스 [IZoomObject](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)