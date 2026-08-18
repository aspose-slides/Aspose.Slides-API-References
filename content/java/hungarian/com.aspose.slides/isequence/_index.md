---
title: ISequence
second_title: Aspose.Slides for Java API Referenciája
description: Sorozatot (hatások gyűjteményét) képviseli.
type: docs
url: /hu/com.aspose.slides/isequence/
---
**Minden megvalósított interfész:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface ISequence extends System.Collections.Generic.IGenericEnumerable<IEffect>
```

Egy sorozatot (hatások gyűjteménye) képvisel.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getCount()](#getCount--) | Visszaadja a hatások számát a sorozatban. |
| [remove(IEffect item)](#remove-com.aspose.slides.IEffect-) | Eltávolítja a megadott hatást a gyűjteményből. |
| [removeAt(int index)](#removeAt-int-) | Eltávolít egy hatást a gyűjteményből. |
| [clear()](#clear--) | Eltávolítja az összes hatást a gyűjteményből. |
| [get_Item(int index)](#get-Item-int-) | Visszaad egy hatást a megadott indexen. |
| [getTriggerShape()](#getTriggerShape--) | Visszaadja vagy beállítja a forma célpontját az INTERACTIVE sorozathoz. |
| [setTriggerShape(IShape value)](#setTriggerShape-com.aspose.slides.IShape-) | Visszaadja vagy beállítja a forma célpontját az INTERACTIVE sorozathoz. |
| [removeByShape(IShape shape)](#removeByShape-com.aspose.slides.IShape-) | Eltávolítja a hatást a megadott forma számára. |
| [getEffectsByShape(IShape shape)](#getEffectsByShape-com.aspose.slides.IShape-) | Visszaad egy tömböt a megadott forma hatásaival. |
| [getEffectsByParagraph(IParagraph paragraph)](#getEffectsByParagraph-com.aspose.slides.IParagraph-) | Visszaad egy tömböt a megadott bekezdés hatásaival. |
| [getCount(IShape shape)](#getCount-com.aspose.slides.IShape-) | Visszaadja a hatások számát a megadott forma esetén. |
| [addEffect(IShape shape, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IShape-int-int-int-) | Új hatást ad a sorozat végéhez. |
| [addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IParagraph-int-int-int-) | Új animációs hatást ad a bekezdéshez a sorozat végén. |
| [addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IChart-int-int-int-int-int-) | Új diagram animációs hatást ad kategóriához vagy sorozathoz a sorozat végén. |
| [addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IChart-int-int-int-int-int-int-) | Új diagram animációs hatást ad a kategória vagy sorozat elemeihez a sorozat végén. |
### getCount() {#getCount--}
```
public abstract int getCount()
```

Visszaadja a hatások számát a sorozatban. Csak olvasható int.

**Returns:**
int
### remove(IEffect item) {#remove-com.aspose.slides.IEffect-}
```
public abstract void remove(IEffect item)
```

Eltávolítja a megadott hatást a gyűjteményből.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [IEffect](../../com.aspose.slides/ieffect) | Eltávolítandó hatás. |
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Eltávolít egy hatást a gyűjteményből.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Eltávolítandó hatás indexe int |
### clear() {#clear--}
```
public abstract void clear()
```

Eltávolítja az összes hatást a gyűjteményből.

### get_Item(int index) {#get-Item-int-}
```
public abstract IEffect get_Item(int index)
```

Visszaad egy hatást a megadott indexen.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Az elem indexe. |

**Returns:**
[IEffect](../../com.aspose.slides/ieffect) - A [IEffect](../../com.aspose.slides/ieffect) objektum.
### getTriggerShape() {#getTriggerShape--}
```
public abstract IShape getTriggerShape()
```

Visszaadja vagy beállítja a forma célpontját az INTERACTIVE sorozathoz. Ha a sorozat nem interaktív, akkor null értéket ad vissza. Olvasás/írás [IShape](../../com.aspose.slides/ishape).

**Returns:**
[IShape](../../com.aspose.slides/ishape)
### setTriggerShape(IShape value) {#setTriggerShape-com.aspose.slides.IShape-}
```
public abstract void setTriggerShape(IShape value)
```

Visszaadja vagy beállítja a forma célpontját az INTERACTIVE sorozathoz. Ha a sorozat nem interaktív, akkor null értéket ad vissza. Olvasás/írás [IShape](../../com.aspose.slides/ishape).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |
### removeByShape(IShape shape) {#removeByShape-com.aspose.slides.IShape-}
```
public abstract void removeByShape(IShape shape)
```

Eltávolítja a hatást a megadott forma számára.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | Forma objektum [IShape](../../com.aspose.slides/ishape) |
### getEffectsByShape(IShape shape) {#getEffectsByShape-com.aspose.slides.IShape-}
```
public abstract IEffect[] getEffectsByShape(IShape shape)
```

Visszaad egy tömböt a megadott forma hatásaival.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | Forma objektum [IShape](../../com.aspose.slides/ishape) |

**Returns:**
com.aspose.slides.IEffect[] - Hatások tömbje [IEffect](../../com.aspose.slides/ieffect)
### getEffectsByParagraph(IParagraph paragraph) {#getEffectsByParagraph-com.aspose.slides.IParagraph-}
```
public abstract IEffect[] getEffectsByParagraph(IParagraph paragraph)
```

Visszaad egy tömböt a megadott bekezdés hatásaival.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| paragraph | [IParagraph](../../com.aspose.slides/iparagraph) | Bekezdés objektum [IParagraph](../../com.aspose.slides/iparagraph) |

**Returns:**
com.aspose.slides.IEffect[] - Hatások tömbje [IEffect](../../com.aspose.slides/ieffect)
### getCount(IShape shape) {#getCount-com.aspose.slides.IShape-}
```
public abstract int getCount(IShape shape)
```

Visszaadja a hatások számát a megadott forma esetén.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | Forma objektum [IShape](../../com.aspose.slides/ishape) |

**Returns:**
int - Hatások száma int
### addEffect(IShape shape, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IShape-int-int-int-}
```
public abstract IEffect addEffect(IShape shape, int effectType, int subtype, int triggerType)
```

Új hatást ad a sorozat végéhez.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | Forma objektum [IShape](../../com.aspose.slides/ishape) a hatás hozzáadása érdekében |
| effectType | int | Animációs hatás típusa [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Animációs hatás altípusa [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | A hatás aktiválási típusa [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Returns:**
[IEffect](../../com.aspose.slides/ieffect) - Új hatás objektum [IEffect](../../com.aspose.slides/ieffect)
### addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IParagraph-int-int-int-}
```
public abstract IEffect addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType)
```

Új animációs hatást ad a bekezdéshez a sorozat végén.

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

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| paragraph | [IParagraph](../../com.aspose.slides/iparagraph) | Bekezdés objektum [IParagraph](../../com.aspose.slides/iparagraph) |
| effectType | int | Animációs hatás típusa [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Animációs hatás altípusa [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | A hatás aktiválási típusa [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Returns:**
[IEffect](../../com.aspose.slides/ieffect) - Új hatás objektum [IEffect](../../com.aspose.slides/ieffect)
### addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IChart-int-int-int-int-int-}
```
public abstract IEffect addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType)
```

Új diagram animációs hatást ad kategóriához vagy sorozathoz a sorozat végén.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| chart | [IChart](../../com.aspose.slides/ichart) | Diagram objektum [IChart](../../com.aspose.slides/ichart) |
| type | int | Animációs hatás típusa [EffectChartMinorGroupingType](../../com.aspose.slides/effectchartminorgroupingtype) |
| index | int | Index int |
| effectType | int | Animációs hatás típusa [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Animációs hatás altípusa [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | A hatás aktiválási típusa [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Returns:**
[IEffect](../../com.aspose.slides/ieffect) - Új hatás objektum [IEffect](../../com.aspose.slides/ieffect)
### addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IChart-int-int-int-int-int-int-}
```
public abstract IEffect addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType)
```

Új diagram animációs hatást ad a kategória vagy sorozat elemeihez a sorozat végén.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| chart | [IChart](../../com.aspose.slides/ichart) | Diagram objektum [IChart](../../com.aspose.slides/ichart) |
| type | int | Animációs hatás típusa [EffectChartMinorGroupingType](../../com.aspose.slides/effectchartminorgroupingtype) |
| seriesIndex | int | Diagram sorozat indexe int |
| categoriesIndex | int | Kategória indexe int |
| effectType | int | Animációs hatás típusa [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Animációs hatás altípusa [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | A hatás aktiválási típusa [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Returns:**
[IEffect](../../com.aspose.slides/ieffect) - Új hatás objektum [IEffect](../../com.aspose.slides/ieffect)