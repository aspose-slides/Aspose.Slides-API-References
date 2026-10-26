---
title: ISequence class
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides.animation/isequence/
---
## ISequence 클래스

시퀀스(효과 컬렉션)를 나타냅니다.

ISequence 유형은 다음 멤버를 제공합니다:

## 속성

| Property | Description |
| :- | :- |
| [`count`](/slides/python-net/ko/aspose.slides.animation/isequence/count/) | 시퀀스에 있는 효과 수를 반환합니다.<br/>            읽기 전용 **int**. |
| [`trigger_shape`](/slides/python-net/ko/aspose.slides.animation/isequence/trigger_shape/) | INTERACTIVE 시퀀스에 대한 shape 대상을 반환하거나 설정합니다.<br/>            시퀀스가 인터랙티브하지 않으면 None을 반환합니다.<br/>            읽기/쓰기 [`IShape`](/slides/python-net/ko/aspose.slides/ishape). |

지정된 인덱스의 효과를 반환합니다.

## 인덱서

| 이름 | 설명 |
| :- | :- |
| [`[index]`](/slides/python-net/ko/aspose.slides.animation/isequence/__getitem__/) | 인덱스 |

## 메서드

| 메서드 | 설명 |
| :- | :- |
| [`add_effect(self, shape, effect_type, subtype, trigger_type)`](/slides/python-net/ko/aspose.slides.animation/isequence/add_effect/#ishape-effecttype-effectsubtype-effecttriggertype) | 새 효과를 시퀀스 끝에 추가합니다. |
| [`add_effect(self, paragraph, effect_type, subtype, trigger_type)`](/slides/python-net/ko/aspose.slides.animation/isequence/add_effect/#iparagraph-effecttype-effectsubtype-effecttriggertype) | 문단에 대한 새 애니메이션 효과를 시퀀스 끝에 추가합니다. |
| [`add_effect(self, chart, type, index, effect_type, subtype, trigger_type)`](/slides/python-net/ko/aspose.slides.animation/isequence/add_effect/#asposeslideschartsichart-effectchartmajorgroupingtype-int-effecttype-effectsubtype-effecttriggertype) | 카테고리 또는 시리즈에 대한 새 차트 애니메이션 효과를 시퀀스 끝에 추가합니다. |
| [`add_effect(self, chart, type, series_index, categories_index, effect_type, subtype, trigger_type)`](/slides/python-net/ko/aspose.slides.animation/isequence/add_effect/#asposeslideschartsichart-effectchartminorgroupingtype-int-int-effecttype-effectsubtype-effecttriggertype) | 카테고리 또는 시리즈의 요소에 대한 새 차트 애니메이션 효과를 시퀀스 끝에 추가합니다. |
| [`remove(self, item)`](/slides/python-net/ko/aspose.slides.animation/isequence/remove/#ieffect) | 컬렉션에서 지정된 효과를 제거합니다. |
| [`remove_at(self, index)`](/slides/python-net/ko/aspose.slides.animation/isequence/remove_at/#int) | 컬렉션에서 효과를 제거합니다. |
| [`clear(self)`](/slides/python-net/ko/aspose.slides.animation/isequence/clear/#) | 컬렉션의 모든 효과를 제거합니다. |
| [`remove_by_shape(self, shape)`](/slides/python-net/ko/aspose.slides.animation/isequence/remove_by_shape/#ishape) | 지정된 shape에 대한 효과를 제거합니다. |
| [`get_effects_by_shape(self, shape)`](/slides/python-net/ko/aspose.slides.animation/isequence/get_effects_by_shape/#ishape) | 지정된 shape에 대한 효과 배열을 반환합니다. |
| [`get_effects_by_paragraph(self, paragraph)`](/slides/python-net/ko/aspose.slides.animation/isequence/get_effects_by_paragraph/#iparagraph) | 지정된 문단에 대한 효과 배열을 반환합니다. |
| [`get_count(self, shape)`](/slides/python-net/ko/aspose.slides.animation/isequence/get_count/#ishape) | 지정된 shape에 대한 효과 수를 반환합니다. |

### 참조
* 모듈 [`aspose.slides.animation`](/slides/python-net/ko/aspose.slides.animation)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)