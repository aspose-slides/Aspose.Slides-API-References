---
title: IExcelDataWorkbook
second_title: Aspose.Slides for Java API Reference
description: Představuje sešit, který poskytuje přístup k Excelovým datům pro obecné použití.
type: docs
url: /cs/com.aspose.slides/iexceldataworkbook/
---```
public interface IExcelDataWorkbook
```

Představuje sešit, který poskytuje přístup k Excelovým datům pro obecné použití.
## Metody

| Metoda | Popis |
| --- | --- |
| [getCells(String formula, boolean skipHiddenCells)](#getCells-java.lang.String-boolean-) | Načte kolekci buněk ze sešitu, které odpovídají zadanému vzorci. |
| [getCell(int worksheetIndex, int row, int column)](#getCell-int-int-int-) | Načte buňku ze zadaného listu pomocí jejího indexu a souřadnic buňky. |
| [getCell(String worksheetName, int row, int column)](#getCell-java.lang.String-int-int-) | Načte buňku ze zadaného listu pomocí jejího názvu a souřadnic buňky. |
| [getCell(int worksheetIndex, String cellName)](#getCell-int-java.lang.String-) | Načte buňku ze zadaného listu pomocí jejího indexu a názvu buňky ve stylu Excel (např. "B2"). |
| [getCell(String worksheetName, String cellName)](#getCell-java.lang.String-java.lang.String-) | Načte buňku ze zadaného listu pomocí názvu buňky ve stylu Excel (např. "B2"). |
| [getChartsFromWorksheet(String worksheetName)](#getChartsFromWorksheet-java.lang.String-) | Načte slovník obsahující indexy a názvy všech grafů v zadaném listu Excelového sešitu. |
| [getWorksheetNames()](#getWorksheetNames--) | Načte názvy všech listů obsažených v Excelovém sešitu. |
### getCells(String formula, boolean skipHiddenCells) {#getCells-java.lang.String-boolean-}
```
public abstract System.Collections.Generic.List<IExcelDataCell> getCells(String formula, boolean skipHiddenCells)
```

Načte kolekci buněk ze sešitu, které odpovídají zadanému vzorci.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  List<IExcelDataCell> cells = wb.getCells("Sheet1!A2:A6", false);
>  System.out.println(cells.size()); //Výstup: 5
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| formula | java.lang.String | Vzorec nebo výraz rozsahu (např. "Sheet1!A1:B3") použité k určení cílových buněk. |
| skipHiddenCells | boolean | Pokud je true, skryté buňky (např. ve skrytých řádcích nebo sloupcích) budou z výsledku vyloučeny. |

**Návratová hodnota:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.slides.IExcelDataCell> - Seznam buněk, které odpovídají zadanému vzorci, jen pro čtení.
### getCell(int worksheetIndex, int row, int column) {#getCell-int-int-int-}
```
public abstract IExcelDataCell getCell(int worksheetIndex, int row, int column)
```

Načte buňku ze zadaného listu pomocí jejího indexu a souřadnic buňky.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getValue().toString());
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| worksheetIndex | int | Index listu založený na nule. |
| row | int | Index řádku buňky založený na nule. |
| column | int | Index sloupce buňky založený na nule. |

**Návratová hodnota:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - Buňka na určeném místě.
### getCell(String worksheetName, int row, int column) {#getCell-java.lang.String-int-int-}
```
public abstract IExcelDataCell getCell(String worksheetName, int row, int column)
```

Načte buňku ze zadaného listu pomocí jejího názvu a souřadnic buňky.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell("Sheet1", 1, 1);
>  System.out.println(cell.getValue().toString());
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| worksheetName | java.lang.String | Název listu. |
| row | int | Index řádku buňky založený na nule. |
| column | int | Index sloupce buňky založený na nule. |

**Návratová hodnota:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - Buňka na určeném místě.
### getCell(int worksheetIndex, String cellName) {#getCell-int-java.lang.String-}
```
public abstract IExcelDataCell getCell(int worksheetIndex, String cellName)
```

Načte buňku ze zadaného listu pomocí jejího indexu a názvu buňky ve stylu Excel (např. "B2").

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, "B2");
>  System.out.println(cell.getValue().toString());
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| worksheetIndex | int | Index listu založený na nule. |
| cellName | java.lang.String | Reference buňky ve stylu Excel (např. "A1", "C5"). |

**Návratová hodnota:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - Buňka na určeném místě.
### getCell(String worksheetName, String cellName) {#getCell-java.lang.String-java.lang.String-}
```
public abstract IExcelDataCell getCell(String worksheetName, String cellName)
```

Načte buňku ze zadaného listu pomocí názvu buňky ve stylu Excel (např. "B2").

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell("Sheet1", "B2");
>  System.out.println(cell.getValue().toString());
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| worksheetName | java.lang.String | Název listu. |
| cellName | java.lang.String | Reference buňky ve stylu Excel (např. "A1", "C5"). |

**Návratová hodnota:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - Buňka na určeném místě.
### getChartsFromWorksheet(String worksheetName) {#getChartsFromWorksheet-java.lang.String-}
```
public abstract System.Collections.Generic.Dictionary<Integer,String> getChartsFromWorksheet(String worksheetName)
```

Načte slovník obsahující indexy a názvy všech grafů v zadaném listu Excelového sešitu.

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


**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| worksheetName | java.lang.String | Název listu, ve kterém se mají hledat grafy. |

**Návratová hodnota:**
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.Integer,java.lang.String> - Slovník, kde klíč je index grafu a hodnota je název grafu.
### getWorksheetNames() {#getWorksheetNames--}
```
public abstract System.Collections.Generic.List<String> getWorksheetNames()
```

Načte názvy všech listů obsažených v Excelovém sešitu.

--------------------

> ```
> Example:
>  
>  IExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  List<String> sheetNames = wb.getWorksheetNames();
>  for (String name : sheetNames)
>      System.out.println(name);
> ```

**Návratová hodnota:**
com.aspose.ms.System.Collections.Generic.List<java.lang.String> - Seznam názvů listů