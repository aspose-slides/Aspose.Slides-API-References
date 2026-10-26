---
title: ChartCategoryCollection
second_title: Aspose.Slides für Java API-Referenz
description: Stellt eine Sammlung von dar
type: docs
url: /de/com.aspose.slides/chartcategorycollection/
---
**Vererbung:**
java.lang.Object, com.aspose.slides.DomObject

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)
```
public class ChartCategoryCollection extends DomObject<ChartData> implements IChartCategoryCollection
```

Stellt eine Sammlung von [ChartCategory](../../com.aspose.slides/chartcategory) dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Ruft das Element am angegebenen Index ab. |
| [getUseCells()](#getUseCells--) | Wenn true, wird das Arbeitsblatt zum Speichern von Kategorien verwendet (dieser Fall unterstützt mehrstufige Kategorien). |
| [setUseCells(boolean value)](#setUseCells-boolean-) | Wenn true, wird das Arbeitsblatt zum Speichern von Kategorien verwendet (dieser Fall unterstützt mehrstufige Kategorien). |
| [getGroupingLevelCount()](#getGroupingLevelCount--) | Gibt die Anzahl der verwendeten Gruppierungsebenen für Kategorien zurück. |
| [add(IChartDataCell chartDataCell)](#add-com.aspose.slides.IChartDataCell-) | Wenn die Kategorie in der Sammlung existiert, wird sie zurückgegeben. |
| [add(Object value)](#add-java.lang.Object-) | Erstellt ein neues [ChartCategory](../../com.aspose.slides/chartcategory) aus dem Wert und fügt es der Sammlung hinzu. |
| [indexOf(IChartCategory value)](#indexOf-com.aspose.slides.IChartCategory-) | Durchsucht das angegebene [ChartCategory](../../com.aspose.slides/chartcategory) und gibt den nullbasierten Index des ersten Vorkommens in der gesamten Collection zurück. |
| [remove(IChartCategory value)](#remove-com.aspose.slides.IChartCategory-) | Entfernt den angegebenen Wert. |
| [removeAt(int index)](#removeAt-int-) | Entfernt das Element am angegebenen Index. |
| [clear()](#clear--) | Entfernt alle Elemente aus der Sammlung. |
| [iterator()](#iterator--) | Gibt einen Enumerator zurück, der durch die Sammlung iteriert. |
| [iteratorJava()](#iteratorJava--) | Gibt einen Java-Iterator für die gesamte Sammlung zurück. |
| [size()](#size--) | Gibt die Anzahl der Elemente in der Sammlung zurück. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Kopiert alle Elemente der Sammlung in das angegebene Array. |
| [isSynchronized()](#isSynchronized--) | Gibt einen Wert zurück, der angibt, ob der Zugriff auf die Liste synchronisiert (thread-safe) ist. |
| [getSyncRoot()](#getSyncRoot--) | Gibt ein Objekt zurück, das zum Synchronisieren des Zugriffs auf die Sammlung verwendet werden kann. |

### get_Item(int index) {#get-Item-int-}
```
public final IChartCategory get_Item(int index)
```

Ruft das Element am angegebenen Index ab.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int |  |

**Rückgabe:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - Das Element am angegebenen Index.

### getUseCells() {#getUseCells--}
```
public final boolean getUseCells()
```

Wenn true, wird das Arbeitsblatt zum Speichern von Kategorien verwendet (dieser Fall unterstützt mehrstufige Kategorien). Wenn false, wird das Arbeitsblatt NICHT zum Speichern von Werten verwendet (und dieser Fall unterstützt keine mehrstufigen Kategorien). Lese/Schreib-Boolean.

**Rückgabe:**
boolean

### setUseCells(boolean value) {#setUseCells-boolean-}
```
public final void setUseCells(boolean value)
```

Wenn true, wird das Arbeitsblatt zum Speichern von Kategorien verwendet (dieser Fall unterstützt mehrstufige Kategorien). Wenn false, wird das Arbeitsblatt NICHT zum Speichern von Werten verwendet (und dieser Fall unterstützt keine mehrstufigen Kategorien). Lese/Schreib-Boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getGroupingLevelCount() {#getGroupingLevelCount--}
```
public final int getGroupingLevelCount()
```

Gibt die Anzahl der verwendeten Gruppierungsebenen für Kategorien zurück. Ist größer als eins für mehrstufige Kategorien. Nur-Lese-int.

**Rückgabe:**
int

### add(IChartDataCell chartDataCell) {#add-com.aspose.slides.IChartDataCell-}
```
public final IChartCategory add(IChartDataCell chartDataCell)
```

Wenn die Kategorie in der Sammlung existiert, wird sie zurückgegeben. Andernfalls wird eine neue Diagrammkategorie aus [IChartDataCell](../../com.aspose.slides/ichartdatacell) erstellt und zur Sammlung hinzugefügt.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| chartDataCell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Zelle, die zur Erstellung der Diagrammkategorie verwendet wird. |

**Rückgabe:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - Hinzugefügte oder vorhandene Kategorie.

### add(Object value) {#add-java.lang.Object-}
```
public final IChartCategory add(Object value)
```

Erstellt ein neues [ChartCategory](../../com.aspose.slides/chartcategory) aus dem Wert und fügt es der Sammlung hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.Object | Der Wert.

--------------------

Diese Methode fügt ein Arbeitsblatt mit dem Namen AUTO_DATA hinzu und fügt dort alle Werte ein. Wenn Sie [ChartDataWorkbook](../../com.aspose.slides/chartdataworkbook) zum Hinzufügen oder Bearbeiten von Zellenwerten verwenden, stellen Sie sicher, dass Sie dieses Arbeitsblatt nicht verwenden. Die maximale Anzahl von Werten, die mit dieser Methode hinzugefügt werden dürfen, darf 16711680 nicht überschreiten |

**Rückgabe:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - Hinzugefügtes [IChartCategory](../../com.aspose.slides/ichartcategory).

### indexOf(IChartCategory value) {#indexOf-com.aspose.slides.IChartCategory-}
```
public final int indexOf(IChartCategory value)
```

Durchsucht das angegebene [ChartCategory](../../com.aspose.slides/chartcategory) und gibt den nullbasierten Index des ersten Vorkommens in der gesamten Collection zurück.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IChartCategory](../../com.aspose.slides/ichartcategory) | Diagrammkategorie. |

**Rückgabe:**
int - Der nullbasierte Index des ersten Vorkommens von value in der gesamten CollectionBase, falls gefunden; andernfalls -1.

### remove(IChartCategory value) {#remove-com.aspose.slides.IChartCategory-}
```
public final void remove(IChartCategory value)
```

Entfernt den angegebenen Wert.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IChartCategory](../../com.aspose.slides/ichartcategory) | Der Wert. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Entfernt das Element am angegebenen Index.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Index einer zu entfernenden Kategorie. |

### clear() {#clear--}
```
public final void clear()
```

Entfernt alle Elemente aus der Sammlung.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartCategory> iterator()
```

Gibt einen Enumerator zurück, der durch die Sammlung iteriert.

**Rückgabe:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartCategory> - Ein IGenericEnumerator, der zum Iterieren durch die Sammlung verwendet werden kann.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartCategory> iteratorJava()
```

Gibt einen Java-Iterator für die gesamte Sammlung zurück.

**Rückgabe:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartCategory> - Ein java.util.Iterator für die gesamte Sammlung.

### size() {#size--}
```
public final int size()
```

Gibt die Anzahl der Elemente in der Sammlung zurück. Nur-Lese-int.

**Rückgabe:**
int

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Kopiert alle Elemente der Sammlung in das angegebene Array.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Ziel-Array. |
| index | int | Startindex im Array. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Gibt einen Wert zurück, der angibt, ob der Zugriff auf die Liste synchronisiert (thread-safe) ist. Nur-Lese-boolean.

**Rückgabe:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Gibt ein Objekt zurück, das zum Synchronisieren des Zugriffs auf die Sammlung verwendet werden kann. Nur-Lese-Object.

Gibt eine Synchronisationswurzel zurück. Nur-Lese-Object.

**Rückgabe:**
java.lang.Object