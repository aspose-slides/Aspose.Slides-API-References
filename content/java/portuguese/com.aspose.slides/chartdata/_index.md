---
title: ChartData
second_title: Referência da API Aspose.Slides para Java
description: Representa os dados usados para a plotagem de um gráfico.
type: docs
url: /pt/com.aspose.slides/chartdata/
---
**Herança:**
java.lang.Object, com.aspose.slides.DomObject

**Todas as Interfaces Implementadas:**
[com.aspose.slides.IChartData](../../com.aspose.slides/ichartdata)
```
public class ChartData extends DomObject<Chart> implements IChartData
```

Representa os dados usados para a plotagem de um gráfico.
## Métodos

| Método | Descrição |
| --- | --- |
| [getChartDataWorkbook()](#getChartDataWorkbook--) | Obtém a fábrica de células para criar células usadas em séries ou categorias de gráfico. |
| [getSeries()](#getSeries--) | Obtém as séries. |
| [getSeriesGroups()](#getSeriesGroups--) | Obtém os grupos de séries. |
| [getCategories()](#getCategories--) | Obtém as categorias principais (ou tanto as categorias principais quanto as secundárias se a propriedade \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) for false). |
| [getUseSecondaryCategories()](#getUseSecondaryCategories--) | Se false então a propriedade \#getSecondaryCategories.getSecondaryCategories retorna null e os dados na propriedade \#getCategories.getCategories são usados tanto para séries principais quanto para secundárias. |
| [setUseSecondaryCategories(boolean value)](#setUseSecondaryCategories-boolean-) | Se false então a propriedade \#getSecondaryCategories.getSecondaryCategories retorna null e os dados na propriedade \#getCategories.getCategories são usados tanto para séries principais quanto para secundárias. |
| [getSecondaryCategories()](#getSecondaryCategories--) | Obtém as categorias secundárias se a propriedade \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) for true. |
| [readWorkbookStream()](#readWorkbookStream--) | Grava o workbook Excel interno em um fluxo de memória. |
| [writeWorkbookStream(byte[] ms)](#writeWorkbookStream-byte---) | Inicializa o workbook Excel interno com o valor especificado pelo usuário. |
| [getDataSourceType()](#getDataSourceType--) | Representa o caminho do workbook externo se a fonte de dados for externa, caso contrário null. |
| [getExternalWorkbookPath()](#getExternalWorkbookPath--) | Representa a fonte de dados do gráfico. |
| [getEmbeddedWorkbookType()](#getEmbeddedWorkbookType--) | Obtém o tipo do workbook incorporado. |
| [getRange()](#getRange--) | Obtém o intervalo de dados do gráfico. |
| [setRange(String formula)](#setRange-java.lang.String-) | Define o intervalo de dados do gráfico. |
| [setExternalWorkbook(String workbookPath)](#setExternalWorkbook-java.lang.String-) | Define o workbook externo como fonte de dados para o gráfico. |
| [setExternalWorkbook(String workbookPath, boolean updateChartData)](#setExternalWorkbook-java.lang.String-boolean-) | Define o workbook externo como fonte de dados para o gráfico. |
| [refreshData()](#refreshData--) | Atualiza os dados do gráfico recarregando-os a partir do workbook fonte. |
| [switchRowColumn()](#switchRowColumn--) | Inverte os dados ao longo do eixo. |

### getChartDataWorkbook() {#getChartDataWorkbook--}
```
public final IChartDataWorkbook getChartDataWorkbook()
```

Obtém a fábrica de células para criar células usadas em séries ou categorias de gráfico. Somente leitura [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook).

**Retorna:**
[IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook)
### getSeries() {#getSeries--}
```
public final IChartSeriesCollection getSeries()
```

Obtém as séries. Somente leitura [IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection).

**Retorna:**
[IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection)
### getSeriesGroups() {#getSeriesGroups--}
```
public final IChartSeriesGroupCollection getSeriesGroups()
```

Obtém os grupos de séries. Somente leitura [IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection).

--------------------

1) Cada grupo de séries contém séries com tipos combináveis. Os grupos de tipos de séries combináveis são definidos e descritos com o enum CombinableSeriesTypesGroup. Além disso, cada grupo de séries contém séries que são plotadas tanto no eixo primário quanto no eixo secundário (não ambos os casos em um mesmo grupo). Portanto, o princípio de agrupamento de séries é o agrupamento por grupos de tipos mencionados acima e por tipo de plotagem primária/secundária. 2) O grupo de séries contém algumas propriedades de séries que são comuns a cada série no grupo (“propriedades do grupo de séries”). As “propriedades do grupo de séries” na classe ChartSeriesGroup são leitura/gravação. Cada uma das “propriedades do grupo de séries” pode ter uma projeção somente leitura na classe ChartSeries.

**Retorna:**
[IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection)
### getCategories() {#getCategories--}
```
public final IChartCategoryCollection getCategories()
```

Obtém as categorias principais (ou tanto as categorias principais quanto as secundárias se a propriedade \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) for false). Somente leitura [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

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

Se \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) for false então a propriedade (\#getSecondaryCategories.getSecondaryCategories) retorna null e os dados nesta propriedade \#getCategories.getCategories são usados tanto para séries principais quanto para secundárias. Se a propriedade for true então os dados na propriedade (\#getSecondaryCategories.getSecondaryCategories) são usados para séries secundárias e os dados na propriedade \#getCategories.getCategories são usados para séries principais.

**Retorna:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)
### getUseSecondaryCategories() {#getUseSecondaryCategories--}
```
public final boolean getUseSecondaryCategories()
```

Se false então a propriedade \#getSecondaryCategories.getSecondaryCategories retorna null e os dados na propriedade \#getCategories.getCategories são usados tanto para séries principais quanto para secundárias. Se true então os dados na propriedade \#getSecondaryCategories.getSecondaryCategories são usados para séries secundárias e os dados na propriedade \#getCategories.getCategories são usados para séries principais. Leitura/Gravação boolean.

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
public final void setUseSecondaryCategories(boolean value)
```

Se false então a propriedade \#getSecondaryCategories.getSecondaryCategories retorna null e os dados na propriedade \#getCategories.getCategories são usados tanto para séries principais quanto para secundárias. Se true então os dados na propriedade \#getSecondaryCategories.getSecondaryCategories são usados para séries secundárias e os dados na propriedade \#getCategories.getCategories são usados para séries principais. Leitura/Gravação boolean.

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
public final IChartCategoryCollection getSecondaryCategories()
```

Obtém as categorias secundárias se a propriedade \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) for true. Somente leitura [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

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

Se \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) for false então esta propriedade (\#getSecondaryCategories.getSecondaryCategories) retorna null e os dados na propriedade \#getCategories.getCategories são usados tanto para séries principais quanto para secundárias. Se a propriedade for true então os dados nesta propriedade \#getSecondaryCategories.getSecondaryCategories são usados para séries secundárias e os dados na propriedade \#getCategories.getCategories são usados para séries principais.

**Retorna:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)
### readWorkbookStream() {#readWorkbookStream--}
```
public final byte[] readWorkbookStream()
```

Grava o workbook Excel interno em um fluxo de memória.

**Retorna:**
byte[] - Retorna uma instância de array de bytes contendo uma cópia do workbook Excel interno.
### writeWorkbookStream(byte[] ms) {#writeWorkbookStream-byte---}
```
public final void writeWorkbookStream(byte[] ms)
```

Inicializa o workbook Excel interno com o valor especificado pelo usuário.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| ms | byte[] | O fluxo fornecido pelo usuário contendo o workbook Excel completo. |

### getDataSourceType() {#getDataSourceType--}
```
public final int getDataSourceType()
```

Representa o caminho do workbook externo se a fonte de dados for externa, caso contrário null.

**Retorna:**
int
### getExternalWorkbookPath() {#getExternalWorkbookPath--}
```
public final String getExternalWorkbookPath()
```

Representa a fonte de dados do gráfico.

**Retorna:**
java.lang.String
### getEmbeddedWorkbookType() {#getEmbeddedWorkbookType--}
```
public final int getEmbeddedWorkbookType()
```

Obtém o tipo do workbook incorporado. Retorna [WorkbookType.NotDefined](../../com.aspose.slides/workbooktype\#NotDefined) se DataSourceType (\#getDataSourceType.getDataSourceType) for [ChartDataSourceType.ExternalWorkbook](../../com.aspose.slides/chartdatasourcetype\#ExternalWorkbook). Somente leitura [WorkbookType](../../com.aspose.slides/workbooktype).

**Retorna:**
int
### getRange() {#getRange--}
```
public final String getRange()
```

Obtém o intervalo de dados do gráfico.

--------------------

> ```
> Presentation pres = new Presentation();
>   try {
>       IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.PercentsStackedBar, 0, 0, 100, 100);
>       String result = ((ChartData)chart.getChartData()).getRange();
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```

**Retorna:**
java.lang.String - Fórmula do intervalo de dados de células. Ex.: "Sheet1!$A$1:$C$4"
### setRange(String formula) {#setRange-java.lang.String-}
```
public final void setRange(String formula)
```

Define o intervalo de dados do gráfico. As séries e categorias serão atualizadas com base no novo intervalo de dados. Se a quantidade de séries no intervalo de dados for maior que a contagem de séries nos dados do gráfico, séries adicionais com o mesmo tipo da última série na coleção atual serão adicionadas ao final da coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| formula | java.lang.String | A fórmula do intervalo de dados de células. Ex.: "Sheet1!$A$1:$C$4" , "SomeSheetName!A1:B100", "Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5". |

### setExternalWorkbook(String workbookPath) {#setExternalWorkbook-java.lang.String-}
```
public final void setExternalWorkbook(String workbookPath)
```

Define o workbook externo como fonte de dados para o gráfico. Os dados do gráfico serão atualizados a partir do workbook de destino.

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>     IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.Pie, 50, 50, 400, 600, true);
>     IChartData chartData = chart.getChartData();
>     ((ChartData)chartData).setExternalWorkbook("../../workbook.xlsx");
>  } finally {
>     if (pres != null) pres.dispose();
>  }
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| workbookPath | java.lang.String | Caminho para o workbook de destino |

### setExternalWorkbook(String workbookPath, boolean updateChartData) {#setExternalWorkbook-java.lang.String-boolean-}
```
public final void setExternalWorkbook(String workbookPath, boolean updateChartData)
```

Define o workbook externo como fonte de dados para o gráfico.

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.Pie, 50, 50, 400, 600, true);
>      IChartData chartData = chart.getChartData();
>      ((ChartData).setExternalWorkbook("http://path/doesnt/exists", false);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| workbookPath | java.lang.String | Caminho para o workbook de destino |
| updateChartData | boolean | Se o valor for false, somente o caminho do workbook será atualizado. Os dados do gráfico não serão carregados e atualizados a partir do workbook de destino. Pode ser usado quando o workbook de destino não existe ou não está disponível. Se o valor for true, os dados do gráfico serão atualizados a partir do workbook de destino. |

### refreshData() {#refreshData--}
```
public final void refreshData()
```

Atualiza os dados do gráfico recarregando-os a partir do workbook fonte.

--------------------

> ```
> Presentation presentation = new Presentation("presentationWithChart.pptx");
>  try {
>      IChart chart = (IChart)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>      chart.getChartData().refreshData();
>  } finally {
>      presentation.dispose();
>  }
> ```

### switchRowColumn() {#switchRowColumn--}
```
public final void switchRowColumn()
```

Inverte os dados ao longo do eixo. Os dados plotados no eixo X serão movidos para o eixo Y e vice-versa.