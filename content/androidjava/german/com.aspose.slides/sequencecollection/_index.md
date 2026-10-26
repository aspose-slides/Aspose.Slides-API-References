---
title: SequenceCollection
second_title: Aspose.Slides für Android über die Java-API-Referenz
description: Stellt eine Sammlung interaktiver Sequenzen dar.
type: docs
url: /de/com.aspose.slides/sequencecollection/
---
**Vererbung:**  
java.lang.Object

**Alle implementierten Schnittstellen:**  
[com.aspose.slides.ISequenceCollection](../../com.aspose.slides/isequencecollection)  
```
public class SequenceCollection implements ISequenceCollection
```

Stellt eine Sammlung interaktiver Sequenzen dar.

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getCount()](#getCount--) | Gibt die Anzahl der Elemente in einer Sammlung zurück Nur lesend int. |
| [add(IShape shapeTrigger)](#add-com.aspose.slides.IShape-) | Fügt eine neue interaktive Sequenz hinzu. |
| [remove(ISequence item)](#remove-com.aspose.slides.ISequence-) | Entfernt die angegebene Sequenz aus einer Sammlung. |
| [removeAt(int index)](#removeAt-int-) | Entfernt die Sequenz am angegebenen Index. |
| [clear()](#clear--) | Entfernt alle Sequenzen aus einer Sammlung. |
| [get_Item(int index)](#get-Item-int-) | Gibt eine Sequenz am angegebenen Index zurück. |
| [iterator()](#iterator--) | Gibt einen Enumerator zurück, der die Sammlung durchläuft. |
| [iteratorJava()](#iteratorJava--) | Gibt einen Java-Iterator für die gesamte Sammlung zurück. |
### getCount() {#getCount--}
```
public final int getCount()
```

Gibt die Anzahl der Elemente in einer Sammlung zurück Nur lesend int.

**Rückgabewert:**  
int
### add(IShape shapeTrigger) {#add-com.aspose.slides.IShape-}
```
public final ISequence add(IShape shapeTrigger)
```

Fügt eine neue interaktive Sequenz hinzu. Lesen/Schreiben [Sequence](../../com.aspose.slides/sequence).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| shapeTrigger | [IShape](../../com.aspose.slides/ishape) |  |

**Rückgabewert:**  
[ISequence](../../com.aspose.slides/isequence)
### remove(ISequence item) {#remove-com.aspose.slides.ISequence-}
```
public final void remove(ISequence item)
```

Entfernt die angegebene Sequenz aus einer Sammlung.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| item | [ISequence](../../com.aspose.slides/isequence) | Zu entfernende Sequenz. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Entfernt die Sequenz am angegebenen Index.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Index der zu löschenden Sequenz. |

### clear() {#clear--}
```
public final void clear()
```

Entfernt alle Sequenzen aus einer Sammlung.

### get_Item(int index) {#get-Item-int-}
```
public final ISequence get_Item(int index)
```

Gibt eine Sequenz am angegebenen Index zurück.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Index des Elements. |

**Rückgabewert:**  
[ISequence](../../com.aspose.slides/isequence) - Das [ISequence](../../com.aspose.slides/isequence)-Objekt.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISequence> iterator()
```

Gibt einen Enumerator zurück, der die Sammlung durchläuft.

**Rückgabewert:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISequence> - Ein IGenericEnumerator, der zum Durchlaufen der Sammlung verwendet werden kann.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISequence> iteratorJava()
```

Gibt einen Java-Iterator für die gesamte Sammlung zurück.

**Rückgabewert:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISequence> - Ein java.util.Iterator für die gesamte Sammlung.