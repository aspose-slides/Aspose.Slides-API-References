---
title: ChartData
second_title: Referencia de API de Aspose.Slides para Java
description: Representa los datos utilizados para trazar un gráfico.
type: docs
url: /es/com.aspose.slides/chartdata/
---
**Herencia:**
java.lang.Object, com.aspose.slides.DomObject

**Todas las interfaces implementadas:**
[com.aspose.slides.IChartData](../../com.aspose.slides/ichartdata)
```
public class ChartData extends DomObject<Chart> implements IChartData
```

Representa los datos utilizados para trazar un gráfico.
## Métodos

| Método | Descripción |
| --- | --- |
| [getChartDataWorkbook()](#getChartDataWorkbook--) | Obtiene la fábrica de celdas para crear celdas usadas en series o categorías del gráfico. |
| [getSeries()](#getSeries--) | Obtiene las series. |
| [getSeriesGroups()](#getSeriesGroups--) | Obtiene los grupos de series. |
| [getCategories()](#getCategories--) | Obtiene las categorías primarias (o tanto las categorías primarias como las secundarias si la propiedad #getUseSecondaryCategories.getUseSecondaryCategories/#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) es falsa). |
| [getUseSecondaryCategories()](#getUseSecondaryCategories--) | Si es falsa, la propiedad #getSecondaryCategories.getSecondaryCategories devuelve null y los datos en la propiedad #getCategories.getCategories se utilizan tanto para series primarias como secundarias. |
| [setUseSecondaryCategories(boolean value)](#setUseSecondaryCategories-boolean-) | Si es falsa, la propiedad #getSecondaryCategories.getSecondaryCategories devuelve null y los datos en la propiedad #getCategories.getCategories se utilizan tanto para series primarias como secundarias. |
| [getSecondaryCategories()](#getSecondaryCategories--) | Obtiene las categorías secundarias si la propiedad #getUseSecondaryCategories.getUseSecondaryCategories/#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) es verdadera. |
| [readWorkbookStream()](#readWorkbookStream--) | Escribe el libro de Excel contenido internamente en un flujo en memoria. |
| [writeWorkbookStream(byte[] ms)](#writeWorkbookStream-byte---) | Inicializa el libro de Excel contenido internamente con el valor especificado por el usuario. |
| [getDataSourceType()](#getDataSourceType--) | Representa la ruta del libro externo si es una fuente de datos externa, null en caso contrario |
| [getExternalWorkbookPath()](#getExternalWorkbookPath--) | Representa la fuente de datos del gráfico |
| [getEmbeddedWorkbookType()](#getEmbeddedWorkbookType--) | Obtiene el tipo del libro incrustado. |
| [getRange()](#getRange--) | Obtiene el rango de datos del gráfico. |
| [setRange(String formula)](#setRange-java.lang.String-) | Establece el rango de datos del gráfico. |
| [setExternalWorkbook(String workbookPath)](#setExternalWorkbook-java.lang.String-) | Establece el libro externo como fuente de datos para el gráfico. |
| [setExternalWorkbook(String workbookPath, boolean updateChartData)](#setExternalWorkbook-java.lang.String-boolean-) | Establece el libro externo como fuente de datos para el gráfico. |
| [refreshData()](#refreshData--) | Actualiza los datos del gráfico recargándolos desde el libro fuente. |
| [switchRowColumn()](#switchRowColumn--) | Intercambia los datos entre los ejes. |
### getChartDataWorkbook() {#getChartDataWorkbook--}
```
public final IChartDataWorkbook getChartDataWorkbook()
```

Obtiene la fábrica de celdas para crear celdas usadas en series o categorías del gráfico. Solo lectura [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook).

**Devuelve:**
[IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook)
### getSeries() {#getSeries--}
```
public final IChartSeriesCollection getSeries()
```

Obtiene las series. Solo lectura [IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection).

**Devuelve:**
[IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection)
### getSeriesGroups() {#getSeriesGroups--}
```
public final IChartSeriesGroupCollection getSeriesGroups()
```

Obtiene los grupos de series. Solo lectura [IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection).

--------------------

1) Cada grupo de series contiene series con tipos combinables. Los grupos de tipos de series combinables se definen y describen con el enumerado CombinableSeriesTypesGroup. Además, cada grupo de series contiene series que se trazan ya sea en los ejes primarios o en los ejes secundarios (no ambos casos en un mismo grupo). Por lo tanto, el principio de agrupación de series es una agrupación por los grupos de tipos mencionados anteriormente y por el tipo de trazado primario/secundario. 2) Un grupo de series contiene algunas propiedades de series que son comunes para cada serie del grupo ("propiedades del grupo de series"). Las "propiedades del grupo de series" en la clase ChartSeriesGroup son de lectura/escritura. Cada una de las "propiedades del grupo de series" puede tener una proyección de solo lectura en la clase ChartSeries.

**Devuelve:**
[IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection)
### getCategories() {#getCategories--}
```
public final IChartCategoryCollection getCategories()
```

Obtiene las categorías primarias (o tanto las categorías primarias como las secundarias si la propiedad #getUseSecondaryCategories.getUseSecondaryCategories/#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) es falsa). Solo lectura [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // las categorías relacionadas son series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // las categorías relacionadas son series.getChart().getChartData().getCategories()
>  }
> ```


--------------------

Si la propiedad #getUseSecondaryCategories.getUseSecondaryCategories/#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) es falsa, la propiedad (\#getSecondaryCategories.getSecondaryCategories) devuelve null y los datos en esta propiedad \#getCategories.getCategories se utilizan tanto para series primarias como secundarias. Si la propiedad #getUseSecondaryCategories.getUseSecondaryCategories/#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) es verdadera, los datos en la propiedad (\#getSecondaryCategories.getSecondaryCategories) se utilizan para series secundarias y los datos en esta propiedad \#getCategories.getCategories se utilizan para series primarias.

**Devuelve:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)
### getUseSecondaryCategories() {#getUseSecondaryCategories--}
```
public final boolean getUseSecondaryCategories()
```

Si es falsa, la propiedad \#getSecondaryCategories.getSecondaryCategories devuelve null y los datos en la propiedad \#getCategories.getCategories se utilizan tanto para series primarias como secundarias. Si es verdadera, los datos en la propiedad \#getSecondaryCategories.getSecondaryCategories se utilizan para series secundarias y los datos en la propiedad \#getCategories.getCategories se utilizan para series primarias. Booleano de lectura/escritura.

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // las categorías relacionadas son series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // las categorías relacionadas son series.getChart().getChartData().getCategories()
>  }
> ```

**Devuelve:**
boolean
### setUseSecondaryCategories(boolean value) {#setUseSecondaryCategories-boolean-}
```
public final void setUseSecondaryCategories(boolean value)
```

Si es falsa, la propiedad \#getSecondaryCategories.getSecondaryCategories devuelve null y los datos en la propiedad \#getCategories.getCategories se utilizan tanto para series primarias como secundarias. Si es verdadera, los datos en la propiedad \#getSecondaryCategories.getSecondaryCategories se utilizan para series secundarias y los datos en la propiedad \#getCategories.getCategories se utilizan para series primarias. Booleano de lectura/escritura.

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // las categorías relacionadas son series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // las categorías relacionadas son series.getChart().getChartData().getCategories()
>  }
> ```


**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getSecondaryCategories() {#getSecondaryCategories--}
```
public final IChartCategoryCollection getSecondaryCategories()
```

Obtiene las categorías secundarias si la propiedad #getUseSecondaryCategories.getUseSecondaryCategories/#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) es verdadera. Solo lectura [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // las categorías relacionadas son series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // las categorías relacionadas son series.getChart().getChartData().getCategories()
>  }
> ```

--------------------

Si la propiedad #getUseSecondaryCategories.getUseSecondaryCategories/#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) es falsa, esta propiedad (\#getSecondaryCategories.getSecondaryCategories) devuelve null y los datos en la propiedad \#getCategories.getCategories se utilizan tanto para series primarias como secundarias. Si la propiedad #getUseSecondaryCategories.getUseSecondaryCategories/#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) es verdadera, los datos en esta propiedad \#getSecondaryCategories.getSecondaryCategories se utilizan para series secundarias y los datos en la propiedad \#getCategories.getCategories se utilizan para series primarias.

**Devuelve:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)
### readWorkbookStream() {#readWorkbookStream--}
```
public final byte[] readWorkbookStream()
```

Escribe el libro de Excel contenido internamente en un flujo en memoria.

**Devuelve:**
byte[] - Devuelve una instancia de matriz de bytes que contiene una copia del libro de Excel contenido internamente.
### writeWorkbookStream(byte[] ms) {#writeWorkbookStream-byte---}
```
public final void writeWorkbookStream(byte[] ms)
```

Inicializa el libro de Excel contenido internamente con el valor especificado por el usuario.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ms | byte[] | El flujo suministrado por el usuario que contiene todo el libro de Excel. |

### getDataSourceType() {#getDataSourceType--}
```
public final int getDataSourceType()
```

Representa la ruta del libro externo si es una fuente de datos externa, null en caso contrario

**Devuelve:**
int
### getExternalWorkbookPath() {#getExternalWorkbookPath--}
```
public final String getExternalWorkbookPath()
```

Representa la fuente de datos del gráfico

**Devuelve:**
java.lang.String
### getEmbeddedWorkbookType() {#getEmbeddedWorkbookType--}
```
public final int getEmbeddedWorkbookType()
```

Obtiene el tipo del libro incrustado. Devuelve [WorkbookType.NotDefined](../../com.aspose.slides/workbooktype\#NotDefined) si DataSourceType (\#getDataSourceType.getDataSourceType) es [ChartDataSourceType.ExternalWorkbook](../../com.aspose.slides/chartdatasourcetype\#ExternalWorkbook). Solo lectura [WorkbookType](../../com.aspose.slides/workbooktype).

**Devuelve:**
int
### getRange() {#getRange--}
```
public final String getRange()
```

Obtiene el rango de datos del gráfico.

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

**Devuelve:**
java.lang.String - Fórmula del rango de datos de celdas. Por ejemplo: "Sheet1!$A$1:$C$4"
### setRange(String formula) {#setRange-java.lang.String-}
```
public final void setRange(String formula)
```

Establece el rango de datos del gráfico. Las series y categorías se actualizarán según el nuevo rango de datos. Si la cantidad de series en el rango de datos es mayor que el número de series en los datos del gráfico, se añadirán series adicionales del mismo tipo que la última serie de la colección actual al final de la colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| formula | java.lang.String | La fórmula del rango de datos de celdas. Por ejemplo: "Sheet1!$A$1:$C$4", "SomeSheetName!A1:B100", "Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5". |

### setExternalWorkbook(String workbookPath) {#setExternalWorkbook-java.lang.String-}
```
public final void setExternalWorkbook(String workbookPath)
```

Establece el libro externo como fuente de datos para el gráfico. Los datos del gráfico se actualizarán desde el libro de destino.

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

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| workbookPath | java.lang.String | Ruta al libro de destino |

### setExternalWorkbook(String workbookPath, boolean updateChartData) {#setExternalWorkbook-java.lang.String-boolean-}
```
public final void setExternalWorkbook(String workbookPath, boolean updateChartData)
```

Establece el libro externo como fuente de datos para el gráfico.

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


**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| workbookPath | java.lang.String | Ruta al libro de destino |
| updateChartData | boolean | Si el valor es false, solo se actualizará la ruta del libro. Los datos del gráfico no se cargarán ni actualizarán desde el libro de destino. Puede usarse cuando el libro de destino no exista o no esté disponible. Si el valor es true, los datos del gráfico se actualizarán desde el libro de destino. |

### refreshData() {#refreshData--}
```
public final void refreshData()
```

Actualiza los datos del gráfico recargándolos desde el libro fuente.

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

Intercambia los datos entre los ejes. Los datos graficados en el eje X se moverán al eje Y y viceversa.