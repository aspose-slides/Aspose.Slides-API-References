---
title: BehaviorCollection
second_title: Aspose.Slides für Android über Java API Referenz
description: Stellt eine Sammlung von Verhaltenseffekten dar.
type: docs
url: /de/com.aspose.slides/behaviorcollection/
---
**Vererbung:**
java.lang.Object

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection)
```
public class BehaviorCollection implements IBehaviorCollection
```

Stellt eine Sammlung von Verhaltenseffekten dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getCount()](#getCount--) | Gibt die Anzahl der Verhaltensweisen in einer Sammlung zurück. |
| [isReadOnly()](#isReadOnly--) | Ermittelt einen Wert, der anzeigt, ob [IGenericCollection](../../com.aspose.slides/igenericcollection) nur lesbar ist. |
| [add(IBehavior item)](#add-com.aspose.slides.IBehavior-) | Fügt ein neues Verhalten zu einer Sammlung hinzu. |
| [indexOf(IBehavior item)](#indexOf-com.aspose.slides.IBehavior-) | Ermittelt den Index eines bestimmten Elements in der Liste. |
| [insert(int index, IBehavior item)](#insert-int-com.aspose.slides.IBehavior-) | Fügt ein neues Verhalten in einer Sammlung an dem angegebenen Index ein. |
| [copyTo(IBehavior[] array, int arrayIndex)](#copyTo-com.aspose.slides.IBehavior---int-) | Kopiert die Elemente von [IGenericCollection](../../com.aspose.slides/igenericcollection) in ein Array, beginnend bei einem bestimmten Array-Index. |
| [remove(IBehavior item)](#remove-com.aspose.slides.IBehavior-) | Entfernt das angegebene Verhalten aus einer Sammlung. |
| [removeAt(int index)](#removeAt-int-) | Entfernt ein Verhalten aus einer Sammlung an dem angegebenen Index. |
| [clear()](#clear--) | Entfernt alle Verhaltensweisen aus einer Sammlung. |
| [contains(IBehavior item)](#contains-com.aspose.slides.IBehavior-) | Bestimmt, ob [IGenericCollection](../../com.aspose.slides/igenericcollection) einen bestimmten Wert enthält. |
| [get_Item(int index)](#get-Item-int-) | Gibt ein Verhalten am angegebenen Index zurück. |
| [set_Item(int index, IBehavior value)](#set-Item-int-com.aspose.slides.IBehavior-) | Setzt ein Verhalten am angegebenen Index. |
| [iterator()](#iterator--) | Gibt einen Enumerator zurück, der die Sammlung durchläuft. |
| [iteratorJava()](#iteratorJava--) | Gibt einen Java-Iterator für die gesamte Sammlung zurück. |
### getCount() {#getCount--}
```
public final int getCount()
```

Gibt die Anzahl der Verhaltensweisen in einer Sammlung zurück. Nur lesbar int.

**Rückgabe:**
int
### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

Ermittelt einen Wert, der anzeigt, ob [IGenericCollection](../../com.aspose.slides/igenericcollection) nur lesbar ist. Nur lesbar boolean.

**Rückgabe:**
boolean - true wenn [IGenericCollection](../../com.aspose.slides/igenericcollection) nur lesbar ist; andernfalls false.
### add(IBehavior item) {#add-com.aspose.slides.IBehavior-}
```
public final void add(IBehavior item)
```

Fügt ein neues Verhalten zu einer Sammlung hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Verhalten, das hinzugefügt werden soll. |
### indexOf(IBehavior item) {#indexOf-com.aspose.slides.IBehavior-}
```
public final int indexOf(IBehavior item)
```

Ermittelt den Index eines bestimmten Elements in der Liste.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Das Objekt, das in der Liste gefunden werden soll. |

**Rückgabe:**
int - Der Index von item, falls im der Liste gefunden; andernfalls -1.
### insert(int index, IBehavior item) {#insert-int-com.aspose.slides.IBehavior-}
```
public final void insert(int index, IBehavior item)
```

Fügt ein neues Verhalten in einer Sammlung an dem angegebenen Index ein.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Index, an dem das neue Verhalten eingefügt werden soll. |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Einzufügenendes Verhalten. |
### copyTo(IBehavior[] array, int arrayIndex) {#copyTo-com.aspose.slides.IBehavior---int-}
```
public final void copyTo(IBehavior[] array, int arrayIndex)
```

Kopiert die Elemente von [IGenericCollection](../../com.aspose.slides/igenericcollection) in ein Array, beginnend bei einem bestimmten Array-Index.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| array | [IBehavior\[\]](../../com.aspose.slides/ibehavior) | Das eindimensionale Array, das das Ziel für die von [IGenericCollection](../../com.aspose.slides/igenericcollection) kopierten Elemente ist. Das Array muss nullbasierte Indizierung besitzen. |
| arrayIndex | int | Der nullbasierte Index im Array, an dem das Kopieren beginnt. |
### remove(IBehavior item) {#remove-com.aspose.slides.IBehavior-}
```
public final boolean remove(IBehavior item)
```

Entfernt das angegebene Verhalten aus einer Sammlung.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Zu entfernendes Verhalten. |

**Rückgabe:**
boolean
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Entfernt ein Verhalten aus einer Sammlung an dem angegebenen Index.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Index des zu entfernenden Verhaltens. |
### clear() {#clear--}
```
public final void clear()
```

Entfernt alle Verhaltensweisen aus einer Sammlung.
### contains(IBehavior item) {#contains-com.aspose.slides.IBehavior-}
```
public final boolean contains(IBehavior item)
```

Bestimmt, ob [IGenericCollection](../../com.aspose.slides/igenericcollection) einen bestimmten Wert enthält.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Das Objekt, das im [IGenericCollection](../../com.aspose.slides/igenericcollection) gefunden werden soll. |

**Rückgabe:**
boolean - true wenn item im [IGenericCollection](../../com.aspose.slides/igenericcollection) gefunden wird; andernfalls false.
### get_Item(int index) {#get-Item-int-}
```
public final IBehavior get_Item(int index)
```

Gibt ein Verhalten am angegebenen Index zurück.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Index des zurückzugebenden Verhaltens. |

**Rückgabe:**
[IBehavior](../../com.aspose.slides/ibehavior) - Animationsverhalten.
### set_Item(int index, IBehavior value) {#set-Item-int-com.aspose.slides.IBehavior-}
```
public final void set_Item(int index, IBehavior value)
```

Setzt ein Verhalten am angegebenen Index.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Index des zu setzenden Verhaltens. |
| value | [IBehavior](../../com.aspose.slides/ibehavior) |  |
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IBehavior> iterator()
```

Gibt einen Enumerator zurück, der die Sammlung durchläuft.

**Rückgabe:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IBehavior> - Ein IGenericEnumerator, der zum Durchlaufen der Sammlung verwendet werden kann.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IBehavior> iteratorJava()
```

Gibt einen Java-Iterator für die gesamte Sammlung zurück.

**Rückgabe:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IBehavior> - Ein java.util.Iterator für die gesamte Sammlung.