---
title: ChartData
second_title: Aspose.Slides pour Android via la référence de l'API Java
description: Représente les données utilisées pour le tracé d'un graphique.
type: docs
url: /fr/com.aspose.slides/chartdata/
---
**Héritage:**
java.lang.Object, com.aspose.slides.DomObject

**Toutes les interfaces implémentées:**
[com.aspose.slides.IChartData](../../com.aspose.slides/ichartdata)
```
public class ChartData extends DomObject<Chart> implements IChartData
```

Represents data used for a chart plotting.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getChartDataWorkbook()](#getChartDataWorkbook--) | Obtient la fabrique de cellules pour créer des cellules utilisées pour les séries ou les catégories du graphique. |
| [getSeries()](#getSeries--) | Obtient les séries. |
| [getSeriesGroups()](#getSeriesGroups--) | Obtient les groupes de séries. |
| [getCategories()](#getCategories--) | Obtient les catégories principales (ou les catégories principales et secondaires si la propriété \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) est false). |
| [getUseSecondaryCategories()](#getUseSecondaryCategories--) | Si false, alors la propriété \#getSecondaryCategories.getSecondaryCategories renvoie null et les données de la propriété \#getCategories.getCategories sont utilisées à la fois pour les séries principales et secondaires. |
| [setUseSecondaryCategories(boolean value)](#setUseSecondaryCategories-boolean-) | Si false, alors la propriété \#getSecondaryCategories.getSecondaryCategories renvoie null et les données de la propriété \#getCategories.getCategories sont utilisées à la fois pour les séries principales et secondaires. |
| [getSecondaryCategories()](#getSecondaryCategories--) | Obtient les catégories secondaires si la propriété \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) est true. |
| [readWorkbookStream()](#readWorkbookStream--) | Écrit le classeur Excel workbook intégré dans un flux en mémoire. |
| [writeWorkbookStream(byte[] ms)](#writeWorkbookStream-byte---) | Initialise le classeur Excel workbook intégré avec la valeur spécifiée par l'utilisateur. |
| [getDataSourceType()](#getDataSourceType--) | Représente le chemin du classeur externe s'il s'agit d'une source de données externe, null sinon |
| [getExternalWorkbookPath()](#getExternalWorkbookPath--) | Représente la source de données du graphique |
| [getEmbeddedWorkbookType()](#getEmbeddedWorkbookType--) | Obtient le type du classeur intégré. |
| [getRange()](#getRange--) | Obtient la plage de données du graphique. |
| [setRange(String formula)](#setRange-java.lang.String-) | Définit la plage de données du graphique. |
| [setExternalWorkbook(String workbookPath)](#setExternalWorkbook-java.lang.String-) | Définit le classeur externe comme source de données pour le graphique. |
| [setExternalWorkbook(String workbookPath, boolean updateChartData)](#setExternalWorkbook-java.lang.String-boolean-) | Définit le classeur externe comme source de données pour le graphique. |
| [switchRowColumn()](#switchRowColumn--) | Échange les données sur l'axe. |
### getChartDataWorkbook() {#getChartDataWorkbook--}
```
public final IChartDataWorkbook getChartDataWorkbook()
```

Obtient la fabrique de cellules pour créer des cellules utilisées pour les séries ou les catégories du graphique. Lecture seule [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook).

**Renvoie :**
[IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook)
### getSeries() {#getSeries--}
```
public final IChartSeriesCollection getSeries()
```

Obtient les séries. Lecture seule [IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection).

**Renvoie :**
[IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection)
### getSeriesGroups() {#getSeriesGroups--}
```
public final IChartSeriesGroupCollection getSeriesGroups()
```

Obtient les groupes de séries. Lecture seule [IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection).

--------------------

1) Chaque groupe de séries contient des séries avec des types combinables. Les groupes de types de séries combinables sont définis et décrits avec l'énumération CombinableSeriesTypesGroup. De plus, chaque groupe de séries contient des séries qui sont tracées sur les axes principaux ou sur les axes secondaires (pas les deux cas dans un même groupe). Ainsi, le principe de regroupement des séries est un regroupement par groupes de types mentionnés ci-above et par type de tracé principal/secondaire. 2) Un groupe de séries contient certaines propriétés de séries qui sont communes à chaque série du groupe (« propriétés de groupe de séries »). Les « propriétés de groupe de séries » dans la classe ChartSeriesGroup sont en lecture/écriture. Chaque « propriété de groupe de séries » peut avoir une projection en lecture seule dans la classe ChartSeries.

**Renvoie :**
[IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection)
### getCategories() {#getCategories--}
```
public final IChartCategoryCollection getCategories()
```

Obtient les catégories principales (ou les catégories principales et secondaires si la propriété \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) est false). Lecture seule [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // related categories are series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // related categories are series.getChart().getChartData().getCategories()
>  }
> ```

--------------------

If \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) property is false then (\#getSecondaryCategories.getSecondaryCategories) property return null and data in this \#getCategories.getCategories property is used both for primary and secondary series. If \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) property is true then data in (\#getSecondaryCategories.getSecondaryCategories) property is used for secondary series and data in this \#getCategories.getCategories property is used for primary series.

**Returns:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)
### getUseSecondaryCategories() {#getUseSecondaryCategories--}
```
public final boolean getUseSecondaryCategories()
```

If false then \#getSecondaryCategories.getSecondaryCategories property return null and data in \#getCategories.getCategories property is used both for primary and secondary series. If true then data in \#getSecondaryCategories.getSecondaryCategories property is used for secondary series and data in \#getCategories.getCategories property is used for primary series. Read/write boolean.

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // les catégories associées sont series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // les catégories associées sont series.getChart().getChartData().getCategories()
>  }
>  ```

**Returns:**
boolean
### setUseSecondaryCategories(boolean value) {#setUseSecondaryCategories-boolean-}
```
public final void setUseSecondaryCategories(boolean value)
```

If false then \#getSecondaryCategories.getSecondaryCategories property return null and data in \#getCategories.getCategories property is used both for primary and secondary series. If true then data in \#getSecondaryCategories.getSecondaryCategories property is used for secondary series and data in \#getCategories.getCategories property is used for primary series. Read/write boolean.

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // les catégories associées sont series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // les catégories associées sont series.getChart().getChartData().getCategories()
>  }
>  ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getSecondaryCategories() {#getSecondaryCategories--}
```
public final IChartCategoryCollection getSecondaryCategories()
```

Gets the secondary categories if \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) property is true. Read-only [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // les catégories associées sont series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // les catégories associées sont series.getChart().getChartData().getCategories()
>  }
>  ```

--------------------

If \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) property is false then this (\#getSecondaryCategories.getSecondaryCategories) property return null and data in \#getCategories.getCategories property is used both for primary and secondary series. If \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) property is true then data in this \#getSecondaryCategories.getSecondaryCategories property is used for secondary series and data in \#getCategories.getCategories property is used for primary series.

**Returns:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)
### readWorkbookStream() {#readWorkbookStream--}
```
public final byte[] readWorkbookStream()
```

Writes the internally contained Excel workbook it into an in-memory stream.

**Returns:**
byte[] - Returns an instance of byte array containing a copy of the internally contained Excel workbook.
### writeWorkbookStream(byte[] ms) {#writeWorkbookStream-byte---}
```
public final void writeWorkbookStream(byte[] ms)
```

Initializes the internally contained Excel workbook with user-specified value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| ms | byte[] | The user-supplied stream containing the entire Excel workbook. |

### getDataSourceType() {#getDataSourceType--}
```
public final int getDataSourceType()
```

Represents external workbook path if external data source, null otherwise

**Returns:**
int
### getExternalWorkbookPath() {#getExternalWorkbookPath--}
```
public final String getExternalWorkbookPath()
```

Represents data source of the chart

**Returns:**
java.lang.String
### getEmbeddedWorkbookType() {#getEmbeddedWorkbookType--}
```
public final int getEmbeddedWorkbookType()
```

Gets the type of the embedded workbook. Returns [WorkbookType.NotDefined](../../com.aspose.slides/workbooktype#NotDefined) if  DataSourceType (\#getDataSourceType.getDataSourceType) is [ChartDataSourceType.ExternalWorkbook](../../com.aspose.slides/chartdatasourcetype#ExternalWorkbook). Read-only [WorkbookType](../../com.aspose.slides/workbooktype).

**Returns:**
int
### getRange() {#getRange--}
```
public final String getRange()
```

Gets chart data range.

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

**Returns:**
java.lang.String - Cells data range formula. E.g: "Sheet1!$A$1:$C$4"
### setRange(String formula) {#setRange-java.lang.String-}
```
public final void setRange(String formula)
```

Set chart data range. Series and categories will be updated based on new data range. If amount of series in data range greater than count of series in the chart data then additional series with the same type as a last series in the current collection will be added to the end of the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| formula | java.lang.String | The cells data range formula. E.g: "Sheet1!$A$1:$C$4" , "SomeSheetName!A1:B100", "Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5". |

### setExternalWorkbook(String workbookPath) {#setExternalWorkbook-java.lang.String-}
```
public final void setExternalWorkbook(String workbookPath)
```

Sets external workbook as a data source for the chart. Chart data will be updated from the target workbook.

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

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| workbookPath | java.lang.String | Path to the target workbook |

### setExternalWorkbook(String workbookPath, boolean updateChartData) {#setExternalWorkbook-java.lang.String-boolean-}
```
public final void setExternalWorkbook(String workbookPath, boolean updateChartData)
```

Sets external workbook as a data source for the chart.

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

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| workbookPath | java.lang.String | Path to the target workbook |
| updateChartData | boolean | If value is false only workbook path will be updated. Chart data won't be loaded and updated from the target workbook. Can be used when target workbook doesn't exist or it's not available. If value is true chart data will be updated from the target workbook. |

### switchRowColumn() {#switchRowColumn--}
```
public final void switchRowColumn()

Échange les données sur l'axe. Les données tracées sur l'axe X seront déplacées vers l'axe Y et inversement.