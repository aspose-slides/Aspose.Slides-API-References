---
title: Sequence
second_title: Aspose.Slides for Java API Referencia
description: Az effektusok szekvenciagyűjteményét reprezentálja.
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

## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getCount()](#getCount--) | Visszaadja az effektek számát a szekvenciában. |
| [remove(IEffect item)](#remove-com.aspose.slides.IEffect-) | Eltávolítja a megadott effektust a gyűjteményből. |
| [removeAt(int index)](#removeAt-int-) | Eltávolít egy effektust a gyűjteményből. |
| [clear()](#clear--) | Eltávolítja az összes effektust a gyűjteményből. |
| [get_Item(int index)](#get-Item-int-) | Visszaad egy effektust a megadott indexen. |
| [iterator()](#iterator--) | Visszaad egy enumerátort, amely végig iterál a gyűjteményen. |
| [iteratorJava()](#iteratorJava--) | Visszaad egy java iterátort a teljes gyűjteményhez. |
| [getTriggerShape()](#getTriggerShape--) | Visszaadja vagy beállítja a forma célpontot az INTERACTIVE szekvenciához. |
| [setTriggerShape(IShape value)](#setTriggerShape-com.aspose.slides.IShape-) | Visszaadja vagy beállítja a forma célpontot az INTERACTIVE szekvenciához. |
| [removeByShape(IShape shape)](#removeByShape-com.aspose.slides.IShape-) | Eltávolítja a hatást a megadott formára. |
| [getEffectsByShape(IShape shape)](#getEffectsByShape-com.aspose.slides.IShape-) | Visszaad egy tömböt a megadott forma effektusairól. |
| [getEffectsByParagraph(IParagraph paragraph)](#getEffectsByParagraph-com.aspose.slides.IParagraph-) | Visszaad egy tömböt a megadott bekezdés effektusairól. |
| [getCount(IShape shape)](#getCount-com.aspose.slides.IShape-) | Visszaadja az effektusok számát a megadott formára. |
| [addEffect(IShape shape, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IShape-int-int-int-) | Új effektust ad a szekvencia végéhez. |
| [addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IParagraph-int-int-int-) | Új animációs effektust ad a bekezdéshez a szekvencia végéhez. |
| [addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IChart-int-int-int-int-int-) | Új diagram animációs effektust ad a kategória vagy sorozat számára a szekvencia végéhez. |
| [addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IChart-int-int-int-int-int-int-) | Új diagram animációs effektust ad a kategória vagy sorozat elemeihez a szekvencia végéhez. |
### getCount() {#getCount--}
```
public final int getCount()
```

Visszaadja az effektek számát a sorozatban. Csak olvasható int.

**Visszatér:**
int
### remove(IEffect item) {#remove-com.aspose.slides.IEffect-}
```
public final void remove(IEffect item)
```

Eltávolítja a megadott effektust a gyűjteményből.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| item | [IEffect](../../com.aspose.slides/ieffect) | Eltávolítandó effektus. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Eltávolít egy effektust a gyűjteményből.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A törlendő effektus indexe. |

### clear() {#clear--}
```
public final void clear()
```

Eltávolítja az összes effektust a gyűjteményből.

### get_Item(int index) {#get-Item-int-}
```
public final IEffect get_Item(int index)
```

Visszaad egy effektust a megadott indexen.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Az elem indexe. |

**Visszatér:**
[IEffect](../../com.aspose.slides/ieffect) - A [IEffect](../../com.aspose.slides/ieffect) objektum.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IEffect> iterator()
```

Visszaad egy enumerátort, amely végig iterál a gyűjteményen.

**Visszatér:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IEffect> - A IGenericEnumerator, amelyet a gyűjtemény bejárására használhat.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IEffect> iteratorJava()
```

Visszaad egy java iterátort a teljes gyűjteményhez.

**Visszatér:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IEffect> - Egy java.util.Iterator a teljes gyűjteményhez.
### getTriggerShape() {#getTriggerShape--}
```
public final IShape getTriggerShape()
```

Visszaadja vagy beállítja a forma célpontot az INTERACTIVE szekvenciához. Ha a szekvencia nem interaktív, akkor null-t ad vissza. Olvasás/írás [IShape](../../com.aspose.slides/ishape).

**Visszatér:**
[IShape](../../com.aspose.slides/ishape)
### setTriggerShape(IShape value) {#setTriggerShape-com.aspose.slides.IShape-}
```
public final void setTriggerShape(IShape value)
```

Visszaadja vagy beállítja a forma célpontot az INTERACTIVE szekvenciához. Ha a szekvencia nem interaktív, akkor null-t ad vissza. Olvasás/írás [IShape](../../com.aspose.slides/ishape).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |

### removeByShape(IShape shape) {#removeByShape-com.aspose.slides.IShape-}
```
public final void removeByShape(IShape shape)
```

Eltávolítja a hatást a megadott formára.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) |  |

### getEffectsByShape(IShape shape) {#getEffectsByShape-com.aspose.slides.IShape-}
```
public final IEffect[] getEffectsByShape(IShape shape)
```

Visszaad egy tömböt a megadott forma effektusairól.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) |  |

**Visszatér:**
com.aspose.slides.IEffect[]
### getEffectsByParagraph(IParagraph paragraph) {#getEffectsByParagraph-com.aspose.slides.IParagraph-}
```
public final IEffect[] getEffectsByParagraph(IParagraph paragraph)
```

Visszaad egy tömböt a megadott bekezdés effektusairól.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| paragraph | [IParagraph](../../com.aspose.slides/iparagraph) |  |

**Visszatér:**
com.aspose.slides.IEffect[]
### getCount(IShape shape) {#getCount-com.aspose.slides.IShape-}
```
public final int getCount(IShape shape)
```

Visszaadja az effektusok számát a megadott formára.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) |  |

**Visszatér:**
int
### addEffect(IShape shape, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IShape-int-int-int-}
```
public final IEffect addEffect(IShape shape, int effectType, int subtype, int triggerType)
```

Új effektust ad a szekvencia végéhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | Forma objektum [IShape](../../com.aspose.slides/ishape) effektus hozzáadásához |
| effectType | int | Animációs effektus típusa [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Animációs effektus altípusai [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Effektus aktiválási típusa [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Visszatér:**
[IEffect](../../com.aspose.slides/ieffect) - Új effektus objektum [IEffect](../../com.aspose.slides/ieffect)
### addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IParagraph-int-int-int-}
```
public final IEffect addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType)
```

Új animációs effektust ad a bekezdéshez a szekvencia végéhez.

--------------------

> ```
> Presentation presentation = new Presentation(path + "input.pptx");
>   try
>   {        
>      // válassza ki a bekezdést a hatás hozzáadásához
>      IAutoShape autoShape = (IAutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>      IParagraph paragraph = autoShape.getTextFrame().getParagraphs().get_Item(0);
>      // adj Fly animációs hatást a kiválasztott bekezdéshez
>      IEffect effect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().addEffect(
>      paragraph, EffectType.Fly, EffectSubtype.Left, EffectTriggerType.OnClick);
>   }  finally {
>      if (presentation != null) presentation.dispose();
>   }
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| paragraph | [IParagraph](../../com.aspose.slides/iparagraph) | Bekezdés objektum [IParagraph](../../com.aspose.slides/iparagraph) |
| effectType | int | Animációs effektus típusa [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Animációs effektus altípusai [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Effektus aktiválási típusa [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Visszatér:**
[IEffect](../../com.aspose.slides/ieffect) - Új effektus objektum [IEffect](../../com.aspose.slides/ieffect)
### addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IChart-int-int-int-int-int-}
```
public final IEffect addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType)
```

Új diagram animációs effektust ad a kategória vagy sorozat számára a szekvencia végéhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| chart | [IChart](../../com.aspose.slides/ichart) | Diagram objektum [IChart](../../com.aspose.slides/ichart) |
| type | int | Animációs effektus típusa [EffectChartMinorGroupingType](../../com.aspose.slides/effectchartminorgroupingtype) |
| index | int | Index int |
| effectType | int | Animációs effektus típusa [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Animációs effektus altípusai [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Effektus aktiválási típusa [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Visszatér:**
[IEffect](../../com.aspose.slides/ieffect) - Új effektus objektum [IEffect](../../com.aspose.slides/ieffect)
### addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IChart-int-int-int-int-int-int-}
```
public final IEffect addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType)
```

Új diagram animációs effektust ad a kategória vagy sorozat elemeihez a szekvencia végéhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| chart | [IChart](../../com.aspose.slides/ichart) | Diagram objektum [IChart](../../com.aspose.slides/ichart) |
| type | int | Animációs effektus típusa [EffectChartMinorGroupingType](../../com.aspose.slides/effectchartminorgroupingtype) |
| seriesIndex | int | Diagram sorozat indexe int |
| categoriesIndex | int | Kategória indexe int |
| effectType | int | Animációs effektus típusa [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Animációs effektus altípusai [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Effektus aktiválási típusa [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Visszatér:**
[IEffect](../../com.aspose.slides/ieffect) - Új effektus objektum [IEffect](../../com.aspose.slides/ieffect)