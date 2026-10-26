---
title: ChartSeriesGroup
second_title: Référence de l'API Aspose.Sildes pour .NET
description: Représente un groupe de séries.
type: docs
weight: 1460
url: /fr/aspose.slides.charts/chartseriesgroup/
---
## ChartSeriesGroup classe

Représente un groupe de séries.

```csharp
public class ChartSeriesGroup : IChartSeriesGroup
```

## Propriétés

| Nom | Description |
| --- | --- |
| [BubbleSizeRepresentation](../../aspose.slides.charts/chartseriesgroup/bubblesizerepresentation) { get; set; } | Spécifie comment les valeurs de taille des bulles sont représentées sur le graphique à bulles. Lecture/écriture [`BubbleSizeRepresentationType`](../bubblesizerepresentationtype). |
| [BubbleSizeScale](../../aspose.slides.charts/chartseriesgroup/bubblesizescale) { get; set; } | Spécifie le facteur d'échelle pour le graphique à bulles (peut être compris entre 0 et 300 pour cent de la taille par défaut). Lecture/écriture Int32. |
| [Chart](../../aspose.slides.charts/chartseriesgroup/chart) { get; } | Renvoie le graphique parent. Lecture seule [`IChart`](../ichart). |
| [DoughnutHoleSize](../../aspose.slides.charts/chartseriesgroup/doughnutholesize) { get; set; } | Spécifie la taille du trou dans un graphique en anneau (peut être compris entre 0 et 90 pour cent de la taille de la zone de tracé). Lecture/écriture Byte. |
| [FirstSliceAngle](../../aspose.slides.charts/chartseriesgroup/firstsliceangle) { get; set; } | Obtient ou définit l'angle de la première tranche de secteur ou d'anneau, en degrés (dans le sens des aiguilles d'une montre à partir du haut, de 0 à 360 degrés). Lecture/écriture UInt16. |
| [GapDepth](../../aspose.slides.charts/chartseriesgroup/gapdepth) { get; set; } | Renvoie ou définit la distance, en pourcentage de la largeur du marqueur, entre les séries de données dans un graphique 3D. Lecture/écriture UInt16. |
| [GapWidth](../../aspose.slides.charts/chartseriesgroup/gapwidth) { get; set; } | Spécifie l'espacement entre les groupes de barres ou de colonnes, en pourcentage de la largeur de la barre ou de la colonne. Lecture/écriture UInt16. |
| [HasSeriesLines](../../aspose.slides.charts/chartseriesgroup/hasserieslines) { get; set; } | Vrai si le graphique possède des lignes de séries. Appliqué aux graphiques à barres empilées et OfPie. Lecture/écriture Boolean. |
| [HiLowLinesFormat](../../aspose.slides.charts/chartseriesgroup/hilowlinesformat) { get; } | Spécifie le format HiLowLines. HiLowLines appliqué avec les types de graphiques HiLowClose, OpenHiLowClose, VolumeHiLowClose et VolumeOpenHiLowClose. |
| [IsColorVaried](../../aspose.slides.charts/chartseriesgroup/iscolorvaried) { get; set; } | Spécifie que chaque marqueur de données dans la série a une couleur différente. Lecture/écriture Boolean. |
| [Item](../../aspose.slides.charts/chartseriesgroup/item) { get; } | Obtient l'élément à l'index spécifié. |
| [Overlap](../../aspose.slides.charts/chartseriesgroup/overlap) { get; set; } | Spécifie le degré de chevauchement des barres et des colonnes sur les graphiques 2D, en pourcentage (de -100% à 100%). - -100%: Espacement maximal (les barres sont complètement séparées). - 0%: Les barres sont placées côte à côte sans chevauchement ni espacement. - 100%: Chevauchement maximal (les barres se chevauchent complètement). Cette propriété est lecture/écriture SByte. |
| [PieSplitBy](../../aspose.slides.charts/chartseriesgroup/piesplitby) { get; set; } | Spécifie comment déterminer quels points de données se trouvent dans le deuxième secteur ou barre d'un graphique pie-of-pie ou bar-of-pie. Lecture/écriture [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/chartseriesgroup/piesplitcustompoints) { get; } | Les informations de division personnalisée pour un graphique pie-of-pie ou bar-of-pie avec une division personnalisée. Contient les points de données qui doivent être dessinés dans le deuxième secteur ou barre d'un graphique pie-of-pie ou bar-of-pie. Lecture seule [`PieSplitCustomPointCollection`](../piesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/chartseriesgroup/piesplitposition) { get; set; } | Spécifie une valeur qui sera utilisée pour déterminer quels points de données se trouvent dans le deuxième secteur ou barre d'un graphique pie-of-pie ou bar-of-pie. Utilisée conjointement avec la propriété PieSplitBy. Lecture/écriture Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/chartseriesgroup/plotonsecondaxis) { get; } | Indique si les séries de ce groupe sont tracées sur l'axe secondaire. Lecture seule Boolean. |
| [SecondPieSize](../../aspose.slides.charts/chartseriesgroup/secondpiesize) { get; set; } | Spécifie la taille du deuxième secteur ou barre d'un graphique pie-of-pie ou bar-of-pie, en pourcentage de la taille du premier secteur (peut être compris entre 5 et 200 pour cent). Lecture/écriture UInt16. |
| [Series](../../aspose.slides.charts/chartseriesgroup/series) { get; } | Renvoie une collection de séries. Lecture seule [`IChartSeriesReadonlyCollection`](../ichartseriesreadonlycollection). |
| [Type](../../aspose.slides.charts/chartseriesgroup/type) { get; } | Renvoie le type de ce groupe de séries. Lecture seule [`CombinableSeriesTypesGroup`](../combinableseriestypesgroup). |
| [UpDownBars](../../aspose.slides.charts/chartseriesgroup/updownbars) { get; } | Fournit l'accès aux barres haut/bas d'un graphique en ligne ou de type Stock. Lecture seule [`IUpDownBarsManager`](../iupdownbarsmanager). |

### Remarques

1) Voir le résumé et les remarques pour la classe ChartSeriesGroupCollection et l'énumération CombinableSeriesTypesGroup. 2) Le groupe de séries contient certaines propriétés de séries qui sont communes à chaque série du groupe ("propriétés du groupe de séries"). "Propriétés du groupe de séries" dans la classe ChartSeriesGroup sont lecture/écriture. Chaque "propriétés du groupe de séries" peut avoir une projection lecture seule dans la classe ChartSeries.

### Voir aussi

* interface [IChartSeriesGroup](../ichartseriesgroup)
* espace de noms [Aspose.Slides.Charts](../../aspose.slides.charts)
* assemblage [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->