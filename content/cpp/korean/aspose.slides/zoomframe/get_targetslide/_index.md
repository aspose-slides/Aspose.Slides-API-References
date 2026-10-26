---
title: get_TargetSlide()
second_title: C++용 Aspose.Slides API 레퍼런스
description: Slide Zoom 객체가 연결하는 슬라이드 객체를 가져옵니다. ISlide를 읽으십시오.
type: docs
weight: 1
url: /ko/aspose.slides/zoomframe/get_targetslide/
---
## ZoomFrame::get_TargetSlide() 메서드


[Slide](../../slide/) Zoom 객체가 연결하는 슬라이드 객체를 가져옵니다. [ISlide](../../islide/)을(를) 읽으십시오.

```cpp
System::SharedPtr<ISlide> Aspose::Slides::ZoomFrame::get_TargetSlide() override
```

## 비고


다음 예제는 대상 슬라이드를 변경하고 [Slide](../../slide/) Zoom 객체에 대한 새 이미지를 생성하는 것을 보여줍니다: 
```cpp
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_TargetSlide(pres->get_Slides()->idx_get(2));
```

## 참조

* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [ISlide](../../islide/)
* 클래스 [ZoomFrame](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)