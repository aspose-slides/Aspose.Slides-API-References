---
title: get_ShowBackground()
second_title: Aspose.Slides C++ API 참조
description: "Zoom이 대상 슬라이드의 배경을 사용할지 여부를 지정하는 값을 가져옵니다. 읽기 전용 bool. 기본값: true"
type: docs
weight: 53
url: /ko/aspose.slides/zoomobject/get_showbackground/
---
## ZoomObject::get_ShowBackground() 메서드

Zoom이 대상 슬라이드의 배경을 사용할지 여부를 지정하는 값을 가져옵니다. 읽기 전용 **bool**. 기본값: true

```cpp
bool Aspose::Slides::ZoomObject::get_ShowBackground() override
```

## 비고

예제에서는 Zoom 개체의 이미지 배경을 제거하는 방법을 보여줍니다:
```cpp
auto pres = System::MakeObject<Presentation>();
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_ShowBackground(false);
```

## 관련 항목

* 클래스 [ZoomObject](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)