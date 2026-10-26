---
title: Sequence
second_title: Aspose.Slides for Android via Java API 参考
description: 表示效果的序列集合。
type: docs
url: /zh/com.aspose.slides/sequence/
---
**继承：**
java.lang.Object

**已实现的接口：**
[com.aspose.slides.ISequence](../../com.aspose.slides/isequence)
```
public final class Sequence implements ISequence
```

表示序列（效果的集合）。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getCount()](#getCount--) | 返回序列中效果的数量。 |
| [remove(IEffect item)](#remove-com.aspose.slides.IEffect-) | 从集合中移除指定的效果。 |
| [removeAt(int index)](#removeAt-int-) | 从集合中移除一个效果。 |
| [clear()](#clear--) | 从集合中移除所有效果。 |
| [get_Item(int index)](#get-Item-int-) | 返回指定索引处的效果。 |
| [iterator()](#iterator--) | 返回一个遍历集合的枚举器。 |
| [iteratorJava()](#iteratorJava--) | 返回整个集合的 java 迭代器。 |
| [getTriggerShape()](#getTriggerShape--) | 返回或设置 INTERACTIVE 序列的形状目标。 |
| [setTriggerShape(IShape value)](#setTriggerShape-com.aspose.slides.IShape-) | 返回或设置 INTERACTIVE 序列的形状目标。 |
| [removeByShape(IShape shape)](#removeByShape-com.aspose.slides.IShape-) | 移除指定形状的效果。 |
| [getEffectsByShape(IShape shape)](#getEffectsByShape-com.aspose.slides.IShape-) | 返回指定形状的效果数组。 |
| [getEffectsByParagraph(IParagraph paragraph)](#getEffectsByParagraph-com.aspose.slides.IParagraph-) | 返回指定段落的效果数组。 |
| [getCount(IShape shape)](#getCount-com.aspose.slides.IShape-) | 返回指定形状的效果计数。 |
| [addEffect(IShape shape, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IShape-int-int-int-) | 在序列末尾添加新效果。 |
| [addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IParagraph-int-int-int-) | 在序列末尾为段落添加新的动画效果。 |
| [addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IChart-int-int-int-int-int-) | 在序列末尾为类别或系列添加新的图表动画效果。 |
| [addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IChart-int-int-int-int-int-int-) | 在序列末尾为类别或系列中的元素添加新的图表动画效果。 |
### getCount() {#getCount--}
```
public final int getCount()
```

返回序列中效果的数量。只读 int。

**返回：**
int
### remove(IEffect item) {#remove-com.aspose.slides.IEffect-}
```
public final void remove(IEffect item)
```

从集合中移除指定的效果。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| item | [IEffect](../../com.aspose.slides/ieffect) | 要移除的效果。 |
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

从集合中移除一个效果。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 应删除的效果的索引。 |
### clear() {#clear--}
```
public final void clear()
```

从集合中移除所有效果。
### get_Item(int index) {#get-Item-int-}
```
public final IEffect get_Item(int index)
```

返回指定索引处的效果。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 元素的索引。 |

**返回：**
[IEffect](../../com.aspose.slides/ieffect) - [IEffect](../../com.aspose.slides/ieffect) 对象。
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IEffect> iterator()
```

返回一个遍历集合的枚举器。

**返回：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IEffect> - 可用于遍历集合的 IGenericEnumerator。
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IEffect> iteratorJava()
```

返回整个集合的 java 迭代器。

**返回：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IEffect> - 一个用于遍历整个集合的 java.util.Iterator。
### getTriggerShape() {#getTriggerShape--}
```
public final IShape getTriggerShape()
```

返回或设置 INTERACTIVE 序列的形状目标。如果序列不是交互式的，则返回 null。可读写 [IShape](../../com.aspose.slides/ishape)。

**返回：**
[IShape](../../com.aspose.slides/ishape)
### setTriggerShape(IShape value) {#setTriggerShape-com.aspose.slides.IShape-}
```
public final void setTriggerShape(IShape value)
```

返回或设置 INTERACTIVE 序列的形状目标。如果序列不是交互式的，则返回 null。可读写 [IShape](../../com.aspose.slides/ishape)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |
### removeByShape(IShape shape) {#removeByShape-com.aspose.slides.IShape-}
```
public final void removeByShape(IShape shape)
```

移除指定形状的效果。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) |  |
### getEffectsByShape(IShape shape) {#getEffectsByShape-com.aspose.slides.IShape-}
```
public final IEffect[] getEffectsByShape(IShape shape)
```

返回指定形状的效果数组。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) |  |

**返回：**
com.aspose.slides.IEffect[]
### getEffectsByParagraph(IParagraph paragraph) {#getEffectsByParagraph-com.aspose.slides.IParagraph-}
```
public final IEffect[] getEffectsByParagraph(IParagraph paragraph)
```

返回指定段落的效果数组。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| paragraph | [IParagraph](../../com.aspose.slides/iparagraph) |  |

**返回：**
com.aspose.slides.IEffect[]
### getCount(IShape shape) {#getCount-com.aspose.slides.IShape-}
```
public final int getCount(IShape shape)
```

返回指定形状的效果计数。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) |  |

**返回：**
int
### addEffect(IShape shape, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IShape-int-int-int-}
```
public final IEffect addEffect(IShape shape, int effectType, int subtype, int triggerType)
```

在序列末尾添加新效果。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | 用于添加效果的形状对象 [IShape](../../com.aspose.slides/ishape) |
| effectType | int | 动画效果的类型 [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | 动画效果的子类型 [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | 效果的触发类型 [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**返回：**
[IEffect](../../com.aspose.slides/ieffect) - 新的效果对象 [IEffect](../../com.aspose.slides/ieffect)
### addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IParagraph-int-int-int-}
```
public final IEffect addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType)
```

在序列末尾为段落添加新的动画效果。

--------------------

> ```
> Presentation presentation = new Presentation(path + "input.pptx");
>   try
>   {        
>      // select paragraph to add effect
>      IAutoShape autoShape = (IAutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>      IParagraph paragraph = autoShape.getTextFrame().getParagraphs().get_Item(0);
>      // add Fly animation effect to selected paragraph
>      IEffect effect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().addEffect(
>      paragraph, EffectType.Fly, EffectSubtype.Left, EffectTriggerType.OnClick);
>   }  finally {
>      if (presentation != null) presentation.dispose();
>   }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| paragraph | [IParagraph](../../com.aspose.slides/iparagraph) | Paragraph object [IParagraph](../../com.aspose.slides/iparagraph) |
| effectType | int | Type of an animation effect [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Subtypes of animation effect [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Trigger type of effect [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Returns:**
[IEffect](../../com.aspose.slides/ieffect) - New effect object [IEffect](../../com.aspose.slides/ieffect)
### addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IChart-int-int-int-int-int-}
```
public final IEffect addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType)
```

Adds the new chart animation effect for category or series to the end of sequence.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| chart | [IChart](../../com.aspose.slides/ichart) | Chart object [IChart](../../com.aspose.slides/ichart) |
| type | int | Type of an animation effect [EffectChartMinorGroupingType](../../com.aspose.slides/effectchartminorgroupingtype) |
| index | int | Index int |
| effectType | int | Type of an animation effect [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Subtypes of animation effect [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Trigger type of effect [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Returns:**
[IEffect](../../com.aspose.slides/ieffect) - New effect object [IEffect](../../com.aspose.slides/ieffect)
### addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IChart-int-int-int-int-int-int-}
```
public final IEffect addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType)

为类别或系列中的元素添加新的图表动画效果。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| chart | [IChart](../../com.aspose.slides/ichart) | 图表对象 [IChart](../../com.aspose.slides/ichart) |
| type | int | 动画效果的类型 [EffectChartMinorGroupingType](../../com.aspose.slides/effectchartminorgroupingtype) |
| seriesIndex | int | 图表系列的索引 |
| categoriesIndex | int | 类别的索引 |
| effectType | int | 动画效果的类型 [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | 动画效果的子类型 [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | 效果的触发类型 [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**返回：**
[IEffect](../../com.aspose.slides/ieffect) - 新的效果对象 [IEffect](../../com.aspose.slides/ieffect)