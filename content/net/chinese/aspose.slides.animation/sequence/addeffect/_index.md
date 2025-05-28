---
title: 添加效果
second_title: Aspose.Slides for .NET API 参考
description: 在序列末尾添加新效果。
type: docs
weight: 40
url: /zh/aspose.slides.animation/sequence/addeffect/
---

## AddEffect(IShape, EffectType, EffectSubtype, EffectTriggerType) {#addeffect_3}

在序列末尾添加新效果。

```csharp
public IEffect AddEffect(IShape shape, EffectType effectType, EffectSubtype subtype, 
    EffectTriggerType triggerType)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| shape | IShape | 要添加效果的形状对象 [`IShape`](../../../aspose.slides/ishape) |
| effectType | EffectType | 动画效果的类型 [`EffectType`](../../effecttype) |
| subtype | EffectSubtype | 动画效果的子类型 [`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | 效果的触发类型 [`EffectTriggerType`](../../effecttriggertype) |

### 返回值

新的效果对象 [`IEffect`](../../ieffect)

### 参见

* 接口 [IEffect](../../ieffect)
* 接口 [IShape](../../../aspose.slides/ishape)
* 枚举 [EffectType](../../effecttype)
* 枚举 [EffectSubtype](../../effectsubtype)
* 枚举 [EffectTriggerType](../../effecttriggertype)
* 类 [Sequence](../../sequence)
* 命名空间 [Aspose.Slides.Animation](../../sequence)
* 程序集 [Aspose.Slides](../../../)

---

## AddEffect(IParagraph, EffectType, EffectSubtype, EffectTriggerType) {#addeffect_2}

在序列末尾为段落添加新动画效果。

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

新的效果对象 [`IEffect`](../../ieffect)

### 示例

```csharp
[C#]
using(Presentation presentation = new Presentation(path + "input.pptx"))
{        
   // 选择要添加效果的段落
   IAutoShape autoShape = (IAutoShape)presentation.Slides[0].Shapes[0];
   IParagraph paragraph = autoShape.TextFrame.Paragraphs[0];

   // 向选择的段落添加飞入动画效果
   IEffect effect = presentation.Slides[0].Timeline.MainSequence.AddEffect(
   paragraph, EffectType.Fly, EffectSubtype.Left, EffectTriggerType.OnClick);
}
```

### 参见

* 接口 [IEffect](../../ieffect)
* 接口 [IParagraph](../../../aspose.slides/iparagraph)
* 枚举 [EffectType](../../effecttype)
* 枚举 [EffectSubtype](../../effectsubtype)
* 枚举 [EffectTriggerType](../../effecttriggertype)
* 类 [Sequence](../../sequence)
* 命名空间 [Aspose.Slides.Animation](../../sequence)
* 程序集 [Aspose.Slides](../../../)

---

## AddEffect(IChart, EffectChartMajorGroupingType, int, EffectType, EffectSubtype, EffectTriggerType) {#addeffect}

为类别或系列添加新的图表动画效果到序列末尾。

```csharp
public IEffect AddEffect(IChart chart, EffectChartMajorGroupingType type, int index, 
    EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| chart | IChart | 图表对象 [`IChart`](../../../aspose.slides.charts/ichart) |
| type | EffectChartMajorGroupingType | 动画效果的类型 [`EffectChartMinorGroupingType`](../../effectchartminorgroupingtype) |
| index | Int32 | 索引 Int32 |
| effectType | EffectType | 动画效果的类型 [`EffectType`](../../effecttype) |
| subtype | EffectSubtype | 动画效果的子类型 [`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | 效果的触发类型 [`EffectTriggerType`](../../effecttriggertype) |

### 返回值

新的效果对象 [`IEffect`](../../ieffect)

### 参见

* 接口 [IEffect](../../ieffect)
* 接口 [IChart](../../../aspose.slides.charts/ichart)
* 枚举 [EffectChartMajorGroupingType](../../effectchartmajorgroupingtype)
* 枚举 [EffectType](../../effecttype)
* 枚举 [EffectSubtype](../../effectsubtype)
* 枚举 [EffectTriggerType](../../effecttriggertype)
* 类 [Sequence](../../sequence)
* 命名空间 [Aspose.Slides.Animation](../../sequence)
* 程序集 [Aspose.Slides](../../../)

---

## AddEffect(IChart, EffectChartMinorGroupingType, int, int, EffectType, EffectSubtype, EffectTriggerType) {#addeffect_1}

为类别或系列中的元素添加新的图表动画效果到序列末尾。

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

新的效果对象 [`IEffect`](../../ieffect)

### 参见

* 接口 [IEffect](../../ieffect)
* 接口 [IChart](../../../aspose.slides.charts/ichart)
* 枚举 [EffectChartMinorGroupingType](../../effectchartminorgroupingtype)
* 枚举 [EffectType](../../effecttype)
* 枚举 [EffectSubtype](../../effectsubtype)
* 枚举 [EffectTriggerType](../../effecttriggertype)
* 类 [Sequence](../../sequence)
* 命名空间 [Aspose.Slides.Animation](../../sequence)
* 程序集 [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->