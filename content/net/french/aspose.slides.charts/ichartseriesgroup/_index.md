---
title: IChartSeriesGroup
second_title: Référence API Aspose.Sildes pour .NET
description: Représente un groupe de séries.
type: docs
weight: 1970
url: /fr/aspose.slides.charts/ichartseriesgroup/
---
## IChartSeriesGroup interface

Représente un groupe de séries.

```csharp
public interface IChartSeriesGroup : IChartComponent
```

## Propriétés

| Name | Description |
| --- | --- |
| [AsIChartComponent](../../aspose.slides.charts/ichartseriesgroup/asichartcomponent) { get; } | Permet d'obtenir l'interface de base IChartComponent. Lecture seule [`IChartComponent`](../ichartcomponent). |
| [BubbleSizeRepresentation](../../aspose.slides.charts/ichartseriesgroup/bubblesizerepresentation) { get; set; } | Spécifie comment les valeurs de taille des bulles sont représentées sur le diagramme à bulles. Lecture/écriture [`BubbleSizeRepresentationType`](../bubblesizerepresentationtype). |
| [BubbleSizeScale](../../aspose.slides.charts/ichartseriesgroup/bubblesizescale) { get; set; } | Spécifie le facteur d'échelle pour le diagramme à bulles (peut être compris entre 0 et 300 pour cent de la taille par défaut). Lecture/écriture Int32. |
| [DoughnutHoleSize](../../aspose.slides.charts/ichartseriesgroup/doughnutholesize) { get; set; } | Spécifie la taille du trou dans un diagramme en anneau (peut être compris entre 10 et 90 pour cent de la taille de la zone de tracé). Lecture/écriture Byte. |
| [FirstSliceAngle](../../aspose.slides.charts/ichartseriesgroup/firstsliceangle) { get; set; } | Obtient ou définit l'angle de la première tranche de diagramme circulaire ou en anneau, en degrés (dans le sens des aiguilles d'une montre à partir du haut, de 0 à 360 degrés). Lecture/écriture UInt16. |
| [GapDepth](../../aspose.slides.charts/ichartseriesgroup/gapdepth) { get; set; } | Obtient ou définit la distance entre les séries de données dans un diagramme 3D, en pourcentage de la largeur du repère. La valeur doit être comprise entre 0 et 500. Lecture/écriture UInt16. |
| [GapWidth](../../aspose.slides.charts/ichartseriesgroup/gapwidth) { get; set; } | Obtient ou définit l'espace entre les groupes de barres ou de colonnes, en pourcentage de la largeur de la barre ou de la colonne. La valeur doit être comprise entre 0 et 500. Lecture/écriture UInt16. |
| [HasSeriesLines](../../aspose.slides.charts/ichartseriesgroup/hasserieslines) { get; set; } | Vrai si le diagramme comporte des lignes de séries. Appliqué aux diagrammes à barres empilées et OfPie. Lecture/écriture Boolean. |
| [HiLowLinesFormat](../../aspose.slides.charts/ichartseriesgroup/hilowlinesformat) { get; } | Spécifie le format HiLowLines. HiLowLines appliqué avec les types de diagrammes HiLowClose, OpenHiLowClose, VolumeHiLowClose et VolumeOpenHiLowClose. |
| [IsColorVaried](../../aspose.slides.charts/ichartseriesgroup/iscolorvaried) { get; set; } | Spécifie que chaque repère de données dans la série a une couleur différente. Lecture/écriture Boolean. |
| [Item](../../aspose.slides.charts/ichartseriesgroup/item) { get; } | Obtient l'élément à l'index spécifié. |
| [Overlap](../../aspose.slides.charts/ichartseriesgroup/overlap) { get; set; } | Spécifie dans quelle mesure les barres et les colonnes doivent se chevaucher sur les diagrammes 2-D, en pourcentage (de -100% à 100%). - -100%: espacement maximal (les barres sont complètement séparées). - 0%: les barres sont placées côte à côte sans chevauchement ni espacement. - 100%: chevauchement maximal (les barres se chevauchent complètement). Cette propriété est lecture/écriture SByte. |
| [PieSplitBy](../../aspose.slides.charts/ichartseriesgroup/piesplitby) { get; set; } | Spécifie comment déterminer quels points de données se trouvent dans le deuxième secteur ou barre d'un diagramme pie-of-pie ou bar-of-pie. Lecture/écriture [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/ichartseriesgroup/piesplitcustompoints) { get; } | Les informations de division personnalisée pour un diagramme pie-of-pie ou bar-of-pie avec une division personnalisée. Contient les points de données qui doivent être dessinés dans le deuxième secteur ou barre d'un diagramme pie-of-pie ou bar-of-pie. Lecture seule [`IPieSplitCustomPointCollection`](../ipiesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/ichartseriesgroup/piesplitposition) { get; set; } | Spécifie une valeur qui doit être utilisée pour déterminer quels points de données se trouvent dans le deuxième secteur ou barre d'un diagramme pie-of-pie ou bar-of-pie. Utilisée conjointement avec la propriété PieSplitBy. Lecture/écriture Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/ichartseriesgroup/plotonsecondaxis) { get; } | Indique si les séries de ce groupe sont tracées sur un axe secondaire. Lecture seule Boolean. |
| [SecondPieSize](../../aspose.slides.charts/ichartseriesgroup/secondpiesize) { get; set; } | Spécifie la taille du deuxième secteur ou barre d'un diagramme pie-of-pie ou bar-of-pie, en pourcentage de la taille du premier secteur (peut être compris entre 5 et 200 pour cent). Lecture/écriture UInt16. |
| [Series](../../aspose.slides.charts/ichartseriesgroup/series) { get; } | Renvoie une collection en lecture seule de séries de diagramme. Lecture seule [`IChartSeriesReadonlyCollection`](../ichartseriesreadonlycollection). |
| [Type](../../aspose.slides.charts/ichartseriesgroup/type) { get; } | Renvoie un type de ce groupe de séries. Lecture seule [`CombinableSeriesTypesGroup`](../combinableseriestypesgroup). |
| [UpDownBars](../../aspose.slides.charts/ichartseriesgroup/updownbars) { get; } | Fournit l'accès aux barres haut/bas d'un diagramme en ligne ou en cours. Lecture seule [`IUpDownBarsManager`](../iupdownbarsmanager). |

### Remarques

1) Voir le résumé et les remarques pour la classe ChartSeriesGroupCollection et l'énumération CombinableSeriesTypesGroup. 2) Le groupe de séries contient certaines propriétés de séries qui sont communes à chaque série du groupe (« propriétés de groupe de séries »). Les « propriétés de groupe de séries » dans la classe ChartSeriesGroup sont lecture/écriture. Chaque « propriété de groupe de séries » peut avoir une projection en lecture seule dans la classe ChartSeries.

### Voir aussi

* interface [IChartComponent](../ichartcomponent)
* espace de noms [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->