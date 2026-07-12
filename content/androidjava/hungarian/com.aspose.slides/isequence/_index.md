---
title: ISequence
second_title: Aspose.Slides Android számára a Java API hivatkozásán keresztül
description: A hatások sorozatgyűjteményét ábrázolja.
type: docs
url: /hu/com.aspose.slides/isequence/
---
**Minden megvalósított interfész:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface ISequence extends System.Collections.Generic.IGenericEnumerable<IEffect>
```

A sorozatot (a hatások gyűjteményét) ábrázolja.
## Metódusok

| Módszer | Leírás |
| --- | --- |
| [getCount()](#getCount--) | Visszaadja a sorozatban lévő hatások számát. |
| [remove(IEffect item)](#remove-com.aspose.slides.IEffect-) | Eltávolítja a megadott hatást egy gyűjteményből. |
| [removeAt(int index)](#removeAt-int-) | Eltávolít egy hatást egy gyűjteményből. |
| [clear()](#clear--) | Eltávolítja az összes hatást egy gyűjteményből. |
| [get_Item(int index)](#get-Item-int-) | Visszaad egy hatást a megadott indexnél. |
| [getTriggerShape()](#getTriggerShape--) | Visszaadja vagy beállítja az alakzat célját az INTERACTIVE sorozathoz. |
| [setTriggerShape(IShape value)](#setTriggerShape-com.aspose.slides.IShape-) | Visszaadja vagy beállítja az alakzat célját az INTERACTIVE sorozathoz. |
| [removeByShape(IShape shape)](#removeByShape-com.aspose.slides.IShape-) | Eltávolítja a hatást a megadott alakzatról. |
| [getEffectsByShape(IShape shape)](#getEffectsByShape-com.aspose.slides.IShape-) | Visszaad egy tömböt a megadott alakzatra vonatkozó hatásokkal. |
| [getEffectsByParagraph(IParagraph paragraph)](#getEffectsByParagraph-com.aspose.slides.IParagraph-) | Visszaad egy tömböt a megadott bekezdésre vonatkozó hatásokkal. |
| [getCount(IShape shape)](#getCount-com.aspose.slides.IShape-) | Visszaadja a hatások számát a megadott alakzatra. |
| [addEffect(IShape shape, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IShape-int-int-int-) | Új hatást ad a sorozat végéhez. |
| [addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IParagraph-int-int-int-) | Új animációs hatást ad a bekezdéshez a sorozat végén. |
| [addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IChart-int-int-int-int-int-) | Új diagram animációs hatást ad a kategóriához vagy sorozathoz a sorozat végén. |
| [addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IChart-int-int-int-int-int-int-) | Új diagram animációs hatást ad a kategória vagy sorozat elemeihez a sorozat végén. |
### getCount() {#getCount--}
```
public abstract int getCount()
```

Visszaadja a sorozatban lévő hatások számát. Csak olvasható int.

**Visszatér:**
int
### remove(IEffect item) {#remove-com.aspose.slides.IEffect-}
```
public abstract void remove(IEffect item)
```

Eltávolítja a megadott hatást egy gyűjteményből.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| item | [IEffect](../../com.aspose.slides/ieffect) | Eltávolítandó hatás. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Eltávolít egy hatást egy gyűjteményből.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Az eltávolítandó hatás indexe. |

### clear() {#clear--}
```
public abstract void clear()
```

Eltávolítja az összes hatást egy gyűjteményből.

### get_Item(int index) {#get-Item-int-}
```
public abstract IEffect get_Item(int index)
```

Visszaad egy hatást a megadott indexnél.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Elem indexe. |

**Visszatér:**
[IEffect](../../com.aspose.slides/ieffect) - A [IEffect](../../com.aspose.slides/ieffect) objektum.
### getTriggerShape() {#getTriggerShape--}
```
public abstract IShape getTriggerShape()
```

Visszaadja vagy beállítja az alakzat célját az INTERACTIVE sorozathoz. Ha a sorozat nem interaktív, akkor null értéket ad vissza. Olvasás/írás [IShape](../../com.aspose.slides/ishape).

**Visszatér:**
[IShape](../../com.aspose.slides/ishape)
### setTriggerShape(IShape value) {#setTriggerShape-com.aspose.slides.IShape-}
```
public abstract void setTriggerShape(IShape value)
```

Visszaadja vagy beállítja az alakzat célját az INTERACTIVE sorozathoz. Ha a sorozat nem interaktív, akkor null értéket ad vissza. Olvasás/írás [IShape](../../com.aspose.slides/ishape).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |

### removeByShape(IShape shape) {#removeByShape-com.aspose.slides.IShape-}
```
public abstract void removeByShape(IShape shape)
```

Eltávolítja a hatást a megadott alakzatról.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | Alakzat objektum [IShape](../../com.aspose.slides/ishape) |

### getEffectsByShape(IShape shape) {#getEffectsByShape-com.aspose.slides.IShape-}
```
public abstract IEffect[] getEffectsByShape(IShape shape)
```

Visszaad egy tömböt a megadott alakzatra vonatkozó hatásokkal.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | Alakzat objektum [IShape](../../com.aspose.slides/ishape) |

**Visszatér:**
com.aspose.slides.IEffect[] - Hatások tömbje [IEffect](../../com.aspose.slides/ieffect)
### getEffectsByParagraph(IParagraph paragraph) {#getEffectsByParagraph-com.aspose.slides.IParagraph-}
```
public abstract IEffect[] getEffectsByParagraph(IParagraph paragraph)
```

Visszaad egy tömböt a megadott bekezdésre vonatkozó hatásokkal.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| paragraph | [IParagraph](../../com.aspose.slides/iparagraph) | Bekezdés objektum [IParagraph](../../com.aspose.slides/iparagraph) |

**Visszatér:**
com.aspose.slides.IEffect[] - Hatások tömbje [IEffect](../../com.aspose.slides/ieffect)
### getCount(IShape shape) {#getCount-com.aspose.slides.IShape-}
```
public abstract int getCount(IShape shape)
```

Visszaadja a hatások számát a megadott alakzatra.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | Alakzat objektum [IShape](../../com.aspose.slides/ishape) |

**Visszatér:**
int - Hatások száma

### addEffect(IShape shape, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IShape-int-int-int-}
```
public abstract IEffect addEffect(IShape shape, int effectType, int subtype, int triggerType)
```

Új hatást ad a sorozat végéhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | Alakzat objektum [IShape](../../com.aspose.slides/ishape) egy hatás hozzáadásához |
| effectType | int | Animációs hatás típusa [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Animációs hatás altípusa [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Hatás aktiválásának típusa [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Visszatér:**
[IEffect](../../com.aspose.slides/ieffect) - Új hatás objektum [IEffect](../../com.aspose.slides/ieffect)
### addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IParagraph-int-int-int-}
```
public abstract IEffect addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType)
```

Új animációs hatást ad a bekezdéshez a sorozat végén.

---

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

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| paragraph | [IParagraph](../../com.aspose.slides/iparagraph) | Bekezdés objektum [IParagraph](../../com.aspose.slides/iparagraph) |
| effectType | int | Animációs hatás típusa [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Animációs hatás altípusa [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Hatás aktiválásának típusa [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Visszatér:**
[IEffect](../../com.aspose.slides/ieffect) - Új hatás objektum [IEffect](../../com.aspose.slides/ieffect)
### addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IChart-int-int-int-int-int-}
```
public abstract IEffect addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType)
```

Új diagram animációs hatást ad a kategóriához vagy sorozathoz a sorozat végén.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| chart | [IChart](../../com.aspose.slides/ichart) | Diagram objektum [IChart](../../com.aspose.slides/ichart) |
| type | int | Animációs hatás típusa [EffectChartMinorGroupingType](../../com.aspose.slides/effectchartminorgroupingtype) |
| index | int | Index |
| effectType | int | Animációs hatás típusa [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Animációs hatás altípusa [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Hatás aktiválásának típusa [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Visszatér:**
[IEffect](../../com.aspose.slides/ieffect) - Új hatás objektum [IEffect](../../com.aspose.slides/ieffect)
### addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IChart-int-int-int-int-int-int-}
```
public abstract IEffect addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType)
```

Új diagram animációs hatást ad a kategória vagy sorozat elemeihez a sorozat végén.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| chart | [IChart](../../com.aspose.slides/ichart) | Diagram objektum [IChart](../../com.aspose.slides/ichart) |
| type | int | Animációs hatás típusa [EffectChartMinorGroupingType](../../com.aspose.slides/effectchartminorgroupingtype) |
| seriesIndex | int | Diagram sorozat indexe |
| categoriesIndex | int | Kategória indexe |
| effectType | int | Animációs hatás típusa [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Animációs hatás altípusa [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Hatás aktiválásának típusa [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Visszatér:**
[IEffect](../../com.aspose.slides/ieffect) - Új hatás objektum [IEffect](../../com.aspose.slides/ieffect)