---
title: IChartSeriesCollection
second_title: Aspose.Slides für Java API-Referenz
description: Stellt eine Sammlung von
type: docs
url: /de/com.aspose.slides/ichartseriescollection/
---
**Alle implementierten Schnittstellen:**
com.aspose.slides.IGenericCollection
```
public interface IChartSeriesCollection extends IGenericCollection<IChartSeries>
```

Stellt eine Sammlung von [IChartSeries](../../com.aspose.slides/ichartseries) dar
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Ruft das Element am angegebenen Index ab. |
| [add(int type)](#add-int-) | Erstellt neue Diagrammserie und fügt sie der Sammlung hinzu. |
| [insert(int index, int type)](#insert-int-int-) | Erstellt neue Diagrammserie und fügt sie in die Sammlung ein. |
| [add(IChartDataCell cellWithSeriesName, int type)](#add-com.aspose.slides.IChartDataCell-int-) | Erstellt neue Diagrammserie aus [IChartDataCell](../../com.aspose.slides/ichartdatacell) und fügt sie der Sammlung hinzu. |
| [add(IChartCellCollection cellsWithSeriesName, int type)](#add-com.aspose.slides.IChartCellCollection-int-) | Erstellt neue Diagrammserie aus [IChartCellCollection](../../com.aspose.slides/ichartcellcollection) und fügt sie der Sammlung hinzu. |
| [add(String name, int type)](#add-java.lang.String-int-) | Erstellt neue Diagrammserie aus dem Wert und fügt sie der Sammlung hinzu. |
| [indexOf(IChartSeries value)](#indexOf-com.aspose.slides.IChartSeries-) | Durchsucht die angegebene [IChartSeries](../../com.aspose.slides/ichartseries) und gibt den nullbasierten Index des ersten Vorkommens in der gesamten Collection zurück. |
| [remove(IChartSeries value)](#remove-com.aspose.slides.IChartSeries-) | Entfernt den angegebenen Wert. |
| [removeAt(int index)](#removeAt-int-) | Entfernt das Element am angegebenen Index |
| [clear()](#clear--) | Entfernt alle Elemente (einschließlich des Diagramm-Stils) aus der Sammlung. |

### get_Item(int index) {#get-Item-int-}
```
public abstract IChartSeries get_Item(int index)
```

Ruft das Element am angegebenen Index ab.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int |  |

**Rückgabewert:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Das Element am angegebenen Index.

### add(int type) {#add-int-}
```
public abstract IChartSeries add(int type)
```

Erstellt neue Diagrammserie und fügt sie der Sammlung hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| type | int | Typ der Serie |

**Rückgabewert:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Neue Diagrammserie.

### insert(int index, int type) {#insert-int-int-}
```
public abstract IChartSeries insert(int index, int type)
```

Erstellt neue Diagrammserie und fügt sie in die Sammlung ein.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Index für die Einfügung |
| type | int | Diagrammtyp [ChartType](../../com.aspose.slides/charttype) |

**Rückgabewert:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Neue Diagrammserie [IChartSeries](../../com.aspose.slides/ichartseries)

### add(IChartDataCell cellWithSeriesName, int type) {#add-com.aspose.slides.IChartDataCell-int-}
```
public abstract IChartSeries add(IChartDataCell cellWithSeriesName, int type)
```

Erstellt neue Diagrammserie aus [IChartDataCell](../../com.aspose.slides/ichartdatacell) und fügt sie der Sammlung hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| cellWithSeriesName | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Zelle, die den Seriennamen enthält. |
| type | int | Typ der Serie festlegen

--------------------

Wenn eine Diagrammserie bereits aus derselben Zelle in der Sammlung existiert, fügt die Methode nichts hinzu und gibt ihren Index zurück. |

**Rückgabewert:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Hinzugefügte Diagrammserie oder bereits in der Sammlung vorhandene Serie.

### add(IChartCellCollection cellsWithSeriesName, int type) {#add-com.aspose.slides.IChartCellCollection-int-}
```
public abstract IChartSeries add(IChartCellCollection cellsWithSeriesName, int type)
```

Erstellt neue Diagrammserie aus [IChartCellCollection](../../com.aspose.slides/ichartcellcollection) und fügt sie der Sammlung hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| cellsWithSeriesName | [IChartCellCollection](../../com.aspose.slides/ichartcellcollection) | Zellen, die den Seriennamen enthalten. |
| type | int | Typ der Serie festlegen

--------------------

Wenn eine Diagrammserie bereits aus derselben Zelle in der Sammlung existiert, fügt die Methode nichts hinzu und gibt ihren Index zurück. |

**Rückgabewert:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Hinzugefügte Diagrammserie oder bereits in der Sammlung vorhandene Serie.

### add(String name, int type) {#add-java.lang.String-int-}
```
public abstract IChartSeries add(String name, int type)
```

Erstellt neue Diagrammserie aus dem Wert und fügt sie der Sammlung hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | java.lang.String | Serienname. |
| type | int | Typ der Serie festlegen |

**Rückgabewert:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Hinzugefügte Diagrammserie.

### indexOf(IChartSeries value) {#indexOf-com.aspose.slides.IChartSeries-}
```
public abstract int indexOf(IChartSeries value)
```

Durchsucht das angegebene [IChartSeries](../../com.aspose.slides/ichartseries) und gibt den nullbasierten Index des ersten Vorkommens in der gesamten Collection zurück.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IChartSeries](../../com.aspose.slides/ichartseries) | Wert der Diagrammserie. |

**Rückgabewert:**
int - Der nullbasierte Index des ersten Vorkommens des Wertes in der gesamten CollectionBase, falls gefunden; andernfalls -1.

### remove(IChartSeries value) {#remove-com.aspose.slides.IChartSeries-}
```
public abstract void remove(IChartSeries value)
```

Entfernt den angegebenen Wert.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IChartSeries](../../com.aspose.slides/ichartseries) | Der Wert. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Entfernt das Element am angegebenen Index

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Index |

### clear() {#clear--}
```
public abstract void clear()
```

Entfernt alle Elemente (einschließlich des Diagramm-Stils) aus der Sammlung.