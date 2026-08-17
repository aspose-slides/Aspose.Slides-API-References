---
title: BehaviorCollection
second_title: Aspose.Slides für Java API Referenz
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
| [isReadOnly()](#isReadOnly--) | Ruft einen Wert ab, der angibt, ob das [IGenericCollection](../../com.aspose.slides/igenericcollection) schreibgeschützt ist. |
| [add(IBehavior item)](#add-com.aspose.slides.IBehavior-) | Fügt einer Sammlung ein neues Verhalten hinzu. |
| [indexOf(IBehavior item)](#indexOf-com.aspose.slides.IBehavior-) | Bestimmt den Index eines bestimmten Elements in der Liste. |
| [insert(int index, IBehavior item)](#insert-int-com.aspose.slides.IBehavior-) | Fügt ein neues Verhalten an einem angegebenen Index in die Sammlung ein. |
| [copyTo(IBehavior[] array, int arrayIndex)](#copyTo-com.aspose.slides.IBehavior---int-) | Kopiert die Elemente des [IGenericCollection](../../com.aspose.slides/igenericcollection) in ein Array, beginnend bei einem bestimmten Array-Index. |
| [remove(IBehavior item)](#remove-com.aspose.slides.IBehavior-) | Entfernt das angegebene Verhalten aus einer Sammlung. |
| [removeAt(int index)](#removeAt-int-) | Entfernt ein Verhalten aus einer Sammlung am angegebenen Index. |
| [clear()](#clear--) | Entfernt alle Verhaltensweisen aus einer Sammlung. |
| [contains(IBehavior item)](#contains-com.aspose.slides.IBehavior-) | Bestimmt, ob [IGenericCollection](../../com.aspose.slides/igenericcollection) einen bestimmten Wert enthält. |
| [get_Item(int index)](#get-Item-int-) | Gibt ein Verhalten am angegebenen Index zurück. |
| [set_Item(int index, IBehavior value)](#set-Item-int-com.aspose.slides.IBehavior-) | Legt ein Verhalten am angegebenen Index fest. |
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

Ruft einen Wert ab, der angibt, ob das [IGenericCollection](../../com.aspose.slides/igenericcollection) schreibgeschützt ist. Nur lesbar boolean.

**Rückgabe:**
boolean – true, wenn das [IGenericCollection](../../com.aspose.slides/igenericcollection) schreibgeschützt ist; sonst false.
### add(IBehavior item) {#add-com.aspose.slides.IBehavior-}
```
public final void add(IBehavior item)
```

Fügt einer Sammlung ein neues Verhalten hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Hinzuzufügendes Verhalten. |
### indexOf(IBehavior item) {#indexOf-com.aspose.slides.IBehavior-}
```
public final int indexOf(IBehavior item)
```

Bestimmt den Index eines bestimmten Elements in der Liste.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Das zu suchende Objekt in der Liste. |

**Rückgabe:**
int – Der Index des Elements, falls im List gefunden; sonst -1.
### insert(int index, IBehavior item) {#insert-int-com.aspose.slides.IBehavior-}
```
public final void insert(int index, IBehavior item)
```

Fügt ein neues Verhalten an einem angegebenen Index in die Sammlung ein.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Index, an dem das neue Verhalten eingefügt werden soll. |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Einzufügenendes Verhalten. |
### copyTo(IBehavior[] array, int arrayIndex) {#copyTo-com.aspose.slides.IBehavior---int-}
```
public final void copyTo(IBehavior[] array, int arrayIndex)
```

Kopiert die Elemente des [IGenericCollection](../../com.aspose.slides/igenericcollection) in ein Array, beginnend bei einem bestimmten Array-Index.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| array | [IBehavior\[\]](../../com.aspose.slides/ibehavior) | Das eindimensionale Array, das das Ziel der von [IGenericCollection](../../com.aspose.slides/igenericcollection) kopierten Elemente ist. Das Array muss nullbasiert indiziert sein. |
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

Entfernt ein Verhalten aus einer Sammlung am angegebenen Index.

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
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Das zu suchende Objekt im [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Rückgabe:**
boolean – true, wenn das Element im [IGenericCollection](../../com.aspose.slides/igenericcollection) gefunden wird; sonst false.
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
[IBehavior](../../com.aspose.slides/ibehavior) – Animationsverhalten.
### set_Item(int index, IBehavior value) {#set-Item-int-com.aspose.slides.IBehavior-}
```
public final void set_Item(int index, IBehavior value)
```

Legt ein Verhalten am angegebenen Index fest.

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