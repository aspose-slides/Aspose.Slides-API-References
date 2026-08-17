---
title: PieSplitCustomPointCollection
second_title: Aspose.Slides für Java API-Referenz
description: Stellt eine Sammlung von Punkten für den Teilungspunkt in einem Bar-of-Pie- oder Pie-of-Pie-Diagramm mit einer benutzerdefinierten Aufteilung dar.
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

Stellt eine Sammlung von Punkten für den Teilungspunkt in einem Bar-of-Pie- oder Pie-of-Pie-Diagramm mit einer benutzerdefinierten Aufteilung dar.

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Gibt das Diagrammdatenpunkt für den angegebenen Index zurück. |
| [add(int dataPointIndex)](#add-int-) | Fügt den Datenpunkt anhand seines Index in der übergeordneten Serienpunktesammlung hinzu. |
| [addItem(IChartDataPoint dataPoint)](#addItem-com.aspose.slides.IChartDataPoint-) | Fügt den Datenpunkt zur Sammlung hinzu. |
| [removeItem(IChartDataPoint dataPoint)](#removeItem-com.aspose.slides.IChartDataPoint-) | Entfernt das Element aus der Sammlung. |
| [remove(int dataPointIndex)](#remove-int-) | Entfernt das Element aus der Sammlung anhand seines Index in der übergeordneten Serienpunktesammlung. |
| [clear()](#clear--) | Entfernt alle Elemente aus dem [IGenericCollection](../../com.aspose.slides/igenericcollection). |
| [containsItem(IChartDataPoint item)](#containsItem-com.aspose.slides.IChartDataPoint-) | Bestimmt, ob [IGenericCollection](../../com.aspose.slides/igenericcollection) einen bestimmten Wert enthält. |
| [copyToTArray(IChartDataPoint[] array, int arrayIndex)](#copyToTArray-com.aspose.slides.IChartDataPoint---int-) | Kopiert die Elemente des [IGenericCollection](../../com.aspose.slides/igenericcollection) in ein Array, beginnend bei einem bestimmten Array-Index. |
| [size()](#size--) | Gibt die Anzahl der Diagrammdatenpunkte zurück oder legt sie fest. |
| [isReadOnly()](#isReadOnly--) | Ermittelt einen Wert, der angibt, ob [IGenericCollection](../../com.aspose.slides/igenericcollection) schreibgeschützt ist. |
| [isSynchronized()](#isSynchronized--) | Gibt einen Wert zurück, der angibt, ob der Zugriff auf die Sammlung synchronisiert (Thread-sicher) ist. |
| [getSyncRoot()](#getSyncRoot--) | Gibt ein Synchronisationsgrundelement zurück. |
| [iterator()](#iterator--) | Gibt einen Enumerator zurück, der die Sammlung durchläuft. |
| [iteratorJava()](#iteratorJava--) | Gibt einen Java-Iterator für die gesamte Sammlung zurück. |

### get_Item(int index) {#get-Item-int-}
```
public final IChartDataPoint get_Item(int index)
```

Gibt das Diagrammdatenpunkt für den angegebenen Index zurück.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Index. |

**Rückgabewert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Diagrammdatenpunkt.

### add(int dataPointIndex) {#add-int-}
```
public final void add(int dataPointIndex)
```

Fügt den Datenpunkt anhand seines Index in der übergeordneten Serienpunktesammlung hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| dataPointIndex | int | Index des Datenpunkts in der übergeordneten Serienpunktesammlung. |

### addItem(IChartDataPoint dataPoint) {#addItem-com.aspose.slides.IChartDataPoint-}
```
public void addItem(IChartDataPoint dataPoint)
```

Fügt den Datenpunkt zur Sammlung hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| dataPoint | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | Datenpunkt, der hinzugefügt wird. |

### removeItem(IChartDataPoint dataPoint) {#removeItem-com.aspose.slides.IChartDataPoint-}
```
public boolean removeItem(IChartDataPoint dataPoint)
```

Entfernt das Element aus der Sammlung.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| dataPoint | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | Datenpunkt, der entfernt wird. |

**Rückgabewert:**
boolean - true, wenn das Element erfolgreich entfernt wurde; andernfalls false. Diese Methode gibt ebenfalls false zurück, wenn das Element nicht in der System.Collections.Generic.List{T} gefunden wurde.

### remove(int dataPointIndex) {#remove-int-}
```
public final void remove(int dataPointIndex)
```

Entfernt das Element aus der Sammlung anhand seines Index in der übergeordneten Serienpunktesammlung.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| dataPointIndex | int | Index des Datenpunkts in der übergeordneten Serienpunktesammlung. |

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
| item | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | Das Objekt, das im [IGenericCollection](../../com.aspose.slides/igenericcollection) gesucht werden soll. |

**Rückgabewert:**
boolean - true, wenn das Element im [IGenericCollection](../../com.aspose.slides/igenericcollection) gefunden wird; andernfalls false.

### copyToTArray(IChartDataPoint[] array, int arrayIndex) {#copyToTArray-com.aspose.slides.IChartDataPoint---int-}
```
public void copyToTArray(IChartDataPoint[] array, int arrayIndex)
```

Kopiert die Elemente des [IGenericCollection](../../com.aspose.slides/igenericcollection) in ein Array, beginnend bei einem bestimmten Array-Index.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| array | [IChartDataPoint\[\]](../../com.aspose.slides/ichartdatapoint) | Das eindimensionale Array, das das Ziel der vom [IGenericCollection](../../com.aspose.slides/igenericcollection) kopierten Elemente ist. Das Array muss nullbasierte Indizierung besitzen. |
| arrayIndex | int | Der nullbasierte Index im Array, an dem das Kopieren beginnt. |

### size() {#size--}
```
public final int size()
```

Gibt die Anzahl der Diagrammdatenpunkte zurück oder legt sie fest. Nur-Lese int.

**Rückgabewert:**
int

### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

Ermittelt einen Wert, der angibt, ob [IGenericCollection](../../com.aspose.slides/igenericcollection) schreibgeschützt ist. Nur-Lese boolean.

**Rückgabewert:**
boolean - true, wenn [IGenericCollection](../../com.aspose.slides/igenericcollection) schreibgeschützt ist; andernfalls false.

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Gibt einen Wert zurück, der angibt, ob der Zugriff auf die Sammlung synchronisiert (Thread-sicher) ist. Nur-Lese boolean.

**Rückgabewert:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Gibt ein Synchronisationsgrundelement zurück. Nur-Lese Object.

**Rückgabewert:**
java.lang.Object

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataPoint> iterator()
```

Gibt einen Enumerator zurück, der die Sammlung durchläuft.

**Rückgabewert:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataPoint> - Ein IGenericEnumerator, der zum Durchlaufen der Sammlung verwendet werden kann.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataPoint> iteratorJava()
```

Gibt einen Java-Iterator für die gesamte Sammlung zurück.

**Rückgabewert:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataPoint> - Ein java.util.Iterator für die gesamte Sammlung.