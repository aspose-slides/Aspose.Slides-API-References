---
title: IBehaviorCollection
second_title: Aspose.Slides für Java API Referenz
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
| [add(IBehavior item)](#add-com.aspose.slides.IBehavior-) | Fügt einer Sammlung ein neues Verhalten hinzu. |
| [indexOf(IBehavior item)](#indexOf-com.aspose.slides.IBehavior-) | Ermittelt den Index eines bestimmten Elements in der Liste. |
| [insert(int index, IBehavior item)](#insert-int-com.aspose.slides.IBehavior-) | Fügt ein neues Verhalten in eine Sammlung an dem angegebenen Index ein. |
| [remove(IBehavior item)](#remove-com.aspose.slides.IBehavior-) | Entfernt das angegebene Verhalten aus einer Sammlung. |
| [removeAt(int index)](#removeAt-int-) | Entfernt ein Verhalten aus einer Sammlung am angegebenen Index. |
| [clear()](#clear--) | Entfernt alle Verhaltensweisen aus einer Sammlung. |
| [contains(IBehavior item)](#contains-com.aspose.slides.IBehavior-) | Ermittelt, ob [IGenericCollection](../../com.aspose.slides/igenericcollection) einen bestimmten Wert enthält. |

### get_Item(int index) {#get-Item-int-}
```
public abstract IBehavior get_Item(int index)
```

Gibt ein Verhalten am angegebenen Index zurück.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Index des zurückzugebenden Verhaltens. |

**Rückgabewert:**
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

Gibt die Anzahl der Verhaltensweisen in einer Sammlung zurück. Nur lesbarer int.

**Rückgabewert:**
int

### add(IBehavior item) {#add-com.aspose.slides.IBehavior-}
```
public abstract void add(IBehavior item)
```

Fügt einer Sammlung ein neues Verhalten hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Zu hinzuzufügendes Verhalten. |

### indexOf(IBehavior item) {#indexOf-com.aspose.slides.IBehavior-}
```
public abstract int indexOf(IBehavior item)
```

Ermittelt den Index eines bestimmten Elements in der Liste.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Das Objekt, das in der Liste gesucht werden soll. |

**Rückgabewert:**
int - Der Index des Elements, wenn es in der Liste gefunden wurde; andernfalls -1.

### insert(int index, IBehavior item) {#insert-int-com.aspose.slides.IBehavior-}
```
public abstract void insert(int index, IBehavior item)
```

Fügt ein neues Verhalten in eine Sammlung am angegebenen Index ein.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Index, an dem das neue Verhalten eingefügt werden soll. |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Einzufügenendes Verhalten. |

### remove(IBehavior item) {#remove-com.aspose.slides.IBehavior-}
```
public abstract boolean remove(IBehavior item)
```

Entfernt das angegebene Verhalten aus einer Sammlung.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Zu entfernendes Verhalten. |

**Rückgabewert:**
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

Ermittelt, ob [IGenericCollection](../../com.aspose.slides/igenericcollection) einen bestimmten Wert enthält.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Das Objekt, das im [IGenericCollection](../../com.aspose.slides/igenericcollection) gesucht werden soll. |

**Rückgabewert:**
boolean - wahr, wenn das Element im [IGenericCollection](../../com.aspose.slides/igenericcollection) gefunden wird; andernfalls falsch.