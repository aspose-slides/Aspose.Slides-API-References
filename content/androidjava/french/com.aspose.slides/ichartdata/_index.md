---
title: IChartData
second_title: Aspose.Slides for Android via Java API Reference
description: Représente les données utilisées pour tracer un graphique.
type: docs
url: /fr/com.aspose.slides/ichartdata/
---```
public interface IChartData
```

Représente les données utilisées pour tracer un graphique.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getChartDataWorkbook()](#getChartDataWorkbook--) | Obtient la fabrique de cellules pour créer des cellules utilisées pour les séries ou catégories de graphique. |
| [getSeries()](#getSeries--) | Obtient les séries. |
| [getSeriesGroups()](#getSeriesGroups--) | Obtient les groupes de séries. |
| [getCategories()](#getCategories--) | Obtient les catégories principales (ou les catégories principales et secondaires si la propriété (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) est false). |
| [getUseSecondaryCategories()](#getUseSecondaryCategories--) | Si false, alors la propriété (\#getSecondaryCategories.getSecondaryCategories) renvoie null et les données de la propriété (\#getCategories.getCategories) sont utilisées à la fois pour les séries principales et secondaires. |
| [setUseSecondaryCategories(boolean value)](#setUseSecondaryCategories-boolean-) | Si false, alors la propriété (\#getSecondaryCategories.getSecondaryCategories) renvoie null et les données de la propriété (\#getCategories.getCategories) sont utilisées à la fois pour les séries principales et secondaires. |
| [getSecondaryCategories()](#getSecondaryCategories--) | Obtient les catégories secondaires si la propriété (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) est true. |
| [readWorkbookStream()](#readWorkbookStream--) | Écrit le classeur Excel intégré dans un flux en mémoire. |
| [writeWorkbookStream(byte[] ms)](#writeWorkbookStream-byte---) | Initialise le classeur Excel intégré avec la valeur spécifiée par l'utilisateur. |
| [setRange(String formula)](#setRange-java.lang.String-) | Définit la plage de données du graphique. |
| [getRange()](#getRange--) | Obtient la plage de données du graphique. |
| [getDataSourceType()](#getDataSourceType--) | Représente la source de données du graphique |
| [getExternalWorkbookPath()](#getExternalWorkbookPath--) | Représente le chemin du classeur externe si la source de données est externe, sinon null |
| [getEmbeddedWorkbookType()](#getEmbeddedWorkbookType--) | Obtient le type du classeur intégré. |
| [switchRowColumn()](#switchRowColumn--) | Échange les données sur l'axe. |
| [setExternalWorkbook(String workbookPath)](#setExternalWorkbook-java.lang.String-) | Définit le classeur externe comme source de données pour le graphique. |
| [setExternalWorkbook(String workbookPath, boolean updateChartData)](#setExternalWorkbook-java.lang.String-boolean-) | Définit le classeur externe comme source de données pour le graphique. |
### getChartDataWorkbook() {#getChartDataWorkbook--}
```
public abstract IChartDataWorkbook getChartDataWorkbook()
```


Obtient la fabrique de cellules pour créer des cellules utilisées pour les séries ou catégories de graphique. Lecture seule [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook).

**Renvoie :**
[IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook)
### getSeries() {#getSeries--}
```
public abstract IChartSeriesCollection getSeries()
```


Obtient les séries. Lecture seule [IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection).

**Renvoie :**
[IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection)
### getSeriesGroups() {#getSeriesGroups--}
```
public abstract IChartSeriesGroupCollection getSeriesGroups()
```


Obtient les groupes de séries. Lecture seule [IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection).

--------------------

Chaque groupe de séries contient des séries de types combinables. Les groupes de types de séries combinables sont définis et décrits avec l'énumération CombinableSeriesTypesGroup. De plus, chaque groupe de séries contient des séries qui sont tracées soit sur les axes principaux soit sur les axes secondaires (pas les deux cas dans un même groupe). Ainsi, le principe du regroupement des séries est un regroupement par groupes de types mentionnés ci-dessus et par type de tracé principal/secondaire.

**Renvoie :**
[IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection)
### getCategories() {#getCategories--}
```
public abstract IChartCategoryCollection getCategories()
```


Obtient les catégories principales (ou les catégories principales et secondaires si la propriété (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) est false). Lecture seule [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

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

If (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) property is false then (\#getSecondaryCategories.getSecondaryCategories) property return null and data in this (\#getCategories.getCategories) property is used both for primary and secondary series. If (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) property is true then data in (\#getSecondaryCategories.getSecondaryCategories) property is used for secondary series and data in this (\#getCategories.getCategories) property is used for primary series.

**Returns:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)
### getUseSecondaryCategories() {#getUseSecondaryCategories--}
```
public abstract boolean getUseSecondaryCategories()
```
If false then (\#getSecondaryCategories.getSecondaryCategories) property return null and data in (\#getCategories.getCategories) property is used both for primary and secondary series. If true then data in (\#getSecondaryCategories.getSecondaryCategories) property is used for secondary series and data in (\#getCategories.getCategories) property is used for primary series. Read/write boolean.

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
> ```

**Returns:**
boolean
### setUseSecondaryCategories(boolean value) {#setUseSecondaryCategories-boolean-}
```
public abstract void setUseSecondaryCategories(boolean value)
```

If false then (\#getSecondaryCategories.getSecondaryCategories) property return null and data in (\#getCategories.getCategories) property is used both for primary and secondary series. If true then data in (\#getSecondaryCategories.getSecondaryCategories) property is used for secondary series and data in (\#getCategories.getCategories) property is used for primary series. Read/write boolean.

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
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getSecondaryCategories() {#getSecondaryCategories--}
```
public abstract IChartCategoryCollection getSecondaryCategories()
```
Gets the secondary categories if (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) property is true. Read-only [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

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
> ```

--------------------

If (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) property is false then this (\#getSecondaryCategories.getSecondaryCategories) property return null and data in (\#getCategories.getCategories) property is used both for primary and secondary series. If (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) property is true then data in this (\#getSecondaryCategories.getSecondaryCategories) property is used for secondary series and data in (\#getCategories.getCategories) property is used for primary series.

**Returns:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)
### readWorkbookStream() {#readWorkbookStream--}
```
public abstract byte[] readWorkbookStream()
```

Écrit le classeur Excel intégré dans un flux en mémoire.

**Renvoie :**
byte[] - Renvoie un tableau d'octets contenant une copie du classeur Excel intégré.
### writeWorkbookStream(byte[] ms) {#writeWorkbookStream-byte---}
```
public abstract void writeWorkbookStream(byte[] ms)
```
Initializes the internally contained Excel workbook with user-specified value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| ms | byte[] | The user-supplied stream containing the entire Excel workbook. |

### setRange(String formula) {#setRange-java.lang.String-}
```
public abstract void setRange(String formula)
```

Set chart data range. Series and categories will be updated based on new data range. If amount of series in data range greater than count of series in the chart data then additional series with the same type as a last series in the current collection will be added to the end of the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| formula | java.lang.String | The cells data range formula. E.g: "Sheet1!$A$1:$C$4" , "SomeSheetName!A1:B100", "Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5". |

### getRange() {#getRange--}
```
public abstract String getRange()
```
Gets chart data range.

--------------------

> ```
> Presentation pres = new Presentation();
>  {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.PercentsStackedBar, 100, 100, 500, 400);
>      String result = ((ChartData)chart.getChartData()).getRange();
>  }
> ```

**Returns:**
java.lang.String - Cells data range formula. E.g: "Sheet1!$A$1:$C$4"
### getDataSourceType() {#getDataSourceType--}
```
public abstract int getDataSourceType()
```

Represents data source of the chart

**Returns:**
int
### getExternalWorkbookPath() {#getExternalWorkbookPath--}
```
public abstract String getExternalWorkbookPath()
```

Represents external workbook path if data source is external, null otherwise

**Returns:**
java.lang.String
### getEmbeddedWorkbookType() {#getEmbeddedWorkbookType--}
```
public abstract int getEmbeddedWorkbookType()
```
Obtient le type du classeur intégré. Retourne [WorkbookType.NotDefined](../../com.aspose.slides/workbooktype\#NotDefined) si DataSourceType (\#getDataSourceType.getDataSourceType) est [ChartDataSourceType.ExternalWorkbook](../../com.aspose.slides/chartdatasourcetype\#ExternalWorkbook). Lecture seule [WorkbookType](../../com.aspose.slides/workbooktype).

**Renvoie :**
int
### switchRowColumn() {#switchRowColumn--}
```
public abstract void switchRowColumn()
```
Échange les données sur l'axe. Les données tracées sur l'axe X seront déplacées vers l'axe Y et inversement.

### setExternalWorkbook(String workbookPath) {#setExternalWorkbook-java.lang.String-}
```
public abstract void setExternalWorkbook(String workbookPath)
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
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| workbookPath | java.lang.String | Path to the target workbook |

### setExternalWorkbook(String workbookPath, boolean updateChartData) {#setExternalWorkbook-java.lang.String-boolean-}
```
public abstract void setExternalWorkbook(String workbookPath, boolean updateChartData)


Définit le classeur externe comme source de données pour le graphique.

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

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| workbookPath | java.lang.String | Chemin vers le classeur cible |
| updateChartData | boolean | Si la valeur est false, seul le chemin du classeur sera mis à jour. Les données du graphique ne seront pas chargées ni mises à jour à partir du classeur cible. Peut être utilisé lorsque le classeur cible n'existe pas ou n'est pas disponible. Si la valeur est true, les données du graphique seront mises à jour à partir du classeur cible. |
