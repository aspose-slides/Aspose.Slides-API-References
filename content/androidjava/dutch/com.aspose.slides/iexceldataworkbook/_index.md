---
title: IExcelDataWorkbook
second_title: Aspose.Slides for Android via Java API Reference
description: Stelt een werkmap voor die toegang biedt tot Excel-gegevens voor algemeen gebruik.
type: docs
url: /nl/com.aspose.slides/iexceldataworkbook/
---```
public interface IExcelDataWorkbook
```

Stelt een werkmap voor die toegang biedt tot Excel-gegevens voor algemeen gebruik.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getCells(String formula, boolean skipHiddenCells)](#getCells-java.lang.String-boolean-) | Haalt een verzameling cellen op uit de werkmap die voldoen aan de opgegeven formule. |
| [getCell(int worksheetIndex, int row, int column)](#getCell-int-int-int-) | Haalt een cel op uit het opgegeven werkblad met behulp van de index en celcoördinaten. |
| [getCell(String worksheetName, int row, int column)](#getCell-java.lang.String-int-int-) | Haalt een cel op uit het opgegeven werkblad met behulp van de naam en celcoördinaten. |
| [getCell(int worksheetIndex, String cellName)](#getCell-int-java.lang.String-) | Haalt een cel op uit het opgegeven werkblad met behulp van de index en de Excel-achtige celnaam (bijv. "B2"). |
| [getCell(String worksheetName, String cellName)](#getCell-java.lang.String-java.lang.String-) | Haalt een cel op uit het opgegeven werkblad met behulp van de Excel-achtige celnaam (bijv. "B2"). |
| [getChartsFromWorksheet(String worksheetName)](#getChartsFromWorksheet-java.lang.String-) | Haalt een woordenboek op dat de indexen en namen van alle grafieken bevat in het opgegeven werkblad van een Excel-werkmap. |
| [getWorksheetNames()](#getWorksheetNames--) | Haalt de namen op van alle werkbladen die zich in de Excel-werkmap bevinden. |
### getCells(String formula, boolean skipHiddenCells) {#getCells-java.lang.String-boolean-}
```
public abstract System.Collections.Generic.List<IExcelDataCell> getCells(String formula, boolean skipHiddenCells)
```


Haalt een verzameling cellen op uit de werkmap die voldoen aan de opgegeven formule.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  List<IExcelDataCell> cells = wb.getCells("Sheet1!A2:A6", false);
>  System.out.println(cells.size()); //Uitvoer: 5
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| formula | java.lang.String | Een formule of bereikexpressie (bijv. "Sheet1!A1:B3") die wordt gebruikt om doelcellen te identificeren. |
| skipHiddenCells | boolean | Indien true, worden verborgen cellen (bijv. in verborgen rijen of kolommen) uitgesloten van het resultaat. |

**Retourneert:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.slides.IExcelDataCell> - Een alleen-lezen lijst van cellen die voldoen aan de opgegeven formule.
### getCell(int worksheetIndex, int row, int column) {#getCell-int-int-int-}
```
public abstract IExcelDataCell getCell(int worksheetIndex, int row, int column)
```


Haalt een cel op uit het opgegeven werkblad met behulp van de index en celcoördinaten.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getValue().toString());
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| worksheetIndex | int | Nulgebaseerde index van het werkblad. |
| row | int | Nulgebaseerde rij-index van de cel. |
| column | int | Nulgebaseerde kolom-index van de cel. |

**Retourneert:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - De cel op de opgegeven locatie.
### getCell(String worksheetName, int row, int column) {#getCell-java.lang.String-int-int-}
```
public abstract IExcelDataCell getCell(String worksheetName, int row, int column)
```


Haalt een cel op uit het opgegeven werkblad met behulp van de naam en celcoördinaten.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell("Sheet1", 1, 1);
>  System.out.println(cell.getValue().toString());
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| worksheetName | java.lang.String | De naam van het werkblad. |
| row | int | Nulgebaseerde rij-index van de cel. |
| column | int | Nulgebaseerde kolom-index van de cel. |

**Retourneert:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - De cel op de opgegeven locatie.
### getCell(int worksheetIndex, String cellName) {#getCell-int-java.lang.String-}
```
public abstract IExcelDataCell getCell(int worksheetIndex, String cellName)
```


Haalt een cel op uit het opgegeven werkblad met behulp van de index en de Excel-achtige celnaam (bijv. "B2").

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, "B2");
>  System.out.println(cell.getValue().toString());
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| worksheetIndex | int | Nulgebaseerde index van het werkblad. |
| cellName | java.lang.String | De Excel-achtige celreferentie (bijv. "A1", "C5"). |

**Retourneert:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - De cel op de opgegeven locatie.
### getCell(String worksheetName, String cellName) {#getCell-java.lang.String-java.lang.String-}
```
public abstract IExcelDataCell getCell(String worksheetName, String cellName)
```


Haalt een cel op uit het opgegeven werkblad met behulp van de Excel-achtige celnaam (bijv. "B2").

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell("Sheet1", "B2");
>  System.out.println(cell.getValue().toString());
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| worksheetName | java.lang.String | De naam van het werkblad. |
| cellName | java.lang.String | De Excel-achtige celreferentie (bijv. "A1", "C5"). |

**Retourneert:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - De cel op de opgegeven locatie.
### getChartsFromWorksheet(String worksheetName) {#getChartsFromWorksheet-java.lang.String-}
```
public abstract System.Collections.Generic.Dictionary<Integer,String> getChartsFromWorksheet(String worksheetName)
```


Haalt een woordenboek op dat de indexen en namen van alle grafieken bevat in het opgegeven werkblad van een Excel-werkmap.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  Dictionary.Enumerator<Integer, String> sheetCharts = wb.getChartsFromWorksheet("worksheetName").iterator();
>  while (sheetCharts.hasNext())
>  {
>      KeyValuePair<Integer, String> chart = sheetCharts.next();
>      System.out.println(chart.getKey() + " : " + chart.getValue());
>  }
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| worksheetName | java.lang.String | De naam van het werkblad om naar grafieken te zoeken. |

**Retourneert:**
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.Integer,java.lang.String> - Een woordenboek waarbij de sleutel de grafiekindex is en de waarde de grafieknaam is.
### getWorksheetNames() {#getWorksheetNames--}
```
public abstract System.Collections.Generic.List<String> getWorksheetNames()
```


Haalt de namen op van alle werkbladen die zich in de Excel-werkmap bevinden.

--------------------

> ```
> Example:
>  
>  IExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  List<String> sheetNames = wb.getWorksheetNames();
>  for (String name : sheetNames)
>      System.out.println(name);
> ```

**Retourneert:**
com.aspose.ms.System.Collections.Generic.List<java.lang.String> - Een lijst van werkbladnamen