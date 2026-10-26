---
title: get_TargetSection()
second_title: Aspose.Slides for C++ API 레퍼런스
description: Section Zoom 객체가 연결하는 섹션 객체를 가져옵니다. ISection을 읽으십시오.
type: docs
weight: 1
url: /ko/aspose.slides/sectionzoomframe/get_targetsection/
---
## SectionZoomFrame::get_TargetSection() 메서드


[Section](../../section/) Zoom 객체가 연결하는 섹션 객체를 가져옵니다. [ISection](../../isection/)를 읽으십시오.

```cpp
System::SharedPtr<ISection> Aspose::Slides::SectionZoomFrame::get_TargetSection() override
```

## 비고


다음 예제는 대상 섹션을 변경하고 섹션 줌 객체에 대한 새 이미지를 생성합니다: 
```cpp
auto pres = System::MakeObject<Presentation>();
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto sectionZoomFrame = shapes->AddSectionZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1));
sectionZoomFrame->set_TargetSection(pres->get_Sections()->idx_get(2));
```

## 관련 항목

* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [ISection](../../isection/)
* 클래스 [SectionZoomFrame](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)