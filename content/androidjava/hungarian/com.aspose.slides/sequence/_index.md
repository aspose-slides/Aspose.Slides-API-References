---
title: Sequence
second_title: Aspose.Slides for Android Java API referencia
description: A hatások sorozatának gyűjteményét jelöli.
type: docs
url: /hu/com.aspose.slides/sequence/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.ISequence](../../com.aspose.slides/isequence)
```
public final class Sequence implements ISequence
```

Represents sequence (collection of effects).
## Metódusok

| Method | Description |
| --- | --- |
| [getCount()](#getCount--) | Visszaadja a hatások számát egy sorozatban. |
| [remove(IEffect item)](#remove-com.aspose.slides.IEffect-) | Eltávolítja a megadott hatást a gyűjteményből. |
| [removeAt(int index)](#removeAt-int-) | Eltávolít egy hatást a gyűjteményből. |
| [clear()](#clear--) | Eltávolítja az összes hatást a gyűjteményből. |
| [get_Item(int index)](#get-Item-int-) | Visszaad egy hatást a megadott indexnél. |
| [iterator()](#iterator--) | Visszaad egy enumerátort, amely bejárja a gyűjteményt. |
| [iteratorJava()](#iteratorJava--) | Visszaad egy java iterátort a teljes gyűjteményhez. |
| [getTriggerShape()](#getTriggerShape--) | Visszaadja vagy beállítja a shape célját az INTERACTIVE sorozathoz. |
| [setTriggerShape(IShape value)](#setTriggerShape-com.aspose.slides.IShape-) | Visszaadja vagy beállítja a shape célját az INTERACTIVE sorozathoz. |
| [removeByShape(IShape shape)](#removeByShape-com.aspose.slides.IShape-) | Eltávolítja a megadott shape hatását. |
| [getEffectsByShape(IShape shape)](#getEffectsByShape-com.aspose.slides.IShape-) | Visszaad egy tömböt a megadott shape hatásaival. |
| [getEffectsByParagraph(IParagraph paragraph)](#getEffectsByParagraph-com.aspose.slides.IParagraph-) | Visszaad egy tömböt a megadott bekezdés hatásaival. |
| [getCount(IShape shape)](#getCount-com.aspose.slides.IShape-) | Visszaadja a megadott shape hatásainak számát. |
| [addEffect(IShape shape, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IShape-int-int-int-) | Új hatást ad a sorozat végéhez. |
| [addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IParagraph-int-int-int-) | Új animációs hatást ad a bekezdéshez a sorozat végéhez. |
| [addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IChart-int-int-int-int-int-) | Új diagram animációs hatást ad a kategóriához vagy sorozathoz a sorozat végéhez. |
| [addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IChart-int-int-int-int-int-int-) | Új diagram animációs hatást ad a kategória vagy sorozat elemeihez a sorozat végéhez. |
### getCount() {#getCount--}
```
public final int getCount()
```

Visszaadja a hatások számát egy sorozatban. Csak olvasható int.

**Returns:**
int
### remove(IEffect item) {#remove-com.aspose.slides.IEffect-}
```
public final void remove(IEffect item)
```

Eltávolítja a megadott hatást a gyűjteményből.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [IEffect](../../com.aspose.slides/ieffect) | Eltávolítandó hatás. |
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Eltávolít egy hatást a gyűjteményből.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Az eltávolítandó hatás indexe. |
### clear() {#clear--}
```
public final void clear()
```

Eltávolítja az összes hatást a gyűjteményből.
### get_Item(int index) {#get-Item-int-}
```
public final IEffect get_Item(int index)
```

Visszaad egy hatást a megadott indexnél.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Az elem indexe. |

**Returns:**
[IEffect](../../com.aspose.slides/ieffect) - A [IEffect](../../com.aspose.slides/ieffect) objektum.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IEffect> iterator()
```

Visszaad egy enumerátort, amely bejárja a gyűjteményt.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IEffect> - Egy IGenericEnumerator, amelyet a gyűjtemény bejárására lehet használni.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IEffect> iteratorJava()
```

Visszaad egy java iterátort a teljes gyűjteményhez.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IEffect> - Egy java.util.Iterator a teljes gyűjteményhez.
### getTriggerShape() {#getTriggerShape--}
```
public final IShape getTriggerShape()
```

Visszaadja vagy beállítja a shape célját az INTERACTIVE sorozathoz. Ha a sorozat nem interaktív, akkor null értéket ad vissza. Olvasás/írás [IShape](../../com.aspose.slides/ishape).

**Returns:**
[IShape](../../com.aspose.slides/ishape)
### setTriggerShape(IShape value) {#setTriggerShape-com.aspose.slides.IShape-}
```
public final void setTriggerShape(IShape value)
```

Visszaadja vagy beállítja a shape célját az INTERACTIVE sorozathoz. Ha a sorozat nem interaktív, akkor null értéket ad vissza. Olvasás/írás [IShape](../../com.aspose.slides/ishape).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |
### removeByShape(IShape shape) {#removeByShape-com.aspose.slides.IShape-}
```
public final void removeByShape(IShape shape)
```

Eltávolítja a megadott shape hatását.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) |  |
### getEffectsByShape(IShape shape) {#getEffectsByShape-com.aspose.slides.IShape-}
```
public final IEffect[] getEffectsByShape(IShape shape)
```

Visszaad egy tömböt a megadott shape hatásaival.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) |  |

**Returns:**
com.aspose.slides.IEffect[]
### getEffectsByParagraph(IParagraph paragraph) {#getEffectsByParagraph-com.aspose.slides.IParagraph-}
```
public final IEffect[] getEffectsByParagraph(IParagraph paragraph)
```

Visszaad egy tömböt a megadott bekezdés hatásaival.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| paragraph | [IParagraph](../../com.aspose.slides/iparagraph) |  |

**Returns:**
com.aspose.slides.IEffect[]
### getCount(IShape shape) {#getCount-com.aspose.slides.IShape-}
```
public final int getCount(IShape shape)
```

Visszaadja a megadott shape hatásainak számát.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) |  |

**Returns:**
int
### addEffect(IShape shape, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IShape-int-int-int-}
```
public final IEffect addEffect(IShape shape, int effectType, int subtype, int triggerType)
```

Új hatást ad a sorozat végéhez.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | Shape objektum [IShape](../../com.aspose.slides/ishape) a hatás hozzáadásához |
| effectType | int | Az animációs hatás típusa [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Az animációs hatás altípusai [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | A hatás aktiválási típusa [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Returns:**
[IEffect](../../com.aspose.slides/ieffect) - Új hatás objektum [IEffect](../../com.aspose.slides/ieffect)
### addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IParagraph-int-int-int-}
```
public final IEffect addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType)
```

Új animációs hatást ad a bekezdéshez a sorozat végéhez.

--------------------

> ```
> Presentation presentation = new Presentation(path + "input.pptx");
>   try
>   {        
>      // kiválasztott bekezdés a hatás hozzáadásához
>      IAutoShape autoShape = (IAutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>      IParagraph paragraph = autoShape.getTextFrame().getParagraphs().get_Item(0);
>      // Fly animációs hatás hozzáadása a kiválasztott bekezdéshez
>      IEffect effect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().addEffect(
>      paragraph, EffectType.Fly, EffectSubtype.Left, EffectTriggerType.OnClick);
>   }  finally {
>      if (presentation != null) presentation.dispose();
>   }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| paragraph | [IParagraph](../../com.aspose.slides/iparagraph) | Paragraph objektum [IParagraph](../../com.aspose.slides/iparagraph) |
| effectType | int | Az animációs hatás típusa [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Az animációs hatás altípusai [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | A hatás aktiválási típusa [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Returns:**
[IEffect](../../com.aspose.slides/ieffect) - Új hatás objektum [IEffect](../../com.aspose.slides/ieffect)
### addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IChart-int-int-int-int-int-}
```
public final IEffect addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType)
```

Új diagram animációs hatást ad a kategóriához vagy sorozathoz a sorozat végéhez.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| chart | [IChart](../../com.aspose.slides/ichart) | Diagram objektum [IChart](../../com.aspose.slides/ichart) |
| type | int | Az animációs hatás típusa [EffectChartMinorGroupingType](../../com.aspose.slides/effectchartminorgroupingtype) |
| index | int | Index int |
| effectType | int | Az animációs hatás típusa [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Az animációs hatás altípusai [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | A hatás aktiválási típusa [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Returns:**
[IEffect](../../com.aspose.slides/ieffect) - Új hatás objektum [IEffect](../../com.aspose.slides/ieffect)
### addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IChart-int-int-int-int-int-int-}
```
public final IEffect addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType)
```

Új diagram animációs hatást ad a kategória vagy sorozat elemeihez a sorozat végéhez.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| chart | [IChart](../../com.aspose.slides/ichart) | Diagram objektum [IChart](../../com.aspose.slides/ichart) |
| type | int | Az animációs hatás típusa [EffectChartMinorGroupingType](../../com.aspose.slides/effectchartminorgroupingtype) |
| seriesIndex | int | A diagram sorozat indexe int |
| categoriesIndex | int | A kategória indexe int |
| effectType | int | Az animációs hatás típusa [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Az animációs hatás altípusai [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | A hatás aktiválási típusa [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Returns:**
[IEffect](../../com.aspose.slides/ieffect) - Új hatás objektum [IEffect](../../com.aspose.slides/ieffect)