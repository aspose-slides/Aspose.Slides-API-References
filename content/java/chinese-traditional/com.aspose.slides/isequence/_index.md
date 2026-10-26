---
title: ISequence
second_title: Aspose.Slides for Java API 參考文件
description: 表示效果的序列集合。
type: docs
url: /zh-hant/com.aspose.slides/isequence/
---
**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface ISequence extends System.Collections.Generic.IGenericEnumerable<IEffect>
```

表示序列（效果的集合）。
## Methods

| 方法 | 說明 |
| --- | --- |
| [getCount()](#getCount--) | 返回序列中效果的數量。 |
| [remove(IEffect item)](#remove-com.aspose.slides.IEffect-) | 從集合中移除指定的效果。 |
| [removeAt(int index)](#removeAt-int-) | 從集合中移除一個效果。 |
| [clear()](#clear--) | 從集合中移除所有效果。 |
| [get_Item(int index)](#get-Item-int-) | 返回指定索引處的效果。 |
| [getTriggerShape()](#getTriggerShape--) | 返回或設定 INTERACTIVE 序列的形狀目標。 |
| [setTriggerShape(IShape value)](#setTriggerShape-com.aspose.slides.IShape-) | 返回或設定 INTERACTIVE 序列的形狀目標。 |
| [removeByShape(IShape shape)](#removeByShape-com.aspose.slides.IShape-) | 移除指定形狀的效果。 |
| [getEffectsByShape(IShape shape)](#getEffectsByShape-com.aspose.slides.IShape-) | 返回指定形狀的效果陣列。 |
| [getEffectsByParagraph(IParagraph paragraph)](#getEffectsByParagraph-com.aspose.slides.IParagraph-) | 返回指定段落的效果陣列。 |
| [getCount(IShape shape)](#getCount-com.aspose.slides.IShape-) | 返回指定形狀的效果計數。 |
| [addEffect(IShape shape, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IShape-int-int-int-) | 在序列末端新增效果。 |
| [addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IParagraph-int-int-int-) | 在序列末端為段落新增動畫效果。 |
| [addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IChart-int-int-int-int-int-) | 在序列末端為類別或系列新增圖表動畫效果。 |
| [addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IChart-int-int-int-int-int-int-) | 在序列末端為類別或系列中的元素新增圖表動畫效果。 |
### getCount() {#getCount--}
```
public abstract int getCount()
```


返回序列中效果的數量。唯讀 int.

**Returns:**
int
### remove(IEffect item) {#remove-com.aspose.slides.IEffect-}
```
public abstract void remove(IEffect item)
```


從集合中移除指定的效果。

**Parameters:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| item | [IEffect](../../com.aspose.slides/ieffect) | 要移除的效果。 |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


從集合中移除一個效果。

**Parameters:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 要移除的效果索引 int |

### clear() {#clear--}
```
public abstract void clear()
```


從集合中移除所有效果。

### get_Item(int index) {#get-Item-int-}
```
public abstract IEffect get_Item(int index)
```


返回指定索引處的效果。

**Parameters:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 元素的索引。 |

**Returns:**
[IEffect](../../com.aspose.slides/ieffect) - The [IEffect](../../com.aspose.slides/ieffect) object.
### getTriggerShape() {#getTriggerShape--}
```
public abstract IShape getTriggerShape()
```


返回或設定 INTERACTIVE 序列的形狀目標。如果序列不是互動的則返回 null。讀寫 [IShape](../../com.aspose.slides/ishape)。

**Returns:**
[IShape](../../com.aspose.slides/ishape)
### setTriggerShape(IShape value) {#setTriggerShape-com.aspose.slides.IShape-}
```
public abstract void setTriggerShape(IShape value)
```


返回或設定 INTERACTIVE 序列的形狀目標。如果序列不是互動的則返回 null。讀寫 [IShape](../../com.aspose.slides/ishape)。

**Parameters:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |

### removeByShape(IShape shape) {#removeByShape-com.aspose.slides.IShape-}
```
public abstract void removeByShape(IShape shape)
```


移除指定形狀的效果。

**Parameters:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | Shape object [IShape](../../com.aspose.slides/ishape) |

### getEffectsByShape(IShape shape) {#getEffectsByShape-com.aspose.slides.IShape-}
```
public abstract IEffect[] getEffectsByShape(IShape shape)
```


返回指定形狀的效果陣列。

**Parameters:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | Shape object [IShape](../../com.aspose.slides/ishape) |

**Returns:**
com.aspose.slides.IEffect[] - Array of effects [IEffect](../../com.aspose.slides/ieffect)
### getEffectsByParagraph(IParagraph paragraph) {#getEffectsByParagraph-com.aspose.slides.IParagraph-}
```
public abstract IEffect[] getEffectsByParagraph(IParagraph paragraph)
```


返回指定段落的效果陣列。

**Parameters:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| paragraph | [IParagraph](../../com.aspose.slides/iparagraph) | Paragraph object [IParagraph](../../com.aspose.slides/iparagraph) |

**Returns:**
com.aspose.slides.IEffect[] - Array of effects [IEffect](../../com.aspose.slides/ieffect)
### getCount(IShape shape) {#getCount-com.aspose.slides.IShape-}
```
public abstract int getCount(IShape shape)
```


返回指定形狀的效果計數。

**Parameters:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | Shape object [IShape](../../com.aspose.slides/ishape) |

**Returns:**
int - Count of effects int
### addEffect(IShape shape, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IShape-int-int-int-}
```
public abstract IEffect addEffect(IShape shape, int effectType, int subtype, int triggerType)
```


在序列末端新增效果。

**Parameters:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | Shape object [IShape](../../com.aspose.slides/ishape) for adding an effect |
| effectType | int | Type of an animation effect [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Subtypes of animation effect [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Trigger type of effect [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Returns:**
[IEffect](../../com.aspose.slides/ieffect) - New effect object [IEffect](../../com.aspose.slides/ieffect)
### addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IParagraph-int-int-int-}
```
public abstract IEffect addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType)
```


在序列末端為段落新增動畫效果。

--------------------

> ```
> Presentation presentation = new Presentation(path + "input.pptx");
>  try
>  {
>     // 選取段落以加入效果
>     IAutoShape autoShape = (IAutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>     IParagraph paragraph = autoShape.getTextFrame().getParagraphs().get_Item(0);
>     // 為選取的段落新增 Fly 動畫效果
>     IEffect effect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().addEffect(
>     paragraph, EffectType.Fly, EffectSubtype.Left, EffectTriggerType.OnClick);
>  } finally {
>     if (presentation != null) presentation.dispose();
>  }
> ```


**Parameters:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| paragraph | [IParagraph](../../com.aspose.slides/iparagraph) | Paragraph object [IParagraph](../../com.aspose.slides/iparagraph) |
| effectType | int | Type of an animation effect [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Subtypes of animation effect [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Trigger type of effect [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Returns:**
[IEffect](../../com.aspose.slides/ieffect) - New effect object [IEffect](../../com.aspose.slides/ieffect)
### addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IChart-int-int-int-int-int-}
```
public abstract IEffect addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType)
```


在序列末端為類別或系列新增圖表動畫效果。

**Parameters:**
| 參數 | 類型 | 說明 |
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
public abstract IEffect addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType)
```


在序列末端為類別或系列中的元素新增圖表動畫效果。

**Parameters:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| chart | [IChart](../../com.aspose.slides/ichart) | Chart object [IChart](../../com.aspose.slides/ichart) |
| type | int | Type of an animation effect [EffectChartMinorGroupingType](../../com.aspose.slides/effectchartminorgroupingtype) |
| seriesIndex | int | Index of chart series int |
| categoriesIndex | int | Index of category int |
| effectType | int | Type of an animation effect [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Subtypes of animation effect [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Trigger type of effect [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Returns:**
[IEffect](../../com.aspose.slides/ieffect) - New effect object [IEffect](../../com.aspose.slides/ieffect)