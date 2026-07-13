---
title: Sequence
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt een sequentiecollectie van effecten voor.
type: docs
url: /nl/com.aspose.slides/sequence/
---
**Erfenis:**
java.lang.Object

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.ISequence](../../com.aspose.slides/isequence)
```
public final class Sequence implements ISequence
```

Stelt een reeks (collectie van effecten) voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getCount()](#getCount--) | Retourneert het aantal effecten in een reeks. |
| [remove(IEffect item)](#remove-com.aspose.slides.IEffect-) | Verwijdert het opgegeven effect uit een verzameling. |
| [removeAt(int index)](#removeAt-int-) | Verwijdert een effect uit een verzameling. |
| [clear()](#clear--) | Verwijdert alle effecten uit een verzameling. |
| [get_Item(int index)](#get-Item-int-) | Retourneert een effect op de opgegeven index. |
| [iterator()](#iterator--) | Retourneert een enumerator die door de verzameling iterereert. |
| [iteratorJava()](#iteratorJava--) | Retourneert een java-iterator voor de volledige verzameling. |
| [getTriggerShape()](#getTriggerShape--) | Retourneert of stelt shape-doel in voor INTERACTIVE-reeks. |
| [setTriggerShape(IShape value)](#setTriggerShape-com.aspose.slides.IShape-) | Retourneert of stelt shape-doel in voor INTERACTIVE-reeks. |
| [removeByShape(IShape shape)](#removeByShape-com.aspose.slides.IShape-) | Verwijdert effect voor de opgegeven shape. |
| [getEffectsByShape(IShape shape)](#getEffectsByShape-com.aspose.slides.IShape-) | Retourneert een array van effecten voor de opgegeven shape. |
| [getEffectsByParagraph(IParagraph paragraph)](#getEffectsByParagraph-com.aspose.slides.IParagraph-) | Retourneert een array van effecten voor de opgegeven alinea. |
| [getCount(IShape shape)](#getCount-com.aspose.slides.IShape-) | Retourneert het aantal effecten voor de opgegeven shape. |
| [addEffect(IShape shape, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IShape-int-int-int-) | Voegt een nieuw effect toe aan het einde van de reeks. |
| [addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IParagraph-int-int-int-) | Voegt een nieuw animatie-effect toe voor alinea aan het einde van de reeks. |
| [addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IChart-int-int-int-int-int-) | Voegt het nieuwe diagramanimatie-effect toe voor categorie of serie aan het einde van de reeks. |
| [addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IChart-int-int-int-int-int-int-) | Voegt het nieuwe diagramanimatie-effect toe voor elementen in categorie of serie aan het einde van de reeks. |
### getCount() {#getCount--}
```
public final int getCount()
```

Retourneert het aantal effecten in een reeks. Alleen-lezen int.

**Retourneert:**
int
### remove(IEffect item) {#remove-com.aspose.slides.IEffect-}
```
public final void remove(IEffect item)
```

Verwijdert het opgegeven effect uit een verzameling.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| item | [IEffect](../../com.aspose.slides/ieffect) | Effect om te verwijderen. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Verwijdert een effect uit een verzameling.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Index van een effect dat moet worden verwijderd. |

### clear() {#clear--}
```
public final void clear()
```

Verwijdert alle effecten uit een verzameling.

### get_Item(int index) {#get-Item-int-}
```
public final IEffect get_Item(int index)
```

Retourneert een effect op de opgegeven index.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Index van element. |

**Retourneert:**
[IEffect](../../com.aspose.slides/ieffect) - De [IEffect](../../com.aspose.slides/ieffect) object.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IEffect> iterator()
```

Retourneert een enumerator die door de verzameling iterereert.

**Retourneert:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IEffect> - Een IGenericEnumerator die kan worden gebruikt om door de verzameling te itereren.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IEffect> iteratorJava()
```

Retourneert een java-iterator voor de volledige verzameling.

**Retourneert:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IEffect> - Een java.util.Iterator voor de volledige verzameling.
### getTriggerShape() {#getTriggerShape--}
```
public final IShape getTriggerShape()
```

Retourneert of stelt shape-doel in voor INTERACTIVE-reeks. If sequence is not interactive then returns null. Lezen/Schrijven [IShape](../../com.aspose.slides/ishape).

**Retourneert:**
[IShape](../../com.aspose.slides/ishape)
### setTriggerShape(IShape value) {#setTriggerShape-com.aspose.slides.IShape-}
```
public final void setTriggerShape(IShape value)
```

Retourneert of stelt shape-doel in voor INTERACTIVE-reeks. If sequence is not interactive then returns null. Lezen/Schrijven [IShape](../../com.aspose.slides/ishape).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |

### removeByShape(IShape shape) {#removeByShape-com.aspose.slides.IShape-}
```
public final void removeByShape(IShape shape)
```

Verwijdert effect voor de opgegeven shape.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) |  |

### getEffectsByShape(IShape shape) {#getEffectsByShape-com.aspose.slides.IShape-}
```
public final IEffect[] getEffectsByShape(IShape shape)
```

Retourneert een array van effecten voor de opgegeven shape.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) |  |

**Retourneert:**
com.aspose.slides.IEffect[]
### getEffectsByParagraph(IParagraph paragraph) {#getEffectsByParagraph-com.aspose.slides.IParagraph-}
```
public final IEffect[] getEffectsByParagraph(IParagraph paragraph)
```

Retourneert een array van effecten voor de opgegeven alinea.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| paragraph | [IParagraph](../../com.aspose.slides/iparagraph) |  |

**Retourneert:**
com.aspose.slides.IEffect[]
### getCount(IShape shape) {#getCount-com.aspose.slides.IShape-}
```
public final int getCount(IShape shape)
```

Retourneert het aantal effecten voor de opgegeven shape.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) |  |

**Retourneert:**
int
### addEffect(IShape shape, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IShape-int-int-int-}
```
public final IEffect addEffect(IShape shape, int effectType, int subtype, int triggerType)
```

Voegt een nieuw effect toe aan het einde van de reeks.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | Shape-object [IShape](../../com.aspose.slides/ishape) voor het toevoegen van een effect |
| effectType | int | Type van een animatie-effect [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Subtypes van animatie-effect [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Trigger-type van effect [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Retourneert:**
[IEffect](../../com.aspose.slides/ieffect) - Nieuw effectobject [IEffect](../../com.aspose.slides/ieffect)
### addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IParagraph-int-int-int-}
```
public final IEffect addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType)
```

Voegt een nieuw animatie-effect toe voor alinea aan het einde van de reeks.

--------------------

> ```
> Presentation presentation = new Presentation(path + "input.pptx");
>   try
>   {        
>      // selecteer alinea om effect toe te voegen
>      IAutoShape autoShape = (IAutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>      IParagraph paragraph = autoShape.getTextFrame().getParagraphs().get_Item(0);
>      // voeg Fly-animatie-effect toe aan geselecteerde alinea
>      IEffect effect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().addEffect(
>      paragraph, EffectType.Fly, EffectSubtype.Left, EffectTriggerType.OnClick);
>   }  finally {
>      if (presentation != null) presentation.dispose();
>   }
> ```


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| paragraph | [IParagraph](../../com.aspose.slides/iparagraph) | Paragraph-object [IParagraph](../../com.aspose.slides/iparagraph) |
| effectType | int | Type van een animatie-effect [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Subtypes van animatie-effect [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Trigger-type van effect [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Retourneert:**
[IEffect](../../com.aspose.slides/ieffect) - Nieuw effectobject [IEffect](../../com.aspose.slides/ieffect)
### addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IChart-int-int-int-int-int-}
```
public final IEffect addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType)
```

Voegt het nieuwe diagramanimatie-effect toe voor categorie of serie aan het einde van de reeks.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| chart | [IChart](../../com.aspose.slides/ichart) | Chart-object [IChart](../../com.aspose.slides/ichart) |
| type | int | Type van een animatie-effect [EffectChartMinorGroupingType](../../com.aspose.slides/effectchartminorgroupingtype) |
| index | int | Index int |
| effectType | int | Type van een animatie-effect [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Subtypes van animatie-effect [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Trigger-type van effect [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Retourneert:**
[IEffect](../../com.aspose.slides/ieffect) - Nieuw effectobject [IEffect](../../com.aspose.slides/ieffect)
### addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IChart-int-int-int-int-int-int-}
```
public final IEffect addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType)
```

Voegt het nieuwe diagramanimatie-effect toe voor elementen in categorie of serie aan het einde van de reeks.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| chart | [IChart](../../com.aspose.slides/ichart) | Chart-object [IChart](../../com.aspose.slides/ichart) |
| type | int | Type van een animatie-effect [EffectChartMinorGroupingType](../../com.aspose.slides/effectchartminorgroupingtype) |
| seriesIndex | int | Index van chart-series int |
| categoriesIndex | int | Index van categorie int |
| effectType | int | Type van een animatie-effect [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Subtypes van animatie-effect [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Trigger-type van effect [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Retourneert:**
[IEffect](../../com.aspose.slides/ieffect) - Nieuw effectobject [IEffect](../../com.aspose.slides/ieffect)