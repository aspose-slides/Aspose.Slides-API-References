---
title: IChartSeriesCollection
second_title: Aspose.Slides för Java API-referens
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

Skapar en ny diagramserie och lägger till den i samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| type | int | Typ av serie |

**Returnerar:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Ny diagramserie.
### insert(int index, int type) {#insert-int-int-}
```
public abstract IChartSeries insert(int index, int type)
```

Skapar en ny diagramserie och infogar den i samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Index för insättning |
| type | int | Diagramtyp [ChartType](../../com.aspose.slides/charttype) |

**Returnerar:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Ny diagramserie [IChartSeries](../../com.aspose.slides/ichartseries)
### add(IChartDataCell cellWithSeriesName, int type) {#add-com.aspose.slides.IChartDataCell-int-}
```
public abstract IChartSeries add(IChartDataCell cellWithSeriesName, int type)
```

Skapar en ny diagramserie från [IChartDataCell](../../com.aspose.slides/ichartdatacell) och lägger till den i samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| cellWithSeriesName | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Cell som innehåller serienamnet. |
| type | int | Typ som anger serietyp |

--------------------

Om diagramserien skapats från samma cell som redan finns i samlingen lägger metoden till inget och returnerar dess index. |

**Returnerar:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Tillagd diagramserie eller serie som redan finns i samlingen.
### add(IChartCellCollection cellsWithSeriesName, int type) {#add-com.aspose.slides.IChartCellCollection-int-}
```
public abstract IChartSeries add(IChartCellCollection cellsWithSeriesName, int type)
```

Skapar en ny diagramserie från [IChartCellCollection](../../com.aspose.slides/ichartcellcollection) och lägger till den i samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| cellsWithSeriesName | [IChartCellCollection](../../com.aspose.slides/ichartcellcollection) | Celler som innehåller serienamnet. |
| type | int | Typ som anger serietyp |

--------------------

Om diagramserien skapats från samma cell som redan finns i samlingen lägger metoden till inget och returnerar dess index. |

**Returnerar:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Tillagd diagramserie eller serie som redan finns i samlingen.
### add(String name, int type) {#add-java.lang.String-int-}
```
public abstract IChartSeries add(String name, int type)
```

Skapar en ny diagramserie från värdet och lägger till den i samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | java.lang.String | Serienamn. |
| type | int | Typ som anger serietyp |

**Returnerar:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Tillagd diagramserie.
### indexOf(IChartSeries value) {#indexOf-com.aspose.slides.IChartSeries-}
```
public abstract int indexOf(IChartSeries value)
```

Söker efter den specificerade [IChartSeries](../../com.aspose.slides/ichartseries) och returnerar det nollbaserade indexet för den första förekomsten i hela samlingen

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IChartSeries](../../com.aspose.slides/ichartseries) | Diagramserievärde. |

**Returnerar:**
int - Det nollbaserade indexet för den första förekomsten av värdet i hela CollectionBase, om hittad; annars -1.
### remove(IChartSeries value) {#remove-com.aspose.slides.IChartSeries-}
```
public abstract void remove(IChartSeries value)
```

Tar bort det specificerade värdet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IChartSeries](../../com.aspose.slides/ichartseries) | Värdet. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Tar bort elementet på det angivna indexet

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Index |

### clear() {#clear--}
```
public abstract void clear()
```

Tar bort alla element (inklusive diagramstilen) från samlingen.