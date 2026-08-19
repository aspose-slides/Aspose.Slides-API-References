---
title: IChartCellCollection
second_title: Aspose.Slides voor Java API-referentie
description: Stelt een collectie van cellen met gegevens voor.
type: docs
url: /nl/com.aspose.slides/ichartcellcollection/
---
**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IChartCellCollection extends System.Collections.Generic.IGenericEnumerable<IChartDataCell>
```

Stelt een collectie van cellen met gegevens voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getCellsAddress()](#getCellsAddress--) | Retourneert het adres van de set cellen in de werkmap. |
| [getConcatenatedValuesFromCells()](#getConcatenatedValuesFromCells--) | Concatenatie-string van alle cel-stringwaarden. |
| [get_Item(int index)](#get-Item-int-) | Retourneert een cel (IChartDataCell) op index. |
| [add(IChartDataCell chartDataCell)](#add-com.aspose.slides.IChartDataCell-) | Voeg een nieuwe cel toe aan de collectie. |
| [add(Object value)](#add-java.lang.Object-) | Maakt [IChartDataCell](../../com.aspose.slides/ichartdatacell) aan van de opgegeven waarde en voegt deze toe aan de collectie. |
| [removeAt(int index)](#removeAt-int-) | Verwijdert een cel uit de collectie op index. |
| [getCount()](#getCount--) | Haalt het aantal cellen in de collectie op. |
### getCellsAddress() {#getCellsAddress--}
```
public abstract String getCellsAddress()
```


Retourneert het adres van de set cellen in de werkmap.

**Retour:**
java.lang.String - Address of the set of cells in workbook String
### getConcatenatedValuesFromCells() {#getConcatenatedValuesFromCells--}
```
public abstract String getConcatenatedValuesFromCells()
```


Concatenatie-string van alle cel-stringwaarden.

**Retour:**
java.lang.String - Resulting string String
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartDataCell get_Item(int index)
```


Retourneert een cel (IChartDataCell) op index.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Index van een cel. |

**Retour:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cel met gegevens.
### add(IChartDataCell chartDataCell) {#add-com.aspose.slides.IChartDataCell-}
```
public abstract void add(IChartDataCell chartDataCell)
```


Voeg een nieuwe cel toe aan de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| chartDataCell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Nieuwe cel om toe te voegen. |

### add(Object value) {#add-java.lang.Object-}
```
public abstract void add(Object value)
```


Maakt [IChartDataCell](../../com.aspose.slides/ichartdatacell) aan van de opgegeven waarde en voegt deze toe aan de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.Object | De waarde.

--------------------

Deze methode voegt een werkblad toe met de naam AUTO\_DATA en voegt daar alle waarden toe. Als u [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook) gebruikt om celwaarden toe te voegen of te bewerken, zorg er dan voor dat u dit werkblad niet gebruikt. Het maximale aantal waarden dat met deze methode kan worden toegevoegd mag 16711680 niet overschrijden.

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Verwijdert een cel uit de collectie op index.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- |
| index | int | Index van een cel om te verwijderen. |

### getCount() {#getCount--}
```
public abstract int getCount()
```


Haalt het aantal cellen in de collectie op. Alleen-lezen int.

**Retour:**
int