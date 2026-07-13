---
title: ChartCellCollection
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt een collectie van cellen met gegevens voor.
type: docs
url: /nl/com.aspose.slides/chartcellcollection/
---
**Erfenis:**
java.lang.Object

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IChartCellCollection](../../com.aspose.slides/ichartcellcollection), com.aspose.slides.IDOMObject
```
public class ChartCellCollection implements IChartCellCollection, IDOMObject
```

Stelt een collectie van cellen met gegevens voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getCellsAddress()](#getCellsAddress--) | Retourneert het adres van de set cellen in de werkmap. |
| [getConcatenatedValuesFromCells()](#getConcatenatedValuesFromCells--) | Concatenatie-string van alle cel-stringwaarden. |
| [get_Item(int index)](#get-Item-int-) | Retourneert een cel (IChartDataCell) per index. |
| [add(IChartDataCell cell)](#add-com.aspose.slides.IChartDataCell-) | Voeg een nieuwe cel toe aan de collectie. |
| [add(Object value)](#add-java.lang.Object-) | Maakt [ChartDataCell](../../com.aspose.slides/chartdatacell) van de opgegeven waarde en voegt het toe aan de collectie. |
| [removeAt(int index)](#removeAt-int-) | Verwijdert een cel uit de collectie op basis van index. |
| [getCount()](#getCount--) | Haalt het aantal cellen in de collectie op. |
| [iterator()](#iterator--) | Retourneert een enumerator die door de collectie itereert. |
| [iteratorJava()](#iteratorJava--) | Retourneert een java-iterator voor de volledige collectie. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getCellsAddress() {#getCellsAddress--}
```
public final String getCellsAddress()
```


Retourneert het adres van de set cellen in de werkmap.

**Retourneert:**
java.lang.String
### getConcatenatedValuesFromCells() {#getConcatenatedValuesFromCells--}
```
public final String getConcatenatedValuesFromCells()
```


Concatenatie-string van alle cel-stringwaarden.

**Retourneert:**
java.lang.String
### get_Item(int index) {#get-Item-int-}
```
public final IChartDataCell get_Item(int index)
```


Retourneert een cel (IChartDataCell) per index.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Index van een cel. |

**Retourneert:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cel met gegevens.
### add(IChartDataCell cell) {#add-com.aspose.slides.IChartDataCell-}
```
public final void add(IChartDataCell cell)
```


Voegt een nieuwe cel toe aan de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| cell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Nieuwe cel die moet worden toegevoegd. |

### add(Object value) {#add-java.lang.Object-}
```
public final void add(Object value)
```


Maakt [ChartDataCell](../../com.aspose.slides/chartdatacell) van de opgegeven waarde en voegt het toe aan de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.Object | De waarde.

--------------------

Deze methode voegt een werkblad met de naam AUTO\_DATA toe en plaatst alle waarden daarin. Als u [ChartDataWorkbook](../../com.aspose.slides/chartdataworkbook) gebruikt om celwaarden toe te voegen of te bewerken, zorg er dan voor dat u dit werkblad niet gebruikt. Het maximale aantal waarden dat met deze methode kan worden toegevoegd mag niet hoger zijn dan 16711680 |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Verwijdert een cel uit de collectie op basis van index.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Index van de te verwijderen cel. |

### getCount() {#getCount--}
```
public final int getCount()
```


Haalt het aantal cellen in de collectie op. Alleen-lezen int.

**Retourneert:**
int
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataCell> iterator()
```


Retourneert een enumerator die door de collectie itereert.

**Retourneert:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataCell> - Een IGenericEnumerator die kan worden gebruikt om door de collectie te itereren.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataCell> iteratorJava()
```


Retourneert een java-iterator voor de volledige collectie.

**Retourneert:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataCell> - Een java.util.Iterator voor de volledige collectie.
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Retourneert Parent\_Immediate-object. Alleen-lezen IDOMObject.

**Retourneert:**
com.aspose.slides.IDOMObject