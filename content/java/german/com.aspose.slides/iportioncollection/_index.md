---
title: IPortionCollection
second_title: Aspose.Slides für Java API Referenz
description: Stellt eine Sammlung von Portionen dar.
type: docs
url: /de/com.aspose.slides/iportioncollection/
---
**Alle implementierten Schnittstellen:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IPortionCollection extends System.Collections.Generic.IGenericEnumerable<IPortion>
```

Stellt eine Sammlung von Portionen dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Ruft das Element am angegebenen Index ab. |
| [getCount()](#getCount--) | Gibt die tatsächlich in der Sammlung enthaltene Anzahl von Elementen zurück. |
| [add(IPortion value)](#add-com.aspose.slides.IPortion-) | Fügt ein Portion am Ende der Sammlung hinzu. |
| [indexOf(IPortion item)](#indexOf-com.aspose.slides.IPortion-) | Bestimmt den Index einer bestimmten Portion in der Sammlung. |
| [insert(int index, IPortion value)](#insert-int-com.aspose.slides.IPortion-) | Fügt ein Portion in die Sammlung an dem angegebenen Index ein. |
| [clear()](#clear--) | Entfernt alle Elemente aus der Sammlung. |
| [contains(IPortion item)](#contains-com.aspose.slides.IPortion-) | Bestimmt, ob [IGenericCollection](../../com.aspose.slides/igenericcollection) einen bestimmten Wert enthält. |
| [remove(IPortion item)](#remove-com.aspose.slides.IPortion-) | Entfernt das erste Vorkommen eines bestimmten Objekts aus dem [IGenericCollection](../../com.aspose.slides/igenericcollection). |
| [removeAt(int index)](#removeAt-int-) | Entfernt das Element am angegebenen Index aus der Sammlung. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IPortion get_Item(int index)
```

Ruft das Element am angegebenen Index ab.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int |  |

**Rückgabewert:**
[IPortion](../../com.aspose.slides/iportion)
### getCount() {#getCount--}
```
public abstract int getCount()
```

Gibt die tatsächlich in der Sammlung enthaltene Anzahl von Elementen zurück. Nur-Lese int.

**Rückgabewert:**
int
### add(IPortion value) {#add-com.aspose.slides.IPortion-}
```
public abstract void add(IPortion value)
```

Fügt ein Portion am Ende der Sammlung hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IPortion](../../com.aspose.slides/iportion) | Die Portion, die am Ende der Sammlung hinzugefügt werden soll. |

### indexOf(IPortion item) {#indexOf-com.aspose.slides.IPortion-}
```
public abstract int indexOf(IPortion item)
```

Bestimmt den Index einer bestimmten Portion in der Sammlung.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | Die Portion, die in der Sammlung gesucht werden soll. |

**Rückgabewert:**
int - Der Index des Elements, falls es in der Sammlung gefunden wurde; andernfalls -1.
### insert(int index, IPortion value) {#insert-int-com.aspose.slides.IPortion-}
```
public abstract void insert(int index, IPortion value)
```

Fügt ein Portion in die Sammlung an dem angegebenen Index ein.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der nullbasierte Index, an dem die Portion eingefügt werden soll. |
| value | [IPortion](../../com.aspose.slides/iportion) | Die einzufügende Portion. |

### clear() {#clear--}
```
public abstract void clear()
```

Entfernt alle Elemente aus der Sammlung.

### contains(IPortion item) {#contains-com.aspose.slides.IPortion-}
```
public abstract boolean contains(IPortion item)
```

Bestimmt, ob [IGenericCollection](../../com.aspose.slides/igenericcollection) einen bestimmten Wert enthält.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | Das zu findende Objekt im [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Rückgabewert:**
boolean - true, wenn das Element im [IGenericCollection](../../com.aspose.slides/igenericcollection) gefunden wurde; sonst false.
### remove(IPortion item) {#remove-com.aspose.slides.IPortion-}
```
public abstract boolean remove(IPortion item)
```

Entfernt das erste Vorkommen eines bestimmten Objekts aus dem [IGenericCollection](../../com.aspose.slides/igenericcollection).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | Das zu entfernende Objekt aus dem [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Rückgabewert:**
boolean - true, wenn das Element erfolgreich aus dem [IGenericCollection](../../com.aspose.slides/igenericcollection) entfernt wurde; sonst false. Diese Methode gibt ebenfalls false zurück, wenn das Element im ursprünglichen [IGenericCollection](../../com.aspose.slides/igenericcollection) nicht gefunden wurde.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Entfernt das Element am angegebenen Index aus der Sammlung.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der nullbasierte Index des zu entfernenden Elements. |
