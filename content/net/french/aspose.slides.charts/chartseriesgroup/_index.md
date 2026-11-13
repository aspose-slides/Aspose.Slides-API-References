---
title: ChartSeriesGroup
second_title: Référence API Aspose.Sildes pour .NET
description: Représente un groupe de séries.
type: docs
weight: 1470
url: /fr/aspose.slides.charts/chartseriesgroup/
---
## ChartSeriesGroup classe

Représente un groupe de séries.

```csharp
public class ChartSeriesGroup : IChartSeriesGroup
```

## Propriétés

| Name | Description |
| --- | --- |
| [BubbleSizeRepresentation](../../aspose.slides.charts/chartseriesgroup/bubblesizerepresentation) { get; set; } | Spécifie comment les valeurs de taille de bulle sont représentées sur le bubble chart. Lecture/écriture [`BubbleSizeRepresentationType`](../bubblesizerepresentationtype). |
| [BubbleSizeScale](../../aspose.slides.charts/chartseriesgroup/bubblesizescale) { get; set; } | Spécifie le facteur d'échelle pour le bubble chart (peut être compris entre 0 et 300 % de la taille par défaut). Lecture/écriture Int32. |
| [Chart](../../aspose.slides.charts/chartseriesgroup/chart) { get; } | Renvoie le diagramme parent. Lecture seule [`IChart`](../ichart). |
| [DoughnutHoleSize](../../aspose.slides.charts/chartseriesgroup/doughnutholesize) { get; set; } | Spécifie la taille du trou dans un doughnut chart (peut être compris entre 0 et 90 % de la taille de la zone du tracé). Lecture/écriture Byte. |
| [FirstSliceAngle](../../aspose.slides.charts/chartseriesgroup/firstsliceangle) { get; set; } | Obtient ou définit l'angle de la première tranche de pie ou doughnut chart, en degrés (dans le sens des aiguilles d'une montre à partir du haut, de 0 à 360 degrés). Lecture/écriture UInt16. |
| [GapDepth](../../aspose.slides.charts/chartseriesgroup/gapdepth) { get; set; } | Obtient ou définit la distance entre les séries de données dans un 3D chart, en pourcentage de la largeur du marqueur. La valeur doit être comprise entre 0 et 500. Lecture/écriture UInt16. |
| [GapWidth](../../aspose.slides.charts/chartseriesgroup/gapwidth) { get; set; } | Obtient ou définit l'espace entre les regroupements de barres ou de colonnes, en pourcentage de la largeur de la barre ou de la colonne. La valeur doit être comprise entre 0 et 500. Lecture/écriture UInt16. |
| [HasSeriesLines](../../aspose.slides.charts/chartseriesgroup/hasserieslines) { get; set; } | True si le chart a des series lines. Appliqué aux stacked bar et OfPie charts. Lecture/écriture Boolean. |
| [HiLowLinesFormat](../../aspose.slides.charts/chartseriesgroup/hilowlinesformat) { get; } | Spécifie le format HiLowLines. HiLowLines appliqué avec HiLowClose, OpenHiLowClose, VolumeHiLowClose et VolumeOpenHiLowClose chart types. |
| [IsColorVaried](../../aspose.slides.charts/chartseriesgroup/iscolorvaried) { get; set; } | Spécifie que chaque marqueur de données dans la série a une couleur différente. Lecture/écriture Boolean. |
| [Item](../../aspose.slides.charts/chartseriesgroup/item) { get; } | Obtient l'élément à l'index spécifié. |
| [Overlap](../../aspose.slides.charts/chartseriesgroup/overlap) { get; set; } | Spécifie le degré de chevauchement des barres et des colonnes sur les 2-D charts, en pourcentage (de -100 % à 100 %). - -100 % : Espacement maximal (les barres sont complètement séparées). - 0 % : Les barres sont placées côte à côte sans chevauchement ni espacement. - 100 % : Chevauchement maximal (les barres se chevauchent entièrement). Cette propriété est lecture/écriture SByte. |
| [PieSplitBy](../../aspose.slides.charts/chartseriesgroup/piesplitby) { get; set; } | Spécifie comment déterminer quels points de données sont dans le deuxième pie ou bar sur un pie-of-pie ou bar-of-pie chart. Lecture/écriture [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/chartseriesgroup/piesplitcustompoints) { get; } | Les informations de division personnalisée pour un pie-of-pie ou bar-of-pie chart avec une division personnalisée. Contient les points de données qui doivent être dessinés dans le deuxième pie ou bar dans un pie-of-pie ou bar-of-pie chart. Lecture seule [`PieSplitCustomPointCollection`](../piesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/chartseriesgroup/piesplitposition) { get; set; } | Spécifie une valeur qui doit être utilisée pour déterminer quels points de données sont dans le deuxième pie ou bar sur un pie-of-pie ou bar-of-pie chart. Utilisée conjointement avec la propriété PieSplitBy. Lecture/écriture Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/chartseriesgroup/plotonsecondaxis) { get; } | Indique si les séries de ce groupe sont tracées sur l'axe secondaire. Lecture seule Boolean. |
| [SecondPieSize](../../aspose.slides.charts/chartseriesgroup/secondpiesize) { get; set; } | Spécifie la taille du deuxième pie ou bar d'un pie-of-pie chart ou d'un bar-of-pie chart, en pourcentage de la taille du premier pie (peut être compris entre 5 et 200 %). Lecture/écriture UInt16. |
| [Series](../../aspose.slides.charts/chartseriesgroup/series) { get; } | Renvoie une collection de séries. Lecture seule [`IChartSeriesReadonlyCollection`](../ichartseriesreadonlycollection). |
| [Type](../../aspose.slides.charts/chartseriesgroup/type) { get; } | Renvoie le type de ce groupe de séries. Lecture seule [`CombinableSeriesTypesGroup`](../combinableseriestypesgroup). |
| [UpDownBars](../../aspose.slides.charts/chartseriesgroup/updownbars) { get; } | Fournit l'accès aux barres up/down de Line- ou Stock-chart. Lecture seule [`IUpDownBarsManager`](../iupdownbarsmanager). |

### Remarques

1) Voir le résumé et les remarques pour la classe ChartSeriesGroupCollection et l'énumération CombinableSeriesTypesGroup. 2) Le groupe de séries contient certaines propriétés de séries qui sont communes à chaque série du groupe ("series group properties"). "Series group properties" dans la classe ChartSeriesGroup sont lecture/écriture. Chacune des "series group properties" peut avoir une projection lecture seule dans la classe ChartSeries.

### Voir aussi

* interface [IChartSeriesGroup](../ichartseriesgroup)
* espace de noms [Aspose.Slides.Charts](../../aspose.slides.charts)
* assemblage [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->