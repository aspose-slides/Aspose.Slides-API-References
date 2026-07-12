---
title: PieSplitCustomPointCollection
second_title: Aspose.Slides für Android über Java API-Referenz
description: Stellt eine Sammlung von Punkten dar, die für den Trennpunkt in einem Balken-zu-Kuchen- oder Kuchen-zu-Kuchen-Diagramm mit einer benutzerdefinierten Aufteilung verwendet werden.
type: docs
url: /de/com.aspose.slides/piesplitcustompointcollection/
---
**Vererbung:**  
java.lang.Object

**Alle implementierten Schnittstellen:**  
[com.aspose.slides.IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)  
```
public class PieSplitCustomPointCollection implements IPieSplitCustomPointCollection
```

Stellt eine Sammlung von Punkten für den Trennpunkt in einem Balken-zu-Kuchen- oder Kuchen-zu-Kuchen-Diagramm mit einer benutzerdefinierten Aufteilung dar.

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Gibt den Diagrammdatenpunkt für den angegebenen Index zurück. |
| [add(int dataPointIndex)](#add-int-) | Fügt einen Datenpunkt anhand seines Indexes in der übergeordneten Serien-Punktesammlung hinzu. |
| [addItem(IChartDataPoint dataPoint)](#addItem-com.aspose.slides.IChartDataPoint-) | Fügt einen Datenpunkt zur Sammlung hinzu. |
| [removeItem(IChartDataPoint dataPoint)](#removeItem-com.aspose.slides.IChartDataPoint-) | Entfernt ein Element aus der Sammlung. |
| [remove(int dataPointIndex)](#remove-int-) | Entfernt ein Element aus der Sammlung anhand seines Indexes in der übergeordneten Serien-Punktesammlung. |
| [clear()](#clear--) | Entfernt alle Elemente aus dem [IGenericCollection](../../com.aspose.slides/igenericcollection). |
| [containsItem(IChartDataPoint item)](#containsItem-com.aspose.slides.IChartDataPoint-) | Bestimmt, ob [IGenericCollection](../../com.aspose.slides/igenericcollection) einen bestimmten Wert enthält. |
| [copyToTArray(IChartDataPoint[] array, int arrayIndex)](#copyToTArray-com.aspose.slides.IChartDataPoint---int-) | Kopiert die Elemente von [IGenericCollection](../../com.aspose.slides/igenericcollection) in ein Array, beginnend bei einem bestimmten Array-Index. |
| [size()](#size--) | Gibt die Anzahl der Diagrammdatenpunkte zurück oder legt sie fest. |
| [isReadOnly()](#isReadOnly--) | Gibt einen Wert zurück, der angibt, ob [IGenericCollection](../../com.aspose.slides/igenericcollection) schreibgeschützt ist. |
| [isSynchronized()](#isSynchronized--) | Gibt einen Wert zurück, der angibt, ob der Zugriff auf die Sammlung synchronisiert (thread-sicher) ist. |
| [getSyncRoot()](#getSyncRoot--) | Gibt die Synchronisationswurzel zurück. |
| [iterator()](#iterator--) | Gibt einen Enumerator zurück, der durch die Sammlung iteriert. |
| [iteratorJava()](#iteratorJava--) | Gibt einen Java-Iterator für die gesamte Sammlung zurück. |

### get_Item(int index) {#get-Item-int-}
```
public final IChartDataPoint get_Item(int index)
```

Gibt den Diagrammdatenpunkt für den angegebenen Index zurück.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Index. |

**Rückgabe:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Diagrammdatenpunkt.

### add(int dataPointIndex) {#add-int-}
```
public final void add(int dataPointIndex)
```

Fügt einen Datenpunkt anhand seines Indexes in der übergeordneten Serien-Punktesammlung hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| dataPointIndex | int | Index des Datenpunkts in der übergeordneten Serien-Punktesammlung. |

### addItem(IChartDataPoint dataPoint) {#addItem-com.aspose.slides.IChartDataPoint-}
```
public void addItem(IChartDataPoint dataPoint)
```

Fügt einen Datenpunkt zur Sammlung hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| dataPoint | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | Der hinzuzufügende Datenpunkt. |

### removeItem(IChartDataPoint dataPoint) {#removeItem-com.aspose.slides.IChartDataPoint-}
```
public boolean removeItem(IChartDataPoint dataPoint)
```

Entfernt ein Element aus der Sammlung.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| dataPoint | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | Der zu entfernende Datenpunkt. |

**Rückgabe:**
boolean - true, wenn das Element erfolgreich entfernt wurde; andernfalls false. Diese Methode gibt ebenfalls false zurück, wenn das Element nicht in der System.Collections.Generic.List{T} gefunden wurde.

### remove(int dataPointIndex) {#remove-int-}
```
public final void remove(int dataPointIndex)
```

Entfernt ein Element aus der Sammlung anhand seines Indexes in der übergeordneten Serien-Punktesammlung.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| dataPointIndex | int | Index des Datenpunkts in der übergeordneten Serien-Punktesammlung. |

### clear() {#clear--}
```
public final void clear()
```

Entfernt alle Elemente aus dem [IGenericCollection](../../com.aspose.slides/igenericcollection).

### containsItem(IChartDataPoint item) {#containsItem-com.aspose.slides.IChartDataPoint-}
```
public boolean containsItem(IChartDataPoint item)
```

Bestimmt, ob [IGenericCollection](../../com.aspose.slides/igenericcollection) einen bestimmten Wert enthält.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| item | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | Das Objekt, das in [IGenericCollection](../../com.aspose.slides/igenericcollection) gesucht werden soll. |

**Rückgabe:**
boolean - true, wenn das Element in [IGenericCollection](../../com.aspose.slides/igenericcollection) gefunden wurde; andernfalls false.

### copyToTArray(IChartDataPoint[] array, int arrayIndex) {#copyToTArray-com.aspose.slides.IChartDataPoint---int-}
```
public void copyToTArray(IChartDataPoint[] array, int arrayIndex)
```

Kopiert die Elemente von [IGenericCollection](../../com.aspose.slides/igenericcollection) in ein Array, beginnend bei einem bestimmten Array-Index.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| array | [IChartDataPoint\[\]](../../com.aspose.slides/ichartdatapoint) | Das eindimensionale Array, das Ziel der von [IGenericCollection](../../com.aspose.slides/igenericcollection) kopierten Elemente ist. Das Array muss nullbasiert indiziert sein. |
| arrayIndex | int | Der nullbasierte Index im Array, an dem das Kopieren beginnt. |

### size() {#size--}
```
public final int size()
```

Gibt die Anzahl der Diagrammdatenpunkte zurück oder legt sie fest. Nur-Lese-int.

**Rückgabe:**
int

### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

Gibt einen Wert zurück, der angibt, ob [IGenericCollection](../../com.aspose.slides/igenericcollection) schreibgeschützt ist. Nur-Lese-boolean.

**Rückgabe:**
boolean - true, wenn [IGenericCollection](../../com.aspose.slides/igenericcollection) schreibgeschützt ist; andernfalls false.

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Gibt einen Wert zurück, der angibt, ob der Zugriff auf die Sammlung synchronisiert (thread-sicher) ist. Nur-Lese-boolean.

**Rückgabe:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Gibt die Synchronisationswurzel zurück. Nur-Lese-Object.

**Rückgabe:**
java.lang.Object

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataPoint> iterator()
```

Gibt einen Enumerator zurück, der durch die Sammlung iteriert.

**Rückgabe:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataPoint> - Ein IGenericEnumerator, der zum Durchlaufen der Sammlung verwendet werden kann.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataPoint> iteratorJava()
```

Gibt einen Java-Iterator für die gesamte Sammlung zurück.

**Rückgabe:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataPoint> - Ein java.util.Iterator für die gesamte Sammlung.