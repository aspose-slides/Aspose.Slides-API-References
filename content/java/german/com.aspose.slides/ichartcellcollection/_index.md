---
title: IChartCellCollection
second_title: Aspose.Slides für Java API-Referenz
description: Stellt eine Sammlung von Zellen mit Daten dar.
type: docs
url: /de/com.aspose.slides/ichartcellcollection/
---
**Alle implementierten Schnittstellen:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IChartCellCollection extends System.Collections.Generic.IGenericEnumerable<IChartDataCell>
```

Stellt eine Sammlung von Zellen mit Daten dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getCellsAddress()](#getCellsAddress--) | Gibt die Adresse des Zellensatzes in der Arbeitsmappe zurück. |
| [getConcatenatedValuesFromCells()](#getConcatenatedValuesFromCells--) | Verkettungszeichenfolge aus allen Zellzeichenfolgenwerten. |
| [get_Item(int index)](#get-Item-int-) | Gibt eine Zelle (IChartDataCell) anhand des Index zurück. |
| [add(IChartDataCell chartDataCell)](#add-com.aspose.slides.IChartDataCell-) | Fügt der Sammlung eine neue Zelle hinzu. |
| [add(Object value)](#add-java.lang.Object-) | Erstellt [IChartDataCell](../../com.aspose.slides/ichartdatacell) aus dem angegebenen Wert und fügt es der Sammlung hinzu. |
| [removeAt(int index)](#removeAt-int-) | Entfernt eine Zelle aus der Sammlung anhand des Index. |
| [getCount()](#getCount--) | Gibt die Anzahl der Zellen in der Sammlung zurück. |
### getCellsAddress() {#getCellsAddress--}
```
public abstract String getCellsAddress()
```


Gibt die Adresse des Zellensatzes in der Arbeitsmappe zurück.

**Rückgabe:**
java.lang.String - Adresse des Zellensatzes in der Arbeitsmappe String
### getConcatenatedValuesFromCells() {#getConcatenatedValuesFromCells--}
```
public abstract String getConcatenatedValuesFromCells()
```


Verkettungszeichenfolge aus allen Zellzeichenfolgenwerten.

**Rückgabe:**
java.lang.String - Ergebniszeichenfolge String
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartDataCell get_Item(int index)
```


Gibt eine Zelle (IChartDataCell) anhand des Index zurück.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Index einer Zelle. |

**Rückgabe:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Zelle mit Daten.
### add(IChartDataCell chartDataCell) {#add-com.aspose.slides.IChartDataCell-}
```
public abstract void add(IChartDataCell chartDataCell)
```


Fügt der Sammlung eine neue Zelle hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| chartDataCell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Neue hinzuzufügende Zelle. |

### add(Object value) {#add-java.lang.Object-}
```
public abstract void add(Object value)
```


Erstellt [IChartDataCell](../../com.aspose.slides/ichartdatacell) aus dem angegebenen Wert und fügt es der Sammlung hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.Object | Der Wert. |

--------------------

Diese Methode fügt ein Arbeitsblatt mit dem Namen AUTO_DATA hinzu und fügt dort alle Werte ein. Wenn Sie [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook) verwenden, um Zellwerte hinzuzufügen oder zu bearbeiten, stellen Sie sicher, dass Sie dieses Arbeitsblatt nicht verwenden. Die maximale Anzahl von Werten, die mit dieser Methode hinzugefügt werden kann, darf 16711680 nicht überschreiten. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Entfernt eine Zelle aus der Sammlung anhand des Index.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Index einer zu entfernenden Zelle. |

### getCount() {#getCount--}
```
public abstract int getCount()
```


Gibt die Anzahl der Zellen in der Sammlung zurück. Nur-Lese int.

**Rückgabe:**
int