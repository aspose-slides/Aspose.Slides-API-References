---
title: IChartData
second_title: Aspose.Slides for Android via Java API Reference
description: Representa los datos utilizados para trazar un gráfico.
type: docs
url: /es/com.aspose.slides/ichartdata/
---```
public interface IChartData
```

Representa los datos utilizados para trazar un gráfico.
## Métodos

| Método | Descripción |
| --- | --- |
| [getChartDataWorkbook()](#getChartDataWorkbook--) | Obtiene la fábrica de celdas para crear celdas utilizadas en series o categorías del gráfico. |
| [getSeries()](#getSeries--) | Obtiene las series. |
| [getSeriesGroups()](#getSeriesGroups--) | Obtiene los grupos de series. |
| [getCategories()](#getCategories--) | Obtiene las categorías principales (o tanto las categorías principales como las secundarias si la propiedad (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) es falsa). |
| [getUseSecondaryCategories()](#getUseSecondaryCategories--) | Si es falsa, la propiedad (\#getSecondaryCategories.getSecondaryCategories) devuelve null y los datos en la propiedad (\#getCategories.getCategories) se utilizan tanto para series principales como secundarias. |
| [setUseSecondaryCategories(boolean value)](#setUseSecondaryCategories-boolean-) | Si es falsa, la propiedad (\#getSecondaryCategories.getSecondaryCategories) devuelve null y los datos en la propiedad (\#getCategories.getCategories) se utilizan tanto para series principales como secundarias. |
| [getSecondaryCategories()](#getSecondaryCategories--) | Obtiene las categorías secundarias si la propiedad (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) es verdadera. |
| [readWorkbookStream()](#readWorkbookStream--) | Escribe el libro de Excel contenido internamente en un flujo en memoria. |
| [writeWorkbookStream(byte[] ms)](#writeWorkbookStream-byte---) | Inicializa el libro de Excel contenido internamente con el valor especificado por el usuario. |
| [setRange(String formula)](#setRange-java.lang.String-) | Establece el rango de datos del gráfico. |
| [getRange()](#getRange--) | Obtiene el rango de datos del gráfico. |
| [getDataSourceType()](#getDataSourceType--) | Representa la fuente de datos del gráfico |
| [getExternalWorkbookPath()](#getExternalWorkbookPath--) | Representa la ruta del libro externo si la fuente de datos es externa, null en caso contrario |
| [getEmbeddedWorkbookType()](#getEmbeddedWorkbookType--) | Obtiene el tipo del libro incrustado. |
| [switchRowColumn()](#switchRowColumn--) | Intercambia los datos entre los ejes. |
| [setExternalWorkbook(String workbookPath)](#setExternalWorkbook-java.lang.String-) | Establece el libro externo como fuente de datos para el gráfico. |
| [setExternalWorkbook(String workbookPath, boolean updateChartData)](#setExternalWorkbook-java.lang.String-boolean-) | Establece el libro externo como fuente de datos para el gráfico. |
### getChartDataWorkbook() {#getChartDataWorkbook--}
```
public abstract IChartDataWorkbook getChartDataWorkbook()
```

Obtiene la fábrica de celdas para crear celdas utilizadas en series o categorías del gráfico. Solo lectura [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook).

**Devuelve:**
[IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook)
### getSeries() {#getSeries--}
```
public abstract IChartSeriesCollection getSeries()
```

Obtiene las series. Solo lectura [IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection).

**Devuelve:**
[IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection)
### getSeriesGroups() {#getSeriesGroups--}
```
public abstract IChartSeriesGroupCollection getSeriesGroups()
```

Obtiene los grupos de series. Solo lectura [IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection).

--------------------

1) Cada grupo de series contiene series con tipos combinables. Los grupos de tipos de series combinables están definidos y descritos con el enumerado CombinableSeriesTypesGroup. Además, cada grupo de series contiene series que se trazan ya sea en los ejes principales o en los ejes secundarios (no en ambos casos dentro de un mismo grupo). Por lo tanto, el principio de agrupación de series es una agrupación por los grupos de tipos mencionados anteriormente y por el tipo de trazado principal/secundario. 2) Un grupo de series contiene algunas propiedades de series que son comunes a cada serie del grupo ("propiedades del grupo de series"). Las "propiedades del grupo de series" en la clase ChartSeriesGroup son lectura/escritura. Cada una de las "propiedades del grupo de series" puede tener una proyección de solo lectura en la clase ChartSeries.

**Devuelve:**
[IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection)
### getCategories() {#getCategories--}
```
public abstract IChartCategoryCollection getCategories()
```

Obtiene las categorías principales (o tanto las categorías principales como las secundarias si la propiedad (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) es falsa). Solo lectura [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

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

Si la propiedad (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) es falsa, la propiedad (\#getSecondaryCategories.getSecondaryCategories) devuelve null y los datos en esta propiedad (\#getCategories.getCategories) se utilizan tanto para series principales como secundarias. Si la propiedad (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) es verdadera, los datos en la propiedad (\#getSecondaryCategories.getSecondaryCategories) se utilizan para series secundarias y los datos en esta propiedad (\#getCategories.getCategories) se utilizan para series principales.

**Devuelve:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)
### getUseSecondaryCategories() {#getUseSecondaryCategories--}
```
public abstract boolean getUseSecondaryCategories()
```

Si es falsa, la propiedad (\#getSecondaryCategories.getSecondaryCategories) devuelve null y los datos en la propiedad (\#getCategories.getCategories) se utilizan tanto para series principales como secundarias. Si es verdadera, los datos en la propiedad (\#getSecondaryCategories.getSecondaryCategories) se utilizan para series secundarias y los datos en la propiedad (\#getCategories.getCategories) se utilizan para series principales. Lectura/escritura booleano.

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
public abstract void setUseSecondaryCategories(boolean value)
```

Si es falsa, la propiedad (\#getSecondaryCategories.getSecondaryCategories) devuelve null y los datos en la propiedad (\#getCategories.getCategories) se utilizan tanto para series principales como secundarias. Si es verdadera, los datos en la propiedad (\#getSecondaryCategories.getSecondaryCategories) se utilizan para series secundarias y los datos en la propiedad (\#getCategories.getCategories) se utilizan para series principales. Lectura/escritura booleano.

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
public abstract IChartCategoryCollection getSecondaryCategories()
```

Obtiene las categorías secundarias si la propiedad (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) es verdadera. Solo lectura [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

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

Si la propiedad (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) es falsa, esta propiedad (\#getSecondaryCategories.getSecondaryCategories) devuelve null y los datos en la propiedad (\#getCategories.getCategories) se utilizan tanto para series principales como secundarias. Si la propiedad (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) es verdadera, los datos en esta propiedad (\#getSecondaryCategories.getSecondaryCategories) se utilizan para series secundarias y los datos en la propiedad (\#getCategories.getCategories) se utilizan para series principales.

**Devuelve:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)
### readWorkbookStream() {#readWorkbookStream--}
```
public abstract byte[] readWorkbookStream()
```

Escribe el libro de Excel contenido internamente en un flujo en memoria.

**Devuelve:**
byte[] - Devuelve una matriz de bytes que contiene una copia del libro de Excel contenido internamente.
### writeWorkbookStream(byte[] ms) {#writeWorkbookStream-byte---}
```
public abstract void writeWorkbookStream(byte[] ms)
```

Inicializa el libro de Excel contenido internamente con el valor especificado por el usuario.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ms | byte[] | El flujo suministrado por el usuario que contiene todo el libro de Excel. |
### setRange(String formula) {#setRange-java.lang.String-}
```
public abstract void setRange(String formula)
```

Establece el rango de datos del gráfico. Las series y categorías se actualizarán en función del nuevo rango de datos. Si la cantidad de series en el rango de datos es mayor que el número de series en los datos del gráfico, se añadirán series adicionales con el mismo tipo que la última serie de la colección actual al final de la colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| formula | java.lang.String | La fórmula del rango de datos de celdas. Por ejemplo: "Sheet1!$A$1:$C$4", "SomeSheetName!A1:B100", "Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5". |
### getRange() {#getRange--}
```
public abstract String getRange()
```

Obtiene el rango de datos del gráfico.

--------------------

> ```
> Presentation pres = new Presentation();
>  {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.PercentsStackedBar, 100, 100, 500, 400);
>      String result = ((ChartData)chart.getChartData()).getRange();
>  }
> ```

**Devuelve:**
java.lang.String - Fórmula del rango de datos de celdas. Por ejemplo: "Sheet1!$A$1:$C$4"
### getDataSourceType() {#getDataSourceType--}
```
public abstract int getDataSourceType()
```

Representa la fuente de datos del gráfico

**Devuelve:**
int
### getExternalWorkbookPath() {#getExternalWorkbookPath--}
```
public abstract String getExternalWorkbookPath()
```

Representa la ruta del libro externo si la fuente de datos es externa, null en caso contrario

**Devuelve:**
java.lang.String
### getEmbeddedWorkbookType() {#getEmbeddedWorkbookType--}
```
public abstract int getEmbeddedWorkbookType()
```

Obtiene el tipo del libro incrustado. Devuelve [WorkbookType.NotDefined](../../com.aspose.slides/workbooktype\#NotDefined) si DataSourceType (\#getDataSourceType.getDataSourceType) es [ChartDataSourceType.ExternalWorkbook](../../com.aspose.slides/chartdatasourcetype\#ExternalWorkbook). Solo lectura [WorkbookType](../../com.aspose.slides/workbooktype).

**Devuelve:**
int
### switchRowColumn() {#switchRowColumn--}
```
public abstract void switchRowColumn()
```

Intercambia los datos entre los ejes. Los datos representados en el eje X se moverán al eje Y y viceversa.

### setExternalWorkbook(String workbookPath) {#setExternalWorkbook-java.lang.String-}
```
public abstract void setExternalWorkbook(String workbookPath)
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
>      if (pres != null) pres.dispose();
>  }
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| workbookPath | java.lang.String | Ruta al libro de destino |
### setExternalWorkbook(String workbookPath, boolean updateChartData) {#setExternalWorkbook-java.lang.String-boolean-}
```
public abstract void setExternalWorkbook(String workbookPath, boolean updateChartData)
```

Establece el libro externo como fuente de datos para el gráfico.

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

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| workbookPath | java.lang.String | Ruta al libro de destino |
| updateChartData | boolean | Si el valor es false, solo se actualizará la ruta del libro. Los datos del gráfico no se cargarán ni actualizarán desde el libro de destino. Puede usarse cuando el libro de destino no existe o no está disponible. Si el valor es true, los datos del gráfico se actualizarán desde el libro de destino. |