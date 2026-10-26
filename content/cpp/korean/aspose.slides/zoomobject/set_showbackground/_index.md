---
title: set_ShowBackground()
second_title: Aspose.Slides C++ API 참조
description: "Zoom이 대상 슬라이드의 배경을 사용할지 여부를 지정하는 값을 설정합니다. bool 형식으로 작성합니다. 기본값: true"
type: docs
weight: 66
url: /ko/aspose.slides/zoomobject/set_showbackground/
---
## ZoomObject::set_ShowBackground(bool) 메서드


Zoom이 대상 슬라이드의 배경을 사용할지 여부를 지정하는 값을 설정합니다. **bool** 형식으로 작성합니다. 기본값: true

```cpp
void Aspose::Slides::ZoomObject::set_ShowBackground(bool value) override
```

## 비고


예제는 Zoom 객체 이미지의 배경을 제거하는 방법을 보여줍니다:
```cpp
auto pres = System::MakeObject<Presentation>();
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_ShowBackground(false);
```

## 참조

* 클래스 [ZoomObject](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)