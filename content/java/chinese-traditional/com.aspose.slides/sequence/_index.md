---
title: Sequence
second_title: Aspose.Slides for Java API 參考
description: 表示效應的序列集合。
type: docs
url: /zh-hant/com.aspose.slides/sequence/
---
**繼承:**
java.lang.Object

**已實作的介面:**
[com.aspose.slides.ISequence](../../com.aspose.slides/isequence)
```
public final class Sequence implements ISequence
```

代表序列（效應的集合）。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getCount()](#getCount--) | 返回序列中效應的數量。 |
| [remove(IEffect item)](#remove-com.aspose.slides.IEffect-) | 從集合中移除指定的效應。 |
| [removeAt(int index)](#removeAt-int-) | 從集合中移除效應。 |
| [clear()](#clear--) | 從集合中移除所有效應。 |
| [get_Item(int index)](#get-Item-int-) | 返回指定索引處的效應。 |
| [iterator()](#iterator--) | 返回可遍歷集合的列舉器。 |
| [iteratorJava()](#iteratorJava--) | 返回整個集合的 java 迭代器。 |
| [getTriggerShape()](#getTriggerShape--) | 返回或設定 INTERACTIVE 序列的形狀目標。 |
| [setTriggerShape(IShape value)](#setTriggerShape-com.aspose.slides.IShape-) | 返回或設定 INTERACTIVE 序列的形狀目標。 |
| [removeByShape(IShape shape)](#removeByShape-com.aspose.slides.IShape-) | 移除指定形狀的效應。 |
| [getEffectsByShape(IShape shape)](#getEffectsByShape-com.aspose.slides.IShape-) | 返回指定形狀的效應陣列。 |
| [getEffectsByParagraph(IParagraph paragraph)](#getEffectsByParagraph-com.aspose.slides.IParagraph-) | 返回指定段落的效應陣列。 |
| [getCount(IShape shape)](#getCount-com.aspose.slides.IShape-) | 返回指定形狀的效應計數。 |
| [addEffect(IShape shape, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IShape-int-int-int-) | 在序列末尾新增效應。 |
| [addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IParagraph-int-int-int-) | 在序列末尾為段落新增動畫效應。 |
| [addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IChart-int-int-int-int-int-) | 在序列末尾為類別或系列新增圖表動畫效應。 |
| [addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IChart-int-int-int-int-int-int-) | 在序列末尾為類別或系列中的元素新增圖表動畫效應。 |
### getCount() {#getCount--}
```
public final int getCount()
```

返回序列中效應的數量。唯讀 int.

**返回：**
int
### remove(IEffect item) {#remove-com.aspose.slides.IEffect-}
```
public final void remove(IEffect item)
```

從集合中移除指定的效應。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| item | [IEffect](../../com.aspose.slides/ieffect) | 要移除的效應。 |
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

從集合中移除效應。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 應該被刪除的效應索引。 |
### clear() {#clear--}
```
public final void clear()
```

從集合中移除所有效應。
### get_Item(int index) {#get-Item-int-}
```
public final IEffect get_Item(int index)
```

返回指定索引處的效應。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 元素的索引。 |

**返回：**
[IEffect](../../com.aspose.slides/ieffect) - 此 [IEffect](../../com.aspose.slides/ieffect) 物件。
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IEffect> iterator()
```

返回可遍歷集合的列舉器。

**返回：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IEffect> - 可用於遍歷集合的 IGenericEnumerator。
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IEffect> iteratorJava()
```

返回整個集合的 java 迭代器。

**返回：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IEffect> - 用於整個集合的 java.util.Iterator。
### getTriggerShape() {#getTriggerShape--}
```
public final IShape getTriggerShape()
```

返回或設定 INTERACTIVE 序列的形狀目標。如果序列非互動式，則返回 null。讀寫 [IShape](../../com.aspose.slides/ishape)。

**返回：**
[IShape](../../com.aspose.slides/ishape)
### setTriggerShape(IShape value) {#setTriggerShape-com.aspose.slides.IShape-}
```
public final void setTriggerShape(IShape value)
```

返回或設定 INTERACTIVE 序列的形狀目標。如果序列非互動式，則返回 null。讀寫 [IShape](../../com.aspose.slides/ishape)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |
### removeByShape(IShape shape) {#removeByShape-com.aspose.slides.IShape-}
```
public final void removeByShape(IShape shape)
```

移除指定形狀的效應。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) |  |
### getEffectsByShape(IShape shape) {#getEffectsByShape-com.aspose.slides.IShape-}
```
public final IEffect[] getEffectsByShape(IShape shape)
```

返回指定形狀的效應陣列。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) |  |

**返回：**
com.aspose.slides.IEffect[]
### getEffectsByParagraph(IParagraph paragraph) {#getEffectsByParagraph-com.aspose.slides.IParagraph-}
```
public final IEffect[] getEffectsByParagraph(IParagraph paragraph)
```

返回指定段落的效應陣列。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| paragraph | [IParagraph](../../com.aspose.slides/iparagraph) |  |

**返回：**
com.aspose.slides.IEffect[]
### getCount(IShape shape) {#getCount-com.aspose.slides.IShape-}
```
public final int getCount(IShape shape)
```

返回指定形狀的效應計數。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) |  |

**返回：**
int
### addEffect(IShape shape, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IShape-int-int-int-}
```
public final IEffect addEffect(IShape shape, int effectType, int subtype, int triggerType)
```

在序列末尾新增效應。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | Shape 物件 [IShape](../../com.aspose.slides/ishape) 用於新增效應 |
| effectType | int | 動畫效應的類型 [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | 動畫效應的子類型 [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | 效應的觸發類型 [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**返回：**
[IEffect](../../com.aspose.slides/ieffect) - 新的效應物件 [IEffect](../../com.aspose.slides/ieffect)
### addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IParagraph-int-int-int-}
```
public final IEffect addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType)
```

在序列末尾為段落新增動畫效應。

--------------------

> ```
> Presentation presentation = new Presentation(path + "input.pptx");
>   try
>   {        
>      // 選取段落以添加效果
>      IAutoShape autoShape = (IAutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>      IParagraph paragraph = autoShape.getTextFrame().getParagraphs().get_Item(0);
>      // 為所選段落添加 Fly 動畫效果
>      IEffect effect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().addEffect(
>      paragraph, EffectType.Fly, EffectSubtype.Left, EffectTriggerType.OnClick);
>   }  finally {
>      if (presentation != null) presentation.dispose();
>   }
> ```


**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| paragraph | [IParagraph](../../com.aspose.slides/iparagraph) | Paragraph 物件 [IParagraph](../../com.aspose.slides/iparagraph) |
| effectType | int | 動畫效應的類型 [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | 動畫效應的子類型 [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | 效應的觸發類型 [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**返回：**
[IEffect](../../com.aspose.slides/ieffect) - 新的效應物件 [IEffect](../../com.aspose.slides/ieffect)
### addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IChart-int-int-int-int-int-}
```
public final IEffect addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType)
```

在序列末尾為類別或系列新增圖表動畫效應。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| chart | [IChart](../../com.aspose.slides/ichart) | 圖表物件 [IChart](../../com.aspose.slides/ichart) |
| type | int | 動畫效應的類型 [EffectChartMinorGroupingType](../../com.aspose.slides/effectchartminorgroupingtype) |
| index | int | 索引 int |
| effectType | int | 動畫效應的類型 [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | 動畫效應的子類型 [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | 效應的觸發類型 [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**返回：**
[IEffect](../../com.aspose.slides/ieffect) - 新的效應物件 [IEffect](../../com.aspose.slides/ieffect)
### addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IChart-int-int-int-int-int-int-}
```
public final IEffect addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType)
```

在序列末尾為類別或系列中的元素新增圖表動畫效應。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| chart | [IChart](../../com.aspose.slides/ichart) | 圖表物件 [IChart](../../com.aspose.slides/ichart) |
| type | int | 動畫效應的類型 [EffectChartMinorGroupingType](../../com.aspose.slides/effectchartminorgroupingtype) |
| seriesIndex | int | 圖表系列的索引 int |
| categoriesIndex | int | 類別的索引 int |
| effectType | int | 動畫效應的類型 [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | 動畫效應的子類型 [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | 效應的觸發類型 [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**返回：**
[IEffect](../../com.aspose.slides/ieffect) - 新的效應物件 [IEffect](../../com.aspose.slides/ieffect)