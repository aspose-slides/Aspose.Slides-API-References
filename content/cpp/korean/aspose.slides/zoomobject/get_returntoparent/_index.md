---
title: get_ReturnToParent()
second_title: Aspose.Slides for C++ API 레퍼런스
description: "슬라이드쇼에서 탐색 동작을 가져옵니다. 읽기 bool. 기본값: false"
type: docs
weight: 27
url: /ko/aspose.slides/zoomobject/get_returntoparent/
---
## ZoomObject::get_ReturnToParent() method

슬라이드쇼에서 탐색 동작을 가져옵니다. 읽기 **bool**. 기본값: false

```cpp
bool Aspose::Slides::ZoomObject::get_ReturnToParent() override
```

## 비고

속성의 true 값은 슬라이드쇼에서 상위로 돌아가는 탐색 동작을 지정합니다.

예시:
```cpp
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_ReturnToParent(true);
```

## 참고

* 클래스 [ZoomObject](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)