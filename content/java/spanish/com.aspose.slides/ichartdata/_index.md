---  
title: IChartData  
second_title: Aspose.Slides for Java API Reference  
description: Represents data used for a chart plotting.  
type: docs  
url: /es/com.aspose.slides/ichartdata/  
---```
public interface IChartData
```

Representa los datos utilizados para la representación de un gráfico.  
## Methods  

| Method | Description |
| --- | --- |
| [getChartDataWorkbook()](#getChartDataWorkbook--) | Obtiene la fábrica de celdas para crear celdas utilizadas en series o categorías del gráfico. |
| [getSeries()](#getSeries--) | Obtiene las series. |
| [getSeriesGroups()](#getSeriesGroups--) | Obtiene los grupos de series. |
| [getCategories()](#getCategories--) | Obtiene las categorías principales (o tanto las categorías principales como las secundarias si la propiedad (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) es false). |
| [getUseSecondaryCategories()](#getUseSecondaryCategories--) | Si es false, la propiedad (\#getSecondaryCategories.getSecondaryCategories) devuelve null y los datos en la propiedad (\#getCategories.getCategories) se usan tanto para series primarias como secundarias. |
| [setUseSecondaryCategories(boolean value)](#setUseSecondaryCategories-boolean-) | Si es false, la propiedad (\#getSecondaryCategories.getSecondaryCategories) devuelve null y los datos en la propiedad (\#getCategories.getCategories) se usan tanto para series primarias como secundarias. |
| [getSecondaryCategories()](#getSecondaryCategories--) | Obtiene las categorías secundarias si la propiedad (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) es true. |
| [readWorkbookStream()](#readWorkbookStream--) | Escribe el libro de Excel contenido internamente en un flujo en memoria. |
| [writeWorkbookStream(byte[] ms)](#writeWorkbookStream-byte---) | Inicializa el libro de Excel contenido internamente con el valor especificado por el usuario. |
| [setRange(String formula)](#setRange-java.lang.String-) | Establece el rango de datos del gráfico. |
| [getRange()](#getRange--) | Obtiene el rango de datos del gráfico. |
| [getDataSourceType()](#getDataSourceType--) | Representa la fuente de datos del gráfico |
| [getExternalWorkbookPath()](#getExternalWorkbookPath--) | Representa la ruta del libro externo si la fuente de datos es externa, null en caso contrario |
| [getEmbeddedWorkbookType()](#getEmbeddedWorkbookType--) | Obtiene el tipo del libro incrustado. |
| [switchRowColumn()](#switchRowColumn--) | Intercambia los datos a lo largo del eje. |
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

1) Cada grupo de series contiene series con tipos combinables. Los grupos de tipos de series combinables se definen y describen con el enum CombinableSeriesTypesGroup. Además, cada grupo de series contiene series que se representan ya sea en los ejes primarios o en los secundarios (no ambos casos en un mismo grupo). Por lo tanto, el principio de agrupación de series es una agrupación por los tipos de grupos mencionados y por el tipo de representación primaria/secundaria. 2) Un grupo de series contiene algunas propiedades de serie que son comunes a cada serie del grupo ("propiedades del grupo de series"). Las "propiedades del grupo de series" en la clase ChartSeriesGroup son lectura/escritura. Cada una de las "propiedades del grupo de series" puede tener una proyección de solo lectura en la clase ChartSeries.

**Devuelve:**  
[IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection)

### getCategories() {#getCategories--}
```
public abstract IChartCategoryCollection getCategories()
```

Obtiene las categorías principales (o tanto las categorías principales como las secundarias si la propiedad (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) es false). Solo lectura [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

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

Si la propiedad (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) es false, entonces la propiedad (\#getSecondaryCategories.getSecondaryCategories) devuelve null y los datos en esta propiedad (\#getCategories.getCategories) se usan tanto para series primarias como secundarias. Si la propiedad es true, los datos en la propiedad (\#getSecondaryCategories.getSecondaryCategories) se usan para series secundarias y los datos en esta propiedad (\#getCategories.getCategories) se usan para series primarias.

**Devuelve:**  
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)

### getUseSecondaryCategories() {#getUseSecondaryCategories--}
```
public abstract boolean getUseSecondaryCategories()
```

Si es false, la propiedad (\#getSecondaryCategories.getSecondaryCategories) devuelve null y los datos en la propiedad (\#getCategories.getCategories) se usan tanto para series primarias como secundarias. Si es true, los datos en la propiedad (\#getSecondaryCategories.getSecondaryCategories) se usan para series secundarias y los datos en la propiedad (\#getCategories.getCategories) se usan para series primarias. Lectura/escritura boolean.

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

Si es false, la propiedad (\#getSecondaryCategories.getSecondaryCategories) devuelve null y los datos en la propiedad (\#getCategories.getCategories) se usan tanto para series primarias como secundarias. Si es true, los datos en la propiedad (\#getSecondaryCategories.getSecondaryCategories) se usan para series secundarias y los datos en la propiedad (\#getCategories.getCategories) se usan para series primarias. Lectura/escritura boolean.

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
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getSecondaryCategories() {#getSecondaryCategories--}
```
public abstract IChartCategoryCollection getSecondaryCategories()
```

Obtiene las categorías secundarias si la propiedad (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) es true. Solo lectura [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

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

Si la propiedad (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) es false, esta propiedad (\#getSecondaryCategories.getSecondaryCategories) devuelve null y los datos en la propiedad (\#getCategories.getCategories) se usan tanto para series primarias como secundarias. Si la propiedad es true, los datos en esta propiedad (\#getSecondaryCategories.getSecondaryCategories) se usan para series secundarias y los datos en la propiedad (\#getCategories.getCategories) se usan para series primarias.

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
| Parameter | Type | Description |
| --- | --- | --- |
| ms | byte[] | El flujo suministrado por el usuario que contiene todo el libro de Excel. |

### setRange(String formula) {#setRange-java.lang.String-}
```
public abstract void setRange(String formula)
```

Establece el rango de datos del gráfico. Las series y categorías se actualizarán basándose en el nuevo rango de datos. Si la cantidad de series en el rango de datos es mayor que el número de series en los datos del gráfico, se agregarán series adicionales con el mismo tipo que la última serie de la colección actual al final de la colección.

**Parámetros:**  
| Parameter | Type | Description |
| --- | --- | --- |
| formula | java.lang.String | La fórmula del rango de datos de celdas. Ej.: "Sheet1!$A$1:$C$4", "SomeSheetName!A1:B100", "Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5". |

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
java.lang.String - Fórmula del rango de datos de celdas. Ej.: "Sheet1!$A$1:$C$4"

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

Intercambia los datos a lo largo del eje. Los datos representados en el eje X pasarán al eje Y y viceversa.

### setExternalWorkbook(String workbookPath) {#setExternalWorkbook-java.lang.String-}
```
public abstract void setExternalWorkbook(String workbookPath)
```

Establece el libro externo como fuente de datos para el gráfico. Los datos del gráfico se actualizarán a partir del libro de destino.

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
| Parameter | Type | Description |
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
| Parameter | Type | Description |
| --- | --- | --- |
| workbookPath | java.lang.String | Ruta al libro de destino |
| updateChartData | boolean | Si el valor es false, solo se actualizará la ruta del libro. No se cargarán ni actualizarán los datos del gráfico desde el libro de destino. Puede usarse cuando el libro de destino no exista o no esté disponible. Si el valor es true, los datos del gráfico se actualizarán desde el libro de destino. |