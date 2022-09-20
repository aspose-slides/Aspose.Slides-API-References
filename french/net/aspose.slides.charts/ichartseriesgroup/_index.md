---
title: IChartSeriesGroup
second_title: Référence de l'API Aspose.Slides pour .NET
description: Représente un groupe de séries.
type: docs
weight: 1830
url: /fr/net/aspose.slides.charts/ichartseriesgroup/
---
## IChartSeriesGroup interface

Représente un groupe de séries.

```csharp
public interface IChartSeriesGroup : IChartComponent
```

## Propriétés

| Nom | La description |
| --- | --- |
| [AsIChartComponent](../../aspose.slides.charts/ichartseriesgroup/asichartcomponent) { get; } | Permet d'obtenir l'interface IChartComponent de base. Lecture seule[`IChartComponent`](../ichartcomponent) . |
| [BubbleSizeRepresentation](../../aspose.slides.charts/ichartseriesgroup/bubblesizerepresentation) { get; set; } | Spécifie comment les valeurs de taille de bulle sont représentées sur le graphique à bulles. Lecture/écriture[`BubbleSizeRepresentationType`](../bubblesizerepresentationtype) . |
| [BubbleSizeScale](../../aspose.slides.charts/ichartseriesgroup/bubblesizescale) { get; set; } | Spécifie le facteur d'échelle du graphique à bulles (peut être entre 0 et 300 % de la taille par défaut). Lecture/écritureInt32 . |
| [DoughnutHoleSize](../../aspose.slides.charts/ichartseriesgroup/doughnutholesize) { get; set; } | Spécifie la taille du trou dans un graphique en anneau (peut être comprise entre 10 et 90 % de la taille de la zone de tracé). Lecture/écritureByte . |
| [FirstSliceAngle](../../aspose.slides.charts/ichartseriesgroup/firstsliceangle) { get; set; } | Obtient ou définit l'angle de la première tranche de graphique à secteurs ou en anneau, en degrés (dans le sens des aiguilles d'une montre à partir du haut, de 0 à 360 degrés). Lecture/écritureUInt16 . |
| [GapDepth](../../aspose.slides.charts/ichartseriesgroup/gapdepth) { get; set; } | Renvoie ou définit la distance, en pourcentage de la largeur du marqueur, entre les séries de données dans un graphique 3D. Lecture/écritureUInt16 . |
| [GapWidth](../../aspose.slides.charts/ichartseriesgroup/gapwidth) { get; set; } | Spécifie l'espace entre les groupes de barres ou de colonnes, sous forme de pourcentage de la largeur de la barre ou de la colonne. Lecture/écritureUInt16 . |
| [HasSeriesLines](../../aspose.slides.charts/ichartseriesgroup/hasserieslines) { get; set; } | Vrai si le graphique comporte des lignes de série. Appliqué aux graphiques à barres empilées et OfPie. Lecture/écritureBoolean . |
| [HiLowLinesFormat](../../aspose.slides.charts/ichartseriesgroup/hilowlinesformat) { get; } | Spécifie le format HiLowLines. HiLowLines appliqué avec les types de graphiques HiLowClose, OpenHiLowClose, VolumeHiLowClose et VolumeOpenHiLowClose. |
| [IsColorVaried](../../aspose.slides.charts/ichartseriesgroup/iscolorvaried) { get; set; } | Spécifie que chaque marqueur de données de la série a une couleur différente. Lecture/écritureBoolean . |
| [Item](../../aspose.slides.charts/ichartseriesgroup/item) { get; } | Obtient l'élément à l'index spécifié. |
| [Overlap](../../aspose.slides.charts/ichartseriesgroup/overlap) { get; set; } | Spécifie le nombre de barres et de colonnes qui doivent se chevaucher sur les graphiques 2D (de -100 à 100). Lecture/écritureSByte . |
| [PieSplitBy](../../aspose.slides.charts/ichartseriesgroup/piesplitby) { get; set; } | Spécifie comment déterminer quels points de données se trouvent dans le deuxième secteur ou barre sur un graphique en secteurs ou en barres. Lecture/écriture[`PieSplitType`](../piesplittype) . |
| [PieSplitCustomPoints](../../aspose.slides.charts/ichartseriesgroup/piesplitcustompoints) { get; } | Les informations de fractionnement personnalisées pour un graphique en secteurs ou en barres avec un fractionnement personnalisé. Contient des points de données qui doivent être dessinés dans le deuxième secteur ou barre d'un secteur ou d'une barre de -graphique circulaire. Lecture seule[`IPieSplitCustomPointCollection`](../ipiesplitcustompointcollection) . |
| [PieSplitPosition](../../aspose.slides.charts/ichartseriesgroup/piesplitposition) { get; set; } | Spécifie une valeur qui doit être utilisée pour déterminer quels points de données se trouvent dans le deuxième camembert ou barre d'un graphique camembert ou barre de camembert. Est utilisé avec la propriété PieSplitBy. Lecture/écritureDouble . |
| [PlotOnSecondAxis](../../aspose.slides.charts/ichartseriesgroup/plotonsecondaxis) { get; } | Indique si la série de ce groupe est tracée sur l'axe secondaire. Lecture seuleBoolean . |
| [SecondPieSize](../../aspose.slides.charts/ichartseriesgroup/secondpiesize) { get; set; } | Spécifie la taille du deuxième secteur ou barre d'un graphique en secteurs ou d'un graphique en barres, sous forme de pourcentage de la taille du premier secteur (peut être compris entre 5 et 200 %). Lire écrireUInt16 . |
| [Series](../../aspose.slides.charts/ichartseriesgroup/series) { get; } | Renvoie une collection en lecture seule de séries de graphiques. En lecture seule[`IChartSeriesReadonlyCollection`](../ichartseriesreadonlycollection) . |
| [Type](../../aspose.slides.charts/ichartseriesgroup/type) { get; } | Renvoie un type de ce groupe de séries. Lecture seule[`CombinableSeriesTypesGroup`](../combinableseriestypesgroup) . |
| [UpDownBars](../../aspose.slides.charts/ichartseriesgroup/updownbars) { get; } | Fournir un accès aux barres haut/bas du graphique linéaire ou boursier. Lecture seule[`IUpDownBarsManager`](../iupdownbarsmanager) . |

### Remarques

1) Voir le résumé et les remarques pour la classe ChartSeriesGroupCollection et l'énumération CombinableSeriesTypesGroup. 2) Le groupe de séries contient des propriétés de série communes à chaque série du groupe ("propriétés du groupe de séries"). "Propriétés du groupe de séries" dans la classe ChartSeriesGroup est en lecture/écriture. Chacune des "propriétés de groupe de séries" peut avoir une projection en lecture seule dans la classe ChartSeries.

### Voir également

* interface [IChartComponent](../ichartcomponent)
* espace de noms [Aspose.Slides.Charts](../../aspose.slides.charts)
* Assemblée [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
