---
title: AddEffect
second_title: Aspose.Sildes for .NET API 참조
description: 시퀀스 끝에 새 효과를 추가합니다.
type: docs
weight: 40
url: /ko/aspose.slides.animation/sequence/addeffect/
---
## AddEffect(IShape, EffectType, EffectSubtype, EffectTriggerType) {#addeffect_3}

시퀀스 끝에 새 효과를 추가합니다.

```csharp
public IEffect AddEffect(IShape shape, EffectType effectType, EffectSubtype subtype, 
    EffectTriggerType triggerType)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| shape | IShape | 효과를 추가하기 위한 Shape 객체 [`IShape`](../../../aspose.slides/ishape) |
| effectType | EffectType | 애니메이션 효과 유형 [`EffectType`](../../effecttype) |
| subtype | EffectSubtype | 애니메이션 효과 하위 유형 [`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | 효과 트리거 유형 [`EffectTriggerType`](../../effecttriggertype) |

### 반환값

새 효과 객체 [`IEffect`](../../ieffect)

### 참고

* 인터페이스 [IEffect](../../ieffect)
* 인터페이스 [IShape](../../../aspose.slides/ishape)
* 열거형 [EffectType](../../effecttype)
* 열거형 [EffectSubtype](../../effectsubtype)
* 열거형 [EffectTriggerType](../../effecttriggertype)
* 클래스 [Sequence](../../sequence)
* 네임스페이스 [Aspose.Slides.Animation](../../sequence)
* 어셈블리 [Aspose.Slides](../../../)

---

## AddEffect(IParagraph, EffectType, EffectSubtype, EffectTriggerType) {#addeffect_2}

시퀀스 끝에 단락에 대한 새 애니메이션 효과를 추가합니다.

```csharp
public IEffect AddEffect(IParagraph paragraph, EffectType effectType, EffectSubtype subtype, 
    EffectTriggerType triggerType)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| paragraph | IParagraph | Paragraph 객체 [`IParagraph`](../../../aspose.slides/iparagraph) |
| effectType | EffectType | 애니메이션 효과 유형 [`EffectType`](../../effecttype) |
| subtype | EffectSubtype | 애니메이션 효과 하위 유형 [`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | 효과 트리거 유형 [`EffectTriggerType`](../../effecttriggertype) |

### 반환값

새 효과 객체 [`IEffect`](../../ieffect)

### 예제

```csharp
[C#]
using(Presentation presentation = new Presentation(path + "input.pptx"))
{        
   // 효과를 추가할 단락을 선택합니다
   IAutoShape autoShape = (IAutoShape)presentation.Slides[0].Shapes[0];
   IParagraph paragraph = autoShape.TextFrame.Paragraphs[0];

   // 선택한 단락에 Fly 애니메이션 효과를 추가합니다
   IEffect effect = presentation.Slides[0].Timeline.MainSequence.AddEffect(
   paragraph, EffectType.Fly, EffectSubtype.Left, EffectTriggerType.OnClick);
}
```

### 참고

* 인터페이스 [IEffect](../../ieffect)
* 인터페이스 [IParagraph](../../../aspose.slides/iparagraph)
* 열거형 [EffectType](../../effecttype)
* 열거형 [EffectSubtype](../../effectsubtype)
* 열거형 [EffectTriggerType](../../effecttriggertype)
* 클래스 [Sequence](../../sequence)
* 네임스페이스 [Aspose.Slides.Animation](../../sequence)
* 어셈블리 [Aspose.Slides](../../../)

---

## AddEffect(IChart, EffectChartMajorGroupingType, int, EffectType, EffectSubtype, EffectTriggerType) {#addeffect}

시퀀스 끝에 범주 또는 시리즈에 대한 새 차트 애니메이션 효과를 추가합니다.

```csharp
public IEffect AddEffect(IChart chart, EffectChartMajorGroupingType type, int index, 
    EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| chart | IChart | Chart 객체 [`IChart`](../../../aspose.slides.charts/ichart) |
| type | EffectChartMajorGroupingType | 애니메이션 효과 유형 [`EffectChartMinorGroupingType`](../../effectchartminorgroupingtype) |
| index | Int32 | Int32 인덱스 |
| effectType | EffectType | 애니메이션 효과 유형 [`EffectType`](../../effecttype) |
| subtype | EffectSubtype | 애니메이션 효과 하위 유형 [`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | 효과 트리거 유형 [`EffectTriggerType`](../../effecttriggertype) |

### 반환값

새 효과 객체 [`IEffect`](../../ieffect)

### 참고

* 인터페이스 [IEffect](../../ieffect)
* 인터페이스 [IChart](../../../aspose.slides.charts/ichart)
* 열거형 [EffectChartMajorGroupingType](../../effectchartmajorgroupingtype)
* 열거형 [EffectType](../../effecttype)
* 열거형 [EffectSubtype](../../effectsubtype)
* 열거형 [EffectTriggerType](../../effecttriggertype)
* 클래스 [Sequence](../../sequence)
* 네임스페이스 [Aspose.Slides.Animation](../../sequence)
* 어셈블리 [Aspose.Slides](../../../)

---

## AddEffect(IChart, EffectChartMinorGroupingType, int, int, EffectType, EffectSubtype, EffectTriggerType) {#addeffect_1}

시퀀스 끝에 범주 또는 시리즈의 요소에 대한 새 차트 애니메이션 효과를 추가합니다.

```csharp
public IEffect AddEffect(IChart chart, EffectChartMinorGroupingType type, int seriesIndex, 
    int categoriesIndex, EffectType effectType, EffectSubtype subtype, 
    EffectTriggerType triggerType)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| chart | IChart | Chart 객체 [`IChart`](../../../aspose.slides.charts/ichart) |
| type | EffectChartMinorGroupingType | 애니메이션 효과 유형 [`EffectChartMinorGroupingType`](../../effectchartminorgroupingtype) |
| seriesIndex | Int32 | 차트 시리즈 인덱스 Int32 |
| categoriesIndex | Int32 | 범주 인덱스 Int32 |
| effectType | EffectType | 애니메이션 효과 유형 [`EffectType`](../../effecttype) |
| subtype | EffectSubtype | 애니메이션 효과 하위 유형 [`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | 효과 트리거 유형 [`EffectTriggerType`](../../effecttriggertype) |

### 반환값

새 효과 객체 [`IEffect`](../../ieffect)

### 참고

* 인터페이스 [IEffect](../../ieffect)
* 인터페이스 [IChart](../../../aspose.slides.charts/ichart)
* 열거형 [EffectChartMinorGroupingType](../../effectchartminorgroupingtype)
* 열거형 [EffectType](../../effecttype)
* 열거형 [EffectSubtype](../../effectsubtype)
* 열거형 [EffectTriggerType](../../effecttriggertype)
* 클래스 [Sequence](../../sequence)
* 네임스페이스 [Aspose.Slides.Animation](../../sequence)
* 어셈블리 [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->