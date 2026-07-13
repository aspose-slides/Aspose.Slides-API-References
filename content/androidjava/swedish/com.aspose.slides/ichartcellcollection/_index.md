---
title: IChartCellCollection
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar en samling av celler med data.
type: docs
url: /sv/com.aspose.slides/ichartcellcollection/
---
**Alla implementerade gränssnitt:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IChartCellCollection extends System.Collections.Generic.IGenericEnumerable<IChartDataCell>
```

Representerar en samling av celler med data.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getCellsAddress()](#getCellsAddress--) | Returnerar adressen till uppsättningen av celler i arbetsboken. |
| [getConcatenatedValuesFromCells()](#getConcatenatedValuesFromCells--) | Kombinerad sträng från alla cellers strängvärden. |
| [get_Item(int index)](#get-Item-int-) | Returnerar en cell (IChartDataCell) efter index. |
| [add(IChartDataCell chartDataCell)](#add-com.aspose.slides.IChartDataCell-) | Lägg till ny cell i samlingen. |
| [add(Object value)](#add-java.lang.Object-) | Skapar [IChartDataCell](../../com.aspose.slides/ichartdatacell) från angivet värde och lägger till den i samlingen. |
| [removeAt(int index)](#removeAt-int-) | Tar bort en cell från samlingen efter index. |
| [getCount()](#getCount--) | Hämtar antalet celler i samlingen. |
### getCellsAddress() {#getCellsAddress--}
```
public abstract String getCellsAddress()
```


Returnerar adressen till uppsättningen av celler i arbetsboken.

**Returnerar:**
java.lang.String - Adress till uppsättningen av celler i arbetsboken String
### getConcatenatedValuesFromCells() {#getConcatenatedValuesFromCells--}
```
public abstract String getConcatenatedValuesFromCells()
```


Kombinerad sträng från alla cellers strängvärden.

**Returnerar:**
java.lang.String - Resultatsträng String
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartDataCell get_Item(int index)
```


Returnerar en cell (IChartDataCell) efter index.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Index för en cell. |

**Returnerar:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell med data.
### add(IChartDataCell chartDataCell) {#add-com.aspose.slides.IChartDataCell-}
```
public abstract void add(IChartDataCell chartDataCell)
```


Lägg till ny cell i samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| chartDataCell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Ny cell att lägga till. |

### add(Object value) {#add-java.lang.Object-}
```
public abstract void add(Object value)
```


Skapar [IChartDataCell](../../com.aspose.slides/ichartdatacell) från angivet värde och lägger till den i samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.Object | Värdet.

--------------------

Den här metoden lägger till ett kalkylblad med namnet AUTO_DATA och lägger till alla värden där. Om du använder [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook) för att lägga till eller redigera Cell-värden, se till att du inte använder detta kalkylblad. Maximalt antal värden som kan läggas till med den här metoden får inte överstiga 16711680 |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Tar bort en cell från samlingen efter index.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Index för en cell att ta bort. |

### getCount() {#getCount--}
```
public abstract int getCount()
```


Hämtar antalet celler i samlingen. Endast läsning int.

**Returnerar:**
int