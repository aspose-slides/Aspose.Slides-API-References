---
title: ISequence
second_title: Aspose.Slides für Android über Java API Referenz
description: Stellt eine Sequenzsammlung von Effekten dar.
type: docs
url: /de/com.aspose.slides/isequence/
---
**Alle implementierten Schnittstellen:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface ISequence extends System.Collections.Generic.IGenericEnumerable<IEffect>
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
| [getTriggerShape()](#getTriggerShape--) | Gibt das Zielshape für INTERACTIVE-Sequenz zurück oder setzt es. |
| [setTriggerShape(IShape value)](#setTriggerShape-com.aspose.slides.IShape-) | Gibt das Zielshape für INTERACTIVE-Sequenz zurück oder setzt es. |
| [removeByShape(IShape shape)](#removeByShape-com.aspose.slides.IShape-) | Entfernt den Effekt für das angegebene Shape. |
| [getEffectsByShape(IShape shape)](#getEffectsByShape-com.aspose.slides.IShape-) | Gibt ein Array von Effekten für das angegebene Shape zurück. |
| [getEffectsByParagraph(IParagraph paragraph)](#getEffectsByParagraph-com.aspose.slides.IParagraph-) | Gibt ein Array von Effekten für den angegebenen Absatz zurück. |
| [getCount(IShape shape)](#getCount-com.aspose.slides.IShape-) | Gibt die Anzahl der Effekte für das angegebene Shape zurück. |
| [addEffect(IShape shape, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IShape-int-int-int-) | Fügt einen neuen Effekt am Ende der Sequenz hinzu. |
| [addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IParagraph-int-int-int-) | Fügt einen neuen Animations-Effekt für den Absatz am Ende der Sequenz hinzu. |
| [addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IChart-int-int-int-int-int-) | Fügt den neuen Diagramm-Animations-Effekt für Kategorie oder Serie am Ende der Sequenz hinzu. |
| [addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IChart-int-int-int-int-int-int-) | Fügt den neuen Diagramm-Animations-Effekt für Elemente in Kategorie oder Serie am Ende der Sequenz hinzu. |
### getCount() {#getCount--}
```
public abstract int getCount()
```

Gibt die Anzahl der Effekte in einer Sequenz zurück. Nur lesbar int.

**Rückgabewert:**
int
### remove(IEffect item) {#remove-com.aspose.slides.IEffect-}
```
public abstract void remove(IEffect item)
```

Entfernt den angegebenen Effekt aus einer Sammlung.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| item | [IEffect](../../com.aspose.slides/ieffect) | Zu entfernender Effekt. |
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Entfernt einen Effekt aus einer Sammlung.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Index des zu entfernenden Effekts int |
### clear() {#clear--}
```
public abstract void clear()
```

Entfernt alle Effekte aus einer Sammlung.

### get_Item(int index) {#get-Item-int-}
```
public abstract IEffect get_Item(int index)
```

Gibt einen Effekt am angegebenen Index zurück.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Index des Elements. |

**Rückgabewert:**
[IEffect](../../com.aspose.slides/ieffect) - Das [IEffect](../../com.aspose.slides/ieffect) Objekt.
### getTriggerShape() {#getTriggerShape--}
```
public abstract IShape getTriggerShape()
```

Gibt das Ziel-Shape für INTERACTIVE-Sequenz zurück oder setzt es. Wenn die Sequenz nicht interaktiv ist, wird null zurückgegeben. Lesen/Schreiben [IShape](../../com.aspose.slides/ishape).

**Rückgabewert:**
[IShape](../../com.aspose.slides/ishape)
### setTriggerShape(IShape value) {#setTriggerShape-com.aspose.slides.IShape-}
```
public abstract void setTriggerShape(IShape value)
```

Gibt das Ziel-Shape für INTERACTIVE-Sequenz zurück oder setzt es. Wenn die Sequenz nicht interaktiv ist, wird null zurückgegeben. Lesen/Schreiben [IShape](../../com.aspose.slides/ishape).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |
### removeByShape(IShape shape) {#removeByShape-com.aspose.slides.IShape-}
```
public abstract void removeByShape(IShape shape)
```

Entfernt den Effekt für das angegebene Shape.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | Shape-Objekt [IShape](../../com.aspose.slides/ishape) |
### getEffectsByShape(IShape shape) {#getEffectsByShape-com.aspose.slides.IShape-}
```
public abstract IEffect[] getEffectsByShape(IShape shape)
```

Gibt ein Array von Effekten für das angegebene Shape zurück.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | Shape-Objekt [IShape](../../com.aspose.slides/ishape) |

**Rückgabewert:**
com.aspose.slides.IEffect[] - Array von Effekten [IEffect](../../com.aspose.slides/ieffect)
### getEffectsByParagraph(IParagraph paragraph) {#getEffectsByParagraph-com.aspose.slides.IParagraph-}
```
public abstract IEffect[] getEffectsByParagraph(IParagraph paragraph)
```

Gibt ein Array von Effekten für den angegebenen Absatz zurück.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| paragraph | [IParagraph](../../com.aspose.slides/iparagraph) | Paragraph-Objekt [IParagraph](../../com.aspose.slides/iparagraph) |

**Rückgabewert:**
com.aspose.slides.IEffect[] - Array von Effekten [IEffect](../../com.aspose.slides/ieffect)
### getCount(IShape shape) {#getCount-com.aspose.slides.IShape-}
```
public abstract int getCount(IShape shape)
```

Gibt die Anzahl der Effekte für das angegebene Shape zurück.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | Shape-Objekt [IShape](../../com.aspose.slides/ishape) |

**Rückgabewert:**
int - Anzahl der Effekte int
### addEffect(IShape shape, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IShape-int-int-int-}
```
public abstract IEffect addEffect(IShape shape, int effectType, int subtype, int triggerType)
```

Fügt einen neuen Effekt am Ende der Sequenz hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | Shape-Objekt [IShape](../../com.aspose.slides/ishape) zum Hinzufügen eines Effekts |
| effectType | int | Typ eines Animations-Effekts [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Untertypen eines Animations-Effekts [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Auslösetyp des Effekts [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Rückgabewert:**
[IEffect](../../com.aspose.slides/ieffect) - Neues Effekt-Objekt [IEffect](../../com.aspose.slides/ieffect)
### addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IParagraph-int-int-int-}
```
public abstract IEffect addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType)
```

Fügt einen neuen Animations-Effekt für den Absatz am Ende der Sequenz hinzu.

--------------------

> ```
> Presentation presentation = new Presentation(path + "input.pptx");
>  try
>  {
>     // Absatz auswählen, um Effekt hinzuzufügen
>     IAutoShape autoShape = (IAutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>     IParagraph paragraph = autoShape.getTextFrame().getParagraphs().get_Item(0);
>     // Fly-Animationseffekt zum ausgewählten Absatz hinzufügen
>     IEffect effect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().addEffect(
>     paragraph, EffectType.Fly, EffectSubtype.Left, EffectTriggerType.OnClick);
>  } finally {
>     if (presentation != null) presentation.dispose();
>  }
> ```


**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| paragraph | [IParagraph](../../com.aspose.slides/iparagraph) | Paragraph-Objekt [IParagraph](../../com.aspose.slides/iparagraph) |
| effectType | int | Typ eines Animations-Effekts [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Untertypen eines Animations-Effekts [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Auslösetyp des Effekts [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Rückgabewert:**
[IEffect](../../com.aspose.slides/ieffect) - Neues Effekt-Objekt [IEffect](../../com.aspose.slides/ieffect)
### addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IChart-int-int-int-int-int-}
```
public abstract IEffect addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType)
```

Fügt den neuen Diagramm-Animations-Effekt für Kategorie oder Serie am Ende der Sequenz hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| chart | [IChart](../../com.aspose.slides/ichart) | Chart-Objekt [IChart](../../com.aspose.slides/ichart) |
| type | int | Typ eines Animations-Effekts [EffectChartMinorGroupingType](../../com.aspose.slides/effectchartminorgroupingtype) |
| index | int | Index int |
| effectType | int | Typ eines Animations-Effekts [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Untertypen eines Animations-Effekts [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Auslösetyp des Effekts [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Rückgabewert:**
[IEffect](../../com.aspose.slides/ieffect) - Neues Effekt-Objekt [IEffect](../../com.aspose.slides/ieffect)
### addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IChart-int-int-int-int-int-int-}
```
public abstract IEffect addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType)
```

Fügt den neuen Diagramm-Animations-Effekt für Elemente in Kategorie oder Serie am Ende der Sequenz hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| chart | [IChart](../../com.aspose.slides/ichart) | Chart-Objekt [IChart](../../com.aspose.slides/ichart) |
| type | int | Typ eines Animations-Effekts [EffectChartMinorGroupingType](../../com.aspose.slides/effectchartminorgroupingtype) |
| seriesIndex | int | Index der Diagramm-Serie int |
| categoriesIndex | int | Index der Kategorie int |
| effectType | int | Typ eines Animations-Effekts [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Untertypen eines Animations-Effekts [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Auslösetyp des Effekts [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Rückgabewert:**
[IEffect](../../com.aspose.slides/ieffect) - Neues Effekt-Objekt [IEffect](../../com.aspose.slides/ieffect)