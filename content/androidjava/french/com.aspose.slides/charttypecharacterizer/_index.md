---
title: ChartTypeCharacterizer
second_title: Référence de l'API Java d'Aspose.Slides pour Android
description: Assistant pour obtenir des informations supplémentaires sur les graphiques et les séries à partir de leur ChartType.
type: docs
url: /fr/com.aspose.slides/charttypecharacterizer/
---
**Héritage :**
java.lang.Object
```
public class ChartTypeCharacterizer
```

Assistant pour obtenir des informations supplémentaires sur les graphiques et les séries par son ChartType.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [ChartTypeCharacterizer()](#ChartTypeCharacterizer--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [isBar3DChart(int chartType)](#isBar3DChart-int-) | Renvoie true si chartType est l'un des sous-types de bar3DChart (colonnes ou barres 3D). |
| [is2DChart(int chartType)](#is2DChart-int-) | Renvoie true si chartType est l'un des types de graphique 2D. |
| [is3DChart(int chartType)](#is3DChart-int-) | Renvoie true si chartType est l'un des types de graphique 3D. |
| [isChartTypeColumn(int chartType)](#isChartTypeColumn-int-) | Renvoie true si chartType est l'un des sous-types de Column. |
| [isChartTypeLine(int chartType)](#isChartTypeLine-int-) | Renvoie true si chartType est l'un des sous-types de Line. |
| [isChartTypePie(int chartType)](#isChartTypePie-int-) | Renvoie true si chartType est l'un des sous-types de Pie. |
| [isChartTypeBar(int chartType)](#isChartTypeBar-int-) | Renvoie true si chartType est l'un des sous-types de Bar. |
| [isChartTypeArea(int chartType)](#isChartTypeArea-int-) | Renvoie true si chartType est l'un des sous-types de Area. |
| [isChartTypeScatter(int chartType)](#isChartTypeScatter-int-) | Renvoie true si chartType est l'un des sous-types de Scatter. |
| [isChartTypeStock(int chartType)](#isChartTypeStock-int-) | Renvoie true si chartType est l'un des sous-types de Stock. |
| [isChartTypeSurface(int chartType)](#isChartTypeSurface-int-) | Renvoie true si chartType est l'un des sous-types de Surface. |
| [isChartTypeDoughnut(int chartType)](#isChartTypeDoughnut-int-) | Renvoie true si chartType est l'un des sous-types de Doughnut. |
| [isChartTypeBubble(int chartType)](#isChartTypeBubble-int-) | Renvoie true si chartType est l'un des sous-types de Bubble. |
| [isChartTypeRadar(int chartType)](#isChartTypeRadar-int-) | Renvoie true si chartType est l'un des sous-types de Radar. |
| [isSeriesUsesXValueCoordinate(int seriesType)](#isSeriesUsesXValueCoordinate-int-) | Renvoie si le type de série spécifié utilise les coordonnées de valeur X. |
| [isSeriesUsesYValueCoordinate(int seriesType)](#isSeriesUsesYValueCoordinate-int-) | Renvoie si le type de série spécifié utilise les coordonnées de valeur Y. |
| [isSeriesUsesValueCoordinate(int seriesType)](#isSeriesUsesValueCoordinate-int-) | Renvoie si le type de série spécifié utilise les coordonnées de valeur. |
| [isSeriesUsesBubbleSizeCoordinate(int seriesType)](#isSeriesUsesBubbleSizeCoordinate-int-) | Renvoie si les coordonnées de taille de bulle peuvent être utilisées pour le type de série spécifié. |
| [hasSeriesTrendLines(int seriesType)](#hasSeriesTrendLines-int-) | Renvoie s'il existe des lignes de tendance de série pour le type de série spécifié. |
| [isErrorBarsXAllowed(int seriesType)](#isErrorBarsXAllowed-int-) | Renvoie si les barres d’erreur X sont autorisées pour le type de série spécifié. |
| [isErrorBarsYAllowed(int seriesType)](#isErrorBarsYAllowed-int-) | Renvoie si les barres d’erreur Y sont autorisées pour le type de série spécifié. |
### ChartTypeCharacterizer() {#ChartTypeCharacterizer--}
```
public ChartTypeCharacterizer()
```


### isBar3DChart(int chartType) {#isBar3DChart-int-}
```
public static boolean isBar3DChart(int chartType)
```


Renvoie true si chartType est l'un des sous-types de bar3DChart (colonnes ou barres 3D).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| chartType | int |  |

**Renvoie :**
boolean
### is2DChart(int chartType) {#is2DChart-int-}
```
public static boolean is2DChart(int chartType)
```


Renvoie true si chartType est l'un des types de graphique 2D.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| chartType | int |  |

**Renvoie :**
boolean
### is3DChart(int chartType) {#is3DChart-int-}
```
public static boolean is3DChart(int chartType)
```


Renvoie true si chartType est l'un des types de graphique 3D.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| chartType | int |  |

**Renvoie :**
boolean
### isChartTypeColumn(int chartType) {#isChartTypeColumn-int-}
```
public static boolean isChartTypeColumn(int chartType)
```


Renvoie true si chartType est l'un des sous-types de Column. Le jeu de sous-types correspond à l’ensemble approprié dans PowerPoint (voir la boîte de dialogue « Change Chart Type » dans PowerPoint) : [ChartType.ClusteredColumn](../../com.aspose.slides/charttype\#ClusteredColumn), [ChartType.ClusteredColumn3D](../../com.aspose.slides/charttype\#ClusteredColumn3D), [ChartType.ClusteredCone](../../com.aspose.slides/charttype\#ClusteredCone), [ChartType.ClusteredCylinder](../../com.aspose.slides/charttype\#ClusteredCylinder), [ChartType.ClusteredPyramid](../../com.aspose.slides/charttype\#ClusteredPyramid), [ChartType.PercentsStackedColumn](../../com.aspose.slides/charttype\#PercentsStackedColumn), [ChartType.PercentsStackedColumn3D](../../com.aspose.slides/charttype\#PercentsStackedColumn3D), [ChartType.PercentsStackedCone](../../com.aspose.slides/charttype\#PercentsStackedCone), [ChartType.PercentsStackedCylinder](../../com.aspose.slides/charttype\#PercentsStackedCylinder), [ChartType.PercentsStackedPyramid](../../com.aspose.slides/charttype\#PercentsStackedPyramid), [ChartType.StackedColumn](../../com.aspose.slides/charttype\#StackedColumn), [ChartType.StackedColumn3D](../../com.aspose.slides/charttype\#StackedColumn3D), [ChartType.StackedCone](../../com.aspose.slides/charttype\#StackedCone), [ChartType.StackedCylinder](../../com.aspose.slides/charttype\#StackedCylinder), [ChartType.StackedPyramid](../../com.aspose.slides/charttype\#StackedPyramid), [ChartType.Column3D](../../com.aspose.slides/charttype\#Column3D), [ChartType.Cylinder3D](../../com.aspose.slides/charttype\#Cylinder3D), [ChartType.Cone3D](../../com.aspose.slides/charttype\#Cone3D), [ChartType.Pyramid3D](../../com.aspose.slides/charttype\#Pyramid3D).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| chartType | int |  |

**Renvoie :**
boolean
### isChartTypeLine(int chartType) {#isChartTypeLine-int-}
```
public static boolean isChartTypeLine(int chartType)
```


Renvoie true si chartType est l'un des sous-types de Line. Le jeu de sous-types correspond à l’ensemble approprié dans PowerPoint (voir la boîte de dialogue « Change Chart Type » dans PowerPoint) : [ChartType.Line](../../com.aspose.slides/charttype\#Line), [ChartType.LineWithMarkers](../../com.aspose.slides/charttype\#LineWithMarkers), [ChartType.PercentsStackedLine](../../com.aspose.slides/charttype\#PercentsStackedLine), [ChartType.PercentsStackedLineWithMarkers](../../com.aspose.slides/charttype\#PercentsStackedLineWithMarkers), [ChartType.StackedLine](../../com.aspose.slides/charttype\#StackedLine), [ChartType.StackedLineWithMarkers](../../com.aspose.slides/charttype\#StackedLineWithMarkers), [ChartType.Line3D](../../com.aspose.slides/charttype\#Line3D).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| chartType | int |  |

**Renvoie :**
boolean
### isChartTypePie(int chartType) {#isChartTypePie-int-}
```
public static boolean isChartTypePie(int chartType)
```


Renvoie true si chartType est l'un des sous-types de Pie. Le jeu de sous-types correspond à l’ensemble approprié dans PowerPoint (voir la boîte de dialogue « Change Chart Type » dans PowerPoint) : [ChartType.BarOfPie](../../com.aspose.slides/charttype\#BarOfPie), [ChartType.ExplodedPie](../../com.aspose.slides/charttype\#ExplodedPie), [ChartType.ExplodedPie3D](../../com.aspose.slides/charttype\#ExplodedPie3D), [ChartType.Pie](../../com.aspose.slides/charttype\#Pie), [ChartType.Pie3D](../../com.aspose.slides/charttype\#Pie3D), [ChartType.PieOfPie](../../com.aspose.slides/charttype\#PieOfPie).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| chartType | int |  |

**Renvoie :**
boolean
### isChartTypeBar(int chartType) {#isChartTypeBar-int-}
```
public static boolean isChartTypeBar(int chartType)
```


Renvoie true si chartType est l'un des sous-types de Bar. Le jeu de sous-types correspond à l’ensemble approprié dans PowerPoint (voir la boîte de dialogue « Change Chart Type » dans PowerPoint) : [ChartType.ClusteredBar](../../com.aspose.slides/charttype\#ClusteredBar), [ChartType.ClusteredBar3D](../../com.aspose.slides/charttype\#ClusteredBar3D), [ChartType.PercentsStackedBar](../../com.aspose.slides/charttype\#PercentsStackedBar), [ChartType.PercentsStackedBar3D](../../com.aspose.slides/charttype\#PercentsStackedBar3D), [ChartType.StackedBar](../../com.aspose.slides/charttype\#StackedBar), [ChartType.StackedBar3D](../../com.aspose.slides/charttype\#StackedBar3D), [ChartType.ClusteredHorizontalCone](../../com.aspose.slides/charttype\#ClusteredHorizontalCone), [ChartType.ClusteredHorizontalCylinder](../../com.aspose.slides/charttype\#ClusteredHorizontalCylinder), [ChartType.ClusteredHorizontalPyramid](../../com.aspose.slides/charttype\#ClusteredHorizontalPyramid), [ChartType.StackedHorizontalCone](../../com.aspose.slides/charttype\#StackedHorizontalCone), [ChartType.StackedHorizontalCylinder](../../com.aspose.slides/charttype\#StackedHorizontalCylinder), [ChartType.StackedHorizontalPyramid](../../com.aspose.slides/charttype\#StackedHorizontalPyramid), [ChartType.PercentsStackedHorizontalCone](../../com.aspose.slides/charttype\#PercentsStackedHorizontalCone), [ChartType.PercentsStackedHorizontalCylinder](../../com.aspose.slides/charttype\#PercentsStackedHorizontalCylinder), [ChartType.PercentsStackedHorizontalPyramid](../../com.aspose.slides/charttype\#PercentsStackedHorizontalPyramid).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| chartType | int |  |

**Renvoie :**
boolean
### isChartTypeArea(int chartType) {#isChartTypeArea-int-}
```
public static boolean isChartTypeArea(int chartType)
```


Renvoie true si chartType est l'un des sous-types de Area. Le jeu de sous-types correspond à l’ensemble approprié dans PowerPoint (voir la boîte de dialogue « Change Chart Type » dans PowerPoint) : [ChartType.Area](../../com.aspose.slides/charttype\#Area), [ChartType.PercentsStackedArea](../../com.aspose.slides/charttype\#PercentsStackedArea), [ChartType.PercentsStackedArea3D](../../com.aspose.slides/charttype\#PercentsStackedArea3D), [ChartType.StackedArea](../../com.aspose.slides/charttype\#StackedArea), [ChartType.StackedArea3D](../../com.aspose.slides/charttype\#StackedArea3D), [ChartType.Area3D](../../com.aspose.slides/charttype\#Area3D).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| chartType | int |  |

**Renvoie :**
boolean
### isChartTypeScatter(int chartType) {#isChartTypeScatter-int-}
```
public static boolean isChartTypeScatter(int chartType)
```


Renvoie true si chartType est l'un des sous-types de Scatter. Le jeu de sous-types correspond à l’ensemble approprié dans PowerPoint (voir la boîte de dialogue « Change Chart Type » dans PowerPoint) : [ChartType.ScatterWithMarkers](../../com.aspose.slides/charttype\#ScatterWithMarkers), [ChartType.ScatterWithSmoothLines](../../com.aspose.slides/charttype\#ScatterWithSmoothLines), [ChartType.ScatterWithSmoothLinesAndMarkers](../../com.aspose.slides/charttype\#ScatterWithSmoothLinesAndMarkers), [ChartType.ScatterWithStraightLines](../../com.aspose.slides/charttype\#ScatterWithStraightLines), [ChartType.ScatterWithStraightLinesAndMarkers](../../com.aspose.slides/charttype\#ScatterWithStraightLinesAndMarkers).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| chartType | int |  |

**Renvoie :**
boolean
### isChartTypeStock(int chartType) {#isChartTypeStock-int-}
```
public static boolean isChartTypeStock(int chartType)
```


Renvoie true si chartType est l'un des sous-types de Stock. Le jeu de sous-types correspond à l’ensemble approprié dans PowerPoint (voir la boîte de dialogue « Change Chart Type » dans PowerPoint) : [ChartType.HighLowClose](../../com.aspose.slides/charttype\#HighLowClose), [ChartType.OpenHighLowClose](../../com.aspose.slides/charttype\#OpenHighLowClose), [ChartType.VolumeHighLowClose](../../com.aspose.slides/charttype\#VolumeHighLowClose), [ChartType.VolumeOpenHighLowClose](../../com.aspose.slides/charttype\#VolumeOpenHighLowClose).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| chartType | int |  |

**Renvoie :**
boolean
### isChartTypeSurface(int chartType) {#isChartTypeSurface-int-}
```
public static boolean isChartTypeSurface(int chartType)
```


Renvoie true si chartType est l'un des sous-types de Surface. Le jeu de sous-types correspond à l’ensemble approprié dans PowerPoint (voir la boîte de dialogue « Change Chart Type » dans PowerPoint) : [ChartType.Surface3D](../../com.aspose.slides/charttype\#Surface3D), [ChartType.WireframeSurface3D](../../com.aspose.slides/charttype\#WireframeSurface3D), [ChartType.Contour](../../com.aspose.slides/charttype\#Contour), [ChartType.WireframeContour](../../com.aspose.slides/charttype\#WireframeContour).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| chartType | int |  |

**Renvoie :**
boolean
### isChartTypeDoughnut(int chartType) {#isChartTypeDoughnut-int-}
```
public static boolean isChartTypeDoughnut(int chartType)
```


Renvoie true si chartType est l'un des sous-types de Doughnut. Le jeu de sous-types correspond à l’ensemble approprié dans PowerPoint (voir la boîte de dialogue « Change Chart Type » dans PowerPoint) : [ChartType.Doughnut](../../com.aspose.slides/charttype\#Doughnut), [ChartType.ExplodedDoughnut](../../com.aspose.slides/charttype\#ExplodedDoughnut).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| chartType | int |  |

**Renvoie :**
boolean
### isChartTypeBubble(int chartType) {#isChartTypeBubble-int-}
```
public static boolean isChartTypeBubble(int chartType)
```


Renvoie true si chartType est l'un des sous-types de Bubble. Le jeu de sous-types correspond à l’ensemble approprié dans PowerPoint (voir la boîte de dialogue « Change Chart Type » dans PowerPoint) : [ChartType.Bubble](../../com.aspose.slides/charttype\#Bubble), [ChartType.BubbleWith3D](../../com.aspose.slides/charttype\#BubbleWith3D).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| chartType | int |  |

**Renvoie :**
boolean
### isChartTypeRadar(int chartType) {#isChartTypeRadar-int-}
```
public static boolean isChartTypeRadar(int chartType)
```


Renvoie true si chartType est l'un des sous-types de Radar. Le jeu de sous-types correspond à l’ensemble approprié dans PowerPoint (voir la boîte de dialogue « Change Chart Type » dans PowerPoint) : [ChartType.FilledRadar](../../com.aspose.slides/charttype\#FilledRadar), [ChartType.Radar](../../com.aspose.slides/charttype\#Radar), [ChartType.RadarWithMarkers](../../com.aspose.slides/charttype\#RadarWithMarkers).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| chartType | int |  |

**Renvoie :**
boolean
### isSeriesUsesXValueCoordinate(int seriesType) {#isSeriesUsesXValueCoordinate-int-}
```
public static boolean isSeriesUsesXValueCoordinate(int seriesType)
```


Renvoie si le type de série spécifié utilise les coordonnées de valeur X.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| seriesType | int | Type de série. |

**Renvoie :**
boolean - True si utilisé, sinon false.
### isSeriesUsesYValueCoordinate(int seriesType) {#isSeriesUsesYValueCoordinate-int-}
```
public static boolean isSeriesUsesYValueCoordinate(int seriesType)
```


Renvoie si le type de série spécifié utilise les coordonnées de valeur Y.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| seriesType | int | Type de série. |

**Renvoie :**
boolean - True si utilisé, sinon false.
### isSeriesUsesValueCoordinate(int seriesType) {#isSeriesUsesValueCoordinate-int-}
```
public static boolean isSeriesUsesValueCoordinate(int seriesType)
```


Renvoie si le type de série spécifié utilise les coordonnées de valeur.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| seriesType | int | Type de série. |

**Renvoie :**
boolean - True si utilisé, sinon false.
### isSeriesUsesBubbleSizeCoordinate(int seriesType) {#isSeriesUsesBubbleSizeCoordinate-int-}
```
public static boolean isSeriesUsesBubbleSizeCoordinate(int seriesType)
```


Renvoie si les coordonnées de taille de bulle peuvent être utilisées pour le type de série spécifié.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| seriesType | int | Type de série. |

**Renvoie :**
boolean - True si utilisable, sinon false.
### hasSeriesTrendLines(int seriesType) {#hasSeriesTrendLines-int-}
```
public static boolean hasSeriesTrendLines(int seriesType)
```


Renvoie s’il existe des lignes de tendance de série pour le type de série spécifié.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| seriesType | int | Type de série. |

**Renvoie :**
boolean - True si présent, sinon false.
### isErrorBarsXAllowed(int seriesType) {#isErrorBarsXAllowed-int-}
```
public static boolean isErrorBarsXAllowed(int seriesType)
```


Renvoie si les barres d’erreur X sont autorisées pour le type de série spécifié.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| seriesType | int | Type de série. |

**Renvoie :**
boolean - True si autorisé, sinon false.
### isErrorBarsYAllowed(int seriesType) {#isErrorBarsYAllowed-int-}
```
public static boolean isErrorBarsYAllowed(int seriesType)
```


Renvoie si les barres d’erreur Y sont autorisées pour le type de série spécifié.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| seriesType | int | Type de série. |

**Renvoie :**
boolean - True si autorisé, sinon false.