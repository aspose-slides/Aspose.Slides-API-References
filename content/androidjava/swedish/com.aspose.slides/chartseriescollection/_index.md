---
title: ChartSeriesCollection
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar en samling av
type: docs
url: /sv/com.aspose.slides/chartseriescollection/
---
**Arv:**
java.lang.Object, com.aspose.slides.DomObject

**Alla implementerade gränssnitt:**
[com.aspose.slides.IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection)
```
public class ChartSeriesCollection extends DomObject<ChartData> implements IChartSeriesCollection
```

Representerar en samling av [ChartSeries](../../com.aspose.slides/chartseries)
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Hämtar elementet på det angivna indexet. |
| [size()](#size--) | Returnerar antalet objekt i samlingen. |
| [add(int type)](#add-int-) | Skapar en ny diagramserie och lägger till den i samlingen. |
| [insert(int index, int type)](#insert-int-int-) | Skapar en ny diagramserie och infogar den i samlingen. |
| [add(IChartDataCell cellWithSeriesName, int type)](#add-com.aspose.slides.IChartDataCell-int-) | Skapar en ny diagramserie från [ChartDataCell](../../com.aspose.slides/chartdatacell) och lägger till den i samlingen. |
| [add(IChartCellCollection cellsWithSeriesName, int type)](#add-com.aspose.slides.IChartCellCollection-int-) | Skapar en ny diagramserie från [ChartCellCollection](../../com.aspose.slides/chartcellcollection) och lägger till den i samlingen. |
| [add(String name, int type)](#add-java.lang.String-int-) | Skapar en ny diagramserie från värde och lägger till den i samlingen. |
| [indexOf(IChartSeries value)](#indexOf-com.aspose.slides.IChartSeries-) | Söker efter den angivna [ChartSeries](../../com.aspose.slides/chartseries) och returnerar det nollbaserade indexet för den första förekomsten i hela samlingen. |
| [remove(IChartSeries value)](#remove-com.aspose.slides.IChartSeries-) | Tar bort det angivna värdet. |
| [removeAt(int index)](#removeAt-int-) | Tar bort en ActiveX-kontroll som lagras på angiven position från samlingen. |
| [clear()](#clear--) | Tar bort alla kontroller från samlingen. |
| [iterator()](#iterator--) | Returnerar en enumerator som itererar genom samlingen. |
| [iteratorJava()](#iteratorJava--) | Returnerar en java-iterator för hela samlingen. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Kopierar hela samlingen till den angivna arrayen. |
| [isSynchronized()](#isSynchronized--) | Returnerar ett värde som indikerar om åtkomst till samlingen är synkroniserad (trådsäker). |
| [getSyncRoot()](#getSyncRoot--) | Returnerar ett synkroniseringsrot. |
### get_Item(int index) {#get-Item-int-}
```
public final IChartSeries get_Item(int index)
```

Hämtar elementet på det angivna indexet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int |  |

**Returnerar:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Elementet på det angivna indexet.
### size() {#size--}
```
public final int size()
```

Returnerar ett antal objekt i samlingen. skrivskyddad int.

**Returnerar:**
int
### add(int type) {#add-int-}
```
public final IChartSeries add(int type)
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
public final IChartSeries insert(int index, int type)
```

Skapar en ny diagramserie och infogar den i samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int |  |
| type | int |  |

**Returnerar:**
[IChartSeries](../../com.aspose.slides/ichartseries)
### add(IChartDataCell cellWithSeriesName, int type) {#add-com.aspose.slides.IChartDataCell-int-}
```
public final IChartSeries add(IChartDataCell cellWithSeriesName, int type)
```

Skapar en ny diagramserie från [ChartDataCell](../../com.aspose.slides/chartdatacell) och lägger till den i samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| cellWithSeriesName | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Cell som innehåller serienamnet. |
| type | int | Typ som anger serietyp |

--------------------

Om diagramserien är skapad från samma cell som redan finns i samlingen så lägger metoden till inget och returnerar dess index. |

**Returnerar:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Tillagd diagramserie eller serie som redan finns i samlingen.
### add(IChartCellCollection cellsWithSeriesName, int type) {#add-com.aspose.slides.IChartCellCollection-int-}
```
public final IChartSeries add(IChartCellCollection cellsWithSeriesName, int type)
```

Skapar en ny diagramserie från [ChartCellCollection](../../com.aspose.slides/chartcellcollection) och lägger till den i samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| cellsWithSeriesName | [IChartCellCollection](../../com.aspose.slides/ichartcellcollection) | Celler som innehåller serienamnet. |
| type | int | Typ som anger serietyp |

--------------------

Om diagramserien är skapad från samma cell som redan finns i samlingen så lägger metoden till inget och returnerar dess index. |

**Returnerar:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Tillagd diagramserie eller serie som redan finns i samlingen.
### add(String name, int type) {#add-java.lang.String-int-}
```
public final IChartSeries add(String name, int type)
```

Skapar en ny diagramserie från värde och lägger till den i samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | java.lang.String | Serienamn. |
| type | int | Typ som anger serietyp |

**Returnerar:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Tillagd diagramserie.
### indexOf(IChartSeries value) {#indexOf-com.aspose.slides.IChartSeries-}
```
public final int indexOf(IChartSeries value)
```

Söker efter den angivna [ChartSeries](../../com.aspose.slides/chartseries) och returnerar det nollbaserade indexet för den första förekomsten i hela samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IChartSeries](../../com.aspose.slides/ichartseries) | Värde för diagramserie. |

**Returnerar:**
int - Det nollbaserade indexet för den första förekomsten av värdet i hela CollectionBase, om hittad; annars -1.
### remove(IChartSeries value) {#remove-com.aspose.slides.IChartSeries-}
```
public final void remove(IChartSeries value)
```

Tar bort det angivna värdet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IChartSeries](../../com.aspose.slides/ichartseries) | Värdet. |
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Tar bort en ActiveX-kontroll som lagras på angiven position från samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Index för kontrollen som ska tas bort. |
### clear() {#clear--}
```
public final void clear()
```

Tar bort alla kontroller från samlingen.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartSeries> iterator()
```

Returnerar en enumerator som itererar genom samlingen.

**Returnerar:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartSeries> - En IGenericEnumerator som kan användas för att iterera genom samlingen.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartSeries> iteratorJava()
```

Returnerar en java-iterator för hela samlingen.

**Returnerar:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartSeries> - En java.util.Iterator för hela samlingen.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Kopierar hela samlingen till den angivna arrayen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Målarray |
| index | int | Index i målarrayen. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Returnerar ett värde som indikerar om åtkomst till samlingen är synkroniserad (trådsäker). skrivskyddad boolean.

**Returnerar:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Returnerar ett synkroniseringsrot. skrivskyddad Object.

**Returnerar:**
java.lang.Object