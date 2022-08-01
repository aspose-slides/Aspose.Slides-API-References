---
title: AddEffect
second_title: Aspose.Slides for .NET API 参考
description: 在序列末尾添加新效果
type: docs
weight: 40
url: /zh/net/aspose.slides.animation/sequence/addeffect/
---
## AddEffect(IShape, EffectType, EffectSubtype, EffectTriggerType) {#addeffect_3}

在序列末尾添加新效果。

```csharp
public IEffect AddEffect(IShape shape, EffectType effectType, EffectSubtype subtype, 
    EffectTriggerType triggerType)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| shape | IShape | 形状对象[`IShape`](../../../aspose.slides/ishape)用于添加效果 |
| effectType | EffectType | 动画效果的类型[`EffectType`](../../effecttype) |
| subtype | EffectSubtype | 动画效果的子类型[`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | 触发效果类型[`EffectTriggerType`](../../effecttriggertype) |

### 返回值

新效果对象[`IEffect`](../../ieffect)

### 也可以看看

* interface [IEffect](../../ieffect)
* interface [IShape](../../../aspose.slides/ishape)
* enum [EffectType](../../effecttype)
* enum [EffectSubtype](../../effectsubtype)
* enum [EffectTriggerType](../../effecttriggertype)
* class [Sequence](../../sequence)
* 命名空间 [Aspose.Slides.Animation](../../sequence)
* 部件 [Aspose.Slides](../../../)

---

## AddEffect(IParagraph, EffectType, EffectSubtype, EffectTriggerType) {#addeffect_2}

为段落添加新的动画效果到序列的末尾。

```csharp
public IEffect AddEffect(IParagraph paragraph, EffectType effectType, EffectSubtype subtype, 
    EffectTriggerType triggerType)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| paragraph | IParagraph | 段落对象[`IParagraph`](../../../aspose.slides/iparagraph) |
| effectType | EffectType | 动画效果的类型[`EffectType`](../../effecttype) |
| subtype | EffectSubtype | 动画效果的子类型[`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | 触发效果类型[`EffectTriggerType`](../../effecttriggertype) |

### 返回值

新效果对象[`IEffect`](../../ieffect)

### 例子

```csharp
[C#]
using(Presentation presentation = new Presentation(path + "input.pptx"))
{        
   // 选择段落添加效果
   IAutoShape autoShape = (IAutoShape)presentation.Slides[0].Shapes[0];
   IParagraph paragraph = autoShape.TextFrame.Paragraphs[0];

   // 给选中的段落添加飞行动画效果
   IEffect effect = presentation.Slides[0].Timeline.MainSequence.AddEffect(
   paragraph, EffectType.Fly, EffectSubtype.Left, EffectTriggerType.OnClick);
}
```

### 也可以看看

* interface [IEffect](../../ieffect)
* interface [IParagraph](../../../aspose.slides/iparagraph)
* enum [EffectType](../../effecttype)
* enum [EffectSubtype](../../effectsubtype)
* enum [EffectTriggerType](../../effecttriggertype)
* class [Sequence](../../sequence)
* 命名空间 [Aspose.Slides.Animation](../../sequence)
* 部件 [Aspose.Slides](../../../)

---

## AddEffect(IChart, EffectChartMajorGroupingType, int, EffectType, EffectSubtype, EffectTriggerType) {#addeffect}

将类别或系列的新图表动画效果添加到序列末尾。

```csharp
public IEffect AddEffect(IChart chart, EffectChartMajorGroupingType type, int index, 
    EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| chart | IChart | 图表对象[`IChart`](../../../aspose.slides.charts/ichart) |
| type | EffectChartMajorGroupingType | 动画效果的类型[`EffectChartMinorGroupingType`](../../effectchartminorgroupingtype) |
| index | Int32 | 指数Int32 |
| effectType | EffectType | 动画效果的类型[`EffectType`](../../effecttype) |
| subtype | EffectSubtype | 动画效果的子类型[`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | 触发效果类型[`EffectTriggerType`](../../effecttriggertype) |

### 返回值

新效果对象[`IEffect`](../../ieffect)

### 也可以看看

* interface [IEffect](../../ieffect)
* interface [IChart](../../../aspose.slides.charts/ichart)
* enum [EffectChartMajorGroupingType](../../effectchartmajorgroupingtype)
* enum [EffectType](../../effecttype)
* enum [EffectSubtype](../../effectsubtype)
* enum [EffectTriggerType](../../effecttriggertype)
* class [Sequence](../../sequence)
* 命名空间 [Aspose.Slides.Animation](../../sequence)
* 部件 [Aspose.Slides](../../../)

---

## AddEffect(IChart, EffectChartMinorGroupingType, int, int, EffectType, EffectSubtype, EffectTriggerType) {#addeffect_1}

将类别或系列中元素的新图表动画效果添加到序列末尾。

```csharp
public IEffect AddEffect(IChart chart, EffectChartMinorGroupingType type, int seriesIndex, 
    int categoriesIndex, EffectType effectType, EffectSubtype subtype, 
    EffectTriggerType triggerType)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| chart | IChart | 图表对象[`IChart`](../../../aspose.slides.charts/ichart) |
| type | EffectChartMinorGroupingType | 动画效果的类型[`EffectChartMinorGroupingType`](../../effectchartminorgroupingtype) |
| seriesIndex | Int32 | 图表系列索引Int32 |
| categoriesIndex | Int32 | 分类索引Int32 |
| effectType | EffectType | 动画效果的类型[`EffectType`](../../effecttype) |
| subtype | EffectSubtype | 动画效果的子类型[`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | 触发效果类型[`EffectTriggerType`](../../effecttriggertype) |

### 返回值

新效果对象[`IEffect`](../../ieffect)

### 也可以看看

* interface [IEffect](../../ieffect)
* interface [IChart](../../../aspose.slides.charts/ichart)
* enum [EffectChartMinorGroupingType](../../effectchartminorgroupingtype)
* enum [EffectType](../../effecttype)
* enum [EffectSubtype](../../effectsubtype)
* enum [EffectTriggerType](../../effecttriggertype)
* class [Sequence](../../sequence)
* 命名空间 [Aspose.Slides.Animation](../../sequence)
* 部件 [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
