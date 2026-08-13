---
title: AddEffect()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 시퀀스 끝에 새 효과를 추가합니다.
type: docs
weight: 157
url: /ko/aspose.slides.animation/sequence/addeffect/
---
## Sequence::AddEffect(System::SharedPtr\<IShape\>, EffectType, EffectSubtype, EffectTriggerType) 메서드

시퀀스 끝에 새 효과를 추가합니다.

```cpp
System::SharedPtr<IEffect> Aspose::Slides::Animation::Sequence::AddEffect(System::SharedPtr<IShape> shape, EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType) override
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../../aspose.slides/ishape/)\> | [Shape](../../../aspose.slides/shape/) 객체 [IShape](../../../aspose.slides/ishape/) 효과를 추가하기 위해 |
| effectType | [EffectType](../../effecttype/) | 애니메이션 효과 [EffectType](../../effecttype/)의 유형 |
| subtype | [EffectSubtype](../../effectsubtype/) | 애니메이션 효과 [EffectSubtype](../../effectsubtype/)의 하위 유형 |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | 효과 [EffectTriggerType](../../effecttriggertype/)의 트리거 유형 |

### 반환값

새 효과 객체 [IEffect](../../ieffect/)

## Sequence::AddEffect(System::SharedPtr\<IParagraph\>, EffectType, EffectSubtype, EffectTriggerType) 메서드

단락에 대한 새 애니메이션 효과를 시퀀스 끝에 추가합니다.

```cpp
System::SharedPtr<IEffect> Aspose::Slides::Animation::Sequence::AddEffect(System::SharedPtr<IParagraph> paragraph, EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType) override
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| paragraph | [System::SharedPtr](../../../system/sharedptr/)\<[IParagraph](../../../aspose.slides/iparagraph/)\> | [Paragraph](../../../aspose.slides/paragraph/) 객체 [IParagraph](../../../aspose.slides/iparagraph/) |
| effectType | [EffectType](../../effecttype/) | 애니메이션 효과 [EffectType](../../effecttype/)의 유형 |
| subtype | [EffectSubtype](../../effectsubtype/) | 애니메이션 효과 [EffectSubtype](../../effectsubtype/)의 하위 유형 |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | 효과 [EffectTriggerType](../../effecttriggertype/)의 트리거 유형 |

### 반환값

새 효과 객체 [IEffect](../../ieffect/)

## 비고

```cpp
auto presentation = System::MakeObject<Presentation>(path + u"input.pptx");
// 효과를 추가할 단락 선택
auto autoShape = System::ExplicitCast<Aspose::Slides::IAutoShape>(presentation->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto paragraph = autoShape->get_TextFrame()->get_Paragraphs()->idx_get(0);
// 선택된 단락에 Fly 애니메이션 효과 추가
auto effect = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence()->AddEffect(
     paragraph, 
     Aspose::Slides::Animation::EffectType::Fly, 
     Aspose::Slides::Animation::EffectSubtype::Left, 
     Aspose::Slides::Animation::EffectTriggerType::OnClick);
```

## Sequence::AddEffect(System::SharedPtr\<Aspose::Slides::Charts::IChart\>, EffectChartMajorGroupingType, int32_t, EffectType, EffectSubtype, EffectTriggerType) 메서드

시퀀스 끝에 카테고리 또는 시리즈에 대한 새 차트 애니메이션 효과를 추가합니다.

```cpp
System::SharedPtr<IEffect> Aspose::Slides::Animation::Sequence::AddEffect(System::SharedPtr<Aspose::Slides::Charts::IChart> chart, EffectChartMajorGroupingType type, int32_t index, EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType) override
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| chart | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Charts::IChart](../../../aspose.slides.charts/ichart/)\> | 차트 객체 [Aspose::Slides::Charts::IChart](../../../aspose.slides.charts/ichart/) |
| type | [EffectChartMajorGroupingType](../../effectchartmajorgroupingtype/) | 애니메이션 효과 [EffectChartMinorGroupingType](../../effectchartminorgroupingtype/)의 유형 |
| index | **int32_t** | 인덱스 **int32_t** |
| effectType | [EffectType](../../effecttype/) | 애니메이션 효과 [EffectType](../../effecttype/)의 유형 |
| subtype | [EffectSubtype](../../effectsubtype/) | 애니메이션 효과 [EffectSubtype](../../effectsubtype/)의 하위 유형 |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | 효과 [EffectTriggerType](../../effecttriggertype/)의 트리거 유형 |

### 반환값

새 효과 객체 [IEffect](../../ieffect/)

## Sequence::AddEffect(System::SharedPtr\<Aspose::Slides::Charts::IChart\>, EffectChartMinorGroupingType, int32_t, int32_t, EffectType, EffectSubtype, EffectTriggerType) 메서드

시퀀스 끝에 카테고리 또는 시리즈 요소에 대한 새 차트 애니메이션 효과를 추가합니다.

```cpp
System::SharedPtr<IEffect> Aspose::Slides::Animation::Sequence::AddEffect(System::SharedPtr<Aspose::Slides::Charts::IChart> chart, EffectChartMinorGroupingType type, int32_t seriesIndex, int32_t categoriesIndex, EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType) override
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| chart | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Charts::IChart](../../../aspose.slides.charts/ichart/)\> | 차트 객체 [Aspose::Slides::Charts::IChart](../../../aspose.slides.charts/ichart/) |
| type | [EffectChartMinorGroupingType](../../effectchartminorgroupingtype/) | 애니메이션 효과 [EffectChartMinorGroupingType](../../effectchartminorgroupingtype/)의 유형 |
| seriesIndex | **int32_t** | 차트 시리즈 인덱스 **int32_t** |
| categoriesIndex | **int32_t** | 카테고리 인덱스 **int32_t** |
| effectType | [EffectType](../../effecttype/) | 애니메이션 효과 [EffectType](../../effecttype/)의 유형 |
| subtype | [EffectSubtype](../../effectsubtype/) | 애니메이션 효과 [EffectSubtype](../../effectsubtype/)의 하위 유형 |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | 효과 [EffectTriggerType](../../effecttriggertype/)의 트리거 유형 |

### 반환값

새 효과 객체 [IEffect](../../ieffect/)

## 관련 보기

* 열거형 [EffectType](../../effecttype/)
* 열거형 [EffectSubtype](../../effectsubtype/)
* 열거형 [EffectTriggerType](../../effecttriggertype/)
* 열거형 [EffectChartMajorGroupingType](../../effectchartmajorgroupingtype/)
* 열거형 [EffectChartMinorGroupingType](../../effectchartminorgroupingtype/)
* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IEffect](../../ieffect/)
* 클래스 [IShape](../../../aspose.slides/ishape/)
* 클래스 [Sequence](../)
* 클래스 [IParagraph](../../../aspose.slides/iparagraph/)
* 클래스 [IChart](../../../aspose.slides.charts/ichart/)
* 네임스페이스 [Aspose::Slides::Animation](../../)
* 라이브러리 [Aspose.Slides](../../../)