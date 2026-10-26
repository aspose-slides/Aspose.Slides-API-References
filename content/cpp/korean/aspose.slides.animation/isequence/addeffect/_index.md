---
title: AddEffect()
second_title: Aspose.Slides for C++ API 참조
description: 시퀀스 끝에 새 효과를 추가합니다.
type: docs
weight: 144
url: /ko/aspose.slides.animation/isequence/addeffect/
---
## ISequence::AddEffect(System::SharedPtr\<IShape\>, EffectType, EffectSubtype, EffectTriggerType) 메서드

시퀀스 끝에 새 효과를 추가합니다.

```cpp
virtual System::SharedPtr<IEffect> Aspose::Slides::Animation::ISequence::AddEffect(System::SharedPtr<IShape> shape, EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../../aspose.slides/ishape/)\> | [Shape](../../../aspose.slides/shape/) 객체 [IShape](../../../aspose.slides/ishape/) 효과를 추가하기 위해 |
| effectType | [EffectType](../../effecttype/) | 애니메이션 효과 [EffectType](../../effecttype/) 유형 |
| subtype | [EffectSubtype](../../effectsubtype/) | 애니메이션 효과 [EffectSubtype](../../effectsubtype/) 하위 유형 |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | 효과 [EffectTriggerType](../../effecttriggertype/) 트리거 유형 |

### 반환값

새 효과 객체 [IEffect](../../ieffect/)

## ISequence::AddEffect(System::SharedPtr\<IParagraph\>, EffectType, EffectSubtype, EffectTriggerType) 메서드

시퀀스 끝에 단락에 대한 새 애니메이션 효과를 추가합니다.

```cpp
virtual System::SharedPtr<IEffect> Aspose::Slides::Animation::ISequence::AddEffect(System::SharedPtr<IParagraph> paragraph, EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| paragraph | [System::SharedPtr](../../../system/sharedptr/)\<[IParagraph](../../../aspose.slides/iparagraph/)\> | [Paragraph](../../../aspose.slides/paragraph/) 객체 [IParagraph](../../../aspose.slides/iparagraph/) |
| effectType | [EffectType](../../effecttype/) | 애니메이션 효과 [EffectType](../../effecttype/) 유형 |
| subtype | [EffectSubtype](../../effectsubtype/) | 애니메이션 효과 [EffectSubtype](../../effectsubtype/) 하위 유형 |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | 효과 [EffectTriggerType](../../effecttriggertype/) 트리거 유형 |

### 반환값

새 효과 객체 [IEffect](../../ieffect/)

## 비고

```cpp
auto presentation = System::MakeObject<Presentation>(path + u"input.pptx");
// 효과를 추가할 단락을 선택합니다
auto autoShape = System::ExplicitCast<IAutoShape>(presentation->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto paragraph = autoShape->get_TextFrame()->get_Paragraphs()->idx_get(0);
// 선택된 단락에 Fly 애니메이션 효과를 추가합니다
auto effect = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence()->AddEffect(
     paragraph, 
     Animation::EffectType::Fly, 
     Animation::EffectSubtype::Left, 
     Animation::EffectTriggerType::OnClick);
```

## ISequence::AddEffect(System::SharedPtr\<Aspose::Slides::Charts::IChart\>, EffectChartMajorGroupingType, int32_t, EffectType, EffectSubtype, EffectTriggerType) 메서드

시퀀스 끝에 범주 또는 시리즈에 대한 새 차트 애니메이션 효과를 추가합니다.

```cpp
virtual System::SharedPtr<IEffect> Aspose::Slides::Animation::ISequence::AddEffect(System::SharedPtr<Aspose::Slides::Charts::IChart> chart, EffectChartMajorGroupingType type, int32_t index, EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| chart | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Charts::IChart](../../../aspose.slides.charts/ichart/)\> | 차트 객체 [Aspose::Slides::Charts::IChart](../../../aspose.slides.charts/ichart/) |
| type | [EffectChartMajorGroupingType](../../effectchartmajorgroupingtype/) | 애니메이션 효과 [EffectChartMinorGroupingType](../../effectchartminorgroupingtype/) 유형 |
| index | **int32_t** | 인덱스 **int32_t** |
| effectType | [EffectType](../../effecttype/) | 애니메이션 효과 [EffectType](../../effecttype/) 유형 |
| subtype | [EffectSubtype](../../effectsubtype/) | 애니메이션 효과 [EffectSubtype](../../effectsubtype/) 하위 유형 |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | 효과 [EffectTriggerType](../../effecttriggertype/) 트리거 유형 |

### 반환값

새 효과 객체 [IEffect](../../ieffect/)

## ISequence::AddEffect(System::SharedPtr\<Aspose::Slides::Charts::IChart\>, EffectChartMinorGroupingType, int32_t, int32_t, EffectType, EffectSubtype, EffectTriggerType) 메서드

시퀀스 끝에 범주 또는 시리즈의 요소에 대한 새 차트 애니메이션 효과를 추가합니다.

```cpp
virtual System::SharedPtr<IEffect> Aspose::Slides::Animation::ISequence::AddEffect(System::SharedPtr<Aspose::Slides::Charts::IChart> chart, EffectChartMinorGroupingType type, int32_t seriesIndex, int32_t categoriesIndex, EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| chart | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Charts::IChart](../../../aspose.slides.charts/ichart/)\> | 차트 객체 [Aspose::Slides::Charts::IChart](../../../aspose.slides.charts/ichart/) |
| type | [EffectChartMinorGroupingType](../../effectchartminorgroupingtype/) | 애니메이션 효과 [EffectChartMinorGroupingType](../../effectchartminorgroupingtype/) 유형 |
| seriesIndex | **int32_t** | 차트 시리즈 인덱스 **int32_t** |
| categoriesIndex | **int32_t** | 범주 인덱스 **int32_t** |
| effectType | [EffectType](../../effecttype/) | 애니메이션 효과 [EffectType](../../effecttype/) 유형 |
| subtype | [EffectSubtype](../../effectsubtype/) | 애니메이션 효과 [EffectSubtype](../../effectsubtype/) 하위 유형 |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | 효과 [EffectTriggerType](../../effecttriggertype/) 트리거 유형 |

### 반환값

새 효과 객체 [IEffect](../../ieffect/)

## 참고

* Enum [EffectType](../../effecttype/)
* Enum [EffectSubtype](../../effectsubtype/)
* Enum [EffectTriggerType](../../effecttriggertype/)
* Enum [EffectChartMajorGroupingType](../../effectchartmajorgroupingtype/)
* Enum [EffectChartMinorGroupingType](../../effectchartminorgroupingtype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEffect](../../ieffect/)
* Class [IShape](../../../aspose.slides/ishape/)
* Class [ISequence](../)
* Class [IParagraph](../../../aspose.slides/iparagraph/)
* Class [IChart](../../../aspose.slides.charts/ichart/)
* Namespace [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)