---
title: ISequence
second_title: Aspose.Slides pro Android prostřednictvím Java API Reference
description: Reprezentuje sekvenci kolekci efektů.
type: docs
url: /cs/com.aspose.slides/isequence/
---
**Všechna implementovaná rozhraní:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface ISequence extends System.Collections.Generic.IGenericEnumerable<IEffect>
```

Represents sequence (collection of effects).

## Metody

| Metoda | Popis |
| --- | --- |
| [getCount()](#getCount--) | Vrací počet efektů v sekvenci. |
| [remove(IEffect item)](#remove-com.aspose.slides.IEffect-) | Odstraňuje určený efekt z kolekce. |
| [removeAt(int index)](#removeAt-int-) | Odstraňuje efekt z kolekce. |
| [clear()](#clear--) | Odstraňuje všechny efekty z kolekce. |
| [get_Item(int index)](#get-Item-int-) | Vrací efekt na zadaném indexu. |
| [getTriggerShape()](#getTriggerShape--) | Vrací nebo nastavuje cíl tvaru pro INTERACTIVE sekvenci. |
| [setTriggerShape(IShape value)](#setTriggerShape-com.aspose.slides.IShape-) | Vrací nebo nastavuje cíl tvaru pro INTERACTIVE sekvenci. |
| [removeByShape(IShape shape)](#removeByShape-com.aspose.slides.IShape-) | Odstraňuje efekt pro zadaný tvar. |
| [getEffectsByShape(IShape shape)](#getEffectsByShape-com.aspose.slides.IShape-) | Vrací pole efektů pro zadaný tvar. |
| [getEffectsByParagraph(IParagraph paragraph)](#getEffectsByParagraph-com.aspose.slides.IParagraph-) | Vrací pole efektů pro zadaný odstavec. |
| [getCount(IShape shape)](#getCount-com.aspose.slides.IShape-) | Vrací počet efektů pro zadaný tvar. |
| [addEffect(IShape shape, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IShape-int-int-int-) | Přidá nový efekt na konec sekvence. |
| [addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IParagraph-int-int-int-) | Přidá nový animační efekt pro odstavec na konec sekvence. |
| [addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IChart-int-int-int-int-int-) | Přidá nový animační efekt diagramu pro kategorii nebo řadu na konec sekvence. |
| [addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IChart-int-int-int-int-int-int-) | Přidá nový animační efekt diagramu pro položky v kategorii nebo řadě na konec sekvence. |

### getCount() {#getCount--}
```
public abstract int getCount()
```

Vrací počet efektů v sekvenci. Pouze pro čtení int.

**Vrací:**
int

### remove(IEffect item) {#remove-com.aspose.slides.IEffect-}
```
public abstract void remove(IEffect item)
```

Odstraňuje určený efekt z kolekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| item | [IEffect](../../com.aspose.slides/ieffect) | Efekt k odstranění. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Odstraňuje efekt z kolekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index efektu k odstranění. |

### clear() {#clear--}
```
public abstract void clear()
```

Odstraňuje všechny efekty z kolekce.

### get_Item(int index) {#get-Item-int-}
```
public abstract IEffect get_Item(int index)
```

Vrací efekt na zadaném indexu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index prvku. |

**Vrací:**
[IEffect](../../com.aspose.slides/ieffect) - Objekt [IEffect](../../com.aspose.slides/ieffect)

### getTriggerShape() {#getTriggerShape--}
```
public abstract IShape getTriggerShape()
```

Vrací nebo nastavuje cíl tvaru pro INTERACTIVE sekvenci. Pokud sekvence není interaktivní, vrací null. Čtení/Zápis [IShape](../../com.aspose.slides/ishape).

**Vrací:**
[IShape](../../com.aspose.slides/ishape)

### setTriggerShape(IShape value) {#setTriggerShape-com.aspose.slides.IShape-}
```
public abstract void setTriggerShape(IShape value)
```

Vrací nebo nastavuje cíl tvaru pro INTERACTIVE sekvenci. Pokud sekvence není interaktivní, vrací null. Čtení/Zápis [IShape](../../com.aspose.slides/ishape).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |

### removeByShape(IShape shape) {#removeByShape-com.aspose.slides.IShape-}
```
public abstract void removeByShape(IShape shape)
```

Odstraňuje efekt pro zadaný tvar.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | Objekt tvaru [IShape](../../com.aspose.slides/ishape) |

### getEffectsByShape(IShape shape) {#getEffectsByShape-com.aspose.slides.IShape-}
```
public abstract IEffect[] getEffectsByShape(IShape shape)
```

Vrací pole efektů pro zadaný tvar.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | Objekt tvaru [IShape](../../com.aspose.slides/ishape) |

**Vrací:**
com.aspose.slides.IEffect[] - Pole efektů [IEffect](../../com.aspose.slides/ieffect)

### getEffectsByParagraph(IParagraph paragraph) {#getEffectsByParagraph-com.aspose.slides.IParagraph-}
```
public abstract IEffect[] getEffectsByParagraph(IParagraph paragraph)
```

Vrací pole efektů pro zadaný odstavec.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| paragraph | [IParagraph](../../com.aspose.slides/iparagraph) | Objekt odstavce [IParagraph](../../com.aspose.slides/iparagraph) |

**Vrací:**
com.aspose.slides.IEffect[] - Pole efektů [IEffect](../../com.aspose.slides/ieffect)

### getCount(IShape shape) {#getCount-com.aspose.slides.IShape-}
```
public abstract int getCount(IShape shape)
```

Vrací počet efektů pro zadaný tvar.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | Objekt tvaru [IShape](../../com.aspose.slides/ishape) |

**Vrací:**
int - Počet efektů

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

**Vrací:**
[IEffect](../../com.aspose.slides/ieffect) - Nový objekt efektu [IEffect](../../com.aspose.slides/ieffect)

### addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IParagraph-int-int-int-}
```
public abstract IEffect addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType)
```

Přidá nový animační efekt pro odstavec na konec sekvence.

--------------------

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

**Vrací:**
[IEffect](../../com.aspose.slides/ieffect) - Nový objekt efektu [IEffect](../../com.aspose.slides/ieffect)

### addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IChart-int-int-int-int-int-}
```
public abstract IEffect addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType)
```

Přidá nový animační efekt diagramu pro kategorii nebo řadu na konec sekvence.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| chart | [IChart](../../com.aspose.slides/ichart) | Objekt diagramu [IChart](../../com.aspose.slides/ichart) |
| type | int | Typ animačního efektu [EffectChartMinorGroupingType](../../com.aspose.slides/effectchartminorgroupingtype) |
| index | int | Index |
| effectType | int | Typ animačního efektu [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Podtypy animačního efektu [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Typ spouštěče efektu [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Vrací:**
[IEffect](../../com.aspose.slides/ieffect) - Nový objekt efektu [IEffect](../../com.aspose.slides/ieffect)

### addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IChart-int-int-int-int-int-int-}
```
public abstract IEffect addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType)
```

Přidá nový animační efekt diagramu pro položky v kategorii nebo řadě na konec sekvence.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| chart | [IChart](../../com.aspose.slides/ichart) | Objekt diagramu [IChart](../../com.aspose.slides/ichart) |
| type | int | Typ animačního efektu [EffectChartMinorGroupingType](../../com.aspose.slides/effectchartminorgroupingtype) |
| seriesIndex | int | Index řady diagramu |
| categoriesIndex | int | Index kategorie |
| effectType | int | Typ animačního efektu [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Podtypy animačního efektu [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Typ spouštěče efektu [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Vrací:**
[IEffect](../../com.aspose.slides/ieffect) - Nový objekt efektu [IEffect](../../com.aspose.slides/ieffect)