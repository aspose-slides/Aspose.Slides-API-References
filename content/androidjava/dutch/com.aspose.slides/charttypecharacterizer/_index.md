---
title: ChartTypeCharacterizer
second_title: Aspose.Slides voor Android via Java API-referentie
description: Helper voor het verkrijgen van aanvullende informatie over diagrammen en series op basis van hun ChartType.
type: docs
url: /nl/com.aspose.slides/charttypecharacterizer/
---
**Inheritance:**
java.lang.Object
```
public class ChartTypeCharacterizer
```

Helper voor het verkrijgen van aanvullende informatie over grafieken en series op basis van hun ChartType.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [ChartTypeCharacterizer()](#ChartTypeCharacterizer--) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [isBar3DChart(int chartType)](#isBar3DChart-int-) | Retourneert true als chartType een van de bar3DChart-subtypen is (3D kolommen of balken). |
| [is2DChart(int chartType)](#is2DChart-int-) | Retourneert true als chartType een van de 2D-grafiektype-subtypen is. |
| [is3DChart(int chartType)](#is3DChart-int-) | Retourneert true als chartType een van de 3D-grafiektype-subtypen is. |
| [isChartTypeColumn(int chartType)](#isChartTypeColumn-int-) | Retourneert true als chartType een van de Column-subtypen is. |
| [isChartTypeLine(int chartType)](#isChartTypeLine-int-) | Retourneert true als chartType een van de Line-subtypen is. |
| [isChartTypePie(int chartType)](#isChartTypePie-int-) | Retourneert true als chartType een van de Pie-subtypen is. |
| [isChartTypeBar(int chartType)](#isChartTypeBar-int-) | Retourneert true als chartType een van de Bar-subtypen is. |
| [isChartTypeArea(int chartType)](#isChartTypeArea-int-) | Retourneert true als chartType een van de Area-subtypen is. |
| [isChartTypeScatter(int chartType)](#isChartTypeScatter-int-) | Retourneert true als chartType een van de Scatter-subtypen is. |
| [isChartTypeStock(int chartType)](#isChartTypeStock-int-) | Retourneert true als chartType een van de Stock-subtypen is. |
| [isChartTypeSurface(int chartType)](#isChartTypeSurface-int-) | Retourneert true als chartType een van de Surface-subtypen is. |
| [isChartTypeDoughnut(int chartType)](#isChartTypeDoughnut-int-) | Retourneert true als chartType een van de Doughnut-subtypen is. |
| [isChartTypeBubble(int chartType)](#isChartTypeBubble-int-) | Retourneert true als chartType een van de Bubble-subtypen is. |
| [isChartTypeRadar(int chartType)](#isChartTypeRadar-int-) | Retourneert true als chartType een van de Radar-subtypen is. |
| [isSeriesUsesXValueCoordinate(int seriesType)](#isSeriesUsesXValueCoordinate-int-) | Retourneert of het opgegeven serietype X-waarde-coördinaten gebruikt. |
| [isSeriesUsesYValueCoordinate(int seriesType)](#isSeriesUsesYValueCoordinate-int-) | Retourneert of het opgegeven serietype Y-waarde-coördinaten gebruikt. |
| [isSeriesUsesValueCoordinate(int seriesType)](#isSeriesUsesValueCoordinate-int-) | Retourneert of het opgegeven serietype waardecoördinaten gebruikt. |
| [isSeriesUsesBubbleSizeCoordinate(int seriesType)](#isSeriesUsesBubbleSizeCoordinate-int-) | Retourneert of bubbel-grootte-coördinaten kunnen worden gebruikt voor het opgegeven serietype. |
| [hasSeriesTrendLines(int seriesType)](#hasSeriesTrendLines-int-) | Retourneert of er trendlijnen voor series zijn voor het opgegeven serietype. |
| [isErrorBarsXAllowed(int seriesType)](#isErrorBarsXAllowed-int-) | Retourneert of foutbalken X zijn toegestaan voor het opgegeven serietype. |
| [isErrorBarsYAllowed(int seriesType)](#isErrorBarsYAllowed-int-) | Retourneert of foutbalken Y zijn toegestaan voor het opgegeven serietype. |
### ChartTypeCharacterizer() {#ChartTypeCharacterizer--}
```
public ChartTypeCharacterizer()
```


### isBar3DChart(int chartType) {#isBar3DChart-int-}
```
public static boolean isBar3DChart(int chartType)
```


Retourneert true als chartType een van de bar3DChart-subtypen is (3D kolommen of balken).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| chartType | int |  |

**Retour:**
boolean
### is2DChart(int chartType) {#is2DChart-int-}
```
public static boolean is2DChart(int chartType)
```


Retourneert true als chartType een van de 2D-grafiektype-subtypen is.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| chartType | int |  |

**Retour:**
boolean
### is3DChart(int chartType) {#is3DChart-int-}
```
public static boolean is3DChart(int chartType)
```


Retourneert true als chartType een van de 3D-grafiektype-subtypen is.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| chartType | int |  |

**Retour:**
boolean
### isChartTypeColumn(int chartType) {#isChartTypeColumn-int-}
```
public static boolean isChartTypeColumn(int chartType)
```


Retourneert true als chartType een van de Column-subtypen is. De set subtypen komt overeen met de overeenkomstige set in PowerPoint (zie dialoog “Change Chart Type” in PowerPoint): [ChartType.ClusteredColumn](../../com.aspose.slides/charttype\#ClusteredColumn), [ChartType.ClusteredColumn3D](../../com.aspose.slides/charttype\#ClusteredColumn3D), [ChartType.ClusteredCone](../../com.aspose.slides/charttype\#ClusteredCone), [ChartType.ClusteredCylinder](../../com.aspose.slides/charttype\#ClusteredCylinder), [ChartType.ClusteredPyramid](../../com.aspose.slides/charttype\#ClusteredPyramid), [ChartType.PercentsStackedColumn](../../com.aspose.slides/charttype\#PercentsStackedColumn), [ChartType.PercentsStackedColumn3D](../../com.aspose.slides/charttype\#PercentsStackedColumn3D), [ChartType.PercentsStackedCone](../../com.aspose.slides/charttype\#PercentsStackedCone), [ChartType.PercentsStackedCylinder](../../com.aspose.slides/charttype\#PercentsStackedCylinder), [ChartType.PercentsStackedPyramid](../../com.aspose.slides/charttype\#PercentsStackedPyramid), [ChartType.StackedColumn](../../com.aspose.slides/charttype\#StackedColumn), [ChartType.StackedColumn3D](../../com.aspose.slides/charttype\#StackedColumn3D), [ChartType.StackedCone](../../com.aspose.slides/charttype\#StackedCone), [ChartType.StackedCylinder](../../com.aspose.slides/charttype\#StackedCylinder), [ChartType.StackedPyramid](../../com.aspose.slides/charttype\#StackedPyramid), [ChartType.Column3D](../../com.aspose.slides/charttype\#Column3D), [ChartType.Cylinder3D](../../com.aspose.slides/charttype\#Cylinder3D), [ChartType.Cone3D](../../com.aspose.slides/charttype\#Cone3D), [ChartType.Pyramid3D](../../com.aspose.slides/charttype\#Pyramid3D).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| chartType | int |  |

**Retour:**
boolean
### isChartTypeLine(int chartType) {#isChartTypeLine-int-}
```
public static boolean isChartTypeLine(int chartType)
```


Retourneert true als chartType een van de Line-subtypen is. De set subtypen komt overeen met de overeenkomstige set in PowerPoint (zie dialoog “Change Chart Type” in PowerPoint): [ChartType.Line](../../com.aspose.slides/charttype\#Line), [ChartType.LineWithMarkers](../../com.aspose.slides/charttype\#LineWithMarkers), [ChartType.PercentsStackedLine](../../com.aspose.slides/charttype\#PercentsStackedLine), [ChartType.PercentsStackedLineWithMarkers](../../com.aspose.slides/charttype\#PercentsStackedLineWithMarkers), [ChartType.StackedLine](../../com.aspose.slides/charttype\#StackedLine), [ChartType.StackedLineWithMarkers](../../com.aspose.slides/charttype\#StackedLineWithMarkers), [ChartType.Line3D](../../com.aspose.slides/charttype\#Line3D).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| chartType | int |  |

**Retour:**
boolean
### isChartTypePie(int chartType) {#isChartTypePie-int-}
```
public static boolean isChartTypePie(int chartType)
```


Retourneert true als chartType een van de Pie-subtypen is. De set subtypen komt overeen met de overeenkomstige set in PowerPoint (zie dialoog “Change Chart Type” in PowerPoint): [ChartType.BarOfPie](../../com.aspose.slides/charttype\#BarOfPie), [ChartType.ExplodedPie](../../com.aspose.slides/charttype\#ExplodedPie), [ChartType.ExplodedPie3D](../../com.aspose.slides/charttype\#ExplodedPie3D), [ChartType.Pie](../../com.aspose.slides/charttype\#Pie), [ChartType.Pie3D](../../com.aspose.slides/charttype\#Pie3D), [ChartType.PieOfPie](../../com.aspose.slides/charttype\#PieOfPie).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| chartType | int |  |

**Retour:**
boolean
### isChartTypeBar(int chartType) {#isChartTypeBar-int-}
```
public static boolean isChartTypeBar(int chartType)
```


Retourneert true als chartType een van de Bar-subtypen is. De set subtypen komt overeen met de overeenkomstige set in PowerPoint (zie dialoog “Change Chart Type” in PowerPoint): [ChartType.ClusteredBar](../../com.aspose.slides/charttype\#ClusteredBar), [ChartType.ClusteredBar3D](../../com.aspose.slides/charttype\#ClusteredBar3D), [ChartType.PercentsStackedBar](../../com.aspose.slides/charttype\#PercentsStackedBar), [ChartType.PercentsStackedBar3D](../../com.aspose.slides/charttype\#PercentsStackedBar3D), [ChartType.StackedBar](../../com.aspose.slides/charttype\#StackedBar), [ChartType.StackedBar3D](../../com.aspose.slides/charttype\#StackedBar3D), [ChartType.ClusteredHorizontalCone](../../com.aspose.slides/charttype\#ClusteredHorizontalCone), [ChartType.ClusteredHorizontalCylinder](../../com.aspose.slides/charttype\#ClusteredHorizontalCylinder), [ChartType.ClusteredHorizontalPyramid](../../com.aspose.slides/charttype\#ClusteredHorizontalPyramid), [ChartType.StackedHorizontalCone](../../com.aspose.slides/charttype\#StackedHorizontalCone), [ChartType.StackedHorizontalCylinder](../../com.aspose.slides/charttype\#StackedHorizontalCylinder), [ChartType.StackedHorizontalPyramid](../../com.aspose.slides/charttype\#StackedHorizontalPyramid), [ChartType.PercentsStackedHorizontalCone](../../com.aspose.slides/charttype\#PercentsStackedHorizontalCone), [ChartType.PercentsStackedHorizontalCylinder](../../com.aspose.slides/charttype\#PercentsStackedHorizontalCylinder), [ChartType.PercentsStackedHorizontalPyramid](../../com.aspose.slides/charttype\#PercentsStackedHorizontalPyramid).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| chartType | int |  |

**Retour:**
boolean
### isChartTypeArea(int chartType) {#isChartTypeArea-int-}
```
public static boolean isChartTypeArea(int chartType)
```


Retourneert true als chartType een van de Area-subtypen is. De set subtypen komt overeen met de overeenkomstige set in PowerPoint (zie dialoog “Change Chart Type” in PowerPoint): [ChartType.Area](../../com.aspose.slides/charttype\#Area), [ChartType.PercentsStackedArea](../../com.aspose.slides/charttype\#PercentsStackedArea), [ChartType.PercentsStackedArea3D](../../com.aspose.slides/charttype\#PercentsStackedArea3D), [ChartType.StackedArea](../../com.aspose.slides/charttype\#StackedArea), [ChartType.StackedArea3D](../../com.aspose.slides/charttype\#StackedArea3D), [ChartType.Area3D](../../com.aspose.slides/charttype\#Area3D).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| chartType | int |  |

**Retour:**
boolean
### isChartTypeScatter(int chartType) {#isChartTypeScatter-int-}
```
public static boolean isChartTypeScatter(int chartType)
```


Retourneert true als chartType een van de Scatter-subtypen is. De set subtypen komt overeen met de overeenkomstige set in PowerPoint (zie dialoog “Change Chart Type” in PowerPoint): [ChartType.ScatterWithMarkers](../../com.aspose.slides/charttype\#ScatterWithMarkers), [ChartType.ScatterWithSmoothLines](../../com.aspose.slides/charttype\#ScatterWithSmoothLines), [ChartType.ScatterWithSmoothLinesAndMarkers](../../com.aspose.slides/charttype\#ScatterWithSmoothLinesAndMarkers), [ChartType.ScatterWithStraightLines](../../com.aspose.slides/charttype\#ScatterWithStraightLines), [ChartType.ScatterWithStraightLinesAndMarkers](../../com.aspose.slides/charttype\#ScatterWithStraightLinesAndMarkers).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| chartType | int |  |

**Retour:**
boolean
### isChartTypeStock(int chartType) {#isChartTypeStock-int-}
```
public static boolean isChartTypeStock(int chartType)
```


Retourneert true als chartType een van de Stock-subtypen is. De set subtypen komt overeen met de overeenkomstige set in PowerPoint (zie dialoog “Change Chart Type” in PowerPoint): [ChartType.HighLowClose](../../com.aspose.slides/charttype\#HighLowClose), [ChartType.OpenHighLowClose](../../com.aspose.slides/charttype\#OpenHighLowClose), [ChartType.VolumeHighLowClose](../../com.aspose.slides/charttype\#VolumeHighLowClose), [ChartType.VolumeOpenHighLowClose](../../com.aspose.slides/charttype\#VolumeOpenHighLowClose).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| chartType | int |  |

**Retour:**
boolean
### isChartTypeSurface(int chartType) {#isChartTypeSurface-int-}
```
public static boolean isChartTypeSurface(int chartType)
```


Retourneert true als chartType een van de Surface-subtypen is. De set subtypen komt overeen met de overeenkomstige set in PowerPoint (zie dialoog “Change Chart Type” in PowerPoint): [ChartType.Surface3D](../../com.aspose.slides/charttype\#Surface3D), [ChartType.WireframeSurface3D](../../com.aspose.slides/charttype\#WireframeSurface3D), [ChartType.Contour](../../com.aspose.slides/charttype\#Contour), [ChartType.WireframeContour](../../com.aspose.slides/charttype\#WireframeContour).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| chartType | int |  |

**Retour:**
boolean
### isChartTypeDoughnut(int chartType) {#isChartTypeDoughnut-int-}
```
public static boolean isChartTypeDoughnut(int chartType)
```


Retourneert true als chartType een van de Doughnut-subtypen is. De set subtypen komt overeen met de overeenkomstige set in PowerPoint (zie dialoog “Change Chart Type” in PowerPoint): [ChartType.Doughnut](../../com.aspose.slides/charttype\#Doughnut), [ChartType.ExplodedDoughnut](../../com.aspose.slides/charttype\#ExplodedDoughnut).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| chartType | int |  |

**Retour:**
boolean
### isChartTypeBubble(int chartType) {#isChartTypeBubble-int-}
```
public static boolean isChartTypeBubble(int chartType)
```


Retourneert true als chartType een van de Bubble-subtypen is. De set subtypen komt overeen met de overeenkomstige set in PowerPoint (zie dialoog “Change Chart Type” in PowerPoint): [ChartType.Bubble](../../com.aspose.slides/charttype\#Bubble), [ChartType.BubbleWith3D](../../com.aspose.slides/charttype\#BubbleWith3D).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| chartType | int |  |

**Retour:**
boolean
### isChartTypeRadar(int chartType) {#isChartTypeRadar-int-}
```
public static boolean isChartTypeRadar(int chartType)
```


Retourneert true als chartType een van de Radar-subtypen is. De set subtypen komt overeen met de overeenkomstige set in PowerPoint (zie dialoog “Change Chart Type” in PowerPoint): [ChartType.FilledRadar](../../com.aspose.slides/charttype\#FilledRadar), [ChartType.Radar](../../com.aspose.slides/charttype\#Radar), [ChartType.RadarWithMarkers](../../com.aspose.slides/charttype\#RadarWithMarkers).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| chartType | int |  |

**Retour:**
boolean
### isSeriesUsesXValueCoordinate(int seriesType) {#isSeriesUsesXValueCoordinate-int-}
```
public static boolean isSeriesUsesXValueCoordinate(int seriesType)
```


Retourneert of het opgegeven serietype X-waarde-coördinaten gebruikt.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| seriesType | int | Serietype. |

**Retour:**
boolean - True if uses otherwise false.
### isSeriesUsesYValueCoordinate(int seriesType) {#isSeriesUsesYValueCoordinate-int-}
```
public static boolean isSeriesUsesYValueCoordinate(int seriesType)
```


Retourneert of het opgegeven serietype Y-waarde-coördinaten gebruikt.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| seriesType | int | Serietype. |

**Retour:**
boolean - True if uses otherwise false.
### isSeriesUsesValueCoordinate(int seriesType) {#isSeriesUsesValueCoordinate-int-}
```
public static boolean isSeriesUsesValueCoordinate(int seriesType)
```


Retourneert of het opgegeven serietype waardecoördinaten gebruikt.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| seriesType | int | Serietype. |

**Retour:**
boolean - True if uses otherwise false.
### isSeriesUsesBubbleSizeCoordinate(int seriesType) {#isSeriesUsesBubbleSizeCoordinate-int-}
```
public static boolean isSeriesUsesBubbleSizeCoordinate(int seriesType)
```


Retourneert of bubbel-grootte-coördinaten kunnen worden gebruikt voor het opgegeven serietype.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| seriesType | int | Serietype. |

**Retour:**
boolean - True if can be used, otherwise false.
### hasSeriesTrendLines(int seriesType) {#hasSeriesTrendLines-int-}
```
public static boolean hasSeriesTrendLines(int seriesType)
```


Retourneert of er trendlijnen voor series zijn voor het opgegeven serietype.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| seriesType | int | Serietype. |

**Retour:**
boolean - True if present otherwise false.
### isErrorBarsXAllowed(int seriesType) {#isErrorBarsXAllowed-int-}
```
public static boolean isErrorBarsXAllowed(int seriesType)
```


Retourneert of foutbalken X zijn toegestaan voor het opgegeven serietype.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| seriesType | int | Serietype. |

**Retour:**
boolean - True if allowed, otherwise false.
### isErrorBarsYAllowed(int seriesType) {#isErrorBarsYAllowed-int-}
```
public static boolean isErrorBarsYAllowed(int seriesType)
```


Retourneert of foutbalken Y zijn toegestaan voor het opgegeven serietype.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| seriesType | int | Serietype. |

**Retour:**
boolean - True if allowed, otherwise false.