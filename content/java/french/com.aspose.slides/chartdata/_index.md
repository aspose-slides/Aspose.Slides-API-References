---
title: ChartData
second_title: Référence de l'API Aspose.Slides pour Java
description: Représente les données utilisées pour le tracé d'un graphique.
type: docs
url: /fr/com.aspose.slides/chartdata/
---
**Héritage :**
java.lang.Object, com.aspose.slides.DomObject

**Toutes les interfaces implémentées :**
[com.aspose.slides.IChartData](../../com.aspose.slides/ichartdata)
```
public class ChartData extends DomObject<Chart> implements IChartData
```

Représente les données utilisées pour le tracé d'un graphique.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getChartDataWorkbook()](#getChartDataWorkbook--) | Obtient la fabrique de cellules pour créer les cellules utilisées pour les séries ou les catégories du graphique. |
| [getSeries()](#getSeries--) | Obtient les séries. |
| [getSeriesGroups()](#getSeriesGroups--) | Obtient les groupes de séries. |
| [getCategories()](#getCategories--) | Obtient les catégories principales (ou les catégories principales et secondaires si la propriété \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) est fausse). |
| [getUseSecondaryCategories()](#getUseSecondaryCategories--) | Si false alors la propriété \#getSecondaryCategories.getSecondaryCategories renvoie null et les données de la propriété \#getCategories.getCategories sont utilisées à la fois pour les séries principales et secondaires. |
| [setUseSecondaryCategories(boolean value)](#setUseSecondaryCategories-boolean-) | Si false alors la propriété \#getSecondaryCategories.getSecondaryCategories renvoie null et les données de la propriété \#getCategories.getCategories sont utilisées à la fois pour les séries principales et secondaires. |
| [getSecondaryCategories()](#getSecondaryCategories--) | Obtient les catégories secondaires si la propriété \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) est vraie. |
| [readWorkbookStream()](#readWorkbookStream--) | Écrit le classeur Excel intégré dans un flux en mémoire. |
| [writeWorkbookStream(byte[] ms)](#writeWorkbookStream-byte---) | Initialise le classeur Excel intégré avec la valeur spécifiée par l'utilisateur. |
| [getDataSourceType()](#getDataSourceType--) | Représente le chemin du classeur externe si source de données externe, sinon null. |
| [getExternalWorkbookPath()](#getExternalWorkbookPath--) | Représente la source de données du graphique. |
| [getEmbeddedWorkbookType()](#getEmbeddedWorkbookType--) | Obtient le type du classeur intégré. |
| [getRange()](#getRange--) | Obtient la plage de données du graphique. |
| [setRange(String formula)](#setRange-java.lang.String-) | Définit la plage de données du graphique. |
| [setExternalWorkbook(String workbookPath)](#setExternalWorkbook-java.lang.String-) | Définir le classeur externe comme source de données pour le graphique. |
| [setExternalWorkbook(String workbookPath, boolean updateChartData)](#setExternalWorkbook-java.lang.String-boolean-) | Définir le classeur externe comme source de données pour le graphique. |
| [switchRowColumn()](#switchRowColumn--) | Échange les données sur l'axe. |

### getChartDataWorkbook() {#getChartDataWorkbook--}
```
public final IChartDataWorkbook getChartDataWorkbook()
```

Obtient la fabrique de cellules pour créer les cellules utilisées pour les séries ou les catégories du graphique. Lecture seule [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook).

**Retour :**
[IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook)
### getSeries() {#getSeries--}
```
public final IChartSeriesCollection getSeries()
```

Obtient les séries. Lecture seule [IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection).

**Retour :**
[IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection)
### getSeriesGroups() {#getSeriesGroups--}
```
public final IChartSeriesGroupCollection getSeriesGroups()
```

Obtient les groupes de séries. Lecture seule [IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection).

--------------------

1) Chaque groupe de séries contient des séries avec des types combinables. Les groupes de types de séries combinables sont définis et décrits avec l'énumération CombinableSeriesTypesGroup. De plus, chaque groupe de séries contient des séries qui sont tracées soit sur les axes principaux, soit sur les axes secondaires (pas les deux cas dans un même groupe). Ainsi, le principe du regroupement des séries est un regroupement par groupes de types mentionnés ci-dessus et par type de tracé principal/secondaire. 2) Un groupe de séries contient certaines propriétés de séries qui sont communes à chaque série du groupe (« propriétés du groupe de séries »). Les « propriétés du groupe de séries » dans la classe ChartSeriesGroup sont en lecture/écriture. Chaque « propriété du groupe de séries » peut avoir une projection en lecture seule dans la classe ChartSeries.

**Retour :**
[IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection)
### getCategories() {#getCategories--}
```
public final IChartCategoryCollection getCategories()
```

Obtient les catégories principales (ou les catégories principales et secondaires si la propriété \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) est fausse). Lecture seule [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

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

Si la propriété \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) est false alors la propriété (\#getSecondaryCategories.getSecondaryCategories) renvoie null et les données de la propriété \#getCategories.getCategories sont utilisées à la fois pour les séries principales et secondaires. Si la propriété \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) est true alors les données de la propriété (\#getSecondaryCategories.getSecondaryCategories) sont utilisées pour les séries secondaires et les données de cette propriété \#getCategories.getCategories sont utilisées pour les séries principales.

**Retour :**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)
### getUseSecondaryCategories() {#getUseSecondaryCategories--}
```
public final boolean getUseSecondaryCategories()
```

Si false alors la propriété \#getSecondaryCategories.getSecondaryCategories renvoie null et les données de la propriété \#getCategories.getCategories sont utilisées à la fois pour les séries principales et secondaires. Si true alors les données de la propriété \#getSecondaryCategories.getSecondaryCategories sont utilisées pour les séries secondaires et les données de la propriété \#getCategories.getCategories sont utilisées pour les séries principales. Lecture/écriture booléen.

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

**Retour :**
boolean
### setUseSecondaryCategories(boolean value) {#setUseSecondaryCategories-boolean-}
```
public final void setUseSecondaryCategories(boolean value)
```

Si false alors la propriété \#getSecondaryCategories.getSecondaryCategories renvoie null et les données de la propriété \#getCategories.getCategories sont utilisées à la fois pour les séries principales et secondaires. Si true alors les données de la propriété \#getSecondaryCategories.getSecondaryCategories sont utilisées pour les séries secondaires et les données de la propriété \#getCategories.getCategories sont utilisées pour les séries principales. Lecture/écriture booléen.

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
public final IChartCategoryCollection getSecondaryCategories()
```

Obtient les catégories secondaires si la propriété \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) est vraie. Lecture seule [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

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

Si la propriété \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) est false alors cette propriété (\#getSecondaryCategories.getSecondaryCategories) renvoie null et les données de la propriété \#getCategories.getCategories sont utilisées à la fois pour les séries principales et secondaires. Si la propriété \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) est true alors les données de cette propriété \#getSecondaryCategories.getSecondaryCategories sont utilisées pour les séries secondaires et les données de la propriété \#getCategories.getCategories sont utilisées pour les séries principales.

**Retour :**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)
### readWorkbookStream() {#readWorkbookStream--}
```
public final byte[] readWorkbookStream()
```

Écrit le classeur Excel intégré dans un flux en mémoire.

**Retour :**
byte[] - Retourne une instance de tableau d'octets contenant une copie du classeur Excel intégré.
### writeWorkbookStream(byte[] ms) {#writeWorkbookStream-byte---}
```
public final void writeWorkbookStream(byte[] ms)
```

Initialise le classeur Excel intégré avec la valeur spécifiée par l'utilisateur.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| ms | byte[] | Le flux fourni par l'utilisateur contenant le classeur Excel complet. |

### getDataSourceType() {#getDataSourceType--}
```
public final int getDataSourceType()
```

Représente le chemin du classeur externe si source de données externe, sinon null.

**Retour :**
int
### getExternalWorkbookPath() {#getExternalWorkbookPath--}
```
public final String getExternalWorkbookPath()
```

Représente la source de données du graphique.

**Retour :**
java.lang.String
### getEmbeddedWorkbookType() {#getEmbeddedWorkbookType--}
```
public final int getEmbeddedWorkbookType()
```

Obtient le type du classeur intégré. Retourne [WorkbookType.NotDefined](../../com.aspose.slides/workbooktype\#NotDefined) si DataSourceType (\#getDataSourceType.getDataSourceType) est [ChartDataSourceType.ExternalWorkbook](../../com.aspose.slides/chartdatasourcetype\#ExternalWorkbook). Lecture seule [WorkbookType](../../com.aspose.slides/workbooktype).

**Retour :**
int
### getRange() {#getRange--}
```
public final String getRange()
```

Obtient la plage de données du graphique.

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

**Retour :**
java.lang.String - Formule de plage de données des cellules. Par ex. : "Sheet1!$A$1:$C$4"
### setRange(String formula) {#setRange-java.lang.String-}
```
public final void setRange(String formula)
```

Définit la plage de données du graphique. Les séries et les catégories seront mises à jour en fonction de la nouvelle plage de données. Si le nombre de séries dans la plage de données est supérieur au nombre de séries dans les données du graphique, alors des séries supplémentaires du même type que la dernière série de la collection actuelle seront ajoutées à la fin de la collection.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| formula | java.lang.String | La formule de plage de données des cellules. Par ex. : "Sheet1!$A$1:$C$4", "SomeSheetName!A1:B100", "Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5". |

### setExternalWorkbook(String workbookPath) {#setExternalWorkbook-java.lang.String-}
```
public final void setExternalWorkbook(String workbookPath)
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
>     if (pres != null) pres.dispose();
>  }
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| workbookPath | java.lang.String | Chemin vers le classeur cible |

### setExternalWorkbook(String workbookPath, boolean updateChartData) {#setExternalWorkbook-java.lang.String-boolean-}
```
public final void setExternalWorkbook(String workbookPath, boolean updateChartData)
```

Définit le classeur externe comme source de données pour le graphique.

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

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| workbookPath | java.lang.String | Chemin vers le classeur cible |
| updateChartData | boolean | Si la valeur est false, seul le chemin du classeur sera mis à jour. Les données du graphique ne seront pas chargées ni mises à jour à partir du classeur cible. Peut être utilisé lorsque le classeur cible n'existe pas ou n'est pas disponible. Si la valeur est true, les données du graphique seront mises à jour à partir du classeur cible. |

### switchRowColumn() {#switchRowColumn--}
```
public final void switchRowColumn()
```

Échange les données sur l'axe. Les données tracées sur l'axe X seront déplacées vers l'axe Y et inversement.