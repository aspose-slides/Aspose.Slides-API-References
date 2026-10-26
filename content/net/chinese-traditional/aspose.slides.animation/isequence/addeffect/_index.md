---
title: AddEffect
second_title: Aspose.Sildes for .NET API 參考
description: 將新效果新增至序列的末端。
type: docs
weight: 50
url: /zh-hant/aspose.slides.animation/isequence/addeffect/
---
## AddEffect(IShape, EffectType, EffectSubtype, EffectTriggerType) {#addeffect_3}

將新的效果新增至序列的末端。

```csharp
public IEffect AddEffect(IShape shape, EffectType effectType, EffectSubtype subtype, 
    EffectTriggerType triggerType)
```

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| shape | IShape | Shape 物件 [`IShape`](../../../aspose.slides/ishape) 用於新增效果 |
| effectType | EffectType | 動畫效果的類型 [`EffectType`](../../effecttype) |
| subtype | EffectSubtype | 動畫效果的子類型 [`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | 效果的觸發類型 [`EffectTriggerType`](../../effecttriggertype) |

### 返回值

新的效果物件 [`IEffect`](../../ieffect)

### 另請參閱

* 介面 [IEffect](../../ieffect)
* 介面 [IShape](../../../aspose.slides/ishape)
* 列舉 [EffectType](../../effecttype)
* 列舉 [EffectSubtype](../../effectsubtype)
* 列舉 [EffectTriggerType](../../effecttriggertype)
* 介面 [ISequence](../../isequence)
* 命名空間 [Aspose.Slides.Animation](../../isequence)
* 組件 [Aspose.Slides](../../../)

---

## AddEffect(IParagraph, EffectType, EffectSubtype, EffectTriggerType) {#addeffect_2}

將新的動畫效果新增至段落的序列末端。

```csharp
public IEffect AddEffect(IParagraph paragraph, EffectType effectType, EffectSubtype subtype, 
    EffectTriggerType triggerType)
```

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| paragraph | IParagraph | Paragraph 物件 [`IParagraph`](../../../aspose.slides/iparagraph) |
| effectType | EffectType | 動畫效果的類型 [`EffectType`](../../effecttype) |
| subtype | EffectSubtype | 動畫效果的子類型 [`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | 效果的觸發類型 [`EffectTriggerType`](../../effecttriggertype) |

### 返回值

新的效果物件 [`IEffect`](../../ieffect)

### 範例

```csharp
[C#]
using(Presentation presentation = new Presentation(path + "input.pptx"))
{        
   // 選取要新增效果的段落
   IAutoShape autoShape = (IAutoShape)presentation.Slides[0].Shapes[0];
   IParagraph paragraph = autoShape.TextFrame.Paragraphs[0];

   // 為選取的段落新增 Fly 動畫效果
   IEffect effect = presentation.Slides[0].Timeline.MainSequence.AddEffect(
   paragraph, EffectType.Fly, EffectSubtype.Left, EffectTriggerType.OnClick);
}
```

### 另請參閱

* 介面 [IEffect](../../ieffect)
* 介面 [IParagraph](../../../aspose.slides/iparagraph)
* 列舉 [EffectType](../../effecttype)
* 列舉 [EffectSubtype](../../effectsubtype)
* 列舉 [EffectTriggerType](../../effecttriggertype)
* 介面 [ISequence](../../isequence)
* 命名空間 [Aspose.Slides.Animation](../../isequence)
* 組件 [Aspose.Slides](../../../)

---

## AddEffect(IChart, EffectChartMajorGroupingType, int, EffectType, EffectSubtype, EffectTriggerType) {#addeffect}

將新的圖表動畫效果（針對類別或序列）新增至序列的末端。

```csharp
public IEffect AddEffect(IChart chart, EffectChartMajorGroupingType type, int index, 
    EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType)
```

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| chart | IChart | Chart 物件 [`IChart`](../../../aspose.slides.charts/ichart) |
| type | EffectChartMajorGroupingType | 動畫效果的類型 [`EffectChartMinorGroupingType`](../../effectchartminorgroupingtype) |
| index | Int32 | Int32 索引 |
| effectType | EffectType | 動畫效果的類型 [`EffectType`](../../effecttype) |
| subtype | EffectSubtype | 動畫效果的子類型 [`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | 效果的觸發類型 [`EffectTriggerType`](../../effecttriggertype) |

### 返回值

新的效果物件 [`IEffect`](../../ieffect)

### 另請參閱

* 介面 [IEffect](../../ieffect)
* 介面 [IChart](../../../aspose.slides.charts/ichart)
* 列舉 [EffectChartMajorGroupingType](../../effectchartmajorgroupingtype)
* 列舉 [EffectType](../../effecttype)
* 列舉 [EffectSubtype](../../effectsubtype)
* 列舉 [EffectTriggerType](../../effecttriggertype)
* 介面 [ISequence](../../isequence)
* 命名空間 [Aspose.Slides.Animation](../../isequence)
* 組件 [Aspose.Slides](../../../)

---

## AddEffect(IChart, EffectChartMinorGroupingType, int, int, EffectType, EffectSubtype, EffectTriggerType) {#addeffect_1}

將新的圖表動畫效果（針對類別或序列中的元素）新增至序列的末端。

```csharp
public IEffect AddEffect(IChart chart, EffectChartMinorGroupingType type, int seriesIndex, 
    int categoriesIndex, EffectType effectType, EffectSubtype subtype, 
    EffectTriggerType triggerType)
```

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| chart | IChart | Chart 物件 [`IChart`](../../../aspose.slides.charts/ichart) |
| type | EffectChartMinorGroupingType | 動畫效果的類型 [`EffectChartMinorGroupingType`](../../effectchartminorgroupingtype) |
| seriesIndex | Int32 | 圖表系列的 Int32 索引 |
| categoriesIndex | Int32 | 類別的 Int32 索引 |
| effectType | EffectType | 動畫效果的類型 [`EffectType`](../../effecttype) |
| subtype | EffectSubtype | 動畫效果的子類型 [`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | 效果的觸發類型 [`EffectTriggerType`](../../effecttriggertype) |

### 返回值

新的效果物件 [`IEffect`](../../ieffect)

### 另請參閱

* 介面 [IEffect](../../ieffect)
* 介面 [IChart](../../../aspose.slides.charts/ichart)
* 列舉 [EffectChartMinorGroupingType](../../effectchartminorgroupingtype)
* 列舉 [EffectType](../../effecttype)
* 列舉 [EffectSubtype](../../effectsubtype)
* 列舉 [EffectTriggerType](../../effecttriggertype)
* 介面 [ISequence](../../isequence)
* 命名空間 [Aspose.Slides.Animation](../../isequence)
* 組件 [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->