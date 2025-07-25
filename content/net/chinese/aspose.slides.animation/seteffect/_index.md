---
title: SetEffect
second_title: Aspose.Sildes for .NET API Reference
description: 表示动画行为的集合效果。
type: docs
weight: 730
url: /zh/aspose.slides.animation/seteffect/
---

## SetEffect class

表示动画行为的集合效果。

```csharp
public class SetEffect : Behavior, ISetEffect
```

## Constructors

| Name | Description |
| --- | --- |
| [SetEffect](seteffect)() | 默认构造函数。 |

## Properties

| Name | Description |
| --- | --- |
| [Accumulate](../../aspose.slides.animation/behavior/accumulate) { get; set; } | 表示动画行为是否被累积。可读/写 [`NullableBool`](../../aspose.slides/nullablebool)。 |
| [Additive](../../aspose.slides.animation/behavior/additive) { get; set; } | 表示当前动画行为是否与其他正在运行的动画结合。可读/写 [`BehaviorAdditiveType`](../behavioradditivetype)。 |
| [Properties](../../aspose.slides.animation/behavior/properties) { get; } | 表示行为的属性。只读 [`IBehaviorPropertyCollection`](../ibehaviorpropertycollection)。 |
| [Timing](../../aspose.slides.animation/behavior/timing) { get; set; } | 表示效果行为的计时属性。可读/写 [`ITiming`](../itiming)。 |
| [To](../../aspose.slides.animation/seteffect/to) { get; set; } | 指定动画效果后某个效果的特定属性。表示点值。仅支持: bool, ColorFormat, float, int, string。可读/写对象。 |

### See Also

* class [Behavior](../behavior)
* interface [ISetEffect](../iseteffect)
* namespace [Aspose.Slides.Animation](../../aspose.slides.animation)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->