---
title: ChartCellCollection
second_title: Aspose.Slides för Java API-referens
description: Representerar en samling av celler med data.
type: docs
url: /sv/com.aspose.slides/chartcellcollection/
---
**Arv:**
java.lang.Object

**Alla implementerade gränssnitt:**
[com.aspose.slides.IChartCellCollection](../../com.aspose.slides/ichartcellcollection), com.aspose.slides.IDOMObject
```
public class ChartCellCollection implements IChartCellCollection, IDOMObject
```

Representerar en samling av celler med data.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getCellsAddress()](#getCellsAddress--) | Returnerar adressen för uppsättningen celler i arbetsboken. |
| [getConcatenatedValuesFromCells()](#getConcatenatedValuesFromCells--) | Konkatenationssträng från alla cellers strängvärden. |
| [get_Item(int index)](#get-Item-int-) | Returnerar en cell (IChartDataCell) efter index. |
| [add(IChartDataCell cell)](#add-com.aspose.slides.IChartDataCell-) | Lägg till en ny cell i samlingen. |
| [add(Object value)](#add-java.lang.Object-) | Skapar [ChartDataCell](../../com.aspose.slides/chartdatacell) från angivet värde och lägger till den i samlingen. |
| [removeAt(int index)](#removeAt-int-) | Tar bort en cell från samlingen efter index. |
| [getCount()](#getCount--) | Hämtar antalet celler i samlingen. |
| [iterator()](#iterator--) | Returnerar en enumerator som itererar genom samlingen. |
| [iteratorJava()](#iteratorJava--) | Returnerar en java-iterator för hela samlingen. |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### getCellsAddress() {#getCellsAddress--}
```
public final String getCellsAddress()
```


Returnerar adressen för uppsättningen celler i arbetsboken.

**Returnerar:**
java.lang.String

### getConcatenatedValuesFromCells() {#getConcatenatedValuesFromCells--}
```
public final String getConcatenatedValuesFromCells()
```


Konkatenationssträng från alla cellers strängvärden.

**Returnerar:**
java.lang.String

### get_Item(int index) {#get-Item-int-}
```
public final IChartDataCell get_Item(int index)
```


Returnerar en cell (IChartDataCell) efter index.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Index för en cell. |

**Returnerar:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell med data.

### add(IChartDataCell cell) {#add-com.aspose.slides.IChartDataCell-}
```
public final void add(IChartDataCell cell)
```


Lägg till en ny cell i samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| cell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Ny cell att lägga till. |

### add(Object value) {#add-java.lang.Object-}
```
public final void add(Object value)
```


Skapar [ChartDataCell](../../com.aspose.slides/chartdatacell) från angivet värde och lägger till den i samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.Object | Värdet. |

--------------------

Denna metod lägger till ett kalkylblad med namnet AUTO_DATA och lägger till alla värden där. Om du använder [ChartDataWorkbook](../../com.aspose.slides/chartdataworkbook) för att lägga till eller redigera Cell-värden, se till att du inte använder detta kalkylblad. Maximalt antal värden som kan läggas till med denna metod får inte överstiga 16711680 |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Tar bort en cell från samlingen efter index.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Index för en cell som ska tas bort. |

### getCount() {#getCount--}
```
public final int getCount()
```


Hämtar antalet celler i samlingen. Skrivskyddad int.

**Returnerar:**
int

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataCell> iterator()
```


Returnerar en enumerator som itererar genom samlingen.

**Returnerar:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataCell> - En IGenericEnumerator som kan användas för att iterera genom samlingen.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataCell> iteratorJava()
```


Returnerar en java-iterator för hela samlingen.

**Returnerar:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataCell> - En java.util.Iterator för hela samlingen.

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Returnerar Parent_Immediate-objektet. Skrivskyddad IDOMObject.

**Returnerar:**
com.aspose.slides.IDOMObject