---
title: ISequenceCollection
second_title: Aspose.Slides für Android über die Java API Referenz
description: Stellt eine Sammlung interaktiver Sequenzen dar.
type: docs
url: /de/com.aspose.slides/isequencecollection/
---
**Alle implementierten Schnittstellen:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface ISequenceCollection extends System.Collections.Generic.IGenericEnumerable<ISequence>
```

Stellt eine Sammlung interaktiver Sequenzen dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getCount()](#getCount--) | Gibt die Anzahl der Elemente in einer Sammlung zurück. Nur-Lese int. |
| [add(IShape shapeTrigger)](#add-com.aspose.slides.IShape-) | Fügt eine neue interaktive Sequenz hinzu. |
| [remove(ISequence item)](#remove-com.aspose.slides.ISequence-) | Entfernt die angegebene Sequenz aus einer Sammlung. |
| [removeAt(int index)](#removeAt-int-) | Entfernt die Sequenz am angegebenen Index. |
| [clear()](#clear--) | Entfernt alle Sequenzen aus einer Sammlung. |
| [get_Item(int index)](#get-Item-int-) | Gibt eine Sequenz am angegebenen Index zurück. |
### getCount() {#getCount--}
```
public abstract int getCount()
```

Gibt die Anzahl der Elemente in einer Sammlung zurück. Nur-Lese int.

**Rückgabe:**
int
### add(IShape shapeTrigger) {#add-com.aspose.slides.IShape-}
```
public abstract ISequence add(IShape shapeTrigger)
```

Fügt eine neue interaktive Sequenz hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| shapeTrigger | [IShape](../../com.aspose.slides/ishape) | Shape-Objekt [IShape](../../com.aspose.slides/ishape) |

**Rückgabe:**
[ISequence](../../com.aspose.slides/isequence) - Neue Sequenz [ISequence](../../com.aspose.slides/isequence)
### remove(ISequence item) {#remove-com.aspose.slides.ISequence-}
```
public abstract void remove(ISequence item)
```

Entfernt die angegebene Sequenz aus einer Sammlung.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| item | [ISequence](../../com.aspose.slides/isequence) | Zu entfernende Sequenz. |
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Entfernt die Sequenz am angegebenen Index.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Index des Elements in der Sammlung int |
### clear() {#clear--}
```
public abstract void clear()
```

Entfernt alle Sequenzen aus einer Sammlung.
### get_Item(int index) {#get-Item-int-}
```
public abstract ISequence get_Item(int index)
```

Gibt eine Sequenz am angegebenen Index zurück.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Index des Elements. |

**Rückgabe:**
[ISequence](../../com.aspose.slides/isequence) - Das [ISequence](../../com.aspose.slides/isequence) Objekt.