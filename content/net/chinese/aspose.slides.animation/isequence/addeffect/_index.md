---
title: AddEffect
second_title: Aspose.Sildes for .NET API 参考
description: 向序列末尾添加新效果。
type: docs
weight: 50
url: /zh/aspose.slides.animation/isequence/addeffect/
---

## AddEffect(IShape, EffectType, EffectSubtype, EffectTriggerType) {#addeffect_3}

向序列末尾添加新效果。

```csharp
public IEffect AddEffect(IShape shape, EffectType effectType, EffectSubtype subtype, 
    EffectTriggerType triggerType)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| shape | IShape | 用于添加效果的形状对象 [`IShape`](../../../aspose.slides/ishape) |
| effectType | EffectType | 动画效果的类型 [`EffectType`](../../effecttype) |
| subtype | EffectSubtype | 动画效果的子类型 [`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | 效果的触发类型 [`EffectTriggerType`](../../effecttriggertype) |

### 返回值

新效果对象 [`IEffect`](../../ieffect)

### 另请参见

* interface [IEffect](../../ieffect)
* interface [IShape](../../../aspose.slides/ishape)
* enum [EffectType](../../effecttype)
* enum [EffectSubtype](../../effectsubtype)
* enum [EffectTriggerType](../../effecttriggertype)
* interface [ISequence](../../isequence)
* namespace [Aspose.Slides.Animation](../../isequence)
* assembly [Aspose.Slides](../../../)

---

## AddEffect(IParagraph, EffectType, EffectSubtype, EffectTriggerType) {#addeffect_2}

向段落的序列末尾添加新的动画效果。

```csharp
public IEffect AddEffect(IParagraph paragraph, EffectType effectType, EffectSubtype subtype, 
    EffectTriggerType triggerType)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| paragraph | IParagraph | 段落对象 [`IParagraph`](../../../aspose.slides/iparagraph) |
| effectType | EffectType | 动画效果的类型 [`EffectType`](../../effecttype) |
| subtype | EffectSubtype | 动画效果的子类型 [`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | 效果的触发类型 [`EffectTriggerType`](../../effecttriggertype) |

### 返回值

新效果对象 [`IEffect`](../../ieffect)

### 示例

```csharp
[C#]
using(Presentation presentation = new Presentation(path + "input.pptx"))
{        
   // 选择段落以添加效果
   IAutoShape autoShape = (IAutoShape)presentation.Slides[0].Shapes[0];
   IParagraph paragraph = autoShape.TextFrame.Paragraphs[0];

   // 为选定的段落添加飞入动画效果
   IEffect effect = presentation.Slides[0].Timeline.MainSequence.AddEffect(
   paragraph, EffectType.Fly, EffectSubtype.Left, EffectTriggerType.OnClick);
}
```

### 另请参见

* interface [IEffect](../../ieffect)
* interface [IParagraph](../../../aspose.slides/iparagraph)
* enum [EffectType](../../effecttype)
* enum [EffectSubtype](../../effectsubtype)
* enum [EffectTriggerType](../../effecttriggertype)
* interface [ISequence](../../isequence)
* namespace [Aspose.Slides.Animation](../../isequence)
* assembly [Aspose.Slides](../../../)

---

## AddEffect(IChart, EffectChartMajorGroupingType, int, EffectType, EffectSubtype, EffectTriggerType) {#addeffect}

为类别或系列的图表末尾添加新的动画效果。

```csharp
public IEffect AddEffect(IChart chart, EffectChartMajorGroupingType type, int index, 
    EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| chart | IChart | 图表对象 [`IChart`](../../../aspose.slides.charts/ichart) |
| type | EffectChartMajorGroupingType | 动画效果的类型 [`EffectChartMinorGroupingType`](../../effectchartminorgroupingtype) |
| index | Int32 | Int32 索引 |
| effectType | EffectType | 动画效果的类型 [`EffectType`](../../effecttype) |
| subtype | EffectSubtype | 动画效果的子类型 [`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | 效果的触发类型 [`EffectTriggerType`](../../effecttriggertype) |

### 返回值

新效果对象 [`IEffect`](../../ieffect)

### 另请参见

* interface [IEffect](../../ieffect)
* interface [IChart](../../../aspose.slides.charts/ichart)
* enum [EffectChartMajorGroupingType](../../effectchartmajorgroupingtype)
* enum [EffectType](../../effecttype)
* enum [EffectSubtype](../../effectsubtype)
* enum [EffectTriggerType](../../effecttriggertype)
* interface [ISequence](../../isequence)
* namespace [Aspose.Slides.Animation](../../isequence)
* assembly [Aspose.Slides](../../../)

---

## AddEffect(IChart, EffectChartMinorGroupingType, int, int, EffectType, EffectSubtype, EffectTriggerType) {#addeffect_1}

为类别或系列中的元素末尾添加新的图表动画效果。

```csharp
public IEffect AddEffect(IChart chart, EffectChartMinorGroupingType type, int seriesIndex, 
    int categoriesIndex, EffectType effectType, EffectSubtype subtype, 
    EffectTriggerType triggerType)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| chart | IChart | 图表对象 [`IChart`](../../../aspose.slides.charts/ichart) |
| type | EffectChartMinorGroupingType | 动画效果的类型 [`EffectChartMinorGroupingType`](../../effectchartminorgroupingtype) |
| seriesIndex | Int32 | 图表系列的索引 Int32 |
| categoriesIndex | Int32 | 类别的索引 Int32 |
| effectType | EffectType | 动画效果的类型 [`EffectType`](../../effecttype) |
| subtype | EffectSubtype | 动画效果的子类型 [`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | 效果的触发类型 [`EffectTriggerType`](../../effecttriggertype) |

### 返回值

新效果对象 [`IEffect`](../../ieffect)

### 另请参见

* interface [IEffect](../../ieffect)
* interface [IChart](../../../aspose.slides.charts/ichart)
* enum [EffectChartMinorGroupingType](../../effectchartminorgroupingtype)
* enum [EffectType](../../effecttype)
* enum [EffectSubtype](../../effectsubtype)
* enum [EffectTriggerType](../../effecttriggertype)
* interface [ISequence](../../isequence)
* namespace [Aspose.Slides.Animation](../../isequence)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->