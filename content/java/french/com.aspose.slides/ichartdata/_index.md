---
title: IChartData
second_title: Aspose.Slides for Java API Reference
description: Représente les données utilisées pour le tracé d'un graphique.
type: docs
url: /fr/com.aspose.slides/ichartdata/
---```
public interface IChartData
```

Représente les données utilisées pour le tracé d'un graphique.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getChartDataWorkbook()](#getChartDataWorkbook--) | Obtient la fabrique de cellules permettant de créer des cellules utilisées pour les séries ou catégories du graphique. |
| [getSeries()](#getSeries--) | Obtient les séries. |
| [getSeriesGroups()](#getSeriesGroups--) | Obtient les groupes de séries. |
| [getCategories()](#getCategories--) | Obtient les catégories principales (ou les catégories principales et secondaires si la propriété (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) est false). |
| [getUseSecondaryCategories()](#getUseSecondaryCategories--) | Si false alors la propriété (\#getSecondaryCategories.getSecondaryCategories) renvoie null et les données de la propriété (\#getCategories.getCategories) sont utilisées à la fois pour les séries primaires et secondaires. |
| [setUseSecondaryCategories(boolean value)](#setUseSecondaryCategories-boolean-) | Si false alors la propriété (\#getSecondaryCategories.getSecondaryCategories) renvoie null et les données de la propriété (\#getCategories.getCategories) sont utilisées à la fois pour les séries primaires et secondaires. |
| [getSecondaryCategories()](#getSecondaryCategories--) | Obtient les catégories secondaires si la propriété (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) est true. |
| [readWorkbookStream()](#readWorkbookStream--) | Écrit le classeur Excel interne dans un flux en mémoire. |
| [writeWorkbookStream(byte[] ms)](#writeWorkbookStream-byte---) | Initialise le classeur Excel interne avec la valeur spécifiée par l'utilisateur. |
| [setRange(String formula)](#setRange-java.lang.String-) | Définit la plage de données du graphique. |
| [getRange()](#getRange--) | Obtient la plage de données du graphique. |
| [getDataSourceType()](#getDataSourceType--) | Représente la source de données du graphique |
| [getExternalWorkbookPath()](#getExternalWorkbookPath--) | Représente le chemin du classeur externe si la source de données est externe, sinon null |
| [getEmbeddedWorkbookType()](#getEmbeddedWorkbookType--) | Obtient le type du classeur intégré. |
| [switchRowColumn()](#switchRowColumn--) | Permute les données sur l'axe. |
| [setExternalWorkbook(String workbookPath)](#setExternalWorkbook-java.lang.String-) | Définit le classeur externe comme source de données pour le graphique. |
| [setExternalWorkbook(String workbookPath, boolean updateChartData)](#setExternalWorkbook-java.lang.String-boolean-) | Définit le classeur externe comme source de données pour le graphique. |
| [refreshData()](#refreshData--) | Rafraîchit les données du graphique en les rechargeant depuis le classeur source. |
### getChartDataWorkbook() {#getChartDataWorkbook--}
```
public abstract IChartDataWorkbook getChartDataWorkbook()
```


Obtient la fabrique de cellules permettant de créer des cellules utilisées pour les séries ou catégories du graphique. Lecture seule [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook).

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

Chaque groupe de séries contient des séries avec des types combinables. Les groupes de types de séries combinables sont définis et décrits avec l’énumération CombinableSeriesTypesGroup. De plus, chaque groupe de séries contient des séries qui sont tracées soit sur les axes principaux, soit sur les axes secondaires (mais pas les deux cas dans un même groupe). Ainsi, le principe de regroupement des séries est un regroupement par groupes de types mentionnés ci-dessus et par type de tracé principal/secondaire.

**Renvoie :**
[IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection)
### getCategories() {#getCategories--}
```
public abstract IChartCategoryCollection getCategories()
```


Obtient les catégories principales (ou les catégories principales et secondaires si la propriété (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) est false). Lecture seule [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

--------------------

> ```
> Exemple. Quelles catégories sont liées aux séries - ChartData.getCategories() ou ChartData.getSecondaryCategories()?
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

Si la propriété (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) est false alors la propriété (\#getSecondaryCategories.getSecondaryCategories) renvoie null et les données de cette propriété (\#getCategories.getCategories) sont utilisées à la fois pour les séries primaires et secondaires. Si la propriété (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) est true alors les données de la propriété (\#getSecondaryCategories.getSecondaryCategories) sont utilisées pour les séries secondaires et les données de cette propriété (\#getCategories.getCategories) sont utilisées pour les séries primaires.

**Renvoie :**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)
### getUseSecondaryCategories() {#getUseSecondaryCategories--}
```
public abstract boolean getUseSecondaryCategories()
```


Si false alors la propriété (\#getSecondaryCategories.getSecondaryCategories) renvoie null et les données de la propriété (\#getCategories.getCategories) sont utilisées à la fois pour les séries primaires et secondaires. Si true alors les données de la propriété (\#getSecondaryCategories.getSecondaryCategories) sont utilisées pour les séries secondaires et les données de la propriété (\#getCategories.getCategories) sont utilisées pour les séries primaires. Lecture/écriture booléen.

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


**Renvoie :**
boolean
### setUseSecondaryCategories(boolean value) {#setUseSecondaryCategories-boolean-}
```
public abstract void setUseSecondaryCategories(boolean value)
```


Si false alors la propriété (\#getSecondaryCategories.getSecondaryCategories) renvoie null et les données de la propriété (\#getCategories.getCategories) sont utilisées à la fois pour les séries primaires et secondaires. Si true alors les données de la propriété (\#getSecondaryCategories.getSecondaryCategories) sont utilisées pour les séries secondaires et les données de la propriété (\#getCategories.getCategories) sont utilisées pour les séries primaires. Lecture/écriture booléen.

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


**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getSecondaryCategories() {#getSecondaryCategories--}
```
public abstract IChartCategoryCollection getSecondaryCategories()
```


Obtient les catégories secondaires si la propriété (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) est true. Lecture seule [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

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

Si la propriété (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) est false alors cette propriété (\#getSecondaryCategories.getSecondaryCategories) renvoie null et les données de la propriété (\#getCategories.getCategories) sont utilisées à la fois pour les séries primaires et secondaires. Si la propriété (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) est true alors les données de cette propriété (\#getSecondaryCategories.getSecondaryCategories) sont utilisées pour les séries secondaires et les données de la propriété (\#getCategories.getCategories) sont utilisées pour les séries primaires.

**Renvoie :**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)
### readWorkbookStream() {#readWorkbookStream--}
```
public abstract byte[] readWorkbookStream()
```


Écrit le classeur Excel interne dans un flux en mémoire.

**Renvoie :**
byte[] - Renvoie un tableau d’octets contenant une copie du classeur Excel interne.
### writeWorkbookStream(byte[] ms) {#writeWorkbookStream-byte---}
```
public abstract void writeWorkbookStream(byte[] ms)
```


Initialise le classeur Excel interne avec la valeur spécifiée par l'utilisateur.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| ms | byte[] | Le flux fourni par l'utilisateur contenant l'intégralité du classeur Excel. |
### setRange(String formula) {#setRange-java.lang.String-}
```
public abstract void setRange(String formula)
```


Définit la plage de données du graphique. Les séries et les catégories seront mises à jour en fonction de la nouvelle plage de données. Si le nombre de séries dans la plage de données dépasse le nombre de séries dans les données du graphique, alors des séries supplémentaires du même type que la dernière série de la collection actuelle seront ajoutées à la fin de la collection.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| formula | java.lang.String | La formule de plage de données des cellules. Par ex : "Sheet1!$A$1:$C$4" , "SomeSheetName!A1:B100", "Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5". |
### getRange() {#getRange--}
```
public abstract String getRange()
```


Obtient la plage de données du graphique.

--------------------

> ```
> Presentation pres = new Presentation();
>  {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.PercentsStackedBar, 100, 100, 500, 400);
>      String result = ((ChartData)chart.getChartData()).getRange();
>  }
> ```

**Renvoie :**
java.lang.String - Formule de plage de données de cellules. Par ex : "Sheet1!$A$1:$C$4"
### getDataSourceType() {#getDataSourceType--}
```
public abstract int getDataSourceType()
```


Représente la source de données du graphique

**Renvoie :**
int
### getExternalWorkbookPath() {#getExternalWorkbookPath--}
```
public abstract String getExternalWorkbookPath()
```


Représente le chemin du classeur externe si la source de données est externe, sinon null

**Renvoie :**
java.lang.String
### getEmbeddedWorkbookType() {#getEmbeddedWorkbookType--}
```
public abstract int getEmbeddedWorkbookType()
```


Obtient le type du classeur intégré. Renvoie [WorkbookType.NotDefined](../../com.aspose.slides/workbooktype\#NotDefined) si DataSourceType (\#getDataSourceType.getDataSourceType) est [ChartDataSourceType.ExternalWorkbook](../../com.aspose.slides/chartdatasourcetype\#ExternalWorkbook). Lecture seule [WorkbookType](../../com.aspose.slides/workbooktype).

**Renvoie :**
int
### switchRowColumn() {#switchRowColumn--}
```
public abstract void switchRowColumn()
```


Permute les données sur l'axe. Les données tracées sur l’axe X seront déplacées vers l’axe Y et inversement.
### setExternalWorkbook(String workbookPath) {#setExternalWorkbook-java.lang.String-}
```
public abstract void setExternalWorkbook(String workbookPath)
```


Définit le classeur externe comme source de données pour le graphique. Les données du graphique seront mises à jour à partir du classeur cible.

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


**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| workbookPath | java.lang.String | Chemin vers le classeur cible |
### setExternalWorkbook(String workbookPath, boolean updateChartData) {#setExternalWorkbook-java.lang.String-boolean-}
```
public abstract void setExternalWorkbook(String workbookPath, boolean updateChartData)
```


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
| updateChartData | boolean | Si la valeur est false, seul le chemin du classeur sera mis à jour. Les données du graphique ne seront pas chargées ni mises à jour à partir du classeur cible. Cela peut être utilisé lorsque le classeur cible n'existe pas ou n'est pas disponible. Si la valeur est true, les données du graphique seront mises à jour à partir du classeur cible. |
### refreshData() {#refreshData--}
```
public abstract void refreshData()
```


Rafraîchit les données du graphique en les rechargeant depuis le classeur source.

--------------------

> ```
> Presentation presentation = new Presentation("presentationWithChart.pptx");
>  try {
>      IChart chart = (IChart)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>      chart.getChartData().refreshData();
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```