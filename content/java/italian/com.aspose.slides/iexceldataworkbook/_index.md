---
title: IExcelDataWorkbook
second_title: Aspose.Slides for Java API Reference
description: Represents a workbook that provides access to Excel data for general use.
type: docs
url: /it/com.aspose.slides/iexceldataworkbook/
---```
public interface IExcelDataWorkbook
```

Rappresenta un workbook che fornisce accesso ai dati Excel per uso generale.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getCells(String formula, boolean skipHiddenCells)](#getCells-java.lang.String-boolean-) | Recupera una collezione di celle dal workbook che corrispondono alla formula specificata. |
| [getCell(int worksheetIndex, int row, int column)](#getCell-int-int-int-) | Recupera una cella dal foglio di lavoro specificato usando il suo indice e le coordinate della cella. |
| [getCell(String worksheetName, int row, int column)](#getCell-java.lang.String-int-int-) | Recupera una cella dal foglio di lavoro specificato usando il suo nome e le coordinate della cella. |
| [getCell(int worksheetIndex, String cellName)](#getCell-int-java.lang.String-) | Recupera una cella dal foglio di lavoro specificato usando il suo indice e il nome della cella in stile Excel (es., "B2"). |
| [getCell(String worksheetName, String cellName)](#getCell-java.lang.String-java.lang.String-) | Recupera una cella dal foglio di lavoro specificato usando il nome della cella in stile Excel (es., "B2"). |
| [getChartsFromWorksheet(String worksheetName)](#getChartsFromWorksheet-java.lang.String-) | Recupera un dizionario contenente gli indici e i nomi di tutti i grafici nel foglio di lavoro specificato di un workbook Excel. |
| [getWorksheetNames()](#getWorksheetNames--) | Recupera i nomi di tutti i fogli di lavoro contenuti nel workbook Excel. |
### getCells(String formula, boolean skipHiddenCells) {#getCells-java.lang.String-boolean-}
```
public abstract System.Collections.Generic.List<IExcelDataCell> getCells(String formula, boolean skipHiddenCells)
```

Recupera una collezione di celle dal workbook che corrispondono alla formula specificata.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  List<IExcelDataCell> cells = wb.getCells("Sheet1!A2:A6", false);
>  System.out.println(cells.size()); //Uscita: 5
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| formula | java.lang.String | Una formula o un'espressione di intervallo (es., "Sheet1!A1:B3") utilizzata per identificare le celle di destinazione. |
| skipHiddenCells | boolean | Se true, le celle nascoste (es., in righe o colonne nascoste) saranno escluse dal risultato. |

**Restituisce:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.slides.IExcelDataCell> - Una lista di sola lettura di celle che corrispondono alla formula specificata.
### getCell(int worksheetIndex, int row, int column) {#getCell-int-int-int-}
```
public abstract IExcelDataCell getCell(int worksheetIndex, int row, int column)
```

Recupera una cella dal foglio di lavoro specificato usando il suo indice e le coordinate della cella.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getValue().toString());
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| worksheetIndex | int | Indice basato su zero del foglio di lavoro. |
| row | int | Indice di riga basato su zero della cella. |
| column | int | Indice di colonna basato su zero della cella. |

**Restituisce:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - La cella nella posizione specificata.
### getCell(String worksheetName, int row, int column) {#getCell-java.lang.String-int-int-}
```
public abstract IExcelDataCell getCell(String worksheetName, int row, int column)
```

Recupera una cella dal foglio di lavoro specificato usando il suo nome e le coordinate della cella.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell("Sheet1", 1, 1);
>  System.out.println(cell.getValue().toString());
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| worksheetName | java.lang.String | Il nome del foglio di lavoro. |
| row | int | Indice di riga basato su zero della cella. |
| column | int | Indice di colonna basato su zero della cella. |

**Restituisce:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - La cella nella posizione specificata.
### getCell(int worksheetIndex, String cellName) {#getCell-int-java.lang.String-}
```
public abstract IExcelDataCell getCell(int worksheetIndex, String cellName)
```

Recupera una cella dal foglio di lavoro specificato usando il suo indice e il nome della cella in stile Excel (es., "B2").

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, "B2");
>  System.out.println(cell.getValue().toString());
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| worksheetIndex | int | Indice basato su zero del foglio di lavoro. |
| cellName | java.lang.String | Il riferimento di cella in stile Excel (es., "A1", "C5"). |

**Restituisce:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - La cella nella posizione specificata.
### getCell(String worksheetName, String cellName) {#getCell-java.lang.String-java.lang.String-}
```
public abstract IExcelDataCell getCell(String worksheetName, String cellName)
```

Recupera una cella dal foglio di lavoro specificato usando il nome della cella in stile Excel (es., "B2").

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell("Sheet1", "B2");
>  System.out.println(cell.getValue().toString());
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| worksheetName | java.lang.String | Il nome del foglio di lavoro. |
| cellName | java.lang.String | Il riferimento di cella in stile Excel (es., "A1", "C5"). |

**Restituisce:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - La cella nella posizione specificata.
### getChartsFromWorksheet(String worksheetName) {#getChartsFromWorksheet-java.lang.String-}
```
public abstract System.Collections.Generic.Dictionary<Integer,String> getChartsFromWorksheet(String worksheetName)
```

Recupera un dizionario contenente gli indici e i nomi di tutti i grafici nel foglio di lavoro specificato di un workbook Excel.

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

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| worksheetName | java.lang.String | Il nome del foglio di lavoro in cui cercare i grafici. |

**Restituisce:**
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.Integer,java.lang.String> - Un dizionario dove la chiave è l'indice del grafico e il valore è il nome del grafico.
### getWorksheetNames() {#getWorksheetNames--}
```
public abstract System.Collections.Generic.List<String> getWorksheetNames()
```

Recupera i nomi di tutti i fogli di lavoro contenuti nel workbook Excel.

--------------------

> ```
> Example:
>  
>  IExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  List<String> sheetNames = wb.getWorksheetNames();
>  for (String name : sheetNames)
>      System.out.println(name);
> ```

**Restituisce:**
com.aspose.ms.System.Collections.Generic.List<java.lang.String> - Una lista di nomi dei fogli di lavoro