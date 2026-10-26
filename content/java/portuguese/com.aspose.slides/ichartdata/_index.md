---
title: IChartData
second_title: Referência da API Aspose.Slides para Java
description: Representa os dados usados para a plotagem de um gráfico.
type: docs
url: /pt/com.aspose.slides/ichartdata/
---```
public interface IChartData
```

Representa os dados usados para a plotagem de um gráfico.
## Métodos

| Método | Descrição |
| --- | --- |
| [getChartDataWorkbook()](#getChartDataWorkbook--) | Obtém a fábrica de células para criar células usadas em séries ou categorias de gráfico. |
| [getSeries()](#getSeries--) | Obtém as séries. |
| [getSeriesGroups()](#getSeriesGroups--) | Obtém os grupos de séries. |
| [getCategories()](#getCategories--) | Obtém as categorias primárias (ou tanto as categorias primárias quanto as secundárias se a propriedade (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) for false). |
| [getUseSecondaryCategories()](#getUseSecondaryCategories--) | Se false então a propriedade (\#getSecondaryCategories.getSecondaryCategories) retorna null e os dados na propriedade (\#getCategories.getCategories) são usados tanto para séries primárias quanto secundárias. |
| [setUseSecondaryCategories(boolean value)](#setUseSecondaryCategories-boolean-) | Se false então a propriedade (\#getSecondaryCategories.getSecondaryCategories) retorna null e os dados na propriedade (\#getCategories.getCategories) são usados tanto para séries primárias quanto secundárias. |
| [getSecondaryCategories()](#getSecondaryCategories--) | Obtém as categorias secundárias se a propriedade (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) for true. |
| [readWorkbookStream()](#readWorkbookStream--) | Grava a pasta de trabalho Excel contida internamente em um fluxo de memória. |
| [writeWorkbookStream(byte[] ms)](#writeWorkbookStream-byte---) | Inicializa a pasta de trabalho Excel contida internamente com o valor especificado pelo usuário. |
| [setRange(String formula)](#setRange-java.lang.String-) | Define o intervalo de dados do gráfico. |
| [getRange()](#getRange--) | Obtém o intervalo de dados do gráfico. |
| [getDataSourceType()](#getDataSourceType--) | Representa a origem de dados do gráfico |
| [getExternalWorkbookPath()](#getExternalWorkbookPath--) | Representa o caminho da pasta de trabalho externa se a origem de dados for externa, caso contrário null |
| [getEmbeddedWorkbookType()](#getEmbeddedWorkbookType--) | Obtém o tipo da pasta de trabalho incorporada. |
| [switchRowColumn()](#switchRowColumn--) | Troca os dados entre os eixos. |
| [setExternalWorkbook(String workbookPath)](#setExternalWorkbook-java.lang.String-) | Define a pasta de trabalho externa como origem de dados para o gráfico. |
| [setExternalWorkbook(String workbookPath, boolean updateChartData)](#setExternalWorkbook-java.lang.String-boolean-) | Define a pasta de trabalho externa como origem de dados para o gráfico. |
### getChartDataWorkbook() {#getChartDataWorkbook--}
```
public abstract IChartDataWorkbook getChartDataWorkbook()
```


Obtém a fábrica de células para criar células usadas em séries ou categorias de gráfico. Somente leitura [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook).

**Retorna:**
[IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook)
### getSeries() {#getSeries--}
```
public abstract IChartSeriesCollection getSeries()
```


Obtém as séries. Somente leitura [IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection).

**Retorna:**
[IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection)
### getSeriesGroups() {#getSeriesGroups--}
```
public abstract IChartSeriesGroupCollection getSeriesGroups()
```


Obtém os grupos de séries. Somente leitura [IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection).

--------------------

1) Cada grupo de séries contém séries com tipos combináveis. Grupos de tipos de séries combináveis são definidos e descritos com o enum CombinableSeriesTypesGroup. Além disso, cada grupo de séries contém séries que são plotadas tanto no eixo primário quanto no eixo secundário (não ambos os casos em um mesmo grupo). Portanto, o princípio de agrupamento de séries é um agrupamento pelos grupos de tipo mencionados acima e pelo tipo de plotagem primário/secundário. 2) Um grupo de séries contém algumas propriedades de série que são comuns a cada série no grupo (“propriedades do grupo de séries”). As “propriedades do grupo de séries” na classe ChartSeriesGroup são leitura/gravação. Cada uma das “propriedades do grupo de séries” pode ter uma projeção somente leitura na classe ChartSeries.

**Retorna:**
[IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection)
### getCategories() {#getCategories--}
```
public abstract IChartCategoryCollection getCategories()
```


Obtém as categorias primárias (ou tanto as categorias primárias quanto as secundárias se a propriedade (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) for false). Somente leitura [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // categorias relacionadas são series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // categorias relacionadas são series.getChart().getChartData().getCategories()
>  }
```

--------------------

Se a propriedade (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) for false então a propriedade (\#getSecondaryCategories.getSecondaryCategories) retorna null e os dados nesta propriedade (\#getCategories.getCategories) são usados tanto para séries primárias quanto secundárias. Se a propriedade (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) for true então os dados na propriedade (\#getSecondaryCategories.getSecondaryCategories) são usados para séries secundárias e os dados nesta propriedade (\#getCategories.getCategories) são usados para séries primárias.

**Retorna:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)
### getUseSecondaryCategories() {#getUseSecondaryCategories--}
```
public abstract boolean getUseSecondaryCategories()
```


Se false então a propriedade (\#getSecondaryCategories.getSecondaryCategories) retorna null e os dados na propriedade (\#getCategories.getCategories) são usados tanto para séries primárias quanto secundárias. Se true então os dados na propriedade (\#getSecondaryCategories.getSecondaryCategories) são usados para séries secundárias e os dados na propriedade (\#getCategories.getCategories) são usados para séries primárias. Leitura/gravação booleano.

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // categorias relacionadas são series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // categorias relacionadas são series.getChart().getChartData().getCategories()
>  }
> ```

**Retorna:**
boolean
### setUseSecondaryCategories(boolean value) {#setUseSecondaryCategories-boolean-}
```
public abstract void setUseSecondaryCategories(boolean value)
```


Se false então a propriedade (\#getSecondaryCategories.getSecondaryCategories) retorna null e os dados na propriedade (\#getCategories.getCategories) são usados tanto para séries primárias quanto secundárias. Se true então os dados na propriedade (\#getSecondaryCategories.getSecondaryCategories) são usados para séries secundárias e os dados na propriedade (\#getCategories.getCategories) são usados para séries primárias. Leitura/gravação booleano.

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // categorias relacionadas são series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // categorias relacionadas são series.getChart().getChartData().getCategories()
>  }
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |
### getSecondaryCategories() {#getSecondaryCategories--}
```
public abstract IChartCategoryCollection getSecondaryCategories()
```


Obtém as categorias secundárias se a propriedade (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) for true. Somente leitura [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // categorias relacionadas são series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // categorias relacionadas são series.getChart().getChartData().getCategories()
>  }
> ```

--------------------

Se a propriedade (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) for false então esta propriedade (\#getSecondaryCategories.getSecondaryCategories) retorna null e os dados na propriedade (\#getCategories.getCategories) são usados tanto para séries primárias quanto secundárias. Se a propriedade (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) for true então os dados nesta propriedade (\#getSecondaryCategories.getSecondaryCategories) são usados para séries secundárias e os dados nesta propriedade (\#getCategories.getCategories) são usados para séries primárias.

**Retorna:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)
### readWorkbookStream() {#readWorkbookStream--}
```
public abstract byte[] readWorkbookStream()
```


Grava a pasta de trabalho Excel contida internamente em um fluxo de memória.

**Retorna:**
byte[] - Retorna um array de bytes contendo uma cópia da pasta de trabalho Excel contida internamente.
### writeWorkbookStream(byte[] ms) {#writeWorkbookStream-byte---}
```
public abstract void writeWorkbookStream(byte[] ms)
```


Inicializa a pasta de trabalho Excel contida internamente com o valor especificado pelo usuário.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| ms | byte[] | O fluxo fornecido pelo usuário contendo a pasta de trabalho Excel completa. |
### setRange(String formula) {#setRange-java.lang.String-}
```
public abstract void setRange(String formula)
```


Define o intervalo de dados do gráfico. Séries e categorias serão atualizadas com base no novo intervalo de dados. Se a quantidade de séries no intervalo de dados for maior que a contagem de séries nos dados do gráfico, séries adicionais com o mesmo tipo da última série da coleção atual serão adicionadas ao final da coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| formula | java.lang.String | A fórmula de intervalo de dados das células. Ex.: "Sheet1!$A$1:$C$4" , "SomeSheetName!A1:B100", "Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5". |
### getRange() {#getRange--}
```
public abstract String getRange()
```


Obtém o intervalo de dados do gráfico.

--------------------

> ```
> Presentation pres = new Presentation();
>  {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.PercentsStackedBar, 100, 100, 500, 400);
>      String result = ((ChartData)chart.getChartData()).getRange();
>  }
> ```

**Retorna:**
java.lang.String - Fórmula do intervalo de dados das células. Ex.: "Sheet1!$A$1:$C$4"
### getDataSourceType() {#getDataSourceType--}
```
public abstract int getDataSourceType()
```


Representa a origem de dados do gráfico

**Retorna:**
int
### getExternalWorkbookPath() {#getExternalWorkbookPath--}
```
public abstract String getExternalWorkbookPath()
```


Representa o caminho da pasta de trabalho externa se a origem de dados for externa, caso contrário null

**Retorna:**
java.lang.String
### getEmbeddedWorkbookType() {#getEmbeddedWorkbookType--}
```
public abstract int getEmbeddedWorkbookType()
```


Obtém o tipo da pasta de trabalho incorporada. Retorna [WorkbookType.NotDefined](../../com.aspose.slides/workbooktype\#NotDefined) se DataSourceType (\#getDataSourceType.getDataSourceType) for [ChartDataSourceType.ExternalWorkbook](../../com.aspose.slides/chartdatasourcetype\#ExternalWorkbook). Somente leitura [WorkbookType](../../com.aspose.slides/workbooktype).

**Retorna:**
int
### switchRowColumn() {#switchRowColumn--}
```
public abstract void switchRowColumn()
```


Troca os dados entre os eixos. Dados plotados no eixo X serão movidos para o eixo Y e vice-versa.
### setExternalWorkbook(String workbookPath) {#setExternalWorkbook-java.lang.String-}
```
public abstract void setExternalWorkbook(String workbookPath)
```


Define a pasta de trabalho externa como origem de dados para o gráfico. Os dados do gráfico serão atualizados a partir da pasta de trabalho alvo.

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>     IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.Pie, 50, 50, 400, 600, true);
>     IChartData chartData = chart.getChartData();
>     ((ChartData)chartData).setExternalWorkbook("../../workbook.xlsx");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| workbookPath | java.lang.String | Caminho para a pasta de trabalho alvo |
### setExternalWorkbook(String workbookPath, boolean updateChartData) {#setExternalWorkbook-java.lang.String-boolean-}
```
public abstract void setExternalWorkbook(String workbookPath, boolean updateChartData)
```


Define a pasta de trabalho externa como origem de dados para o gráfico.

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>     IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.Pie, 50, 50, 400, 600, true);
>     IChartData chartData = chart.getChartData();
>     ((ChartData)chartData).setExternalWorkbook("http://path/doesnt/exists", false);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| workbookPath | java.lang.String | Caminho para a pasta de trabalho alvo |
| updateChartData | boolean | Se o valor for false apenas o caminho da pasta de trabalho será atualizado. Os dados do gráfico não serão carregados e atualizados a partir da pasta de trabalho alvo. Pode ser usado quando a pasta de trabalho alvo não existe ou não está disponível. Se o valor for true os dados do gráfico serão atualizados a partir da pasta de trabalho alvo. |