---
title: IBehaviorCollection
second_title: Aspose.Slides für Android über Java API-Referenz
description: Stellt eine Sammlung von Verhaltenseffekten dar.
type: docs
url: /de/com.aspose.slides/ibehaviorcollection/
---
**Alle implementierten Schnittstellen:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IBehaviorCollection extends System.Collections.Generic.IGenericEnumerable<IBehavior>
```

Stellt eine Sammlung von Verhaltenseffekten dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Gibt ein Verhalten am angegebenen Index zurück. |
| [set_Item(int index, IBehavior value)](#set-Item-int-com.aspose.slides.IBehavior-) | Gibt ein Verhalten am angegebenen Index zurück. |
| [getCount()](#getCount--) | Gibt die Anzahl der Verhaltensweisen in einer Sammlung zurück. |
| [add(IBehavior item)](#add-com.aspose.slides.IBehavior-) | Fügt ein neues Verhalten zu einer Sammlung hinzu. |
| [indexOf(IBehavior item)](#indexOf-com.aspose.slides.IBehavior-) | Bestimmt den Index eines bestimmten Elements in der Liste. |
| [insert(int index, IBehavior item)](#insert-int-com.aspose.slides.IBehavior-) | Fügt ein neues Verhalten in einer Sammlung an dem angegebenen Index ein. |
| [remove(IBehavior item)](#remove-com.aspose.slides.IBehavior-) | Entfernt ein angegebenes Verhalten aus einer Sammlung. |
| [removeAt(int index)](#removeAt-int-) | Entfernt ein Verhalten aus einer Sammlung am angegebenen Index. |
| [clear()](#clear--) | Entfernt alle Verhaltensweisen aus einer Sammlung. |
| [contains(IBehavior item)](#contains-com.aspose.slides.IBehavior-) | Bestimmt, ob [IGenericCollection](../../com.aspose.slides/igenericcollection) einen bestimmten Wert enthält. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IBehavior get_Item(int index)
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
public abstract void set_Item(int index, IBehavior value)
```


Gibt ein Verhalten am angegebenen Index zurück.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Index des zurückzugebenden Verhaltens. |
| value | [IBehavior](../../com.aspose.slides/ibehavior) |  |

### getCount() {#getCount--}
```
public abstract int getCount()
```


Gibt die Anzahl der Verhaltensweisen in einer Sammlung zurück. Nur lesbar int.

**Rückgabe:**
int
### add(IBehavior item) {#add-com.aspose.slides.IBehavior-}
```
public abstract void add(IBehavior item)
```


Fügt ein neues Verhalten zu einer Sammlung hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Hinzuzufügendes Verhalten. |

### indexOf(IBehavior item) {#indexOf-com.aspose.slides.IBehavior-}
```
public abstract int indexOf(IBehavior item)
```


Bestimmt den Index eines bestimmten Elements in der Liste.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Das Objekt, das in der Liste gesucht werden soll. |

**Rückgabe:**
int - Der Index des Elements, falls in der Liste gefunden; andernfalls -1.
### insert(int index, IBehavior item) {#insert-int-com.aspose.slides.IBehavior-}
```
public abstract void insert(int index, IBehavior item)
```


Fügt ein neues Verhalten in einer Sammlung an dem angegebenen Index ein.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Index, an dem das neue Verhalten eingefügt werden soll. |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Verhalten zum Einfügen. |

### remove(IBehavior item) {#remove-com.aspose.slides.IBehavior-}
```
public abstract boolean remove(IBehavior item)
```


Entfernt ein angegebenes Verhalten aus einer Sammlung.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Zu entfernendes Verhalten. |

**Rückgabe:**
boolean - Wahr, wenn ein Verhalten erfolgreich entfernt wurde boolean
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Entfernt ein Verhalten aus einer Sammlung am angegebenen Index.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Index des zu entfernenden Verhaltens. |

### clear() {#clear--}
```
public abstract void clear()
```


Entfernt alle Verhaltensweisen aus einer Sammlung.

### contains(IBehavior item) {#contains-com.aspose.slides.IBehavior-}
```
public abstract boolean contains(IBehavior item)
```


Bestimmt, ob [IGenericCollection](../../com.aspose.slides/igenericcollection) einen bestimmten Wert enthält.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Das Objekt, das im [IGenericCollection](../../com.aspose.slides/igenericcollection) gesucht werden soll. |

**Rückgabe:**
boolean - wahr, wenn das Element im [IGenericCollection](../../com.aspose.slides/igenericcollection) gefunden wird; andernfalls falsch.