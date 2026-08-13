---
title: set_TransitionDuration()
second_title: Aspose.Slides for C++ API 레퍼런스
description: "Zoom과 슬라이드 사이 전환의 지속 시간을 설정합니다. float을 입력합니다. 기본값: 1.0f"
type: docs
weight: 118
url: /ko/aspose.slides/zoomobject/set_transitionduration/
---
## ZoomObject::set_TransitionDuration(float) 메서드

Zoom과 슬라이드 사이 전환의 지속 시간을 설정합니다. **float** 형식으로 입력합니다. 기본값: 1.0f

```cpp
void Aspose::Slides::ZoomObject::set_TransitionDuration(float value) override
```

## 비고

지정되지 않은 경우 (TransitionDur = 0), 대상 슬라이드 전환 및 해당 전환과 연결된 타이밍을 사용합니다.

예제는 Zoom과 슬라이드 사이 전환의 지속 시간을 변경하는 방법을 보여줍니다:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_TransitionDuration(2.5f);
```

## 참조

* 클래스 [ZoomObject](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)