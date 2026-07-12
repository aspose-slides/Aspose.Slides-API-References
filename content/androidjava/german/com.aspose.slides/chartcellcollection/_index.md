---
title: ChartCellCollection
second_title: Aspose.Slides für Android über Java API-Referenz
description: Stellt eine Sammlung von Zellen mit Daten dar.
type: docs
url: /de/com.aspose.slides/chartcellcollection/
---
**Vererbung:**
java.lang.Object

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IChartCellCollection](../../com.aspose.slides/ichartcellcollection), com.aspose.slides.IDOMObject
```
public class ChartCellCollection implements IChartCellCollection, IDOMObject
```

Stellt eine Sammlung von Zellen mit Daten dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getCellsAddress()](#getCellsAddress--) | Gibt die Adresse des Zellensatzes in der Arbeitsmappe zurück. |
| [getConcatenatedValuesFromCells()](#getConcatenatedValuesFromCells--) | Verkettete Zeichenfolge aus allen Zellwerten. |
| [get_Item(int index)](#get-Item-int-) | Gibt eine Zelle (IChartDataCell) nach Index zurück. |
| [add(IChartDataCell cell)](#add-com.aspose.slides.IChartDataCell-) | Fügt der Sammlung eine neue Zelle hinzu. |
| [add(Object value)](#add-java.lang.Object-) | Erstellt [ChartDataCell](../../com.aspose.slides/chartdatacell) aus dem angegebenen Wert und fügt es der Sammlung hinzu. |
| [removeAt(int index)](#removeAt-int-) | Entfernt eine Zelle aus der Sammlung nach Index. |
| [getCount()](#getCount--) | Ermittelt die Anzahl der Zellen in der Sammlung. |
| [iterator()](#iterator--) | Gibt einen Enumerator zurück, der die Sammlung durchläuft. |
| [iteratorJava()](#iteratorJava--) | Gibt einen Java-Iterator für die gesamte Sammlung zurück. |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### getCellsAddress() {#getCellsAddress--}
```
public final String getCellsAddress()
```

Gibt die Adresse des Zellensatzes in der Arbeitsmappe zurück.

**Rückgabe:**
java.lang.String

### getConcatenatedValuesFromCells() {#getConcatenatedValuesFromCells--}
```
public final String getConcatenatedValuesFromCells()
```

Verkettete Zeichenfolge aus allen Zellwerten.

**Rückgabe:**
java.lang.String

### get_Item(int index) {#get-Item-int-}
```
public final IChartDataCell get_Item(int index)
```

Gibt eine Zelle (IChartDataCell) nach Index zurück.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Index einer Zelle. |

**Rückgabe:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Zelle mit Daten.

### add(IChartDataCell cell) {#add-com.aspose.slides.IChartDataCell-}
```
public final void add(IChartDataCell cell)
```

Fügt der Sammlung eine neue Zelle hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| cell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Neue hinzuzufügende Zelle. |

### add(Object value) {#add-java.lang.Object-}
```
public final void add(Object value)
```

Erstellt [ChartDataCell](../../com.aspose.slides/chartdatacell) aus dem angegebenen Wert und fügt es der Sammlung hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.Object | Der Wert. |

--------------------

Diese Methode fügt ein Arbeitsblatt mit dem Namen AUTO_DATA hinzu und fügt dort alle Werte ein. Wenn Sie [ChartDataWorkbook](../../com.aspose.slides/chartdataworkbook) verwenden, um Zellwerte hinzuzufügen oder zu bearbeiten, stellen Sie sicher, dass Sie dieses Arbeitsblatt nicht verwenden. Die maximale Anzahl von Werten, die mit dieser Methode hinzugefügt werden kann, darf 16711680 nicht überschreiten |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Entfernt eine Zelle aus der Sammlung nach Index.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Index einer zu entfernenden Zelle. |

### getCount() {#getCount--}
```
public final int getCount()
```

Ermittelt die Anzahl der Zellen in der Sammlung. Nur-Lese int.

**Rückgabe:**
int

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataCell> iterator()
```

Gibt einen Enumerator zurück, der die Sammlung durchläuft.

**Rückgabe:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataCell> - Ein IGenericEnumerator, der zum Durchlaufen der Sammlung verwendet werden kann.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataCell> iteratorJava()
```

Gibt einen Java-Iterator für die gesamte Sammlung zurück.

**Rückgabe:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataCell> - Ein java.util.Iterator für die gesamte Sammlung.

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Gibt das Parent_Immediate-Objekt zurück. Nur-Lese IDOMObject.

**Rückgabe:**
com.aspose.slides.IDOMObject