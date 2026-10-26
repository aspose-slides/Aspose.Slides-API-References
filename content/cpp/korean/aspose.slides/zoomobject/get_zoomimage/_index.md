---
title: get_ZoomImage()
second_title: Aspose.Slides for C++ API 레퍼런스
description: Zoom 객체의 이미지를 가져옵니다. IPPImage를 읽어보세요.
type: docs
weight: 79
url: /ko/aspose.slides/zoomobject/get_zoomimage/
---
## ZoomObject::get_ZoomImage() 메서드

Zoom 객체의 이미지를 가져옵니다. [IPPImage](../../ippimage/)를 읽어보세요.

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ZoomObject::get_ZoomImage() override
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
* 클래스 [ZoomObject](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)