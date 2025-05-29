---
title: ChartSeriesGroup
second_title: Référence de l'API Aspose.Slides pour .NET
description: Représente un groupe de séries.
type: docs
weight: 1380
url: /fr/aspose.slides.charts/chartseriesgroup/
---

## Classe ChartSeriesGroup

Représente un groupe de séries.

```csharp
public class ChartSeriesGroup : IChartSeriesGroup
```

## Propriétés

| Nom | Description |
| --- | --- |
| [BubbleSizeRepresentation](../../aspose.slides.charts/chartseriesgroup/bubblesizerepresentation) { get; set; } | Spécifie comment les valeurs de taille de bulle sont représentées sur le graphique en bulles. Lecture/écriture [`BubbleSizeRepresentationType`](../bubblesizerepresentationtype). |
| [BubbleSizeScale](../../aspose.slides.charts/chartseriesgroup/bubblesizescale) { get; set; } | Spécifie le facteur d'échelle pour le graphique en bulles (peut être entre 0 et 300 pourcents de la taille par défaut). Lecture/écriture Int32. |
| [Chart](../../aspose.slides.charts/chartseriesgroup/chart) { get; } | Renvoie le graphique parent. Lecture seule [`IChart`](../ichart). |
| [DoughnutHoleSize](../../aspose.slides.charts/chartseriesgroup/doughnutholesize) { get; set; } | Spécifie la taille du trou dans un graphique en anneau (peut être entre 0 et 90 pourcents de la taille de la zone de tracé). Lecture/écriture Byte. |
| [FirstSliceAngle](../../aspose.slides.charts/chartseriesgroup/firstsliceangle) { get; set; } | Obtient ou définit l'angle de la première tranche de tarte ou d'anneau, en degrés (dans le sens des aiguilles d'une montre à partir du haut, de 0 à 360 degrés). Lecture/écriture UInt16. |
| [GapDepth](../../aspose.slides.charts/chartseriesgroup/gapdepth) { get; set; } | Renvoie ou définit la distance, en pourcentage de la largeur du marqueur, entre les séries de données dans un graphique 3D. Lecture/écriture UInt16. |
| [GapWidth](../../aspose.slides.charts/chartseriesgroup/gapwidth) { get; set; } | Spécifie l'espace entre les clusters de barres ou de colonnes, en pourcentage de la largeur de la barre ou de la colonne. Lecture/écriture UInt16. |
| [HasSeriesLines](../../aspose.slides.charts/chartseriesgroup/hasserieslines) { get; set; } | Vrai si le graphique a des lignes de séries. Appliqué aux graphiques à barres empilées et aux graphiques de tarte. Lecture/écriture Boolean. |
| [HiLowLinesFormat](../../aspose.slides.charts/chartseriesgroup/hilowlinesformat) { get; } | Spécifie le format des HiLowLines. HiLowLines appliqué avec les types de graphiques HiLowClose, OpenHiLowClose, VolumeHiLowClose et VolumeOpenHiLowClose. |
| [IsColorVaried](../../aspose.slides.charts/chartseriesgroup/iscolorvaried) { get; set; } | Spécifie que chaque marqueur de données dans la série a une couleur différente. Lecture/écriture Boolean. |
| [Item](../../aspose.slides.charts/chartseriesgroup/item) { get; } | Obtient l'élément à l'index spécifié. |
| [Overlap](../../aspose.slides.charts/chartseriesgroup/overlap) { get; set; } | Spécifie combien de barres et de colonnes doivent se chevaucher sur des graphiques 2D, en pourcentage (de -100 % à 100 %). - -100 % : Espacement maximum (les barres sont complètement séparées). - 0 % : Les barres sont côte à côte sans chevauchement ni espacement. - 100 % : Chevauchement maximum (les barres se chevauchent complètement). Cette propriété est lecture/écriture SByte. |
| [PieSplitBy](../../aspose.slides.charts/chartseriesgroup/piesplitby) { get; set; } | Spécifie comment déterminer quels points de données se trouvent dans la seconde tarte ou barre sur un graphique de tarte à tartes ou de barre à barres. Lecture/écriture [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/chartseriesgroup/piesplitcustompoints) { get; } | Les informations de séparation personnalisées pour un graphique de tarte à tartes ou de barre à barres avec une séparation personnalisée. Contient les points de données qui doivent être tracés dans la seconde tarte ou barre dans un graphique de tarte à tartes ou de barre à barres. Lecture seule [`PieSplitCustomPointCollection`](../piesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/chartseriesgroup/piesplitposition) { get; set; } | Spécifie une valeur qui sera utilisée pour déterminer quels points de données se trouvent dans la seconde tarte ou barre sur un graphique de tarte à tartes ou de barre à barres. Utilisée avec la propriété PieSplitBy. Lecture/écriture Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/chartseriesgroup/plotonsecondaxis) { get; } | Indique si la série de ce groupe est tracée sur l'axe secondaire. Lecture seule Boolean. |
| [SecondPieSize](../../aspose.slides.charts/chartseriesgroup/secondpiesize) { get; set; } | Spécifie la taille de la seconde tarte ou barre d'un graphique de tarte à tartes ou d'un graphique de barre à barres, en pourcentage de la taille de la première tarte (peut être entre 5 et 200 pourcents). Lecture/écriture UInt16. |
| [Series](../../aspose.slides.charts/chartseriesgroup/series) { get; } | Renvoie une collection de séries. Lecture seule [`IChartSeriesReadonlyCollection`](../ichartseriesreadonlycollection). |
| [Type](../../aspose.slides.charts/chartseriesgroup/type) { get; } | Renvoie un type de ce groupe de séries. Lecture seule [`CombinableSeriesTypesGroup`](../combinableseriestypesgroup). |
| [UpDownBars](../../aspose.slides.charts/chartseriesgroup/updownbars) { get; } | Fournit un accès aux barres montantes/baisées des graphiques en ligne ou en actions. Lecture seule [`IUpDownBarsManager`](../iupdownbarsmanager). |

### Remarques

1) Voir le résumé et les remarques pour la classe ChartSeriesGroupCollection et l'énumération CombinableSeriesTypesGroup. 2) Un groupe de séries contient certaines propriétés de série qui sont communes à chaque série dans le groupe ("propriétés du groupe de séries"). Les "propriétés du groupe de séries" dans la classe ChartSeriesGroup sont lecture/écriture. Chacune des "propriétés du groupe de séries" peut avoir une projection en lecture seule dans la classe ChartSeries.

### Voir Aussi

* interface [IChartSeriesGroup](../ichartseriesgroup)
* namespace [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->