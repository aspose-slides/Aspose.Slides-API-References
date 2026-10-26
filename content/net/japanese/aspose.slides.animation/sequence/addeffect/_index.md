---
title: AddEffect
second_title: Aspose.Sildes for .NET API リファレンス
description: シーケンスの末尾に新しいエフェクトを追加します。
type: docs
weight: 40
url: /ja/aspose.slides.animation/sequence/addeffect/
---
## AddEffect(IShape, EffectType, EffectSubtype, EffectTriggerType) {#addeffect_3}

シーケンスの末尾に新しいエフェクトを追加します。

```csharp
public IEffect AddEffect(IShape shape, EffectType effectType, EffectSubtype subtype, 
    EffectTriggerType triggerType)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| shape | IShape | Shape object [`IShape`](../../../aspose.slides/ishape) for adding an effect |
| effectType | EffectType | Type of an animation effect [`EffectType`](../../effecttype) |
| subtype | EffectSubtype | Subtypes of animation effect [`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | Trigger type of effect [`EffectTriggerType`](../../effecttriggertype) |

### 戻り値

新しいエフェクト オブジェクト [`IEffect`](../../ieffect)

### 参照

* インターフェイス [IEffect](../../ieffect)
* インターフェイス [IShape](../../../aspose.slides/ishape)
* enum [EffectType](../../effecttype)
* enum [EffectSubtype](../../effectsubtype)
* enum [EffectTriggerType](../../effecttriggertype)
* クラス [Sequence](../../sequence)
* 名前空間 [Aspose.Slides.Animation](../../sequence)
* アセンブリ [Aspose.Slides](../../../)

---

## AddEffect(IParagraph, EffectType, EffectSubtype, EffectTriggerType) {#addeffect_2}

段落に対して新しいアニメーションエフェクトをシーケンスの末尾に追加します。

```csharp
public IEffect AddEffect(IParagraph paragraph, EffectType effectType, EffectSubtype subtype, 
    EffectTriggerType triggerType)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| paragraph | IParagraph | Paragraph object [`IParagraph`](../../../aspose.slides/iparagraph) |
| effectType | EffectType | Type of an animation effect [`EffectType`](../../effecttype) |
| subtype | EffectSubtype | Subtypes of animation effect [`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | Trigger type of effect [`EffectTriggerType`](../../effecttriggertype) |

### 戻り値

新しいエフェクト オブジェクト [`IEffect`](../../ieffect)

### 例

```csharp
[C#]
using(Presentation presentation = new Presentation(path + "input.pptx"))
{        
   // エフェクトを追加する段落を選択
   IAutoShape autoShape = (IAutoShape)presentation.Slides[0].Shapes[0];
   IParagraph paragraph = autoShape.TextFrame.Paragraphs[0];

   // 選択した段落にFlyアニメーションエフェクトを追加
   IEffect effect = presentation.Slides[0].Timeline.MainSequence.AddEffect(
   paragraph, EffectType.Fly, EffectSubtype.Left, EffectTriggerType.OnClick);
}
```

### 参照

* インターフェイス [IEffect](../../ieffect)
* インターフェイス [IParagraph](../../../aspose.slides/iparagraph)
* enum [EffectType](../../effecttype)
* enum [EffectSubtype](../../effectsubtype)
* enum [EffectTriggerType](../../effecttriggertype)
* クラス [Sequence](../../sequence)
* 名前空間 [Aspose.Slides.Animation](../../sequence)
* アセンブリ [Aspose.Slides](../../../)

---

## AddEffect(IChart, EffectChartMajorGroupingType, int, EffectType, EffectSubtype, EffectTriggerType) {#addeffect}

カテゴリまたは系列に対する新しいチャートアニメーションエフェクトをシーケンスの末尾に追加します。

```csharp
public IEffect AddEffect(IChart chart, EffectChartMajorGroupingType type, int index, 
    EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| chart | IChart | Chart object [`IChart`](../../../aspose.slides.charts/ichart) |
| type | EffectChartMajorGroupingType | Type of an animation effect [`EffectChartMinorGroupingType`](../../effectchartminorgroupingtype) |
| index | Int32 | Index Int32 |
| effectType | EffectType | Type of an animation effect [`EffectType`](../../effecttype) |
| subtype | EffectSubtype | Subtypes of animation effect [`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | Trigger type of effect [`EffectTriggerType`](../../effecttriggertype) |

### 戻り値

新しいエフェクト オブジェクト [`IEffect`](../../ieffect)

### 参照

* インターフェイス [IEffect](../../ieffect)
* インターフェイス [IChart](../../../aspose.slides.charts/ichart)
* enum [EffectChartMajorGroupingType](../../effectchartmajorgroupingtype)
* enum [EffectType](../../effecttype)
* enum [EffectSubtype](../../effectsubtype)
* enum [EffectTriggerType](../../effecttriggertype)
* クラス [Sequence](../../sequence)
* 名前空間 [Aspose.Slides.Animation](../../sequence)
* アセンブリ [Aspose.Slides](../../../)

---

## AddEffect(IChart, EffectChartMinorGroupingType, int, int, EffectType, EffectSubtype, EffectTriggerType) {#addeffect_1}

カテゴリまたは系列内の要素に対する新しいチャートアニメーションエフェクトをシーケンスの末尾に追加します。

```csharp
public IEffect AddEffect(IChart chart, EffectChartMinorGroupingType type, int seriesIndex, 
    int categoriesIndex, EffectType effectType, EffectSubtype subtype, 
    EffectTriggerType triggerType)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| chart | IChart | Chart object [`IChart`](../../../aspose.slides.charts/ichart) |
| type | EffectChartMinorGroupingType | Type of an animation effect [`EffectChartMinorGroupingType`](../../effectchartminorgroupingtype) |
| seriesIndex | Int32 | Index of chart series Int32 |
| categoriesIndex | Int32 | Index of category Int32 |
| effectType | EffectType | Type of an animation effect [`EffectType`](../../effecttype) |
| subtype | EffectSubtype | Subtypes of animation effect [`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | Trigger type of effect [`EffectTriggerType`](../../effecttriggertype) |

### 戻り値

新しいエフェクト オブジェクト [`IEffect`](../../ieffect)

### 参照

* インターフェイス [IEffect](../../ieffect)
* インターフェイス [IChart](../../../aspose.slides.charts/ichart)
* enum [EffectChartMinorGroupingType](../../effectchartminorgroupingtype)
* enum [EffectType](../../effecttype)
* enum [EffectSubtype](../../effectsubtype)
* enum [EffectTriggerType](../../effecttriggertype)
* クラス [Sequence](../../sequence)
* 名前空間 [Aspose.Slides.Animation](../../sequence)
* アセンブリ [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->