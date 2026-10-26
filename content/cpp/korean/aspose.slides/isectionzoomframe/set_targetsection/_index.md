---
title: set_TargetSection()
second_title: Aspose.Slides for C++ API 참조
description: Section Zoom 객체와 연결된 섹션 객체를 설정합니다. ISection을 씁니다.
type: docs
weight: 14
url: /ko/aspose.slides/isectionzoomframe/set_targetsection/
---
## ISectionZoomFrame::set_TargetSection(System::SharedPtr\<ISection\>) 메서드

[Section](../../section/) Zoom 객체와 연결된 섹션 객체를 설정합니다. [ISection](../../isection/)를 씁니다.

```cpp
virtual void Aspose::Slides::ISectionZoomFrame::set_TargetSection(System::SharedPtr<ISection> value)=0
```

## 비고

이 예제는 대상 섹션을 변경하고 섹션 줌 객체에 대한 새 이미지를 생성합니다: 
```cpp
auto pres = System::MakeObject<Presentation>();
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto sectionZoomFrame = shapes->AddSectionZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1));
sectionZoomFrame->set_TargetSection(pres->get_Sections()->idx_get(2));
```

## 참조

* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [ISection](../../isection/)
* 클래스 [ISectionZoomFrame](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)