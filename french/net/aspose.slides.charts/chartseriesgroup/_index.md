---
title: ChartSeriesGroup
second_title: Référence de l'API Aspose.Slides pour .NET
description: Représente un groupe de séries.
type: docs
weight: 1340
url: /fr/net/aspose.slides.charts/chartseriesgroup/
---
## ChartSeriesGroup class

Représente un groupe de séries.

```csharp
public class ChartSeriesGroup : IChartSeriesGroup
```

## Propriétés

| Nom | La description |
| --- | --- |
| [BubbleSizeRepresentation](../../aspose.slides.charts/chartseriesgroup/bubblesizerepresentation) { get; set; } | Spécifie comment les valeurs de taille de bulle sont représentées sur le graphique à bulles. Lecture/écriture[`BubbleSizeRepresentationType`](../bubblesizerepresentationtype) . |
| [BubbleSizeScale](../../aspose.slides.charts/chartseriesgroup/bubblesizescale) { get; set; } | Spécifie le facteur d'échelle du graphique à bulles (peut être entre 0 et 300 % de la taille par défaut). Lecture/écritureInt32 . |
| [Chart](../../aspose.slides.charts/chartseriesgroup/chart) { get; } | Renvoie le graphique parent. Lecture seule[`IChart`](../ichart) . |
| [DoughnutHoleSize](../../aspose.slides.charts/chartseriesgroup/doughnutholesize) { get; set; } | Spécifie la taille du trou dans un graphique en anneau (peut être comprise entre 0 et 90 % de la taille de la zone de tracé). Lecture/écritureByte . |
| [FirstSliceAngle](../../aspose.slides.charts/chartseriesgroup/firstsliceangle) { get; set; } | Obtient ou définit l'angle de la première tranche de graphique à secteurs ou en anneau, en degrés (dans le sens des aiguilles d'une montre à partir du haut, de 0 à 360 degrés). Lecture/écritureUInt16 . |
| [GapDepth](../../aspose.slides.charts/chartseriesgroup/gapdepth) { get; set; } | Renvoie ou définit la distance, en pourcentage de la largeur du marqueur, entre les séries de données dans un graphique 3D. Lecture/écritureUInt16 . |
| [GapWidth](../../aspose.slides.charts/chartseriesgroup/gapwidth) { get; set; } | Spécifie l'espace entre les groupes de barres ou de colonnes, sous forme de pourcentage de la largeur de la barre ou de la colonne. Lecture/écritureUInt16 . |
| [HasSeriesLines](../../aspose.slides.charts/chartseriesgroup/hasserieslines) { get; set; } | Vrai si le graphique comporte des lignes de série. Appliqué aux graphiques à barres empilées et OfPie. Lecture/écritureBoolean . |
| [HiLowLinesFormat](../../aspose.slides.charts/chartseriesgroup/hilowlinesformat) { get; } | Spécifie le format HiLowLines. HiLowLines appliqué avec les types de graphiques HiLowClose, OpenHiLowClose, VolumeHiLowClose et VolumeOpenHiLowClose. |
| [IsColorVaried](../../aspose.slides.charts/chartseriesgroup/iscolorvaried) { get; set; } | Spécifie que chaque marqueur de données de la série a une couleur différente. Lecture/écritureBoolean . |
| [Item](../../aspose.slides.charts/chartseriesgroup/item) { get; } | Obtient l'élément à l'index spécifié. |
| [Overlap](../../aspose.slides.charts/chartseriesgroup/overlap) { get; set; } | Spécifie le nombre de barres et de colonnes qui doivent se chevaucher sur les graphiques 2D (de -100 à 100). Lecture/écritureSByte . |
| [PieSplitBy](../../aspose.slides.charts/chartseriesgroup/piesplitby) { get; set; } | Spécifie comment déterminer quels points de données se trouvent dans le deuxième secteur ou barre sur un graphique en secteurs ou en barres. Lecture/écriture[`PieSplitType`](../piesplittype) . |
| [PieSplitCustomPoints](../../aspose.slides.charts/chartseriesgroup/piesplitcustompoints) { get; } | Les informations de fractionnement personnalisées pour un graphique en secteurs ou en barres avec un fractionnement personnalisé. Contient des points de données qui doivent être dessinés dans le deuxième secteur ou barre d'un secteur ou d'une barre de -graphique circulaire. Lecture seule[`PieSplitCustomPointCollection`](../piesplitcustompointcollection) . |
| [PieSplitPosition](../../aspose.slides.charts/chartseriesgroup/piesplitposition) { get; set; } | Spécifie une valeur qui doit être utilisée pour déterminer quels points de données se trouvent dans le deuxième camembert ou barre d'un graphique camembert ou barre de camembert. Est utilisé avec la propriété PieSplitBy. Lecture/écritureDouble . |
| [PlotOnSecondAxis](../../aspose.slides.charts/chartseriesgroup/plotonsecondaxis) { get; } | Indique si la série de ce groupe est tracée sur l'axe secondaire. Lecture seuleBoolean . |
| [SecondPieSize](../../aspose.slides.charts/chartseriesgroup/secondpiesize) { get; set; } | Spécifie la taille du deuxième secteur ou barre d'un graphique en secteurs ou d'un graphique en barres, sous forme de pourcentage de la taille du premier secteur (peut être compris entre 5 et 200 %). Lire écrireUInt16 . |
| [Series](../../aspose.slides.charts/chartseriesgroup/series) { get; } | Renvoie une collection de séries. Lecture seule[`IChartSeriesReadonlyCollection`](../ichartseriesreadonlycollection) . |
| [Type](../../aspose.slides.charts/chartseriesgroup/type) { get; } | Renvoie un type de ce groupe de séries. Lecture seule[`CombinableSeriesTypesGroup`](../combinableseriestypesgroup) . |
| [UpDownBars](../../aspose.slides.charts/chartseriesgroup/updownbars) { get; } | Fournir un accès aux barres haut/bas du graphique linéaire ou boursier. Lecture seule[`IUpDownBarsManager`](../iupdownbarsmanager) . |

### Remarques

1) Voir le résumé et les remarques pour la classe ChartSeriesGroupCollection et l'énumération CombinableSeriesTypesGroup. 2) Le groupe de séries contient des propriétés de série communes à chaque série du groupe ("propriétés du groupe de séries"). "Propriétés du groupe de séries" dans la classe ChartSeriesGroup est en lecture/écriture. Chacune des "propriétés de groupe de séries" peut avoir une projection en lecture seule dans la classe ChartSeries.

### Voir également

* interface [IChartSeriesGroup](../ichartseriesgroup)
* espace de noms [Aspose.Slides.Charts](../../aspose.slides.charts)
* Assemblée [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
