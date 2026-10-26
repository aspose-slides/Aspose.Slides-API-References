---
title: set_ReturnToParent()
second_title: Aspose.Slides for C++ API 레퍼런스
description: "슬라이드쇼에서 탐색 동작을 설정합니다. bool을 씁니다. 기본값: false"
type: docs
weight: 40
url: /ko/aspose.slides/zoomobject/set_returntoparent/
---
## ZoomObject::set_ReturnToParent(bool) 메서드

슬라이드쇼에서 탐색 동작을 설정합니다. **bool**을 씁니다. 기본값: false

```cpp
void Aspose::Slides::ZoomObject::set_ReturnToParent(bool value) override
```

## 비고

속성의 true 값은 슬라이드쇼에서 부모로 돌아가는 탐색 동작을 지정합니다.

예시: 
```cpp
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_ReturnToParent(true);
```

## 추가 참조

* 클래스 [ZoomObject](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)