---
title: IExcelDataWorkbook
second_title: Aspose.Slides for Android via Java API Reference
description: Represents a workbook that provides access to Excel data for general use.
type: docs
url: /pt/com.aspose.slides/iexceldataworkbook/
---```
public interface IExcelDataWorkbook
```

Representa uma pasta de trabalho que fornece acesso a dados do Excel para uso geral.
## Métodos

| Método | Descrição |
| --- | --- |
| [getCells(String formula, boolean skipHiddenCells)](#getCells-java.lang.String-boolean-) | Retrieves a collection of cells from the workbook that match the specified formula. |
| [getCell(int worksheetIndex, int row, int column)](#getCell-int-int-int-) | Retrieves a cell from the specified worksheet using its index and cell coordinates. |
| [getCell(String worksheetName, int row, int column)](#getCell-java.lang.String-int-int-) | Retrieves a cell from the specified worksheet using its name and cell coordinates. |
| [getCell(int worksheetIndex, String cellName)](#getCell-int-java.lang.String-) | Retrieves a cell from the specified worksheet using its index and Excel-style cell name (e.g., "B2"). |
| [getCell(String worksheetName, String cellName)](#getCell-java.lang.String-java.lang.String-) | Retrieves a cell from the specified worksheet using Excel-style cell name (e.g., "B2"). |
| [getChartsFromWorksheet(String worksheetName)](#getChartsFromWorksheet-java.lang.String-) | Retrieves a dictionary containing the indexes and names of all charts in the specified worksheet of an Excel workbook. |
| [getWorksheetNames()](#getWorksheetNames--) | Retrieves the names of all worksheets contained in the Excel workbook. |
### getCells(String formula, boolean skipHiddenCells) {#getCells-java.lang.String-boolean-}
```
public abstract System.Collections.Generic.List<IExcelDataCell> getCells(String formula, boolean skipHiddenCells)
```


Recupera uma coleção de células da pasta de trabalho que correspondem à fórmula especificada.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  List<IExcelDataCell> cells = wb.getCells("Sheet1!A2:A6", false);
>  System.out.println(cells.size()); //Saída: 5
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| formula | java.lang.String | Uma fórmula ou expressão de intervalo (e.g., "Sheet1!A1:B3") usada para identificar as células-alvo. |
| skipHiddenCells | boolean | Se true, células ocultas (e.g., in hidden rows or columns) serão excluídas do resultado. |

**Retorna:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.slides.IExcelDataCell> - Uma lista somente leitura de células que correspondem à fórmula especificada.
### getCell(int worksheetIndex, int row, int column) {#getCell-int-int-int-}
```
public abstract IExcelDataCell getCell(int worksheetIndex, int row, int column)
```


Recupera uma célula da planilha especificada usando seu índice e coordenadas da célula.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getValue().toString());
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| worksheetIndex | int | Índice baseado em zero da planilha. |
| row | int | Índice da linha baseado em zero da célula. |
| column | int | Índice da coluna baseado em zero da célula. |

**Retorna:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - A célula na localização especificada.
### getCell(String worksheetName, int row, int column) {#getCell-java.lang.String-int-int-}
```
public abstract IExcelDataCell getCell(String worksheetName, int row, int column)
```


Recupera uma célula da planilha especificada usando seu nome e coordenadas da célula.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell("Sheet1", 1, 1);
>  System.out.println(cell.getValue().toString());
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| worksheetName | java.lang.String | O nome da planilha. |
| row | int | Índice da linha baseado em zero da célula. |
| column | int | Índice da coluna baseado em zero da célula. |

**Retorna:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - A célula na localização especificada.
### getCell(int worksheetIndex, String cellName) {#getCell-int-java.lang.String-}
```
public abstract IExcelDataCell getCell(int worksheetIndex, String cellName)
```


Recupera uma célula da planilha especificada usando seu índice e o nome da célula no estilo Excel (e.g., "B2").

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, "B2");
>  System.out.println(cell.getValue().toString());
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| worksheetIndex | int | Índice baseado em zero da planilha. |
| cellName | java.lang.String | A referência da célula no estilo Excel (e.g., "A1", "C5"). |

**Retorna:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - A célula na localização especificada.
### getCell(String worksheetName, String cellName) {#getCell-java.lang.String-java.lang.String-}
```
public abstract IExcelDataCell getCell(String worksheetName, String cellName)
```


Recupera uma célula da planilha especificada usando o nome da célula no estilo Excel (e.g., "B2").

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell("Sheet1", "B2");
>  System.out.println(cell.getValue().toString());
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| worksheetName | java.lang.String | O nome da planilha. |
| cellName | java.lang.String | A referência da célula no estilo Excel (e.g., "A1", "C5"). |

**Retorna:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - A célula na localização especificada.
### getChartsFromWorksheet(String worksheetName) {#getChartsFromWorksheet-java.lang.String-}
```
public abstract System.Collections.Generic.Dictionary<Integer,String> getChartsFromWorksheet(String worksheetName)
```


Recupera um dicionário contendo os índices e nomes de todos os gráficos na planilha especificada de uma pasta de trabalho do Excel.

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

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| worksheetName | java.lang.String | O nome da planilha onde procurar os gráficos. |

**Retorna:**
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.Integer,java.lang.String> - Um dicionário onde a chave é o índice do gráfico e o valor é o nome do gráfico.
### getWorksheetNames() {#getWorksheetNames--}
```
public abstract System.Collections.Generic.List<String> getWorksheetNames()
```


Recupera os nomes de todas as planilhas contidas na pasta de trabalho do Excel.

--------------------

> ```
> Example:
>  
>  IExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  List<String> sheetNames = wb.getWorksheetNames();
>  for (String name : sheetNames)
>      System.out.println(name);
> ```

**Retorna:**
com.aspose.ms.System.Collections.Generic.List<java.lang.String> - Uma lista de nomes de planilhas