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
| [getChartDataWorkbook()](#getChartDataWorkbook--) | Obtient la fabrique de cellules pour créer des cellules utilisées pour les séries ou les catégories du graphique. |
| [getSeries()](#getSeries--) | Obtient les séries. |
| [getSeriesGroups()](#getSeriesGroups--) | Obtient les groupes de séries. |
| [getCategories()](#getCategories--) | Obtient les catégories principales (ou les catégories principales et secondaires si la propriété (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) est fausse). |
| [getUseSecondaryCategories()](#getUseSecondaryCategories--) | Si false alors la propriété (\#getSecondaryCategories.getSecondaryCategories) renvoie null et les données de la propriété (\#getCategories.getCategories) sont utilisées à la fois pour les séries principales et secondaires. |
| [setUseSecondaryCategories(boolean value)](#setUseSecondaryCategories-boolean-) | Si false alors la propriété (\#getSecondaryCategories.getSecondaryCategories) renvoie null et les données de la propriété (\#getCategories.getCategories) sont utilisées à la fois pour les séries principales et secondaires. |
| [getSecondaryCategories()](#getSecondaryCategories--) | Obtient les catégories secondaires si la propriété (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) est vraie. |
| [readWorkbookStream()](#readWorkbookStream--) | Écrit le classeur Excel interne dans un flux en mémoire. |
| [writeWorkbookStream(byte[] ms)](#writeWorkbookStream-byte---) | Initialise le classeur Excel interne avec la valeur spécifiée par l'utilisateur. |
| [setRange(String formula)](#setRange-java.lang.String-) | Définit la plage de données du graphique. |
| [getRange()](#getRange--) | Obtient la plage de données du graphique. |
| [getDataSourceType()](#getDataSourceType--) | Représente la source de données du graphique |
| [getExternalWorkbookPath()](#getExternalWorkbookPath--) | Représente le chemin du classeur externe si la source de données est externe, sinon null |
| [getEmbeddedWorkbookType()](#getEmbeddedWorkbookType--) | Obtient le type du classeur intégré. |
| [switchRowColumn()](#switchRowColumn--) | Échange les données d'un axe à l'autre. |
| [setExternalWorkbook(String workbookPath)](#setExternalWorkbook-java.lang.String-) | Définit le classeur externe comme source de données pour le graphique. |
| [setExternalWorkbook(String workbookPath, boolean updateChartData)](#setExternalWorkbook-java.lang.String-boolean-) | Définit le classeur externe comme source de données pour le graphique. |
### getChartDataWorkbook() {#getChartDataWorkbook--}
```
public abstract IChartDataWorkbook getChartDataWorkbook()
```

Obtient la fabrique de cellules pour créer des cellules utilisées pour les séries ou les catégories du graphique. Lecture seule [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook).

**Retour:**  
[IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook)
### getSeries() {#getSeries--}
```
public abstract IChartSeriesCollection getSeries()
```

Obtient les séries. Lecture seule [IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection).

**Retour:**  
[IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection)
### getSeriesGroups() {#getSeriesGroups--}
```
public abstract IChartSeriesGroupCollection getSeriesGroups()
```

Obtient les groupes de séries. Lecture seule [IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection).

--------------------

1) Chaque groupe de Series contient des Series avec des types combinables. Les groupes de types de Series combinables sont définis et décrits avec l'énumération CombinableSeriesTypesGroup. De plus, chaque groupe de Series contient des Series qui sont tracées soit sur les axes principaux, soit sur les axes secondaires (pas les deux cas dans un même groupe). Ainsi, le principe de groupement des Series est un groupement par les types de groupes mentionnés ci-dessus et par le type de tracé principal/secondaire. 2) Un groupe de Series contient certaines propriétés de Series qui sont communes à chaque Series du groupe (« propriétés du groupe de Series »). Les « propriétés du groupe de Series » dans la classe ChartSeriesGroup sont lecture/écriture. Chacune des « propriétés du groupe de Series » peut avoir une projection lecture seule dans la classe ChartSeries.

**Retour:**  
[IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection)
### getCategories() {#getCategories--}
```
public abstract IChartCategoryCollection getCategories()
```

Obtient les catégories principales (ou les catégories principales et secondaires si la propriété (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) est fausse). Lecture seule [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

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
```

--------------------

Si la propriété (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) est fausse alors la propriété (\#getSecondaryCategories.getSecondaryCategories) renvoie null et les données de cette propriété (\#getCategories.getCategories) sont utilisées à la fois pour les séries principales et secondaires. Si la propriété (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) est vraie alors les données de la propriété (\#getSecondaryCategories.getSecondaryCategories) sont utilisées pour les séries secondaires et les données de cette propriété (\#getCategories.getCategories) sont utilisées pour les séries principales.

**Retour:**  
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)
### getUseSecondaryCategories() {#getUseSecondaryCategories--}
```
public abstract boolean getUseSecondaryCategories()
```

Si false alors la propriété (\#getSecondaryCategories.getSecondaryCategories) renvoie null et les données de la propriété (\#getCategories.getCategories) sont utilisées à la fois pour les séries principales et secondaires. Si true alors les données de la propriété (\#getSecondaryCategories.getSecondaryCategories) sont utilisées pour les séries secondaires et les données de la propriété (\#getCategories.getCategories) sont utilisées pour les séries principales. Lecture/écriture booléen.

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

**Retour:**  
boolean
### setUseSecondaryCategories(boolean value) {#setUseSecondaryCategories-boolean-}
```
public abstract void setUseSecondaryCategories(boolean value)
```

Si false alors la propriété (\#getSecondaryCategories.getSecondaryCategories) renvoie null et les données de la propriété (\#getCategories.getCategories) sont utilisées à la fois pour les séries principales et secondaires. Si true alors les données de la propriété (\#getSecondaryCategories.getSecondaryCategories) sont utilisées pour les séries secondaires et les données de la propriété (\#getCategories.getCategories) sont utilisées pour les séries principales. Lecture/écriture booléen.

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

Obtient les catégories secondaires si la propriété (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) est vraie. Lecture seule [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

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


Si la propriété (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) est fausse alors cette propriété (\#getSecondaryCategories.getSecondaryCategories) renvoie null et les données de la propriété (\#getCategories.getCategories) sont utilisées à la fois pour les séries principales et secondaires. Si la propriété (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) est vraie alors les données de cette propriété (\#getSecondaryCategories.getSecondaryCategories) sont utilisées pour les séries secondaires et les données de la propriété (\#getCategories.getCategories) sont utilisées pour les séries principales.

**Retour:**  
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)
### readWorkbookStream() {#readWorkbookStream--}
```
public abstract byte[] readWorkbookStream()
```

Écrit le classeur Excel interne dans un flux en mémoire.

**Retour:**  
byte[] - Retourne un tableau d'octets contenant une copie du classeur Excel interne.
### writeWorkbookStream(byte[] ms) {#writeWorkbookStream-byte---}
```
public abstract void writeWorkbookStream(byte[] ms)
```

Initialise le classeur Excel interne avec la valeur spécifiée par l'utilisateur.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| ms | byte[] | Le flux fourni par l'utilisateur contenant le classeur Excel complet. |
### setRange(String formula) {#setRange-java.lang.String-}
```
public abstract void setRange(String formula)
```

Définit la plage de données du graphique. Les séries et les catégories seront mises à jour en fonction de la nouvelle plage de données. Si le nombre de séries dans la plage de données est supérieur au nombre de séries dans les données du graphique, alors des séries supplémentaires du même type que la dernière série de la collection actuelle seront ajoutées à la fin de la collection.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| formula | java.lang.String | La formule de plage de données des cellules. Par ex. : "Sheet1!$A$1:$C$4", "SomeSheetName!A1:B100", "Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5". |
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

**Retour:**  
java.lang.String - Formule de plage de données des cellules. Par ex. : "Sheet1!$A$1:$C$4"
### getDataSourceType() {#getDataSourceType--}
```
public abstract int getDataSourceType()
```

Représente la source de données du graphique

**Retour:**  
int
### getExternalWorkbookPath() {#getExternalWorkbookPath--}
```
public abstract String getExternalWorkbookPath()
```

Représente le chemin du classeur externe si la source de données est externe, sinon null

**Retour:**  
java.lang.String
### getEmbeddedWorkbookType() {#getEmbeddedWorkbookType--}
```
public abstract int getEmbeddedWorkbookType()
```

Obtient le type du classeur intégré. Retourne [WorkbookType.NotDefined](../../com.aspose.slides/workbooktype\#NotDefined) si DataSourceType (\#getDataSourceType.getDataSourceType) est [ChartDataSourceType.ExternalWorkbook](../../com.aspose.slides/chartdatasourcetype\#ExternalWorkbook). Lecture seule [WorkbookType](../../com.aspose.slides/workbooktype).

**Retour:**  
int
### switchRowColumn() {#switchRowColumn--}
```
public abstract void switchRowColumn()
```

Échange les données d'un axe à l'autre. Les données tracées sur l'axe X seront déplacées vers l'axe Y et inversement.
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
| updateChartData | boolean | Si la valeur est false, seul le chemin du classeur sera mis à jour. Les données du graphique ne seront pas chargées ni mises à jour à partir du classeur cible. Peut être utilisé lorsque le classeur cible n'existe pas ou n'est pas disponible. Si la valeur est true, les données du graphique seront mises à jour à partir du classeur cible. |