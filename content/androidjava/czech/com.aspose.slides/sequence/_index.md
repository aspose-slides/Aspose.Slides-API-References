---
title: Sequence
second_title: Aspose.Slides pro Android přes Java API
description: Representuje kolekci efektů sekvence.
type: docs
url: /cs/com.aspose.slides/sequence/
---
**Dědičnost:**
java.lang.Object

**Všechny implementované rozhraní:**
[com.aspose.slides.ISequence](../../com.aspose.slides/isequence)
```
public final class Sequence implements ISequence
```

Representuje sekvenci (kolekci efektů).
## Metody

| Metoda | Popis |
| --- | --- |
| [getCount()](#getCount--) | Vrací počet efektů v sekvenci. |
| [remove(IEffect item)](#remove-com.aspose.slides.IEffect-) | Odstraňuje zadaný efekt z kolekce. |
| [removeAt(int index)](#removeAt-int-) | Odstraňuje efekt z kolekce. |
| [clear()](#clear--) | Odstraňuje všechny efekty z kolekce. |
| [get_Item(int index)](#get-Item-int-) | Vrací efekt na zadaném indexu. |
| [iterator()](#iterator--) | Vrací enumerátor, který prochází kolekcí. |
| [iteratorJava()](#iteratorJava--) | Vrací java iterátor pro celou kolekci. |
| [getTriggerShape()](#getTriggerShape--) | Vrací nebo nastavuje cílový tvar pro INTERACTIVE sekvenci. |
| [setTriggerShape(IShape value)](#setTriggerShape-com.aspose.slides.IShape-) | Vrací nebo nastavuje cílový tvar pro INTERACTIVE sekvenci. |
| [removeByShape(IShape shape)](#removeByShape-com.aspose.slides.IShape-) | Odstraňuje efekt pro zadaný tvar. |
| [getEffectsByShape(IShape shape)](#getEffectsByShape-com.aspose.slides.IShape-) | Vrací pole efektů pro zadaný tvar. |
| [getEffectsByParagraph(IParagraph paragraph)](#getEffectsByParagraph-com.aspose.slides.IParagraph-) | Vrací pole efektů pro zadaný odstavec. |
| [getCount(IShape shape)](#getCount-com.aspose.slides.IShape-) | Vrací počet efektů pro zadaný tvar. |
| [addEffect(IShape shape, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IShape-int-int-int-) | Přidá nový efekt na konec sekvence. |
| [addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IParagraph-int-int-int-) | Přidá nový animační efekt pro odstavec na konec sekvence. |
| [addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IChart-int-int-int-int-int-) | Přidá nový animační efekt diagramu pro kategorii nebo sérii na konec sekvence. |
| [addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IChart-int-int-int-int-int-int-) | Přidá nový animační efekt diagramu pro prvky v kategorii nebo sérii na konec sekvence. |
### getCount() {#getCount--}
```
public final int getCount()
```

Vrací počet efektů v sekvenci. Pouze ke čtení int.

**Vrací:**
int
### remove(IEffect item) {#remove-com.aspose.slides.IEffect-}
```
public final void remove(IEffect item)
```

Odstraňuje zadaný efekt z kolekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| item | [IEffect](../../com.aspose.slides/ieffect) | Efekt k odstranění. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Odstraňuje efekt z kolekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index efektu, který má být smazán. |

### clear() {#clear--}
```
public final void clear()
```

Odstraňuje všechny efekty z kolekce.

### get_Item(int index) {#get-Item-int-}
```
public final IEffect get_Item(int index)
```

Vrací efekt na zadaném indexu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index prvku. |

**Vrací:**
[IEffect](../../com.aspose.slides/ieffect) - Objekt [IEffect](../../com.aspose.slides/ieffect).
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IEffect> iterator()
```

Vrací enumerátor, který prochází kolekcí.

**Vrací:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IEffect> - IGenericEnumerator, který může být použit k procházení kolekce.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IEffect> iteratorJava()
```

Vrací java iterátor pro celou kolekci.

**Vrací:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IEffect> - java.util.Iterator pro celou kolekci.
### getTriggerShape() {#getTriggerShape--}
```
public final IShape getTriggerShape()
```

Vrací nebo nastavuje cílový tvar pro INTERACTIVE sekvenci. Pokud sekvence není interaktivní, vrací null. Čtení/Zápis [IShape](../../com.aspose.slides/ishape).

**Vrací:**
[IShape](../../com.aspose.slides/ishape)
### setTriggerShape(IShape value) {#setTriggerShape-com.aspose.slides.IShape-}
```
public final void setTriggerShape(IShape value)
```

Vrací nebo nastavuje cílový tvar pro INTERACTIVE sekvenci. Pokud sekvence není interaktivní, vrací null. Čtení/Zápis [IShape](../../com.aspose.slides/ishape).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |

### removeByShape(IShape shape) {#removeByShape-com.aspose.slides.IShape-}
```
public final void removeByShape(IShape shape)
```

Odstraňuje efekt pro zadaný tvar.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) |  |

### getEffectsByShape(IShape shape) {#getEffectsByShape-com.aspose.slides.IShape-}
```
public final IEffect[] getEffectsByShape(IShape shape)
```

Vrací pole efektů pro zadaný tvar.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) |  |

**Vrací:**
com.aspose.slides.IEffect[]
### getEffectsByParagraph(IParagraph paragraph) {#getEffectsByParagraph-com.aspose.slides.IParagraph-}
```
public final IEffect[] getEffectsByParagraph(IParagraph paragraph)
```

Vrací pole efektů pro zadaný odstavec.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| paragraph | [IParagraph](../../com.aspose.slides/iparagraph) |  |

**Vrací:**
com.aspose.slides.IEffect[]
### getCount(IShape shape) {#getCount-com.aspose.slides.IShape-}
```
public final int getCount(IShape shape)
```

Vrací počet efektů pro zadaný tvar.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) |  |

**Vrací:**
int
### addEffect(IShape shape, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IShape-int-int-int-}
```
public final IEffect addEffect(IShape shape, int effectType, int subtype, int triggerType)
```

Přidá nový efekt na konec sekvence.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | Objekt Shape [IShape](../../com.aspose.slides/ishape) pro přidání efektu |
| effectType | int | Typ animačního efektu [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Podtypy animačního efektu [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Typ spouštěče efektu [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Vrací:**
[IEffect](../../com.aspose.slides/ieffect) - Nový objekt efektu [IEffect](../../com.aspose.slides/ieffect)
### addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IParagraph-int-int-int-}
```
public final IEffect addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType)
```

Přidá nový animační efekt pro odstavec na konec sekvence.

--------------------

> ```
> Presentation presentation = new Presentation(path + "input.pptx");
>   try
>   {        
>      // vyberte odstavec pro přidání efektu
>      IAutoShape autoShape = (IAutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>      IParagraph paragraph = autoShape.getTextFrame().getParagraphs().get_Item(0);
>      // přidejte Fly animační efekt do vybraného odstavce
>      IEffect effect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().addEffect(
>      paragraph, EffectType.Fly, EffectSubtype.Left, EffectTriggerType.OnClick);
>   }  finally {
>      if (presentation != null) presentation.dispose();
>   }
> ```


**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| paragraph | [IParagraph](../../com.aspose.slides/iparagraph) | Objekt Paragraph [IParagraph](../../com.aspose.slides/iparagraph) |
| effectType | int | Typ animačního efektu [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Podtypy animačního efektu [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Typ spouštěče efektu [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Vrací:**
[IEffect](../../com.aspose.slides/ieffect) - Nový objekt efektu [IEffect](../../com.aspose.slides/ieffect)
### addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IChart-int-int-int-int-int-}
```
public final IEffect addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType)
```

Přidá nový animační efekt diagramu pro kategorii nebo sérii na konec sekvence.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| chart | [IChart](../../com.aspose.slides/ichart) | Objekt Chart [IChart](../../com.aspose.slides/ichart) |
| type | int | Typ animačního efektu [EffectChartMinorGroupingType](../../com.aspose.slides/effectchartminorgroupingtype) |
| index | int | Index int |
| effectType | int | Typ animačního efektu [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Podtypy animačního efektu [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Typ spouštěče efektu [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Vrací:**
[IEffect](../../com.aspose.slides/ieffect) - Nový objekt efektu [IEffect](../../com.aspose.slides/ieffect)
### addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IChart-int-int-int-int-int-int-}
```
public final IEffect addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType)
```

Přidá nový animační efekt diagramu pro prvky v kategorii nebo sérii na konec sekvence.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| chart | [IChart](../../com.aspose.slides/ichart) | Objekt Chart [IChart](../../com.aspose.slides/ichart) |
| type | int | Typ animačního efektu [EffectChartMinorGroupingType](../../com.aspose.slides/effectchartminorgroupingtype) |
| seriesIndex | int | Index série diagramu int |
| categoriesIndex | int | Index kategorie int |
| effectType | int | Typ animačního efektu [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Podtypy animačního efektu [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Typ spouštěče efektu [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Vrací:**
[IEffect](../../com.aspose.slides/ieffect) - Nový objekt efektu [IEffect](../../com.aspose.slides/ieffect)