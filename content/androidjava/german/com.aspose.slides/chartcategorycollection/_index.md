---
title: ChartCategoryCollection
second_title: Aspose.Slides für Android über die Java-API-Referenz
description: Repräsentiert eine Sammlung von
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

Repräsentiert eine Sammlung von [ChartCategory](../../com.aspose.slides/chartcategory)
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Gibt das Element am angegebenen Index zurück. |
| [getUseCells()](#getUseCells--) | Wenn true dann wird das Arbeitsblatt zur Speicherung von Kategorien verwendet (dieser Fall unterstützt mehrstufige Kategorien). |
| [setUseCells(boolean value)](#setUseCells-boolean-) | Wenn true dann wird das Arbeitsblatt zur Speicherung von Kategorien verwendet (dieser Fall unterstützt mehrstufige Kategorien). |
| [getGroupingLevelCount()](#getGroupingLevelCount--) | Gibt die Anzahl der verwendeten Kategoriegruppierungsebenen zurück. |
| [add(IChartDataCell chartDataCell)](#add-com.aspose.slides.IChartDataCell-) | Wenn die Kategorie in der Sammlung existiert, wird sie zurückgegeben. |
| [add(Object value)](#add-java.lang.Object-) | Erstellt ein neues [ChartCategory](../../com.aspose.slides/chartcategory) aus dem Wert und fügt es der Sammlung hinzu. |
| [indexOf(IChartCategory value)](#indexOf-com.aspose.slides.IChartCategory-) | Durchsucht das angegebene [ChartCategory](../../com.aspose.slides/chartcategory) und gibt den nullbasierten Index des ersten Vorkommens in der gesamten Collection zurück. |
| [remove(IChartCategory value)](#remove-com.aspose.slides.IChartCategory-) | Entfernt den angegebenen Wert. |
| [removeAt(int index)](#removeAt-int-) | Entfernt das Element am angegebenen Index. |
| [clear()](#clear--) | Entfernt alle Elemente aus der Sammlung. |
| [iterator()](#iterator--) | Gibt einen Enumerator zurück, der die Sammlung durchläuft. |
| [iteratorJava()](#iteratorJava--) | Gibt einen Java-Iterator für die gesamte Sammlung zurück. |
| [size()](#size--) | Gibt die Anzahl der Elemente in der Sammlung zurück. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Kopiert alle Elemente der Sammlung in das angegebene Array. |
| [isSynchronized()](#isSynchronized--) | Gibt einen Wert zurück, der angibt, ob der Zugriff auf die List synchronisiert ist (Thread-sicher). |
| [getSyncRoot()](#getSyncRoot--) | Gibt ein Objekt zurück, das zum Synchronisieren des Zugriffs auf die Sammlung verwendet werden kann. |

### get_Item(int index) {#get-Item-int-}
```
public final IChartCategory get_Item(int index)
```

Gibt das Element am angegebenen Index zurück.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int |  |

**Rückgabewert:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - Das Element am angegebenen Index.

### getUseCells() {#getUseCells--}
```
public final boolean getUseCells()
```

Wenn true dann wird das Arbeitsblatt zur Speicherung von Kategorien verwendet (dieser Fall unterstützt mehrstufige Kategorien). Wenn false dann wird das Arbeitsblatt NICHT zur Speicherung von Werten verwendet (und dieser Fall unterstützt keine mehrstufigen Kategorien). Lese/Schreib boolesch.

**Rückgabewert:**
boolean

### setUseCells(boolean value) {#setUseCells-boolean-}
```
public final void setUseCells(boolean value)
```

Wenn true dann wird das Arbeitsblatt zur Speicherung von Kategorien verwendet (dieser Fall unterstützt mehrstufige Kategorien). Wenn false dann wird das Arbeitsblatt NICHT zur Speicherung von Werten verwendet (und dieser Fall unterstützt keine mehrstufigen Kategorien). Lese/Schreib boolesch.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getGroupingLevelCount() {#getGroupingLevelCount--}
```
public final int getGroupingLevelCount()
```

Gibt die Anzahl der verwendeten Kategoriegruppierungsebenen zurück. Ist bei mehrstufigen Kategorien größer als eins. Nur lesbar int.

**Rückgabewert:**
int

### add(IChartDataCell chartDataCell) {#add-com.aspose.slides.IChartDataCell-}
```
public final IChartCategory add(IChartDataCell chartDataCell)
```

Wenn die Kategorie in der Sammlung existiert, wird sie zurückgegeben. Andernfalls wird eine neue Diagrammkategorie aus [IChartDataCell](../../com.aspose.slides/ichartdatacell) erstellt und der Sammlung hinzugefügt.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| chartDataCell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Zelle, die zum Erstellen der Diagrammkategorie verwendet wird. |

**Rückgabewert:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - Hinzugefügte oder vorhandene Kategorie.

### add(Object value) {#add-java.lang.Object-}
```
public final IChartCategory add(Object value)
```

Erstellt ein neues [ChartCategory](../../com.aspose.slides/chartcategory) aus dem Wert und fügt es der Sammlung hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.Object | Der Wert. |

--------------------
Diese Methode fügt ein Arbeitsblatt mit dem Namen AUTO_DATA hinzu und fügt dort alle Werte ein. Wenn Sie [ChartDataWorkbook](../../com.aspose.slides/chartdataworkbook) zum Hinzufügen oder Bearbeiten von Zellwerten verwenden, stellen Sie sicher, dass Sie dieses Arbeitsblatt nicht verwenden. Die maximale Anzahl an über diese Methode hinzugefügten Werten darf 16711680 nicht überschreiten |

**Rückgabewert:**
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

**Rückgabewert:**
int - Der nullbasierte Index des ersten Vorkommens des Werts in der gesamten CollectionBase, falls gefunden; sonst -1.

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

Gibt einen Enumerator zurück, der die Sammlung durchläuft.

**Rückgabewert:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartCategory> - Ein IGenericEnumerator, der zum Durchlaufen der Sammlung verwendet werden kann.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartCategory> iteratorJava()
```

Gibt einen Java-Iterator für die gesamte Sammlung zurück.

**Rückgabewert:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartCategory> - Ein java.util.Iterator für die gesamte Sammlung.

### size() {#size--}
```
public final int size()
```

Gibt die Anzahl der Elemente in der Sammlung zurück. Nur lesbar int.

**Rückgabewert:**
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

Gibt einen Wert zurück, der angibt, ob der Zugriff auf die List synchronisiert ist (Thread-sicher). Nur lesbar boolesch.

**Rückgabewert:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Gibt ein Objekt zurück, das zum Synchronisieren des Zugriffs auf die Sammlung verwendet werden kann. Nur lesbar Object.

Gibt eine Synchronisationswurzel zurück. Nur lesbar Object.

**Rückgabewert:**
java.lang.Object