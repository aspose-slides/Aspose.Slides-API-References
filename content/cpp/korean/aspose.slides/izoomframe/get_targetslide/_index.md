---
title: get_TargetSlide()
second_title: Aspose.Slides for C++ API 레퍼런스
description: Slide Zoom 객체가 링크하는 슬라이드 객체를 가져옵니다. ISlide을 읽으십시오.
type: docs
weight: 1
url: /ko/aspose.slides/izoomframe/get_targetslide/
---
## IZoomFrame::get_TargetSlide() 메서드

[Slide](../../slide/) Zoom 객체가 연결되는 슬라이드 객체를 가져옵니다. [ISlide](../../islide/)를 읽으십시오.

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::IZoomFrame::get_TargetSlide()=0
```

## 비고

다음 예제는 대상 슬라이드를 변경하고 [Slide](../../slide/) Zoom 객체에 대한 새 이미지를 생성하는 방법을 보여줍니다:
```cpp
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_TargetSlide(pres->get_Slides()->idx_get(2));
```

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISlide](../../islide/)
* Class [IZoomFrame](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)