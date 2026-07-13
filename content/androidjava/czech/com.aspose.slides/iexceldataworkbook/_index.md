---
title: IExcelDataWorkbook
second_title: Aspose.Slides for Android via Java API Reference
description: Represents a workbook that provides access to Excel data for general use.
type: docs
url: /cs/com.aspose.slides/iexceldataworkbook/
---```
public interface IExcelDataWorkbook
```

Representuje sešit, který poskytuje přístup k datům Excelu pro obecné použití.
## Metody

| Metoda | Popis |
| --- | --- |
| [getCells(String formula, boolean skipHiddenCells)](#getCells-java.lang.String-boolean-) | Načte kolekci buněk ze sešitu, které odpovídají zadanému vzorci. |
| [getCell(int worksheetIndex, int row, int column)](#getCell-int-int-int-) | Načte buňku z uvedeného listu pomocí jeho indexu a souřadnic buňky. |
| [getCell(String worksheetName, int row, int column)](#getCell-java.lang.String-int-int-) | Načte buňku z uvedeného listu pomocí jeho názvu a souřadnic buňky. |
| [getCell(int worksheetIndex, String cellName)](#getCell-int-java.lang.String-) | Načte buňku z uvedeného listu pomocí jeho indexu a názvu buňky ve stylu Excel (např. "B2"). |
| [getCell(String worksheetName, String cellName)](#getCell-java.lang.String-java.lang.String-) | Načte buňku z uvedeného listu pomocí názvu buňky ve stylu Excel (např. "B2"). |
| [getChartsFromWorksheet(String worksheetName)](#getChartsFromWorksheet-java.lang.String-) | Načte slovník obsahující indexy a názvy všech grafů v uvedeném listu sešitu Excel. |
| [getWorksheetNames()](#getWorksheetNames--) | Načte názvy všech listů obsažených v sešitu Excel. |
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
>  ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| formula | java.lang.String | Vzorec nebo rozsahový výraz (např. "Sheet1!A1:B3") použitý k určení cílových buněk. |
| skipHiddenCells | boolean | Pokud je true, skryté buňky (např. ve skrytých řádcích nebo sloupcích) budou vyloučeny z výsledku. |

**Návratová hodnota:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.slides.IExcelDataCell> - Seznam buněk jen pro čtení, který odpovídá zadanému vzorci.
### getCell(int worksheetIndex, int row, int column) {#getCell-int-int-int-}
```
public abstract IExcelDataCell getCell(int worksheetIndex, int row, int column)
```


Načte buňku z uvedeného listu pomocí jeho indexu a souřadnic buňky.

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
| worksheetIndex | int | Index listu (číslování od nuly). |
| row | int | Index řádku buňky (číslování od nuly). |
| column | int | Index sloupce buňky (číslování od nuly). |

**Návratová hodnota:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - Buňka na zadané pozici.
### getCell(String worksheetName, int row, int column) {#getCell-java.lang.String-int-int-}
```
public abstract IExcelDataCell getCell(String worksheetName, int row, int column)
```


Načte buňku z uvedeného listu pomocí jeho názvu a souřadnic buňky.

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
| row | int | Index řádku buňky (číslování od nuly). |
| column | int | Index sloupce buňky (číslování od nuly). |

**Návratová hodnota:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - Buňka na zadané pozici.
### getCell(int worksheetIndex, String cellName) {#getCell-int-java.lang.String-}
```
public abstract IExcelDataCell getCell(int worksheetIndex, String cellName)
```


Načte buňku z uvedeného listu pomocí jeho indexu a názvu buňky ve stylu Excel (např. "B2").

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
| worksheetIndex | int | Index listu (číslování od nuly). |
| cellName | java.lang.String | Reference buňky ve stylu Excel (např. "A1", "C5"). |

**Návratová hodnota:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - Buňka na zadané pozici.
### getCell(String worksheetName, String cellName) {#getCell-java.lang.String-java.lang.String-}
```
public abstract IExcelDataCell getCell(String worksheetName, String cellName)
```


Načte buňku z uvedeného listu pomocí názvu buňky ve stylu Excel (např. "B2").

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
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - Buňka na zadané pozici.
### getChartsFromWorksheet(String worksheetName) {#getChartsFromWorksheet-java.lang.String-}
```
public abstract System.Collections.Generic.Dictionary<Integer,String> getChartsFromWorksheet(String worksheetName)
```


Načte slovník obsahující indexy a názvy všech grafů v uvedeném listu sešitu Excel.

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


Načte názvy všech listů obsažených v sešitu Excel.

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