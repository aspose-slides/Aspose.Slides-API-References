---
title: ChartSeriesCollection
second_title: Aspose.Slides für Java API Referenz
description: Stellt Sammlung von
type: docs
url: /de/com.aspose.slides/chartseriescollection/
---
**Vererbung:**
java.lang.Object, com.aspose.slides.DomObject

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection)
```
public class ChartSeriesCollection extends DomObject<ChartData> implements IChartSeriesCollection
```

Stellt eine Sammlung von [ChartSeries](../../com.aspose.slides/chartseries) dar
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Ruft das Element am angegebenen Index ab. |
| [size()](#size--) | Gibt die Anzahl der Objekte in der Sammlung zurück. |
| [add(int type)](#add-int-) | Erstellt eine neue Diagrammserie und fügt sie der Sammlung hinzu. |
| [insert(int index, int type)](#insert-int-int-) | Erstellt eine neue Diagrammserie und fügt sie in die Sammlung ein. |
| [add(IChartDataCell cellWithSeriesName, int type)](#add-com.aspose.slides.IChartDataCell-int-) | Erstellt eine neue Diagrammserie aus [ChartDataCell](../../com.aspose.slides/chartdatacell) und fügt sie der Sammlung hinzu. |
| [add(IChartCellCollection cellsWithSeriesName, int type)](#add-com.aspose.slides.IChartCellCollection-int-) | Erstellt eine neue Diagrammserie aus [ChartCellCollection](../../com.aspose.slides/chartcellcollection) und fügt sie der Sammlung hinzu. |
| [add(String name, int type)](#add-java.lang.String-int-) | Erstellt eine neue Diagrammserie aus dem Wert und fügt sie der Sammlung hinzu. |
| [indexOf(IChartSeries value)](#indexOf-com.aspose.slides.IChartSeries-) | Durchsucht das angegebene [ChartSeries](../../com.aspose.slides/chartseries) und gibt den nullbasierten Index des ersten Vorkommens in der gesamten Collection zurück. |
| [remove(IChartSeries value)](#remove-com.aspose.slides.IChartSeries-) | Entfernt den angegebenen Wert. |
| [removeAt(int index)](#removeAt-int-) | Entfernt ein ActiveX-Steuerelement, das an der angegebenen Position gespeichert ist, aus der Sammlung. |
| [clear()](#clear--) | Entfernt alle Steuerelemente aus der Sammlung. |
| [iterator()](#iterator--) | Gibt einen Aufzählungsobjekt zurück, das die Sammlung durchläuft. |
| [iteratorJava()](#iteratorJava--) | Gibt einen Java-Iterator für die gesamte Sammlung zurück. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Kopiert die gesamte Sammlung in das angegebene Array. |
| [isSynchronized()](#isSynchronized--) | Gibt einen Wert zurück, der angibt, ob der Zugriff auf die Sammlung synchronisiert (thread-sicher) ist. |
| [getSyncRoot()](#getSyncRoot--) | Gibt eine Synchronisationswurzel zurück. |
### get_Item(int index) {#get-Item-int-}
```
public final IChartSeries get_Item(int index)
```

Ruft das Element am angegebenen Index ab.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int |  |

**Rückgabewert:**
[IChartSeries](../../com.aspose.slides/ichartseries) – Das Element am angegebenen Index.
### size() {#size--}
```
public final int size()
```

Gibt die Anzahl der Objekte in der Sammlung zurück. Nur lesbarer int.

**Rückgabewert:**
int
### add(int type) {#add-int-}
```
public final IChartSeries add(int type)
```

Erstellt eine neue Diagrammserie und fügt sie der Sammlung hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| type | int | Typ der Serie |

**Rückgabewert:**
[IChartSeries](../../com.aspose.slides/ichartseries) – Neue Diagrammserie.
### insert(int index, int type) {#insert-int-int-}
```
public final IChartSeries insert(int index, int type)
```

Erstellt eine neue Diagrammserie und fügt sie in die Sammlung ein.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int |  |
| type | int |  |

**Rückgabewert:**
[IChartSeries](../../com.aspose.slides/ichartseries)
### add(IChartDataCell cellWithSeriesName, int type) {#add-com.aspose.slides.IChartDataCell-int-}
```
public final IChartSeries add(IChartDataCell cellWithSeriesName, int type)
```

Erstellt eine neue Diagrammserie aus [ChartDataCell](../../com.aspose.slides/chartdatacell) und fügt sie der Sammlung hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| cellWithSeriesName | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Zelle, die den Seriennamen enthält. |
| type | int | Typ der Serie |

--------------------

Wenn eine Diagrammserie aus derselben Zelle, die bereits in der Sammlung ist, erstellt wird, fügt die Methode nichts hinzu und gibt ihren Index zurück. |

**Rückgabewert:**
[IChartSeries](../../com.aspose.slides/ichartseries) – Hinzugefügte Diagrammserie oder bereits in der Sammlung vorhandene Serie.
### add(IChartCellCollection cellsWithSeriesName, int type) {#add-com.aspose.slides.IChartCellCollection-int-}
```
public final IChartSeries add(IChartCellCollection cellsWithSeriesName, int type)
```

Erstellt eine neue Diagrammserie aus [ChartCellCollection](../../com.aspose.slides/chartcellcollection) und fügt sie der Sammlung hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| cellsWithSeriesName | [IChartCellCollection](../../com.aspose.slides/ichartcellcollection) | Zellen, die den Seriennamen enthalten. |
| type | int | Typ der Serie |

--------------------

Wenn eine Diagrammserie aus derselben Zelle, die bereits in der Sammlung ist, erstellt wird, fügt die Methode nichts hinzu und gibt ihren Index zurück. |

**Rückgabewert:**
[IChartSeries](../../com.aspose.slides/ichartseries) – Hinzugefügte Diagrammserie oder bereits in der Sammlung vorhandene Serie.
### add(String name, int type) {#add-java.lang.String-int-}
```
public final IChartSeries add(String name, int type)
```

Erstellt eine neue Diagrammserie aus dem Wert und fügt sie der Sammlung hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | java.lang.String | Serienname. |
| type | int | Typ der Serie |

**Rückgabewert:**
[IChartSeries](../../com.aspose.slides/ichartseries) – Hinzugefügte Diagrammserie.
### indexOf(IChartSeries value) {#indexOf-com.aspose.slides.IChartSeries-}
```
public final int indexOf(IChartSeries value)
```

Durchsucht das angegebene [ChartSeries](../../com.aspose.slides/chartseries) und gibt den nullbasierten Index des ersten Vorkommens in der gesamten Collection zurück.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IChartSeries](../../com.aspose.slides/ichartseries) | Wert der Diagrammserie. |

**Rückgabewert:**
int – Der nullbasierte Index des ersten Vorkommens von value in der gesamten CollectionBase, falls gefunden; andernfalls -1.
### remove(IChartSeries value) {#remove-com.aspose.slides.IChartSeries-}
```
public final void remove(IChartSeries value)
```

Entfernt den angegebenen Wert.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IChartSeries](../../com.aspose.slides/ichartseries) | Der Wert. |
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Entfernt ein ActiveX-Steuerelement, das an der angegebenen Position gespeichert ist, aus der Sammlung.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Index des zu entfernenden Steuerelements. |
### clear() {#clear--}
```
public final void clear()
```

Entfernt alle Steuerelemente aus der Sammlung.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartSeries> iterator()
```

Gibt einen Aufzählungsobjekt zurück, das die Sammlung durchläuft.

**Rückgabewert:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartSeries> – Ein IGenericEnumerator, der verwendet werden kann, um die Sammlung zu durchlaufen.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartSeries> iteratorJava()
```

Gibt einen Java-Iterator für die gesamte Sammlung zurück.

**Rückgabewert:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartSeries> – Ein java.util.Iterator für die gesamte Sammlung.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Kopiert die gesamte Sammlung in das angegebene Array.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Zielarray |
| index | int | Index im Zielarray. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Gibt einen Wert zurück, der angibt, ob der Zugriff auf die Sammlung synchronisiert (thread-sicher) ist. Nur lesbarer boolean.

**Rückgabewert:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Gibt eine Synchronisationswurzel zurück. Nur lesbares Object.

**Rückgabewert:**
java.lang.Object