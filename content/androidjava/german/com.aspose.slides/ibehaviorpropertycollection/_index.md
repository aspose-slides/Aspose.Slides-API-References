---
title: IBehaviorPropertyCollection
second_title: Aspose.Slides für Android über Java API Reference
description: Stellt die Timing-Eigenschaften für das Effektverhalten dar.
type: docs
url: /de/com.aspose.slides/ibehaviorpropertycollection/
---
**Alle implementierten Schnittstellen:**
com.aspose.ms.System.Collections.Generic.IGenericList
```
public interface IBehaviorPropertyCollection extends System.Collections.Generic.IGenericList<IBehaviorProperty>
```

Stellt die Timing-Eigenschaften für das Effektverhalten dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [add(String propertyValue)](#add-java.lang.String-) | Fügt der Sammlung eine neue Eigenschaft hinzu. |
| [indexOf(String propertyValue)](#indexOf-java.lang.String-) | Ermittelt den Index eines bestimmten Elements anhand des Eigenschaftswerts in der Liste. |
| [insert(int index, String propertyValue)](#insert-int-java.lang.String-) | Fügt an dem angegebenen Index eine neue Eigenschaft (mit dem angegebenen Eigenschaftswert) in die Sammlung ein. |
| [remove(String propertyValue)](#remove-java.lang.String-) | Entfernt die angegebene Eigenschaft aus der Sammlung. |
| [contains(String propertyValue)](#contains-java.lang.String-) | Ermittelt, ob [IGenericCollection](../../com.aspose.slides/igenericcollection) einen bestimmten Wert enthält. |
### add(String propertyValue) {#add-java.lang.String-}
```
public abstract void add(String propertyValue)
```

Fügt der Sammlung eine neue Eigenschaft hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| propertyValue | java.lang.String | Wert der hinzuzufügenden Eigenschaft. |

### indexOf(String propertyValue) {#indexOf-java.lang.String-}
```
public abstract int indexOf(String propertyValue)
```

Ermittelt den Index eines bestimmten Elements anhand des Eigenschaftswerts in der Liste.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| propertyValue | java.lang.String | Wert der Eigenschaft |

**Rückgabewert:**
int - Der Index der Eigenschaft mit dem angegebenen Wert
### insert(int index, String propertyValue) {#insert-int-java.lang.String-}
```
public abstract void insert(int index, String propertyValue)
```

Fügt an dem angegebenen Index eine neue Eigenschaft (mit dem angegebenen Eigenschaftswert) in die Sammlung ein.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Index, an dem eine neue Eigenschaft eingefügt werden soll. |
| propertyValue | java.lang.String | Wert der hinzuzufügenden Eigenschaft. |

### remove(String propertyValue) {#remove-java.lang.String-}
```
public abstract boolean remove(String propertyValue)
```

Entfernt die angegebene Eigenschaft aus der Sammlung.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| propertyValue | java.lang.String | Wert der zu entfernenden Eigenschaft. |

**Rückgabewert:**
boolean - Wahr, wenn eine Eigenschaft erfolgreich entfernt wurde
### contains(String propertyValue) {#contains-java.lang.String-}
```
public abstract boolean contains(String propertyValue)
```

Ermittelt, ob [IGenericCollection](../../com.aspose.slides/igenericcollection) einen bestimmten Wert enthält.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| propertyValue | java.lang.String | Wert der Eigenschaft, die im [IGenericCollection](../../com.aspose.slides/igenericcollection) gesucht werden soll. |

**Rückgabewert:**
boolean - wahr, wenn propertyValue im [IGenericCollection](../../com.aspose.slides/igenericcollection) gefunden wird; andernfalls false.