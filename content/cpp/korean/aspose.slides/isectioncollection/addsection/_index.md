---
title: AddSection()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 특정 슬라이드에서 시작되는 새 섹션을 추가합니다.
type: docs
weight: 14
url: /ko/aspose.slides/isectioncollection/addsection/
---
## ISectionCollection::AddSection(System::String, System::SharedPtr\<ISlide\>) method

특정 슬라이드에서 시작되는 새 섹션을 추가합니다.

```cpp
virtual System::SharedPtr<ISection> Aspose::Slides::ISectionCollection::AddSection(System::String name, System::SharedPtr<ISlide> startedFromSlide)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| name | [System::String](../../../system/string/) | 섹션 이름 |
| startedFromSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | 섹션의 첫 번째 슬라이드 |

### 반환 값

추가된 섹션.

## 관련 항목

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISection](../../isection/)
* Class [String](../../../system/string/)
* Class [ISlide](../../islide/)
* Class [ISectionCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)