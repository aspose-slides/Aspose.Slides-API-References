---
title: ExcelDataWorkbook
second_title: Aspose.Slides pro Android pomocí Java API Reference
description: Představuje sešit, který poskytuje přístup k datům Excel pro obecné použití.
type: docs
url: /cs/com.aspose.slides/exceldataworkbook/
---
**Dědičnost:**
java.lang.Object

**Všechny implementované rozhraní:**
[com.aspose.slides.IExcelDataWorkbook](../../com.aspose.slides/iexceldataworkbook)
```
public class ExcelDataWorkbook implements IExcelDataWorkbook
```

Representuje sešit, který poskytuje přístup k datům Excel pro obecné použití.
## Konstruktory

| Konstruktor | Popis |
| --- | --- |
| [ExcelDataWorkbook(String filePath)](#ExcelDataWorkbook-java.lang.String-) | Inicializuje novou instanci pomocí zadané cesty k souboru. |
| [ExcelDataWorkbook(InputStream stream)](#ExcelDataWorkbook-java.io.InputStream-) | Inicializuje novou instanci třídy pomocí poskytnutého proudu. |
## Metody

| Metoda | Popis |
| --- | --- |
| [getCells(String formula, boolean skipHiddenCells)](#getCells-java.lang.String-boolean-) | Načte sbírku buněk ze sešitu, které odpovídají zadanému vzorci. |
| [getCell(int worksheetIndex, int row, int column)](#getCell-int-int-int-) | Načte buňku z určeného listu pomocí jeho indexu a souřadnic buňky. |
| [getCell(String worksheetName, int row, int column)](#getCell-java.lang.String-int-int-) | Načte buňku z určeného listu pomocí jeho názvu a souřadnic buňky. |
| [getCell(int worksheetIndex, String cellName)](#getCell-int-java.lang.String-) | Načte buňku z určeného listu pomocí jeho indexu a názvu buňky ve stylu Excel (např. "B2"). |
| [getCell(String worksheetName, String cellName)](#getCell-java.lang.String-java.lang.String-) | Načte buňku z určeného listu pomocí názvu buňky ve stylu Excel (např. "B2"). |
| [getChartsFromWorksheet(String worksheetName)](#getChartsFromWorksheet-java.lang.String-) | Načte slovník obsahující indexy a názvy všech grafů v určeném listu sešitu Excel. |
| [getWorksheetNames()](#getWorksheetNames--) | Načte názvy všech listů obsažených v sešitu Excel. |
### ExcelDataWorkbook(String filePath) {#ExcelDataWorkbook-java.lang.String-}
```
public ExcelDataWorkbook(String filePath)
```

Inicializuje novou instanci pomocí zadané cesty k souboru.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| filePath | java.lang.String | Úplná cesta k souboru sešitu Excel. |

### ExcelDataWorkbook(InputStream stream) {#ExcelDataWorkbook-java.io.InputStream-}
```
public ExcelDataWorkbook(InputStream stream)
```

Inicializuje novou instanci třídy pomocí poskytnutého proudu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| stream | java.io.InputStream | Proud obsahující data sešitu Excel. |

### getCells(String formula, boolean skipHiddenCells) {#getCells-java.lang.String-boolean-}
```
public final System.Collections.Generic.List<IExcelDataCell> getCells(String formula, boolean skipHiddenCells)
```

Načte sbírku buněk ze sešitu, které odpovídají zadanému vzorci.

--------------------

> ```
> ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  List<IExcelDataCell> cells = wb.getCells("Sheet1!A2:A6", false);
>  System.out.println(cells.size()); //Výstup: 5
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| formula | java.lang.String | Vzorec nebo výraz rozsahu (např. "Sheet1!A1:B3") používaný k určení cílových buněk. |
| skipHiddenCells | boolean | Pokud je true, skryté buňky (např. ve skrytých řádcích nebo sloupcích) budou z výsledku vyloučeny. |

**Vrací:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.slides.IExcelDataCell> - Seznam buněk pouze pro čtení, které odpovídají zadanému vzorci.
### getCell(int worksheetIndex, int row, int column) {#getCell-int-int-int-}
```
public final IExcelDataCell getCell(int worksheetIndex, int row, int column)
```

Načte buňku z určeného listu pomocí jeho indexu a souřadnic buňky.

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
| worksheetIndex | int | Index listu od nuly. |
| row | int | Index řádku buňky od nuly. |
| column | int | Index sloupce buňky od nuly. |

**Vrací:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - Buňka na zadaném místě.
### getCell(String worksheetName, int row, int column) {#getCell-java.lang.String-int-int-}
```
public final IExcelDataCell getCell(String worksheetName, int row, int column)
```

Načte buňku z určeného listu pomocí jeho názvu a souřadnic buňky.

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
| row | int | Index řádku buňky od nuly. |
| column | int | Index sloupce buňky od nuly. |

**Vrací:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - Buňka na zadaném místě.
### getCell(int worksheetIndex, String cellName) {#getCell-int-java.lang.String-}
```
public final IExcelDataCell getCell(int worksheetIndex, String cellName)
```

Načte buňku z určeného listu pomocí jeho indexu a názvu buňky ve stylu Excel (např. "B2").

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
| worksheetIndex | int | Index listu od nuly. |
| cellName | java.lang.String | Reference buňky ve stylu Excel (např. "A1", "C5"). |

**Vrací:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - Buňka na zadaném místě.
### getCell(String worksheetName, String cellName) {#getCell-java.lang.String-java.lang.String-}
```
public final IExcelDataCell getCell(String worksheetName, String cellName)
```

Načte buňku z určeného listu pomocí názvu buňky ve stylu Excel (např. "B2").

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

**Vrací:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - Buňka na zadaném místě.
### getChartsFromWorksheet(String worksheetName) {#getChartsFromWorksheet-java.lang.String-}
```
public final System.Collections.Generic.Dictionary<Integer,String> getChartsFromWorksheet(String worksheetName)
```

Načte slovník obsahující indexy a názvy všech grafů v určeném listu sešitu Excel.

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
| worksheetName | java.lang.String | Název listu, ve kterém se mají vyhledat grafy. |

**Vrací:**
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.Integer,java.lang.String> - Slovník, kde klíč je index grafu a hodnota je název grafu.
### getWorksheetNames() {#getWorksheetNames--}
```
public final System.Collections.Generic.List<String> getWorksheetNames()
```

Načte názvy všech listů obsažených v sešitu Excel.

--------------------

> ```
> Příklad:
>  
>  IExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  List<String> sheetNames = wb.getWorksheetNames();
>  for (String name : sheetNames)
>      System.out.println(name);
> ```

**Vrací:**
com.aspose.ms.System.Collections.Generic.List<java.lang.String> - Seznam názvů listů