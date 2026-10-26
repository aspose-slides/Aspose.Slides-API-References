---
title: Sequence
second_title: Aspose.Slides für Android über die Java API Referenz
description: Stellt eine Sequenzsammlung von Effekten dar.
type: docs
url: /de/com.aspose.slides/sequence/
---
**Vererbung:**
java.lang.Object

**Alle implementierten Schnittstellen:**
[com.aspose.slides.ISequence](../../com.aspose.slides/isequence)
```
public final class Sequence implements ISequence
```

Stellt eine Sequenz (Sammlung von Effekten) dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getCount()](#getCount--) | Gibt die Anzahl der Effekte in einer Sequenz zurück. |
| [remove(IEffect item)](#remove-com.aspose.slides.IEffect-) | Entfernt den angegebenen Effekt aus einer Sammlung. |
| [removeAt(int index)](#removeAt-int-) | Entfernt einen Effekt aus einer Sammlung. |
| [clear()](#clear--) | Entfernt alle Effekte aus einer Sammlung. |
| [get_Item(int index)](#get-Item-int-) | Gibt einen Effekt am angegebenen Index zurück. |
| [iterator()](#iterator--) | Gibt einen Enumerator zurück, der die Sammlung durchläuft. |
| [iteratorJava()](#iteratorJava--) | Gibt einen Java-Iterator für die gesamte Sammlung zurück. |
| [getTriggerShape()](#getTriggerShape--) | Gibt das Zielshape für die INTERACTIVE-Sequenz zurück oder setzt es. |
| [setTriggerShape(IShape value)](#setTriggerShape-com.aspose.slides.IShape-) | Gibt das Zielshape für die INTERACTIVE-Sequenz zurück oder setzt es. |
| [removeByShape(IShape shape)](#removeByShape-com.aspose.slides.IShape-) | Entfernt den Effekt für das angegebene Shape. |
| [getEffectsByShape(IShape shape)](#getEffectsByShape-com.aspose.slides.IShape-) | Gibt ein Array von Effekten für das angegebene Shape zurück. |
| [getEffectsByParagraph(IParagraph paragraph)](#getEffectsByParagraph-com.aspose.slides.IParagraph-) | Gibt ein Array von Effekten für den angegebenen Absatz zurück. |
| [getCount(IShape shape)](#getCount-com.aspose.slides.IShape-) | Gibt die Anzahl der Effekte für das angegebene Shape zurück. |
| [addEffect(IShape shape, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IShape-int-int-int-) | Fügt der Sequenz einen neuen Effekt am Ende hinzu. |
| [addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IParagraph-int-int-int-) | Fügt der Sequenz am Ende einen neuen Animations-Effekt für den Absatz hinzu. |
| [addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IChart-int-int-int-int-int-) | Fügt der Sequenz am Ende einen neuen Diagramm-Animations-Effekt für die Kategorie oder Serie hinzu. |
| [addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IChart-int-int-int-int-int-int-) | Fügt der Sequenz am Ende einen neuen Diagramm-Animations-Effekt für Elemente in einer Kategorie oder Serie hinzu. |
### getCount() {#getCount--}
```
public final int getCount()
```


Gibt die Anzahl der Effekte in einer Sequenz zurück. Nur Lese-Zugriff int.

**Rückgabe:**
int
### remove(IEffect item) {#remove-com.aspose.slides.IEffect-}
```
public final void remove(IEffect item)
```


Entfernt den angegebenen Effekt aus einer Sammlung.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| item | [IEffect](../../com.aspose.slides/ieffect) | Zu entfernender Effekt. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Entfernt einen Effekt aus einer Sammlung.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Index des zu löschenden Effekts. |

### clear() {#clear--}
```
public final void clear()
```


Entfernt alle Effekte aus einer Sammlung.

### get_Item(int index) {#get-Item-int-}
```
public final IEffect get_Item(int index)
```


Gibt einen Effekt am angegebenen Index zurück.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Index des Elements. |

**Rückgabe:**
[IEffect](../../com.aspose.slides/ieffect) - Das [IEffect](../../com.aspose.slides/ieffect)-Objekt.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IEffect> iterator()
```


Gibt einen Enumerator zurück, der die Sammlung durchläuft.

**Rückgabe:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IEffect> - Ein IGenericEnumerator, der zum Durchlaufen der Sammlung verwendet werden kann.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IEffect> iteratorJava()
```


Gibt einen Java-Iterator für die gesamte Sammlung zurück.

**Rückgabe:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IEffect> - Ein java.util.Iterator für die gesamte Sammlung.
### getTriggerShape() {#getTriggerShape--}
```
public final IShape getTriggerShape()
```


Gibt das Zielshape für die INTERACTIVE-Sequenz zurück oder setzt es. Wenn die Sequenz nicht interaktiv ist, wird null zurückgegeben. Lesen/Schreiben [IShape](../../com.aspose.slides/ishape).

**Rückgabe:**
[IShape](../../com.aspose.slides/ishape)
### setTriggerShape(IShape value) {#setTriggerShape-com.aspose.slides.IShape-}
```
public final void setTriggerShape(IShape value)
```


Gibt das Zielshape für die INTERACTIVE-Sequenz zurück oder setzt es. Wenn die Sequenz nicht interaktiv ist, wird null zurückgegeben. Lesen/Schreiben [IShape](../../com.aspose.slides/ishape).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |

### removeByShape(IShape shape) {#removeByShape-com.aspose.slides.IShape-}
```
public final void removeByShape(IShape shape)
```


Entfernt den Effekt für das angegebene Shape.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) |  |

### getEffectsByShape(IShape shape) {#getEffectsByShape-com.aspose.slides.IShape-}
```
public final IEffect[] getEffectsByShape(IShape shape)
```


Gibt ein Array von Effekten für das angegebene Shape zurück.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) |  |

**Rückgabe:**
com.aspose.slides.IEffect[]
### getEffectsByParagraph(IParagraph paragraph) {#getEffectsByParagraph-com.aspose.slides.IParagraph-}
```
public final IEffect[] getEffectsByParagraph(IParagraph paragraph)
```


Gibt ein Array von Effekten für den angegebenen Absatz zurück.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| paragraph | [IParagraph](../../com.aspose.slides/iparagraph) |  |

**Rückgabe:**
com.aspose.slides.IEffect[]
### getCount(IShape shape) {#getCount-com.aspose.slides.IShape-}
```
public final int getCount(IShape shape)
```


Gibt die Anzahl der Effekte für das angegebene Shape zurück.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) |  |

**Rückgabe:**
int
### addEffect(IShape shape, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IShape-int-int-int-}
```
public final IEffect addEffect(IShape shape, int effectType, int subtype, int triggerType)
```


Fügt der Sequenz einen neuen Effekt am Ende hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | Shape-Objekt [IShape](../../com.aspose.slides/ishape) zum Hinzufügen eines Effekts |
| effectType | int | Typ eines Animations-Effekts [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Untertyp des Animations-Effekts [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Auslöser-Typ des Effekts [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Rückgabe:**
[IEffect](../../com.aspose.slides/ieffect) - Neues Effekt-Objekt [IEffect](../../com.aspose.slides/ieffect)
### addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IParagraph-int-int-int-}
```
public final IEffect addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType)
```


Fügt der Sequenz am Ende einen neuen Animations-Effekt für den Absatz hinzu.

--------------------

> ```
> Presentation presentation = new Presentation(path + "input.pptx");
>   try
>   {        
>      // Absatz auswählen, um Effekt hinzuzufügen
>      IAutoShape autoShape = (IAutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>      IParagraph paragraph = autoShape.getTextFrame().getParagraphs().get_Item(0);
>      // Flug-Animationseffekt zum ausgewählten Absatz hinzufügen
>      IEffect effect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().addEffect(
>      paragraph, EffectType.Fly, EffectSubtype.Left, EffectTriggerType.OnClick);
>   }  finally {
>      if (presentation != null) presentation.dispose();
>   }
> ```


**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| paragraph | [IParagraph](../../com.aspose.slides/iparagraph) | Absatz-Objekt [IParagraph](../../com.aspose.slides/iparagraph) |
| effectType | int | Typ eines Animations-Effekts [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Untertyp des Animations-Effekts [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Auslöser-Typ des Effekts [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Rückgabe:**
[IEffect](../../com.aspose.slides/ieffect) - Neues Effekt-Objekt [IEffect](../../com.aspose.slides/ieffect)
### addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IChart-int-int-int-int-int-}
```
public final IEffect addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType)
```


Fügt der Sequenz am Ende einen neuen Diagramm-Animations-Effekt für die Kategorie oder Serie hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| chart | [IChart](../../com.aspose.slides/ichart) | Diagramm-Objekt [IChart](../../com.aspose.slides/ichart) |
| type | int | Typ eines Animations-Effekts [EffectChartMinorGroupingType](../../com.aspose.slides/effectchartminorgroupingtype) |
| index | int | Index int |
| effectType | int | Typ eines Animations-Effekts [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Untertyp des Animations-Effekts [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Auslöser-Typ des Effekts [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Rückgabe:**
[IEffect](../../com.aspose.slides/ieffect) - Neues Effekt-Objekt [IEffect](../../com.aspose.slides/ieffect)
### addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IChart-int-int-int-int-int-int-}
```
public final IEffect addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType)
```


Fügt der Sequenz am Ende einen neuen Diagramm-Animations-Effekt für Elemente in einer Kategorie oder Serie hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| chart | [IChart](../../com.aspose.slides/ichart) | Diagramm-Objekt [IChart](../../com.aspose.slides/ichart) |
| type | int | Typ eines Animations-Effekts [EffectChartMinorGroupingType](../../com.aspose.slides/effectchartminorgroupingtype) |
| seriesIndex | int | Index der Diagramm-Serie int |
| categoriesIndex | int | Index der Kategorie int |
| effectType | int | Typ eines Animations-Effekts [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Untertyp des Animations-Effekts [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Auslöser-Typ des Effekts [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Rückgabe:**
[IEffect](../../com.aspose.slides/ieffect) - Neues Effekt-Objekt [IEffect](../../com.aspose.slides/ieffect)