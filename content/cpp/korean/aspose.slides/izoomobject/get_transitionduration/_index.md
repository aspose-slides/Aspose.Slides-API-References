---
title: get_TransitionDuration()
second_title: Aspose.Slides for C++ API 참조
description: "Zoom과 슬라이드 사이 전환의 지속 시간을 가져옵니다. float를 읽습니다. 기본값: 1.0f"
type: docs
weight: 105
url: /ko/aspose.slides/izoomobject/get_transitionduration/
---
## IZoomObject::get_TransitionDuration() 메서드


Zoom과 슬라이드 사이 전환의 지속 시간을 가져옵니다. **float** 읽기. 기본값: 1.0f

```cpp
virtual float Aspose::Slides::IZoomObject::get_TransitionDuration()=0
```

## 비고

지정되지 않은 경우(TransitionDur = 0), 대상 슬라이드 전환 및 해당 전환과 연결된 타이밍을 사용합니다.

예제는 Zoom과 슬라이드 사이 전환 지속 시간을 변경하는 방법을 보여줍니다:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_TransitionDuration(2.5f);
```

## 참조

* 클래스 [IZoomObject](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)