---
title: IChartSeriesCollection
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar en samling av
type: docs
url: /sv/com.aspose.slides/ichartseriescollection/
---
**Alla implementerade gränssnitt:**
com.aspose.slides.IGenericCollection
```
public interface IChartSeriesCollection extends IGenericCollection<IChartSeries>
```

Representerar en samling av [IChartSeries](../../com.aspose.slides/ichartseries)
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Gets the element at the specified index. |
| [add(int type)](#add-int-) | Creates new chart series and adds it to the collection. |
| [insert(int index, int type)](#insert-int-int-) | Creates new chart series and inserts it into the collection. |
| [add(IChartDataCell cellWithSeriesName, int type)](#add-com.aspose.slides.IChartDataCell-int-) | Creates new chart series from [IChartDataCell](../../com.aspose.slides/ichartdatacell) and adds it to the collection. |
| [add(IChartCellCollection cellsWithSeriesName, int type)](#add-com.aspose.slides.IChartCellCollection-int-) | Creates new chart series from [IChartCellCollection](../../com.aspose.slides/ichartcellcollection) and adds it to the collection. |
| [add(String name, int type)](#add-java.lang.String-int-) | Creates new chart series from value and adds it to the collection. |
| [indexOf(IChartSeries value)](#indexOf-com.aspose.slides.IChartSeries-) | Searches for the specified [IChartSeries](../../com.aspose.slides/ichartseries) and returns the zero-based index of the first occurrence within the entire Collection |
| [remove(IChartSeries value)](#remove-com.aspose.slides.IChartSeries-) | Removes the specified value. |
| [removeAt(int index)](#removeAt-int-) | Removes the element at the specified index |
| [clear()](#clear--) | Removes all elements (including the chart style) from the collection. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartSeries get_Item(int index)
```


Hämtar elementet på det angivna indexet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int |  |

**Returnerar:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Elementet på det angivna indexet.
### add(int type) {#add-int-}
```
public abstract IChartSeries add(int type)
```


Skapar en ny chart series and adds it to the collection.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| type | int | Typ av series |

**Returnerar:**
[IChartSeries](../../com.aspose.slides/ichartseries) - New chart series.
### insert(int index, int type) {#insert-int-int-}
```
public abstract IChartSeries insert(int index, int type)
```


Skapar en ny chart series and inserts it into the collection.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Index för insertion int |
| type | int | Diagramtype [ChartType](../../com.aspose.slides/charttype) |

**Returnerar:**
[IChartSeries](../../com.aspose.slides/ichartseries) - New chart series [IChartSeries](../../com.aspose.slides/ichartseries)
### add(IChartDataCell cellWithSeriesName, int type) {#add-com.aspose.slides.IChartDataCell-int-}
```
public abstract IChartSeries add(IChartDataCell cellWithSeriesName, int type)
```


Skapar en ny chart series from [IChartDataCell](../../com.aspose.slides/ichartdatacell) and adds it to the collection.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| cellWithSeriesName | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Cell som contain series name. |
| type | int | Type set type of series

--------------------

Om chart series careted from same cell already in collection then method adds nothing and returns it's index. |

**Returnerar:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Added chart series or series that already is in collection.
### add(IChartCellCollection cellsWithSeriesName, int type) {#add-com.aspose.slides.IChartCellCollection-int-}
```
public abstract IChartSeries add(IChartCellCollection cellsWithSeriesName, int type)
```


Skapar en ny chart series from [IChartCellCollection](../../com.aspose.slides/ichartcellcollection) and adds it to the collection.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| cellsWithSeriesName | [IChartCellCollection](../../com.aspose.slides/ichartcellcollection) | Cells which contain series name. |
| type | int | Type set type of series

--------------------

Om chart series careted from same cell already in collection then method adds nothing and returns it's index. |

**Returnerar:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Added chart series or series that already is in collection.
### add(String name, int type) {#add-java.lang.String-int-}
```
public abstract IChartSeries add(String name, int type)
```


Skapar en ny chart series from value and adds it to the collection.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | java.lang.String | Series name. |
| type | int | Type set type of series |

**Returnerar:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Added chart series.
### indexOf(IChartSeries value) {#indexOf-com.aspose.slides.IChartSeries-}
```
public abstract int indexOf(IChartSeries value)
```


Söker efter den angivna [IChartSeries](../../com.aspose.slides/ichartseries) and returns the zero-based index of the first occurrence within the entire Collection

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IChartSeries](../../com.aspose.slides/ichartseries) | Chart series value. |

**Returnerar:**
int - Det nollbaserade indexet för den första förekomsten av value within the entire CollectionBase, if found; otherwise, -1.
### remove(IChartSeries value) {#remove-com.aspose.slides.IChartSeries-}
```
public abstract void remove(IChartSeries value)
```


Tar bort det angivna värdet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IChartSeries](../../com.aspose.slides/ichartseries) | The value. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Tar bort elementet på det angivna indexet

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Index int |

### clear() {#clear--}
```
public abstract void clear()
```


Tar bort alla element (including the chart style) from the collection.