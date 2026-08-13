---
title: set_TargetSlide()
second_title: Aspose.Slides C++용 API 참조
description: Slide Zoom 객체가 연결되는 슬라이드 개체를 설정합니다. ISlide를 씁니다.
type: docs
weight: 14
url: /ko/aspose.slides/izoomframe/set_targetslide/
---
## IZoomFrame::set_TargetSlide(System::SharedPtr\<ISlide\>) method

[Slide](../../slide/) Zoom 객체가 연결되는 슬라이드 개체를 설정합니다. [ISlide](../../islide/)를 씁니다.

```cpp
virtual void Aspose::Slides::IZoomFrame::set_TargetSlide(System::SharedPtr<ISlide> value)=0
```

## 주석

다음 예제는 대상 슬라이드를 변경하고 [Slide](../../slide/) Zoom 객체에 대한 새 이미지를 생성하는 방법을 보여줍니다:
```cpp
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_TargetSlide(pres->get_Slides()->idx_get(2));
```

## 참고

* typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [ISlide](../../islide/)
* 클래스 [IZoomFrame](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)