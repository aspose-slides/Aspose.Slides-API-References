---
title: ExcelDataWorkbook
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa uma pasta de trabalho que fornece acesso a dados do Excel para uso geral.
type: docs
url: /pt/com.aspose.slides/exceldataworkbook/
---
**Herança:**
java.lang.Object

**Todas as interfaces implementadas:**
[com.aspose.slides.IExcelDataWorkbook](../../com.aspose.slides/iexceldataworkbook)
```
public class ExcelDataWorkbook implements IExcelDataWorkbook
```

Representa uma pasta de trabalho que fornece acesso a dados do Excel para uso geral.
## Construtores

| Construtor | Descrição |
| --- | --- |
| [ExcelDataWorkbook(String filePath)](#ExcelDataWorkbook-java.lang.String-) | Inicializa uma nova instância usando o caminho de arquivo especificado. |
| [ExcelDataWorkbook(InputStream stream)](#ExcelDataWorkbook-java.io.InputStream-) | Inicializa uma nova instância da classe usando o fluxo fornecido. |
## Métodos

| Método | Descrição |
| --- | --- |
| [getCells(String formula, boolean skipHiddenCells)](#getCells-java.lang.String-boolean-) | Recupera uma coleção de células da pasta de trabalho que correspondem à fórmula especificada. |
| [getCell(int worksheetIndex, int row, int column)](#getCell-int-int-int-) | Recupera uma célula da planilha especificada usando seu índice e coordenadas da célula. |
| [getCell(String worksheetName, int row, int column)](#getCell-java.lang.String-int-int-) | Recupera uma célula da planilha especificada usando seu nome e coordenadas da célula. |
| [getCell(int worksheetIndex, String cellName)](#getCell-int-java.lang.String-) | Recupera uma célula da planilha especificada usando seu índice e o nome da célula no estilo Excel (por exemplo, "B2"). |
| [getCell(String worksheetName, String cellName)](#getCell-java.lang.String-java.lang.String-) | Recupera uma célula da planilha especificada usando o nome da célula no estilo Excel (por exemplo, "B2"). |
| [getChartsFromWorksheet(String worksheetName)](#getChartsFromWorksheet-java.lang.String-) | Recupera um dicionário contendo os índices e nomes de todos os gráficos na planilha especificada de uma pasta de trabalho do Excel. |
| [getWorksheetNames()](#getWorksheetNames--) | Recupera os nomes de todas as planilhas contidas na pasta de trabalho do Excel. |
### ExcelDataWorkbook(String filePath) {#ExcelDataWorkbook-java.lang.String-}
```
public ExcelDataWorkbook(String filePath)
```

Inicializa uma nova instância usando o caminho de arquivo especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| filePath | java.lang.String | O caminho completo para o arquivo da pasta de trabalho do Excel. |
### ExcelDataWorkbook(InputStream stream) {#ExcelDataWorkbook-java.io.InputStream-}
```
public ExcelDataWorkbook(InputStream stream)
```

Inicializa uma nova instância da classe usando o fluxo fornecido.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| stream | java.io.InputStream | Um fluxo contendo os dados da pasta de trabalho do Excel. |
### getCells(String formula, boolean skipHiddenCells) {#getCells-java.lang.String-boolean-}
```
public final System.Collections.Generic.List<IExcelDataCell> getCells(String formula, boolean skipHiddenCells)
```

Recupera uma coleção de células da pasta de trabalho que correspondem à fórmula especificada.

--------------------

> ```
> ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  List<IExcelDataCell> cells = wb.getCells("Sheet1!A2:A6", false);
>  System.out.println(cells.size()); //Output: 5
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| formula | java.lang.String | Uma fórmula ou expressão de intervalo (por exemplo, "Sheet1!A1:B3") usada para identificar as células de destino. |
| skipHiddenCells | boolean | Se verdadeiro, células ocultas (por exemplo, em linhas ou colunas ocultas) serão excluídas do resultado. |

**Retorna:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.slides.IExcelDataCell> - Uma lista somente leitura de células que correspondem à fórmula especificada.
### getCell(int worksheetIndex, int row, int column) {#getCell-int-int-int-}
```
public final IExcelDataCell getCell(int worksheetIndex, int row, int column)
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
| row | int | Índice baseado em zero da linha da célula. |
| column | int | Índice baseado em zero da coluna da célula. |

**Retorna:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - A célula na localização especificada.
### getCell(String worksheetName, int row, int column) {#getCell-java.lang.String-int-int-}
```
public final IExcelDataCell getCell(String worksheetName, int row, int column)
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
| row | int | Índice baseado em zero da linha da célula. |
| column | int | Índice baseado em zero da coluna da célula. |

**Retorna:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - A célula na localização especificada.
### getCell(int worksheetIndex, String cellName) {#getCell-int-java.lang.String-}
```
public final IExcelDataCell getCell(int worksheetIndex, String cellName)
```

Recupera uma célula da planilha especificada usando seu índice e o nome da célula no estilo Excel (por exemplo, "B2").

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
| cellName | java.lang.String | A referência da célula no estilo Excel (por exemplo, "A1", "C5"). |

**Retorna:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - A célula na localização especificada.
### getCell(String worksheetName, String cellName) {#getCell-java.lang.String-java.lang.String-}
```
public final IExcelDataCell getCell(String worksheetName, String cellName)
```

Recupera uma célula da planilha especificada usando o nome da célula no estilo Excel (por exemplo, "B2").

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
| cellName | java.lang.String | A referência da célula no estilo Excel (por exemplo, "A1", "C5"). |

**Retorna:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - A célula na localização especificada.
### getChartsFromWorksheet(String worksheetName) {#getChartsFromWorksheet-java.lang.String-}
```
public final System.Collections.Generic.Dictionary<Integer,String> getChartsFromWorksheet(String worksheetName)
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
| worksheetName | java.lang.String | O nome da planilha a ser pesquisada por gráficos. |

**Retorna:**
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.Integer,java.lang.String> - Um dicionário onde a chave é o índice do gráfico e o valor é o nome do gráfico.
### getWorksheetNames() {#getWorksheetNames--}
```
public final System.Collections.Generic.List<String> getWorksheetNames()
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