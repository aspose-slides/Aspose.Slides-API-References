---
title: ISequence
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt een sequentie voor, een collectie van effecten.
type: docs
url: /nl/com.aspose.slides/isequence/
---
**Alle geïmplementeerde interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface ISequence extends System.Collections.Generic.IGenericEnumerable<IEffect>
```

Stelt een sequentie (collectie van effecten) voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getCount()](#getCount--) | Retourneert het aantal effecten in een sequentie. |
| [remove(IEffect item)](#remove-com.aspose.slides.IEffect-) | Verwijdert het opgegeven effect uit een collectie. |
| [removeAt(int index)](#removeAt-int-) | Verwijdert een effect uit een collectie. |
| [clear()](#clear--) | Verwijdert alle effecten uit een collectie. |
| [get_Item(int index)](#get-Item-int-) | Retourneert een effect op de opgegeven index. |
| [getTriggerShape()](#getTriggerShape--) | Retourneert of stelt de shape-target in voor een INTERACTIVE sequentie. |
| [setTriggerShape(IShape value)](#setTriggerShape-com.aspose.slides.IShape-) | Retourneert of stelt de shape-target in voor een INTERACTIVE sequentie. |
| [removeByShape(IShape shape)](#removeByShape-com.aspose.slides.IShape-) | Verwijdert een effect voor de opgegeven shape. |
| [getEffectsByShape(IShape shape)](#getEffectsByShape-com.aspose.slides.IShape-) | Retourneert een array van effecten voor de opgegeven shape. |
| [getEffectsByParagraph(IParagraph paragraph)](#getEffectsByParagraph-com.aspose.slides.IParagraph-) | Retourneert een array van effecten voor de opgegeven alinea. |
| [getCount(IShape shape)](#getCount-com.aspose.slides.IShape-) | Retourneert het aantal effecten voor de opgegeven shape. |
| [addEffect(IShape shape, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IShape-int-int-int-) | Voegt een nieuw effect toe aan het einde van de sequentie. |
| [addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IParagraph-int-int-int-) | Voegt een nieuw animatie-effect voor een alinea toe aan het einde van de sequentie. |
| [addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IChart-int-int-int-int-int-) | Voegt het nieuwe grafiekanimatie-effect toe voor een categorie of serie aan het einde van de sequentie. |
| [addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IChart-int-int-int-int-int-int-) | Voegt het nieuwe grafiekanimatie-effect toe voor elementen in een categorie of serie aan het einde van de sequentie. |
### getCount() {#getCount--}
```
public abstract int getCount()
```

Retourneert het aantal effecten in een sequentie. Alleen-lezen int.

**Retour:**
int
### remove(IEffect item) {#remove-com.aspose.slides.IEffect-}
```
public abstract void remove(IEffect item)
```

Verwijdert het opgegeven effect uit een collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| item | [IEffect](../../com.aspose.slides/ieffect) | Effect om te verwijderen. |
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Verwijdert een effect uit een collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Index van te verwijderen effect int |
### clear() {#clear--}
```
public abstract void clear()
```

Verwijdert alle effecten uit een collectie.

### get_Item(int index) {#get-Item-int-}
```
public abstract IEffect get_Item(int index)
```

Retourneert een effect op de opgegeven index.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Index van element. |

**Retour:**
[IEffect](../../com.aspose.slides/ieffect) - Het [IEffect](../../com.aspose.slides/ieffect) object.
### getTriggerShape() {#getTriggerShape--}
```
public abstract IShape getTriggerShape()
```

Retourneert of stelt de shape-target in voor een INTERACTIVE sequentie. Als de sequentie niet interactief is, wordt null geretourneerd. Lezen/Schrijven [IShape](../../com.aspose.slides/ishape).

**Retour:**
[IShape](../../com.aspose.slides/ishape)
### setTriggerShape(IShape value) {#setTriggerShape-com.aspose.slides.IShape-}
```
public abstract void setTriggerShape(IShape value)
```

Retourneert of stelt de shape-target in voor een INTERACTIVE sequentie. Als de sequentie niet interactief is, wordt null geretourneerd. Lezen/Schrijven [IShape](../../com.aspose.slides/ishape).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |
### removeByShape(IShape shape) {#removeByShape-com.aspose.slides.IShape-}
```
public abstract void removeByShape(IShape shape)
```

Verwijdert een effect voor de opgegeven shape.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | Shape-object [IShape](../../com.aspose.slides/ishape) |
### getEffectsByShape(IShape shape) {#getEffectsByShape-com.aspose.slides.IShape-}
```
public abstract IEffect[] getEffectsByShape(IShape shape)
```

Retourneert een array van effecten voor de opgegeven shape.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | Shape-object [IShape](../../com.aspose.slides/ishape) |

**Retour:**
com.aspose.slides.IEffect[] - Array van effecten [IEffect](../../com.aspose.slides/ieffect)
### getEffectsByParagraph(IParagraph paragraph) {#getEffectsByParagraph-com.aspose.slides.IParagraph-}
```
public abstract IEffect[] getEffectsByParagraph(IParagraph paragraph)
```

Retourneert een array van effecten voor de opgegeven alinea.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| paragraph | [IParagraph](../../com.aspose.slides/iparagraph) | Paragraph-object [IParagraph](../../com.aspose.slides/iparagraph) |

**Retour:**
com.aspose.slides.IEffect[] - Array van effecten [IEffect](../../com.aspose.slides/ieffect)
### getCount(IShape shape) {#getCount-com.aspose.slides.IShape-}
```
public abstract int getCount(IShape shape)
```

Retourneert het aantal effecten voor de opgegeven shape.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | Shape-object [IShape](../../com.aspose.slides/ishape) |

**Retour:**
int - Aantal effecten int
### addEffect(IShape shape, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IShape-int-int-int-}
```
public abstract IEffect addEffect(IShape shape, int effectType, int subtype, int triggerType)
```

Voegt een nieuw effect toe aan het einde van de sequentie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | Shape-object [IShape](../../com.aspose.slides/ishape) voor het toevoegen van een effect |
| effectType | int | Type van een animatie-effect [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Subtype van animatie-effect [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Trigger-type van effect [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Retour:**
[IEffect](../../com.aspose.slides/ieffect) - Nieuw effectobject [IEffect](../../com.aspose.slides/ieffect)
### addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IParagraph-int-int-int-}
```
public abstract IEffect addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType)
```

Voegt een nieuw animatie-effect voor een alinea toe aan het einde van de sequentie.

--------------------

> ```
> Presentation presentation = new Presentation(path + "input.pptx");
>  try
>  {
>     // selecteer alinea om effect toe te voegen
>     IAutoShape autoShape = (IAutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>     IParagraph paragraph = autoShape.getTextFrame().getParagraphs().get_Item(0);
>     // voeg Fly animatie-effect toe aan geselecteerde alinea
>     IEffect effect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().addEffect(
>     paragraph, EffectType.Fly, EffectSubtype.Left, EffectTriggerType.OnClick);
>  } finally {
>     if (presentation != null) presentation.dispose();
>  }
> ```


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| paragraph | [IParagraph](../../com.aspose.slides/iparagraph) | Paragraph-object [IParagraph](../../com.aspose.slides/iparagraph) |
| effectType | int | Type van een animatie-effect [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Subtype van animatie-effect [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Trigger-type van effect [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Retour:**
[IEffect](../../com.aspose.slides/ieffect) - Nieuw effectobject [IEffect](../../com.aspose.slides/ieffect)
### addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IChart-int-int-int-int-int-}
```
public abstract IEffect addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType)
```

Voegt het nieuwe grafiekanimatie-effect toe voor een categorie of serie aan het einde van de sequentie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| chart | [IChart](../../com.aspose.slides/ichart) | Chart-object [IChart](../../com.aspose.slides/ichart) |
| type | int | Type van een animatie-effect [EffectChartMinorGroupingType](../../com.aspose.slides/effectchartminorgroupingtype) |
| index | int | Index int |
| effectType | int | Type van een animatie-effect [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Subtype van animatie-effect [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Trigger-type van effect [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Retour:**
[IEffect](../../com.aspose.slides/ieffect) - Nieuw effectobject [IEffect](../../com.aspose.slides/ieffect)
### addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IChart-int-int-int-int-int-int-}
```
public abstract IEffect addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType)
```

Voegt het nieuwe grafiekanimatie-effect toe voor elementen in een categorie of serie aan het einde van de sequentie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| chart | [IChart](../../com.aspose.slides/ichart) | Chart-object [IChart](../../com.aspose.slides/ichart) |
| type | int | Type van een animatie-effect [EffectChartMinorGroupingType](../../com.aspose.slides/effectchartminorgroupingtype) |
| seriesIndex | int | Index van grafiekserie int |
| categoriesIndex | int | Index van categorie int |
| effectType | int | Type van een animatie-effect [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Subtype van animatie-effect [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Trigger-type van effect [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Retour:**
[IEffect](../../com.aspose.slides/ieffect) - Nieuw effectobject [IEffect](../../com.aspose.slides/ieffect)