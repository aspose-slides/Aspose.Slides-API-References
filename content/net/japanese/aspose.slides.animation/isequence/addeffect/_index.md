---
title: AddEffect
second_title: Aspose.Sildes for .NET API リファレンス
description: シーケンスの末尾に新しいエフェクトを追加します。
type: docs
weight: 50
url: /ja/aspose.slides.animation/isequence/addeffect/
---
## AddEffect(IShape, EffectType, EffectSubtype, EffectTriggerType) {#addeffect_3}

シーケンスの末尾に新しいエフェクトを追加します。

```csharp
public IEffect AddEffect(IShape shape, EffectType effectType, EffectSubtype subtype, 
    EffectTriggerType triggerType)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| shape | IShape | エフェクトを追加するための Shape オブジェクト [`IShape`](../../../aspose.slides/ishape) |
| effectType | EffectType | アニメーション効果の種類 [`EffectType`](../../effecttype) |
| subtype | EffectSubtype | アニメーション効果のサブタイプ [`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | エフェクトのトリガータイプ [`EffectTriggerType`](../../effecttriggertype) |

### 戻り値

新しいエフェクトオブジェクト [`IEffect`](../../ieffect)

### 参照

* インターフェイス [IEffect](../../ieffect)
* インターフェイス [IShape](../../../aspose.slides/ishape)
* 列挙型 [EffectType](../../effecttype)
* 列挙型 [EffectSubtype](../../effectsubtype)
* 列挙型 [EffectTriggerType](../../effecttriggertype)
* インターフェイス [ISequence](../../isequence)
* 名前空間 [Aspose.Slides.Animation](../../isequence)
* アセンブリ [Aspose.Slides](../../../)

---

## AddEffect(IParagraph, EffectType, EffectSubtype, EffectTriggerType) {#addeffect_2}

段落用の新しいアニメーション効果をシーケンスの末尾に追加します。

```csharp
public IEffect AddEffect(IParagraph paragraph, EffectType effectType, EffectSubtype subtype, 
    EffectTriggerType triggerType)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| paragraph | IParagraph | Paragraph オブジェクト [`IParagraph`](../../../aspose.slides/iparagraph) |
| effectType | EffectType | アニメーション効果の種類 [`EffectType`](../../effecttype) |
| subtype | EffectSubtype | アニメーション効果のサブタイプ [`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | エフェクトのトリガータイプ [`EffectTriggerType`](../../effecttriggertype) |

### 戻り値

新しいエフェクトオブジェクト [`IEffect`](../../ieffect)

### 例

```csharp
[C#]
using(Presentation presentation = new Presentation(path + "input.pptx"))
{        
   // エフェクトを追加する段落を選択
   IAutoShape autoShape = (IAutoShape)presentation.Slides[0].Shapes[0];
   IParagraph paragraph = autoShape.TextFrame.Paragraphs[0];

   // 選択した段落に Fly アニメーションエフェクトを追加
   IEffect effect = presentation.Slides[0].Timeline.MainSequence.AddEffect(
   paragraph, EffectType.Fly, EffectSubtype.Left, EffectTriggerType.OnClick);
}
```

### 参照

* インターフェイス [IEffect](../../ieffect)
* インターフェイス [IParagraph](../../../aspose.slides/iparagraph)
* 列挙型 [EffectType](../../effecttype)
* 列挙型 [EffectSubtype](../../effectsubtype)
* 列挙型 [EffectTriggerType](../../effecttriggertype)
* インターフェイス [ISequence](../../isequence)
* 名前空間 [Aspose.Slides.Animation](../../isequence)
* アセンブリ [Aspose.Slides](../../../)

---

## AddEffect(IChart, EffectChartMajorGroupingType, int, EffectType, EffectSubtype, EffectTriggerType) {#addeffect}

カテゴリまたは系列に対する新しいチャートアニメーション効果をシーケンスの末尾に追加します。

```csharp
public IEffect AddEffect(IChart chart, EffectChartMajorGroupingType type, int index, 
    EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| chart | IChart | Chart オブジェクト [`IChart`](../../../aspose.slides.charts/ichart) |
| type | EffectChartMajorGroupingType | アニメーション効果の種類 [`EffectChartMinorGroupingType`](../../effectchartminorgroupingtype) |
| index | Int32 | Int32 のインデックス |
| effectType | EffectType | アニメーション効果の種類 [`EffectType`](../../effecttype) |
| subtype | EffectSubtype | アニメーション効果のサブタイプ [`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | エフェクトのトリガータイプ [`EffectTriggerType`](../../effecttriggertype) |

### 戻り値

新しいエフェクトオブジェクト [`IEffect`](../../ieffect)

### 参照

* インターフェイス [IEffect](../../ieffect)
* インターフェイス [IChart](../../../aspose.slides.charts/ichart)
* 列挙型 [EffectChartMajorGroupingType](../../effectchartmajorgroupingtype)
* 列挙型 [EffectType](../../effecttype)
* 列挙型 [EffectSubtype](../../effectsubtype)
* 列挙型 [EffectTriggerType](../../effecttriggertype)
* インターフェイス [ISequence](../../isequence)
* 名前空間 [Aspose.Slides.Animation](../../isequence)
* アセンブリ [Aspose.Slides](../../../)

---

## AddEffect(IChart, EffectChartMinorGroupingType, int, int, EffectType, EffectSubtype, EffectTriggerType) {#addeffect_1}

カテゴリまたは系列内の要素に対する新しいチャートアニメーション効果をシーケンスの末尾に追加します。

```csharp
public IEffect AddEffect(IChart chart, EffectChartMinorGroupingType type, int seriesIndex, 
    int categoriesIndex, EffectType effectType, EffectSubtype subtype, 
    EffectTriggerType triggerType)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| chart | IChart | Chart オブジェクト [`IChart`](../../../aspose.slides.charts/ichart) |
| type | EffectChartMinorGroupingType | アニメーション効果の種類 [`EffectChartMinorGroupingType`](../../effectchartminorgroupingtype) |
| seriesIndex | Int32 | チャート系列のインデックス Int32 |
| categoriesIndex | Int32 | カテゴリのインデックス Int32 |
| effectType | EffectType | アニメーション効果の種類 [`EffectType`](../../effecttype) |
| subtype | EffectSubtype | アニメーション効果のサブタイプ [`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | エフェクトのトリガータイプ [`EffectTriggerType`](../../effecttriggertype) |

### 戻り値

新しいエフェクトオブジェクト [`IEffect`](../../ieffect)

### 参照

* インターフェイス [IEffect](../../ieffect)
* インターフェイス [IChart](../../../aspose.slides.charts/ichart)
* 列挙型 [EffectChartMinorGroupingType](../../effectchartminorgroupingtype)
* 列挙型 [EffectType](../../effecttype)
* 列挙型 [EffectSubtype](../../effectsubtype)
* 列挙型 [EffectTriggerType](../../effecttriggertype)
* インターフェイス [ISequence](../../isequence)
* 名前空間 [Aspose.Slides.Animation](../../isequence)
* アセンブリ [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->