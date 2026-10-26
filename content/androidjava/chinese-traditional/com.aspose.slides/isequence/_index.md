---
title: ISequence
second_title: Aspose.Slides for Android 透過 Java API 參考
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
## 方法

| 方法 | 說明 |
| --- | --- |
| [getCount()](#getCount--) | 傳回序列中效果的數量。 |
| [remove(IEffect item)](#remove-com.aspose.slides.IEffect-) | 從集合中移除指定的效果。 |
| [removeAt(int index)](#removeAt-int-) | 從集合中移除效果。 |
| [clear()](#clear--) | 從集合中移除所有效果。 |
| [get_Item(int index)](#get-Item-int-) | 傳回指定索引處的效果。 |
| [getTriggerShape()](#getTriggerShape--) | 傳回或設定 INTERACTIVE 序列的形狀目標。 |
| [setTriggerShape(IShape value)](#setTriggerShape-com.aspose.slides.IShape-) | 傳回或設定 INTERACTIVE 序列的形狀目標。 |
| [removeByShape(IShape shape)](#removeByShape-com.aspose.slides.IShape-) | 移除指定形狀的效果。 |
| [getEffectsByShape(IShape shape)](#getEffectsByShape-com.aspose.slides.IShape-) | 傳回指定形狀的效果陣列。 |
| [getEffectsByParagraph(IParagraph paragraph)](#getEffectsByParagraph-com.aspose.slides.IParagraph-) | 傳回指定段落的效果陣列。 |
| [getCount(IShape shape)](#getCount-com.aspose.slides.IShape-) | 傳回指定形狀的效果數量。 |
| [addEffect(IShape shape, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IShape-int-int-int-) | 在序列末端加入新效果。 |
| [addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IParagraph-int-int-int-) | 在序列末端為段落加入新動畫效果。 |
| [addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IChart-int-int-int-int-int-) | 在序列末端為類別或系列加入新的圖表動畫效果。 |
| [addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IChart-int-int-int-int-int-int-) | 在序列末端為類別或系列中的元素加入新的圖表動畫效果。 |
### getCount() {#getCount--}
```
public abstract int getCount()
```


傳回序列中效果的數量。唯讀 int。

**傳回：**
int
### remove(IEffect item) {#remove-com.aspose.slides.IEffect-}
```
public abstract void remove(IEffect item)
```


從集合中移除指定的效果。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| item | [IEffect](../../com.aspose.slides/ieffect) | 要移除的效果。 |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


從集合中移除效果。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 要移除之效果的索引 int |

### clear() {#clear--}
```
public abstract void clear()
```


從集合中移除所有效果。

### get_Item(int index) {#get-Item-int-}
```
public abstract IEffect get_Item(int index)
```


傳回指定索引處的效果。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 元素的索引。 |

**傳回：**
[IEffect](../../com.aspose.slides/ieffect) - [IEffect](../../com.aspose.slides/ieffect) 物件。
### getTriggerShape() {#getTriggerShape--}
```
public abstract IShape getTriggerShape()
```


傳回或設定 INTERACTIVE 序列的形狀目標。如果序列不是互動的則傳回 null。讀寫 [IShape](../../com.aspose.slides/ishape)。

**傳回：**
[IShape](../../com.aspose.slides/ishape)
### setTriggerShape(IShape value) {#setTriggerShape-com.aspose.slides.IShape-}
```
public abstract void setTriggerShape(IShape value)
```


傳回或設定 INTERACTIVE 序列的形狀目標。如果序列不是互動的則傳回 null。讀寫 [IShape](../../com.aspose.slides/ishape)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |

### removeByShape(IShape shape) {#removeByShape-com.aspose.slides.IShape-}
```
public abstract void removeByShape(IShape shape)
```


移除指定形狀的效果。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | 形狀物件 [IShape](../../com.aspose.slides/ishape) |

### getEffectsByShape(IShape shape) {#getEffectsByShape-com.aspose.slides.IShape-}
```
public abstract IEffect[] getEffectsByShape(IShape shape)
```


傳回指定形狀的效果陣列。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | 形狀物件 [IShape](../../com.aspose.slides/ishape) |

**傳回：**
com.aspose.slides.IEffect[] - 效果陣列 [IEffect](../../com.aspose.slides/ieffect)
### getEffectsByParagraph(IParagraph paragraph) {#getEffectsByParagraph-com.aspose.slides.IParagraph-}
```
public abstract IEffect[] getEffectsByParagraph(IParagraph paragraph)
```


傳回指定段落的效果陣列。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| paragraph | [IParagraph](../../com.aspose.slides/iparagraph) | 段落物件 [IParagraph](../../com.aspose.slides/iparagraph) |

**傳回：**
com.aspose.slides.IEffect[] - 效果陣列 [IEffect](../../com.aspose.slides/ieffect)
### getCount(IShape shape) {#getCount-com.aspose.slides.IShape-}
```
public abstract int getCount(IShape shape)
```


傳回指定形狀的效果數量。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | 形狀物件 [IShape](../../com.aspose.slides/ishape) |

**傳回：**
int - 效果數量 int
### addEffect(IShape shape, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IShape-int-int-int-}
```
public abstract IEffect addEffect(IShape shape, int effectType, int subtype, int triggerType)
```


在序列末端加入新效果。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | 用於加入效果的形狀物件 [IShape](../../com.aspose.slides/ishape) |
| effectType | int | 動畫效果類型 [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | 動畫效果子類型 [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | 效果的觸發類型 [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**傳回：**
[IEffect](../../com.aspose.slides/ieffect) - 新的效果物件 [IEffect](../../com.aspose.slides/ieffect)
### addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IParagraph-int-int-int-}
```
public abstract IEffect addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType)
```


在序列末端為段落加入新動畫效果。

--------------------

> ```
> Presentation presentation = new Presentation(path + "input.pptx");
>  try
>  {
>     // select paragraph to add effect
>     IAutoShape autoShape = (IAutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>     IParagraph paragraph = autoShape.getTextFrame().getParagraphs().get_Item(0);
>     // add Fly animation effect to selected paragraph
>     IEffect effect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().addEffect(
>     paragraph, EffectType.Fly, EffectSubtype.Left, EffectTriggerType.OnClick);
>  } finally {
>     if (presentation != null) presentation.dispose();
>  }
> ```

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| paragraph | [IParagraph](../../com.aspose.slides/iparagraph) | 段落物件 [IParagraph](../../com.aspose.slides/iparagraph) |
| effectType | int | 動畫效果類型 [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | 動畫效果子類型 [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | 效果的觸發類型 [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**傳回：**
[IEffect](../../com.aspose.slides/ieffect) - 新的效果物件 [IEffect](../../com.aspose.slides/ieffect)
### addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IChart-int-int-int-int-int-}
```
public abstract IEffect addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType)
```


在序列末端為類別或系列加入新的圖表動畫效果。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| chart | [IChart](../../com.aspose.slides/ichart) | 圖表物件 [IChart](../../com.aspose.slides/ichart) |
| type | int | 動畫效果類型 [EffectChartMinorGroupingType](../../com.aspose.slides/effectchartminorgroupingtype) |
| index | int | 索引 int |
| effectType | int | 動畫效果類型 [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | 動畫效果子類型 [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | 效果的觸發類型 [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**傳回：**
[IEffect](../../com.aspose.slides/ieffect) - 新的效果物件 [IEffect](../../com.aspose.slides/ieffect)
### addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IChart-int-int-int-int-int-int-}
```
public abstract IEffect addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType)
```


在序列末端為類別或系列中的元素加入新的圖表動畫效果。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| chart | [IChart](../../com.aspose.slides/ichart) | 圖表物件 [IChart](../../com.aspose.slides/ichart) |
| type | int | 動畫效果類型 [EffectChartMinorGroupingType](../../com.aspose.slides/effectchartminorgroupingtype) |
| seriesIndex | int | 圖表系列的索引 int |
| categoriesIndex | int | 類別的索引 int |
| effectType | int | 動畫效果類型 [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | 動畫效果子類型 [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | 效果的觸發類型 [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**傳回：**
[IEffect](../../com.aspose.slides/ieffect) - 新的效果物件 [IEffect](../../com.aspose.slides/ieffect)