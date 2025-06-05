---
title: IChartSeriesGroup
second_title: Référence de l'API Aspose.Slides pour .NET
description: Représente un groupe de séries.
type: docs
weight: 1870
url: /fr/aspose.slides.charts/ichartseriesgroup/
---

## Interface IChartSeriesGroup

Représente un groupe de séries.

```csharp
public interface IChartSeriesGroup : IChartComponent
```

## Propriétés

| Nom | Description |
| --- | --- |
| [AsIChartComponent](../../aspose.slides.charts/ichartseriesgroup/asichartcomponent) { get; } | Permet d'obtenir l'interface de base IChartComponent. Lecture seule [`IChartComponent`](../ichartcomponent). |
| [BubbleSizeRepresentation](../../aspose.slides.charts/ichartseriesgroup/bubblesizerepresentation) { get; set; } | Spécifie comment les valeurs de taille des bulles sont représentées sur le graphique à bulles. Lecture/écriture [`BubbleSizeRepresentationType`](../bubblesizerepresentationtype). |
| [BubbleSizeScale](../../aspose.slides.charts/ichartseriesgroup/bubblesizescale) { get; set; } | Spécifie le facteur d'échelle pour le graphique à bulles (peut varier entre 0 et 300 pourcents de la taille par défaut). Lecture/écriture Int32. |
| [DoughnutHoleSize](../../aspose.slides.charts/ichartseriesgroup/doughnutholesize) { get; set; } | Spécifie la taille du trou dans un graphique en anneau (peut varier entre 10 et 90 pourcents de la taille de la zone de tracé). Lecture/écriture Byte. |
| [FirstSliceAngle](../../aspose.slides.charts/ichartseriesgroup/firstsliceangle) { get; set; } | Obtient ou définit l'angle de la première tranche de graphique en secteur ou en anneau, en degrés (dans le sens des aiguilles d'une montre depuis le haut, de 0 à 360 degrés). Lecture/écriture UInt16. |
| [GapDepth](../../aspose.slides.charts/ichartseriesgroup/gapdepth) { get; set; } | Renvoie ou définit la distance, en pourcentage de la largeur du marqueur, entre les séries de données dans un graphique 3D. Lecture/écriture UInt16. |
| [GapWidth](../../aspose.slides.charts/ichartseriesgroup/gapwidth) { get; set; } | Spécifie l'espace entre les clusters de barres ou de colonnes, en pourcentage de la largeur des barres ou des colonnes. Lecture/écriture UInt16. |
| [HasSeriesLines](../../aspose.slides.charts/ichartseriesgroup/hasserieslines) { get; set; } | Vrai si le graphique a des lignes de série. Applicable aux graphiques à barres empilées et aux graphiques en secteurs de type OfPie. Lecture/écriture Boolean. |
| [HiLowLinesFormat](../../aspose.slides.charts/ichartseriesgroup/hilowlinesformat) { get; } | Spécifie le format des HiLowLines. HiLowLines appliqués avec les types de graphiques HiLowClose, OpenHiLowClose, VolumeHiLowClose et VolumeOpenHiLowClose. |
| [IsColorVaried](../../aspose.slides.charts/ichartseriesgroup/iscolorvaried) { get; set; } | Spécifie que chaque marqueur de données dans la série a une couleur différente. Lecture/écriture Boolean. |
| [Item](../../aspose.slides.charts/ichartseriesgroup/item) { get; } | Obtient l'élément à l'index spécifié. |
| [Overlap](../../aspose.slides.charts/ichartseriesgroup/overlap) { get; set; } | Spécifie dans quelle mesure les barres et les colonnes doivent se chevaucher sur les graphiques 2D, en pourcentage (de -100% à 100%). - -100% : Espacement maximum (les barres sont complètement séparées). - 0% : Les barres sont placées côte à côte sans chevauchement ni espacement. - 100% : Chevauchement maximum (les barres se chevauchent complètement). Cette propriété est en lecture/écriture SByte. |
| [PieSplitBy](../../aspose.slides.charts/ichartseriesgroup/piesplitby) { get; set; } | Spécifie comment déterminer quels points de données se trouvent dans le deuxième secteur ou barre d'un graphique en secteurs de type pie-of-pie ou bar-of-pie. Lecture/écriture [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/ichartseriesgroup/piesplitcustompoints) { get; } | Les informations de séparation personnalisées pour un graphique en secteurs de type pie-of-pie ou bar-of-pie avec une séparation personnalisée. Contient des points de données qui doivent être tracés dans le deuxième secteur ou barre dans un graphique en secteurs de type pie-of-pie ou bar-of-pie. Lecture seule [`IPieSplitCustomPointCollection`](../ipiesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/ichartseriesgroup/piesplitposition) { get; set; } | Spécifie une valeur qui doit être utilisée pour déterminer quels points de données se trouvent dans le deuxième secteur ou barre d'un graphique en secteurs de type pie-of-pie ou bar-of-pie. Est utilisée avec la propriété PieSplitBy. Lecture/écriture Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/ichartseriesgroup/plotonsecondaxis) { get; } | Indique si les séries de ce groupe sont tracées sur l'axe secondaire. Lecture seule Boolean. |
| [SecondPieSize](../../aspose.slides.charts/ichartseriesgroup/secondpiesize) { get; set; } | Spécifie la taille du deuxième secteur ou barre d'un graphique en secteurs de type pie-of-pie ou bar-of-pie, en pourcentage de la taille du premier secteur (peut varier entre 5 et 200 pourcents). Lecture/écriture UInt16. |
| [Series](../../aspose.slides.charts/ichartseriesgroup/series) { get; } | Renvoie une collection en lecture seule de séries de graphiques. Lecture seule [`IChartSeriesReadonlyCollection`](../ichartseriesreadonlycollection). |
| [Type](../../aspose.slides.charts/ichartseriesgroup/type) { get; } | Renvoie un type de ce groupe de séries. Lecture seule [`CombinableSeriesTypesGroup`](../combinableseriestypesgroup). |
| [UpDownBars](../../aspose.slides.charts/ichartseriesgroup/updownbars) { get; } | Provide accès aux barres montantes/décroissantes du graphique en ligne ou de type actions. Lecture seule [`IUpDownBarsManager`](../iupdownbarsmanager). |

### Remarques

1) Voir le résumé et les remarques pour la classe ChartSeriesGroupCollection et l'énumération CombinableSeriesTypesGroup. 2) Le groupe de séries contient certaines propriétés de série qui sont communes à chaque série du groupe ("propriétés du groupe de séries"). Les "propriétés du groupe de séries" dans la classe ChartSeriesGroup sont en lecture/écriture. Chacune des "propriétés du groupe de séries" peut avoir une projection en lecture seule dans la classe ChartSeries.

### Voir aussi

* interface [IChartComponent](../ichartcomponent)
* namespace [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->