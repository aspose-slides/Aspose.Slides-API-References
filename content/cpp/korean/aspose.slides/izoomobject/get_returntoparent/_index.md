---
title: get_ReturnToParent()
second_title: Aspose.Slides for C++ API 레퍼런스
description: "슬라이드쇼에서 탐색 동작을 가져옵니다. 읽기 bool. 기본값: false"
type: docs
weight: 27
url: /ko/aspose.slides/izoomobject/get_returntoparent/
---
## IZoomObject::get_ReturnToParent() 메서드

슬라이드쇼에서 탐색 동작을 가져옵니다. 읽기 **bool**. 기본값: false

```cpp
virtual bool Aspose::Slides::IZoomObject::get_ReturnToParent()=0
```
## 비고

True 값은 슬라이드쇼에서 부모로 반환하는 탐색 동작을 지정합니다. 

예:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_ReturnToParent(true);
```
## 참조

* 클래스 [IZoomObject](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)