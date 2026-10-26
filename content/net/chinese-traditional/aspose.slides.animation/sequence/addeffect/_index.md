---
title: AddEffect
second_title: Aspose.Sildes 的 .NET API 參考
description: 將新的效果新增至序列的末端。
type: docs
weight: 40
url: /zh-hant/aspose.slides.animation/sequence/addeffect/
---
## AddEffect(IShape, EffectType, EffectSubtype, EffectTriggerType) {#addeffect_3}

將新的效果新增至序列的末端。

```csharp
public IEffect AddEffect(IShape shape, EffectType effectType, EffectSubtype subtype, 
    EffectTriggerType triggerType)
```

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| shape | IShape | 用於新增效果的形狀物件 [`IShape`](../../../aspose.slides/ishape) |
| effectType | EffectType | 動畫效果的類型 [`EffectType`](../../effecttype) |
| subtype | EffectSubtype | 動畫效果的子類型 [`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | 效果的觸發類型 [`EffectTriggerType`](../../effecttriggertype) |

### 傳回值

New effect object [`IEffect`](../../ieffect)

### 另請參閱

* interface [IEffect](../../ieffect)
* interface [IShape](../../../aspose.slides/ishape)
* enum [EffectType](../../effecttype)
* enum [EffectSubtype](../../effectsubtype)
* enum [EffectTriggerType](../../effecttriggertype)
* class [Sequence](../../sequence)
* namespace [Aspose.Slides.Animation](../../sequence)
* assembly [Aspose.Slides](../../../)

---

## AddEffect(IParagraph, EffectType, EffectSubtype, EffectTriggerType) {#addeffect_2}

將段落的動畫效果新增至序列的末端。

```csharp
public IEffect AddEffect(IParagraph paragraph, EffectType effectType, EffectSubtype subtype, 
    EffectTriggerType triggerType)
```

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| paragraph | IParagraph | 段落物件 [`IParagraph`](../../../aspose.slides/iparagraph) |
| effectType | EffectType | 動畫效果的類型 [`EffectType`](../../effecttype) |
| subtype | EffectSubtype | 動畫效果的子類型 [`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | 效果的觸發類型 [`EffectTriggerType`](../../effecttriggertype) |

### 傳回值

New effect object [`IEffect`](../../ieffect)

### 範例

```csharp
[C#]
using(Presentation presentation = new Presentation(path + "input.pptx"))
{        
   // 選擇要加入效果的段落
   IAutoShape autoShape = (IAutoShape)presentation.Slides[0].Shapes[0];
   IParagraph paragraph = autoShape.TextFrame.Paragraphs[0];

   // 為選取的段落新增 Fly 動畫效果
   IEffect effect = presentation.Slides[0].Timeline.MainSequence.AddEffect(
   paragraph, EffectType.Fly, EffectSubtype.Left, EffectTriggerType.OnClick);
}
```

### 另請參閱

* interface [IEffect](../../ieffect)
* interface [IParagraph](../../../aspose.slides/iparagraph)
* enum [EffectType](../../effecttype)
* enum [EffectSubtype](../../effectsubtype)
* enum [EffectTriggerType](../../effecttriggertype)
* class [Sequence](../../sequence)
* namespace [Aspose.Slides.Animation](../../sequence)
* assembly [Aspose.Slides](../../../)

---

## AddEffect(IChart, EffectChartMajorGroupingType, int, EffectType, EffectSubtype, EffectTriggerType) {#addeffect}

將新的圖表動畫效果（針對類別或系列）新增至序列的末端。

```csharp
public IEffect AddEffect(IChart chart, EffectChartMajorGroupingType type, int index, 
    EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType)
```

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| chart | IChart | 圖表物件 [`IChart`](../../../aspose.slides.charts/ichart) |
| type | EffectChartMajorGroupingType | 動畫效果的類型 [`EffectChartMinorGroupingType`](../../effectchartminorgroupingtype) |
| index | Int32 | 索引 Int32 |
| effectType | EffectType | 動畫效果的類型 [`EffectType`](../../effecttype) |
| subtype | EffectSubtype | 動畫效果的子類型 [`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | 效果的觸發類型 [`EffectTriggerType`](../../effecttriggertype) |

### 傳回值

New effect object [`IEffect`](../../ieffect)

### 另請參閱

* interface [IEffect](../../ieffect)
* interface [IChart](../../../aspose.slides.charts/ichart)
* enum [EffectChartMajorGroupingType](../../effectchartmajorgroupingtype)
* enum [EffectType](../../effecttype)
* enum [EffectSubtype](../../effectsubtype)
* enum [EffectTriggerType](../../effecttriggertype)
* class [Sequence](../../sequence)
* namespace [Aspose.Slides.Animation](../../sequence)
* assembly [Aspose.Slides](../../../)

---

## AddEffect(IChart, EffectChartMinorGroupingType, int, int, EffectType, EffectSubtype, EffectTriggerType) {#addeffect_1}

將新的圖表動畫效果（針對類別或系列中的元素）新增至序列的末端。

```csharp
public IEffect AddEffect(IChart chart, EffectChartMinorGroupingType type, int seriesIndex, 
    int categoriesIndex, EffectType effectType, EffectSubtype subtype, 
    EffectTriggerType triggerType)
```

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| chart | IChart | 圖表物件 [`IChart`](../../../aspose.slides.charts/ichart) |
| type | EffectChartMinorGroupingType | 動畫效果的類型 [`EffectChartMinorGroupingType`](../../effectchartminorgroupingtype) |
| seriesIndex | Int32 | 圖表系列的索引 Int32 |
| categoriesIndex | Int32 | 類別的索引 Int32 |
| effectType | EffectType | 動畫效果的類型 [`EffectType`](../../effecttype) |
| subtype | EffectSubtype | 動畫效果的子類型 [`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | 效果的觸發類型 [`EffectTriggerType`](../../effecttriggertype) |

### 傳回值

New effect object [`IEffect`](../../ieffect)

### 另請參閱

* interface [IEffect](../../ieffect)
* interface [IChart](../../../aspose.slides.charts/ichart)
* enum [EffectChartMinorGroupingType](../../effectchartminorgroupingtype)
* enum [EffectType](../../effecttype)
* enum [EffectSubtype](../../effectsubtype)
* enum [EffectTriggerType](../../effecttriggertype)
* class [Sequence](../../sequence)
* namespace [Aspose.Slides.Animation](../../sequence)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->