---
title: get_ImageType()
second_title: Aspose.Slides for C++ API 레퍼런스
description: "줌 객체의 이미지 유형을 가져옵니다. ZoomImageType을 읽으세요. 기본값: Preview"
type: docs
weight: 1
url: /ko/aspose.slides/zoomobject/get_imagetype/
---
## ZoomObject::get_ImageType() 메서드

줌 객체의 이미지 유형을 가져옵니다. [ZoomImageType](../../zoomimagetype/)를 읽으세요. 기본값: Preview

```cpp
ZoomImageType Aspose::Slides::ZoomObject::get_ImageType() override
```

## 비고

Zoom 객체가 슬라이드 미리 보기 또는 표지 이미지를 사용하고 있는지 지정합니다.

다음 예제는 이미지 유형을 Preview 값으로 변경하는 것을 보여줍니다. 이 경우 Zoom 객체의 현재 이미지가 슬라이드 이미지로 변경됩니다: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto image = pres->get_Images()->AddImage(Image::FromFile(u"image.png"));
auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1), image);
zoomFrame->set_ImageType(ZoomImageType::Preview);
```

## 참고

* 열거형 [ZoomImageType](../../zoomimagetype/)
* 클래스 [ZoomObject](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)