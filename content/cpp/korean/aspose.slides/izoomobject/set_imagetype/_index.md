---
title: set_ImageType()
second_title: Aspose.Slides for C++ API 참조
description: "줌 객체의 이미지 유형을 설정합니다. ZoomImageType을 작성합니다. 기본값: Preview"
type: docs
weight: 14
url: /ko/aspose.slides/izoomobject/set_imagetype/
---
## IZoomObject::set_ImageType(ZoomImageType) 메서드


줌 객체의 이미지 유형을 설정합니다. 작성 [ZoomImageType](../../zoomimagetype/). 기본값: Preview

```cpp
virtual void Aspose::Slides::IZoomObject::set_ImageType(ZoomImageType value)=0
```

## 비고


Zoom 객체가 슬라이드 미리보기 또는 표지 이미지를 사용하는지 지정합니다. 

이 예제는 Image Type을 Preview 값으로 변경하는 것을 보여줍니다. 이 경우 Zoom 객체의 현재 이미지가 슬라이드 이미지로 변경됩니다: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto image = pres->get_Images()->AddImage(Image::FromFile(u"image.png"));
auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1), image);
zoomFrame->set_ImageType(ZoomImageType::Preview);
```

## 참조

* Enum [ZoomImageType](../../zoomimagetype/)
* Class [IZoomObject](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)