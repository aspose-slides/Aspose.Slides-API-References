---
title: IPortionCollection
second_title: Aspose.Slides für Android über die Java-API-Referenz
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
| [get_Item(int index)](#get-Item-int-) | Gibt das Element am angegebenen Index zurück. |
| [getCount()](#getCount--) | Gibt die tatsächlich in der Sammlung enthaltene Elementanzahl zurück. |
| [add(IPortion value)](#add-com.aspose.slides.IPortion-) | Fügt ein Portion am Ende der Sammlung hinzu. |
| [indexOf(IPortion item)](#indexOf-com.aspose.slides.IPortion-) | Bestimmt den Index eines bestimmten Portion in der Sammlung. |
| [insert(int index, IPortion value)](#insert-int-com.aspose.slides.IPortion-) | Fügt ein Portion an dem angegebenen Index in die Sammlung ein. |
| [clear()](#clear--) | Entfernt alle Elemente aus der Sammlung. |
| [contains(IPortion item)](#contains-com.aspose.slides.IPortion-) | Bestimmt, ob das [IGenericCollection](../../com.aspose.slides/igenericcollection) einen bestimmten Wert enthält. |
| [remove(IPortion item)](#remove-com.aspose.slides.IPortion-) | Entfernt das erste Vorkommen eines bestimmten Objekts aus dem [IGenericCollection](../../com.aspose.slides/igenericcollection). |
| [removeAt(int index)](#removeAt-int-) | Entfernt das Element am angegebenen Index der Sammlung. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IPortion get_Item(int index)
```

Gibt das Element am angegebenen Index zurück.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int |  |

**Rückgabe:**
[IPortion](../../com.aspose.slides/iportion)
### getCount() {#getCount--}
```
public abstract int getCount()
```

Gibt die tatsächlich in der Sammlung enthaltene Elementanzahl zurück. Nur-Lese int.

**Rückgabe:**
int
### add(IPortion value) {#add-com.aspose.slides.IPortion-}
```
public abstract void add(IPortion value)
```

Fügt ein Portion am Ende der Sammlung hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IPortion](../../com.aspose.slides/iportion) | Das Portion, das am Ende der Sammlung hinzugefügt werden soll. |
### indexOf(IPortion item) {#indexOf-com.aspose.slides.IPortion-}
```
public abstract int indexOf(IPortion item)
```

Bestimmt den Index eines bestimmten Portion in der Sammlung.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | Der Portion, der in der Sammlung gesucht werden soll. |

**Rückgabe:**
int – Der Index von item, falls er in der Sammlung gefunden wird; sonst -1.
### insert(int index, IPortion value) {#insert-int-com.aspose.slides.IPortion-}
```
public abstract void insert(int index, IPortion value)
```

Fügt ein Portion an dem angegebenen Index in die Sammlung ein.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der nullbasierte Index, an dem Portion eingefügt werden soll. |
| value | [IPortion](../../com.aspose.slides/iportion) | Das einzufügende Portion. |
### clear() {#clear--}
```
public abstract void clear()
```

Entfernt alle Elemente aus der Sammlung.

### contains(IPortion item) {#contains-com.aspose.slides.IPortion-}
```
public abstract boolean contains(IPortion item)
```

Bestimmt, ob das [IGenericCollection](../../com.aspose.slides/igenericcollection) einen bestimmten Wert enthält.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | Das Objekt, das im [IGenericCollection](../../com.aspose.slides/igenericcollection) gesucht werden soll. |

**Rückgabe:**
boolean – true, wenn item im [IGenericCollection](../../com.aspose.slides/igenericcollection) gefunden wird; sonst false.
### remove(IPortion item) {#remove-com.aspose.slides.IPortion-}
```
public abstract boolean remove(IPortion item)
```

Entfernt das erste Vorkommen eines bestimmten Objekts aus dem [IGenericCollection](../../com.aspose.slides/igenericcollection).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | Das zu entfernende Objekt aus dem [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Rückgabe:**
boolean – true, wenn item erfolgreich aus dem [IGenericCollection](../../com.aspose.slides/igenericcollection) entfernt wurde; sonst false. Diese Methode gibt ebenfalls false zurück, wenn item im ursprünglichen [IGenericCollection](../../com.aspose.slides/igenericcollection) nicht gefunden wird.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Entfernt das Element am angegebenen Index der Sammlung.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der nullbasierte Index des zu entfernenden Elements. |