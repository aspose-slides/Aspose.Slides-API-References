---
title: ExcelDataWorkbook
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt een werkmap voor die toegang biedt tot Excel-gegevens voor algemeen gebruik.
type: docs
url: /nl/com.aspose.slides/exceldataworkbook/
---
**Erfenis:**
java.lang.Object

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IExcelDataWorkbook](../../com.aspose.slides/iexceldataworkbook)
```
public class ExcelDataWorkbook implements IExcelDataWorkbook
```

Stelt een werkmap voor die toegang biedt tot Excel-gegevens voor algemeen gebruik.
## Constructoren

| Constructor | Beschrijving |
| --- | --- |
| [ExcelDataWorkbook(String filePath)](#ExcelDataWorkbook-java.lang.String-) | Initialiseert een nieuw exemplaar met het opgegeven bestandspad. |
| [ExcelDataWorkbook(InputStream stream)](#ExcelDataWorkbook-java.io.InputStream-) | Initialiseert een nieuw exemplaar van de klasse met de opgegeven stream. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getCells(String formula, boolean skipHiddenCells)](#getCells-java.lang.String-boolean-) | Haalt een verzameling cellen op uit de werkmap die overeenkomen met de opgegeven formule. |
| [getCell(int worksheetIndex, int row, int column)](#getCell-int-int-int-) | Haalt een cel op uit het opgegeven werkblad met behulp van de index en celcoördinaten. |
| [getCell(String worksheetName, int row, int column)](#getCell-java.lang.String-int-int-) | Haalt een cel op uit het opgegeven werkblad met behulp van de naam en celcoördinaten. |
| [getCell(int worksheetIndex, String cellName)](#getCell-int-java.lang.String-) | Haalt een cel op uit het opgegeven werkblad met behulp van de index en Excel-stijl celnaam (bijv. “B2”). |
| [getCell(String worksheetName, String cellName)](#getCell-java.lang.String-java.lang.String-) | Haalt een cel op uit het opgegeven werkblad met Excel-stijl celnaam (bijv. “B2”). |
| [getChartsFromWorksheet(String worksheetName)](#getChartsFromWorksheet-java.lang.String-) | Haalt een dictionary op met de indexen en namen van alle diagrammen in het opgegeven werkblad van een Excel-werkmap. |
| [getWorksheetNames()](#getWorksheetNames--) | Haalt de namen op van alle werkbladen die in de Excel-werkmap staan. |
### ExcelDataWorkbook(String filePath) {#ExcelDataWorkbook-java.lang.String-}
```
public ExcelDataWorkbook(String filePath)
```


Initialiseert een nieuw exemplaar met het opgegeven bestandspad.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filePath | java.lang.String | Het volledige pad naar het Excel-werkmap-bestand. |

### ExcelDataWorkbook(InputStream stream) {#ExcelDataWorkbook-java.io.InputStream-}
```
public ExcelDataWorkbook(InputStream stream)
```


Initialiseert een nieuw exemplaar van de klasse met de opgegeven stream.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | java.io.InputStream | Een stream met de Excel-werkmap-gegevens. |

### getCells(String formula, boolean skipHiddenCells) {#getCells-java.lang.String-boolean-}
```
public final System.Collections.Generic.List<IExcelDataCell> getCells(String formula, boolean skipHiddenCells)
```


Haal een verzameling cellen op uit de werkmap die overeenkomen met de opgegeven formule.

--------------------

> ```
> ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  List<IExcelDataCell> cells = wb.getCells("Sheet1!A2:A6", false);
>  System.out.println(cells.size()); //Output: 5
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| formula | java.lang.String | Een formule- of bereikexpressie (bijv. “Sheet1!A1:B3”) om de doelcellen te identificeren. |
| skipHiddenCells | boolean | Indien true, worden verborgen cellen (bijv. in verborgen rijen of kolommen) uitgesloten van het resultaat. |

**Retourwaarde:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.slides.IExcelDataCell> - Een alleen-lezen lijst met cellen die overeenkomen met de opgegeven formule.
### getCell(int worksheetIndex, int row, int column) {#getCell-int-int-int-}
```
public final IExcelDataCell getCell(int worksheetIndex, int row, int column)
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
| worksheetIndex | int | Nul-gebaseerde index van het werkblad. |
| row | int | Nul-gebaseerde rij-index van de cel. |
| column | int | Nul-gebaseerde kolom-index van de cel. |

**Retourwaarde:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - De cel op de opgegeven locatie.
### getCell(String worksheetName, int row, int column) {#getCell-java.lang.String-int-int-}
```
public final IExcelDataCell getCell(String worksheetName, int row, int column)
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
| row | int | Nul-gebaseerde rij-index van de cel. |
| column | int | Nul-gebaseerde kolom-index van de cel. |

**Retourwaarde:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - De cel op de opgegeven locatie.
### getCell(int worksheetIndex, String cellName) {#getCell-int-java.lang.String-}
```
public final IExcelDataCell getCell(int worksheetIndex, String cellName)
```


Haalt een cel op uit het opgegeven werkblad met behulp van de index en Excel-stijl celnaam (bijv. “B2”).

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
| worksheetIndex | int | Nul-gebaseerde index van het werkblad. |
| cellName | java.lang.String | De Excel-stijl celreferentie (bijv. “A1”, “C5”). |

**Retourwaarde:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - De cel op de opgegeven locatie.
### getCell(String worksheetName, String cellName) {#getCell-java.lang.String-java.lang.String-}
```
public final IExcelDataCell getCell(String worksheetName, String cellName)
```


Haalt een cel op uit het opgegeven werkblad met Excel-stijl celnaam (bijv. “B2”).

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
| cellName | java.lang.String | De Excel-stijl celreferentie (bijv. “A1”, “C5”). |

**Retourwaarde:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - De cel op de opgegeven locatie.
### getChartsFromWorksheet(String worksheetName) {#getChartsFromWorksheet-java.lang.String-}
```
public final System.Collections.Generic.Dictionary<Integer,String> getChartsFromWorksheet(String worksheetName)
```


Haalt een dictionary op met de indexen en namen van alle diagrammen in het opgegeven werkblad van een Excel-werkmap.

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
| worksheetName | java.lang.String | De naam van het werkblad waarin naar diagrammen wordt gezocht. |

**Retourwaarde:**
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.Integer,java.lang.String> - Een dictionary waarbij de sleutel de diagramindex is en de waarde de diagramnaam.
### getWorksheetNames() {#getWorksheetNames--}
```
public final System.Collections.Generic.List<String> getWorksheetNames()
```


Haalt de namen op van alle werkbladen die in de Excel-werkmap staan.

--------------------

> ```
> Example:
>  
>  IExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  List<String> sheetNames = wb.getWorksheetNames();
>  for (String name : sheetNames)
>      System.out.println(name);
> ```


**Retourwaarde:**
com.aspose.ms.System.Collections.Generic.List<java.lang.String> - Een lijst met werkbladnamen