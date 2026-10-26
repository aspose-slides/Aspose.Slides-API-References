---
title: ISequence
second_title: Aspose.Slides pro Java API Reference
description: Reprezentuje sekvenční kolekci efektů.
type: docs
url: /cs/com.aspose.slides/isequence/
---
**Všechna implementovaná rozhraní:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface ISequence extends System.Collections.Generic.IGenericEnumerable<IEffect>
```

Reprezentuje sekvenci (kolekci efektů).
## Metody

| Metoda | Popis |
| --- | --- |
| [getCount()](#getCount--) | Vrací počet efektů v sekvenci. |
| [remove(IEffect item)](#remove-com.aspose.slides.IEffect-) | Odebere určený efekt z kolekce. |
| [removeAt(int index)](#removeAt-int-) | Odebere efekt z kolekce. |
| [clear()](#clear--) | Odebere všechny efekty z kolekce. |
| [get_Item(int index)](#get-Item-int-) | Vrací efekt na určeném indexu. |
| [getTriggerShape()](#getTriggerShape--) | Vrací nebo nastavuje cílový tvar pro INTERACTIVE sekvenci. |
| [setTriggerShape(IShape value)](#setTriggerShape-com.aspose.slides.IShape-) | Vrací nebo nastavuje cílový tvar pro INTERACTIVE sekvenci. |
| [removeByShape(IShape shape)](#removeByShape-com.aspose.slides.IShape-) | Odstraní efekt pro určený tvar. |
| [getEffectsByShape(IShape shape)](#getEffectsByShape-com.aspose.slides.IShape-) | Vrací pole efektů pro určený tvar. |
| [getEffectsByParagraph(IParagraph paragraph)](#getEffectsByParagraph-com.aspose.slides.IParagraph-) | Vrací pole efektů pro určený odstavec. |
| [getCount(IShape shape)](#getCount-com.aspose.slides.IShape-) | Vrací počet efektů pro určený tvar. |
| [addEffect(IShape shape, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IShape-int-int-int-) | Přidá nový efekt na konec sekvence. |
| [addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IParagraph-int-int-int-) | Přidá nový animační efekt pro odstavec na konec sekvence. |
| [addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IChart-int-int-int-int-int-) | Přidá nový animační efekt grafu pro kategorii nebo řadu na konec sekvence. |
| [addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IChart-int-int-int-int-int-int-) | Přidá nový animační efekt grafu pro prvky v kategorii nebo řadě na konec sekvence. |
### getCount() {#getCount--}
```
public abstract int getCount()
```


Vrací počet efektů v sekvenci. Pouze ke čtení int.

**Návrat:**
int
### remove(IEffect item) {#remove-com.aspose.slides.IEffect-}
```
public abstract void remove(IEffect item)
```


Odebere určený efekt z kolekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| item | [IEffect](../../com.aspose.slides/ieffect) | Efekt k odstranění. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Odebere efekt z kolekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index efektu k odstranění int |

### clear() {#clear--}
```
public abstract void clear()
```


Odebere všechny efekty z kolekce.

### get_Item(int index) {#get-Item-int-}
```
public abstract IEffect get_Item(int index)
```


Vrací efekt na určeném indexu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index elementu. |

**Návrat:**
[IEffect](../../com.aspose.slides/ieffect) - Objekt [IEffect](../../com.aspose.slides/ieffect).
### getTriggerShape() {#getTriggerShape--}
```
public abstract IShape getTriggerShape()
```


Vrací nebo nastavuje cílový tvar pro INTERACTIVE sekvenci. Pokud sekvence není interaktivní, vrací null. Čtení/zápis [IShape](../../com.aspose.slides/ishape).

**Návrat:**
[IShape](../../com.aspose.slides/ishape)
### setTriggerShape(IShape value) {#setTriggerShape-com.aspose.slides.IShape-}
```
public abstract void setTriggerShape(IShape value)
```


Vrací nebo nastavuje cílový tvar pro INTERACTIVE sekvenci. Pokud sekvence není interaktivní, vrací null. Čtení/zápis [IShape](../../com.aspose.slides/ishape).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |

### removeByShape(IShape shape) {#removeByShape-com.aspose.slides.IShape-}
```
public abstract void removeByShape(IShape shape)
```


Odstraní efekt pro určený tvar.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | Objekt tvaru [IShape](../../com.aspose.slides/ishape) |

### getEffectsByShape(IShape shape) {#getEffectsByShape-com.aspose.slides.IShape-}
```
public abstract IEffect[] getEffectsByShape(IShape shape)
```


Vrací pole efektů pro určený tvar.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | Objekt tvaru [IShape](../../com.aspose.slides/ishape) |

**Návrat:**
com.aspose.slides.IEffect[] - Pole efektů [IEffect](../../com.aspose.slides/ieffect)
### getEffectsByParagraph(IParagraph paragraph) {#getEffectsByParagraph-com.aspose.slides.IParagraph-}
```
public abstract IEffect[] getEffectsByParagraph(IParagraph paragraph)
```


Vrací pole efektů pro určený odstavec.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| paragraph | [IParagraph](../../com.aspose.slides/iparagraph) | Objekt odstavce [IParagraph](../../com.aspose.slides/iparagraph) |

**Návrat:**
com.aspose.slides.IEffect[] - Pole efektů [IEffect](../../com.aspose.slides/ieffect)
### getCount(IShape shape) {#getCount-com.aspose.slides.IShape-}
```
public abstract int getCount(IShape shape)
```


Vrací počet efektů pro určený tvar.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | Objekt tvaru [IShape](../../com.aspose.slides/ishape) |

**Návrat:**
int - Počet efektů int
### addEffect(IShape shape, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IShape-int-int-int-}
```
public abstract IEffect addEffect(IShape shape, int effectType, int subtype, int triggerType)
```


Přidá nový efekt na konec sekvence.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | Objekt tvaru [IShape](../../com.aspose.slides/ishape) pro přidání efektu |
| effectType | int | Typ animačního efektu [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Podtypy animačního efektu [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Typ spouštěče efektu [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Návrat:**
[IEffect](../../com.aspose.slides/ieffect) - Nový objekt efektu [IEffect](../../com.aspose.slides/ieffect)
### addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IParagraph-int-int-int-}
```
public abstract IEffect addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType)
```


Přidá nový animační efekt pro odstavec na konec sekvence.

> ```
> Presentation presentation = new Presentation(path + "input.pptx");
>  try
>  {
>     // vyberte odstavec pro přidání efektu
>     IAutoShape autoShape = (IAutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>     IParagraph paragraph = autoShape.getTextFrame().getParagraphs().get_Item(0);
>     // přidejte efekt Fly animace k vybranému odstavci
>     IEffect effect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().addEffect(
>     paragraph, EffectType.Fly, EffectSubtype.Left, EffectTriggerType.OnClick);
>  } finally {
>     if (presentation != null) presentation.dispose();
>  }
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| paragraph | [IParagraph](../../com.aspose.slides/iparagraph) | Objekt odstavce [IParagraph](../../com.aspose.slides/iparagraph) |
| effectType | int | Typ animačního efektu [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Podtypy animačního efektu [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Typ spouštěče efektu [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Návrat:**
[IEffect](../../com.aspose.slides/ieffect) - Nový objekt efektu [IEffect](../../com.aspose.slides/ieffect)
### addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IChart-int-int-int-int-int-}
```
public abstract IEffect addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType)
```


Přidá nový animační efekt grafu pro kategorii nebo řadu na konec sekvence.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| chart | [IChart](../../com.aspose.slides/ichart) | Objekt grafu [IChart](../../com.aspose.slides/ichart) |
| type | int | Typ animačního efektu [EffectChartMinorGroupingType](../../com.aspose.slides/effectchartminorgroupingtype) |
| index | int | Index int |
| effectType | int | Typ animačního efektu [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Podtypy animačního efektu [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Typ spouštěče efektu [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Návrat:**
[IEffect](../../com.aspose.slides/ieffect) - Nový objekt efektu [IEffect](../../com.aspose.slides/ieffect)
### addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IChart-int-int-int-int-int-int-}
```
public abstract IEffect addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType)
```


Přidá nový animační efekt grafu pro prvky v kategorii nebo řadě na konec sekvence.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| chart | [IChart](../../com.aspose.slides/ichart) | Objekt grafu [IChart](../../com.aspose.slides/ichart) |
| type | int | Typ animačního efektu [EffectChartMinorGroupingType](../../com.aspose.slides/effectchartminorgroupingtype) |
| seriesIndex | int | Index řady grafu int |
| categoriesIndex | int | Index kategorie int |
| effectType | int | Typ animačního efektu [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Podtypy animačního efektu [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Typ spouštěče efektu [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Návrat:**
[IEffect](../../com.aspose.slides/ieffect) - Nový objekt efektu [IEffect](../../com.aspose.slides/ieffect)