---
title: ChartTypeCharacterizer
second_title: Aspose.Slides for Android via Java API Reference
description:  Helper for getting additional information about charts and series by its ChartType.
type: docs
weight: 103
url: /androidjava/com.aspose.slides/charttypecharacterizer/
---
**Inheritance:**
java.lang.Object
```
public class ChartTypeCharacterizer
```

Helper for getting additional information about charts and series by its ChartType.
## Constructors

| Constructor | Description |
| --- | --- |
| [ChartTypeCharacterizer()](#ChartTypeCharacterizer--) |  |
## Methods

| Method | Description |
| --- | --- |
| [isBar3DChart(int chartType)](#isBar3DChart-int-) | Return true if chartType is one of bar3DChart subtypes (3D columns or bars). |
| [is2DChart(int chartType)](#is2DChart-int-) | Return true if chartType is one of 2D chart types. |
| [is3DChart(int chartType)](#is3DChart-int-) | Return true if chartType is one of 3D chart types. |
| [isChartTypeColumn(int chartType)](#isChartTypeColumn-int-) | Return true if chartType is one of Column subtypes. |
| [isChartTypeLine(int chartType)](#isChartTypeLine-int-) | Return true if chartType is one of Line subtypes. |
| [isChartTypePie(int chartType)](#isChartTypePie-int-) | Return true if chartType is one of Pie subtypes. |
| [isChartTypeBar(int chartType)](#isChartTypeBar-int-) | Return true if chartType is one of Bar subtypes. |
| [isChartTypeArea(int chartType)](#isChartTypeArea-int-) | Return true if chartType is one of Area subtypes. |
| [isChartTypeScatter(int chartType)](#isChartTypeScatter-int-) | Return true if chartType is one of Scatter subtypes. |
| [isChartTypeStock(int chartType)](#isChartTypeStock-int-) | Return true if chartType is one of Stock subtypes. |
| [isChartTypeSurface(int chartType)](#isChartTypeSurface-int-) | Return true if chartType is one of Surface subtypes. |
| [isChartTypeDoughnut(int chartType)](#isChartTypeDoughnut-int-) | Return true if chartType is one of Doughnut subtypes. |
| [isChartTypeBubble(int chartType)](#isChartTypeBubble-int-) | Return true if chartType is one of Bubble subtypes. |
| [isChartTypeRadar(int chartType)](#isChartTypeRadar-int-) | Return true if chartType is one of Radar subtypes. |
| [isSeriesUsesXValueCoordinate(int seriesType)](#isSeriesUsesXValueCoordinate-int-) | Returns if specified series type uses X value coordinates. |
| [isSeriesUsesYValueCoordinate(int seriesType)](#isSeriesUsesYValueCoordinate-int-) | Returns if specified series type uses Y value coordinates. |
| [isSeriesUsesValueCoordinate(int seriesType)](#isSeriesUsesValueCoordinate-int-) | Returns if specified series type uses value coordinates. |
| [isSeriesUsesBubbleSizeCoordinate(int seriesType)](#isSeriesUsesBubbleSizeCoordinate-int-) | Returns if bubble size coordinates can be used for specified series type. |
| [hasSeriesTrendLines(int seriesType)](#hasSeriesTrendLines-int-) | Returns if there are series trend lines for specified series type. |
| [isErrorBarsXAllowed(int seriesType)](#isErrorBarsXAllowed-int-) | Returns if error bars X allowed for specified series type. |
| [isErrorBarsYAllowed(int seriesType)](#isErrorBarsYAllowed-int-) | Returns if error bars Y allowed for specified series type. |
### ChartTypeCharacterizer() {#ChartTypeCharacterizer--}
```
public ChartTypeCharacterizer()
```


### isBar3DChart(int chartType) {#isBar3DChart-int-}
```
public static boolean isBar3DChart(int chartType)
```


Return true if chartType is one of bar3DChart subtypes (3D columns or bars).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| chartType | int |  |

**Returns:**
boolean
### is2DChart(int chartType) {#is2DChart-int-}
```
public static boolean is2DChart(int chartType)
```


Return true if chartType is one of 2D chart types.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| chartType | int |  |

**Returns:**
boolean
### is3DChart(int chartType) {#is3DChart-int-}
```
public static boolean is3DChart(int chartType)
```


Return true if chartType is one of 3D chart types.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| chartType | int |  |

**Returns:**
boolean
### isChartTypeColumn(int chartType) {#isChartTypeColumn-int-}
```
public static boolean isChartTypeColumn(int chartType)
```


Return true if chartType is one of Column subtypes. Subtypes set corresponds to the appropriate set in PowerPoint (see "Change Chart Type" dialog in PowerPoint): [ChartType\#ClusteredColumn](../../com.aspose.slides/charttype\#ClusteredColumn), [ChartType\#ClusteredColumn3D](../../com.aspose.slides/charttype\#ClusteredColumn3D), [ChartType\#ClusteredCone](../../com.aspose.slides/charttype\#ClusteredCone), [ChartType\#ClusteredCylinder](../../com.aspose.slides/charttype\#ClusteredCylinder), [ChartType\#ClusteredPyramid](../../com.aspose.slides/charttype\#ClusteredPyramid), [ChartType\#PercentsStackedColumn](../../com.aspose.slides/charttype\#PercentsStackedColumn), [ChartType\#PercentsStackedColumn3D](../../com.aspose.slides/charttype\#PercentsStackedColumn3D), [ChartType\#PercentsStackedCone](../../com.aspose.slides/charttype\#PercentsStackedCone), [ChartType\#PercentsStackedCylinder](../../com.aspose.slides/charttype\#PercentsStackedCylinder), [ChartType\#PercentsStackedPyramid](../../com.aspose.slides/charttype\#PercentsStackedPyramid), [ChartType\#StackedColumn](../../com.aspose.slides/charttype\#StackedColumn), [ChartType\#StackedColumn3D](../../com.aspose.slides/charttype\#StackedColumn3D), [ChartType\#StackedCone](../../com.aspose.slides/charttype\#StackedCone), [ChartType\#StackedCylinder](../../com.aspose.slides/charttype\#StackedCylinder), [ChartType\#StackedPyramid](../../com.aspose.slides/charttype\#StackedPyramid), [ChartType\#Column3D](../../com.aspose.slides/charttype\#Column3D), [ChartType\#Cylinder3D](../../com.aspose.slides/charttype\#Cylinder3D), [ChartType\#Cone3D](../../com.aspose.slides/charttype\#Cone3D), [ChartType\#Pyramid3D](../../com.aspose.slides/charttype\#Pyramid3D).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| chartType | int |  |

**Returns:**
boolean
### isChartTypeLine(int chartType) {#isChartTypeLine-int-}
```
public static boolean isChartTypeLine(int chartType)
```


Return true if chartType is one of Line subtypes. Subtypes set corresponds to the appropriate set in PowerPoint (see "Change Chart Type" dialog in PowerPoint): [ChartType\#Line](../../com.aspose.slides/charttype\#Line), [ChartType\#LineWithMarkers](../../com.aspose.slides/charttype\#LineWithMarkers), [ChartType\#PercentsStackedLine](../../com.aspose.slides/charttype\#PercentsStackedLine), [ChartType\#PercentsStackedLineWithMarkers](../../com.aspose.slides/charttype\#PercentsStackedLineWithMarkers), [ChartType\#StackedLine](../../com.aspose.slides/charttype\#StackedLine), [ChartType\#StackedLineWithMarkers](../../com.aspose.slides/charttype\#StackedLineWithMarkers), [ChartType\#Line3D](../../com.aspose.slides/charttype\#Line3D).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| chartType | int |  |

**Returns:**
boolean
### isChartTypePie(int chartType) {#isChartTypePie-int-}
```
public static boolean isChartTypePie(int chartType)
```


Return true if chartType is one of Pie subtypes. Subtypes set corresponds to the appropriate set in PowerPoint (see "Change Chart Type" dialog in PowerPoint): [ChartType\#BarOfPie](../../com.aspose.slides/charttype\#BarOfPie), [ChartType\#ExplodedPie](../../com.aspose.slides/charttype\#ExplodedPie), [ChartType\#ExplodedPie3D](../../com.aspose.slides/charttype\#ExplodedPie3D), [ChartType\#Pie](../../com.aspose.slides/charttype\#Pie), [ChartType\#Pie3D](../../com.aspose.slides/charttype\#Pie3D), [ChartType\#PieOfPie](../../com.aspose.slides/charttype\#PieOfPie).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| chartType | int |  |

**Returns:**
boolean
### isChartTypeBar(int chartType) {#isChartTypeBar-int-}
```
public static boolean isChartTypeBar(int chartType)
```


Return true if chartType is one of Bar subtypes. Subtypes set corresponds to the appropriate set in PowerPoint (see "Change Chart Type" dialog in PowerPoint): [ChartType\#ClusteredBar](../../com.aspose.slides/charttype\#ClusteredBar), [ChartType\#ClusteredBar3D](../../com.aspose.slides/charttype\#ClusteredBar3D), [ChartType\#PercentsStackedBar](../../com.aspose.slides/charttype\#PercentsStackedBar), [ChartType\#PercentsStackedBar3D](../../com.aspose.slides/charttype\#PercentsStackedBar3D), [ChartType\#StackedBar](../../com.aspose.slides/charttype\#StackedBar), [ChartType\#StackedBar3D](../../com.aspose.slides/charttype\#StackedBar3D), [ChartType\#ClusteredHorizontalCone](../../com.aspose.slides/charttype\#ClusteredHorizontalCone), [ChartType\#ClusteredHorizontalCylinder](../../com.aspose.slides/charttype\#ClusteredHorizontalCylinder), [ChartType\#ClusteredHorizontalPyramid](../../com.aspose.slides/charttype\#ClusteredHorizontalPyramid), [ChartType\#StackedHorizontalCone](../../com.aspose.slides/charttype\#StackedHorizontalCone), [ChartType\#StackedHorizontalCylinder](../../com.aspose.slides/charttype\#StackedHorizontalCylinder), [ChartType\#StackedHorizontalPyramid](../../com.aspose.slides/charttype\#StackedHorizontalPyramid), [ChartType\#PercentsStackedHorizontalCone](../../com.aspose.slides/charttype\#PercentsStackedHorizontalCone), [ChartType\#PercentsStackedHorizontalCylinder](../../com.aspose.slides/charttype\#PercentsStackedHorizontalCylinder), [ChartType\#PercentsStackedHorizontalPyramid](../../com.aspose.slides/charttype\#PercentsStackedHorizontalPyramid).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| chartType | int |  |

**Returns:**
boolean
### isChartTypeArea(int chartType) {#isChartTypeArea-int-}
```
public static boolean isChartTypeArea(int chartType)
```


Return true if chartType is one of Area subtypes. Subtypes set corresponds to the appropriate set in PowerPoint (see "Change Chart Type" dialog in PowerPoint): [ChartType\#Area](../../com.aspose.slides/charttype\#Area), [ChartType\#PercentsStackedArea](../../com.aspose.slides/charttype\#PercentsStackedArea), [ChartType\#PercentsStackedArea3D](../../com.aspose.slides/charttype\#PercentsStackedArea3D), [ChartType\#StackedArea](../../com.aspose.slides/charttype\#StackedArea), [ChartType\#StackedArea3D](../../com.aspose.slides/charttype\#StackedArea3D), [ChartType\#Area3D](../../com.aspose.slides/charttype\#Area3D).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| chartType | int |  |

**Returns:**
boolean
### isChartTypeScatter(int chartType) {#isChartTypeScatter-int-}
```
public static boolean isChartTypeScatter(int chartType)
```


Return true if chartType is one of Scatter subtypes. Subtypes set corresponds to the appropriate set in PowerPoint (see "Change Chart Type" dialog in PowerPoint): [ChartType\#ScatterWithMarkers](../../com.aspose.slides/charttype\#ScatterWithMarkers), [ChartType\#ScatterWithSmoothLines](../../com.aspose.slides/charttype\#ScatterWithSmoothLines), [ChartType\#ScatterWithSmoothLinesAndMarkers](../../com.aspose.slides/charttype\#ScatterWithSmoothLinesAndMarkers), [ChartType\#ScatterWithStraightLines](../../com.aspose.slides/charttype\#ScatterWithStraightLines), [ChartType\#ScatterWithStraightLinesAndMarkers](../../com.aspose.slides/charttype\#ScatterWithStraightLinesAndMarkers).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| chartType | int |  |

**Returns:**
boolean
### isChartTypeStock(int chartType) {#isChartTypeStock-int-}
```
public static boolean isChartTypeStock(int chartType)
```


Return true if chartType is one of Stock subtypes. Subtypes set corresponds to the appropriate set in PowerPoint (see "Change Chart Type" dialog in PowerPoint): [ChartType\#HighLowClose](../../com.aspose.slides/charttype\#HighLowClose), [ChartType\#OpenHighLowClose](../../com.aspose.slides/charttype\#OpenHighLowClose), [ChartType\#VolumeHighLowClose](../../com.aspose.slides/charttype\#VolumeHighLowClose), [ChartType\#VolumeOpenHighLowClose](../../com.aspose.slides/charttype\#VolumeOpenHighLowClose).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| chartType | int |  |

**Returns:**
boolean
### isChartTypeSurface(int chartType) {#isChartTypeSurface-int-}
```
public static boolean isChartTypeSurface(int chartType)
```


Return true if chartType is one of Surface subtypes. Subtypes set corresponds to the appropriate set in PowerPoint (see "Change Chart Type" dialog in PowerPoint): [ChartType\#Surface3D](../../com.aspose.slides/charttype\#Surface3D), [ChartType\#WireframeSurface3D](../../com.aspose.slides/charttype\#WireframeSurface3D), [ChartType\#Contour](../../com.aspose.slides/charttype\#Contour), [ChartType\#WireframeContour](../../com.aspose.slides/charttype\#WireframeContour).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| chartType | int |  |

**Returns:**
boolean
### isChartTypeDoughnut(int chartType) {#isChartTypeDoughnut-int-}
```
public static boolean isChartTypeDoughnut(int chartType)
```


Return true if chartType is one of Doughnut subtypes. Subtypes set corresponds to the appropriate set in PowerPoint (see "Change Chart Type" dialog in PowerPoint): [ChartType\#Doughnut](../../com.aspose.slides/charttype\#Doughnut), [ChartType\#ExplodedDoughnut](../../com.aspose.slides/charttype\#ExplodedDoughnut).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| chartType | int |  |

**Returns:**
boolean
### isChartTypeBubble(int chartType) {#isChartTypeBubble-int-}
```
public static boolean isChartTypeBubble(int chartType)
```


Return true if chartType is one of Bubble subtypes. Subtypes set corresponds to the appropriate set in PowerPoint (see "Change Chart Type" dialog in PowerPoint): [ChartType\#Bubble](../../com.aspose.slides/charttype\#Bubble), [ChartType\#BubbleWith3D](../../com.aspose.slides/charttype\#BubbleWith3D).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| chartType | int |  |

**Returns:**
boolean
### isChartTypeRadar(int chartType) {#isChartTypeRadar-int-}
```
public static boolean isChartTypeRadar(int chartType)
```


Return true if chartType is one of Radar subtypes. Subtypes set corresponds to the appropriate set in PowerPoint (see "Change Chart Type" dialog in PowerPoint): [ChartType\#FilledRadar](../../com.aspose.slides/charttype\#FilledRadar), [ChartType\#Radar](../../com.aspose.slides/charttype\#Radar), [ChartType\#RadarWithMarkers](../../com.aspose.slides/charttype\#RadarWithMarkers).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| chartType | int |  |

**Returns:**
boolean
### isSeriesUsesXValueCoordinate(int seriesType) {#isSeriesUsesXValueCoordinate-int-}
```
public static boolean isSeriesUsesXValueCoordinate(int seriesType)
```


Returns if specified series type uses X value coordinates.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| seriesType | int | Series type. |

**Returns:**
boolean - True if uses otherwise false.
### isSeriesUsesYValueCoordinate(int seriesType) {#isSeriesUsesYValueCoordinate-int-}
```
public static boolean isSeriesUsesYValueCoordinate(int seriesType)
```


Returns if specified series type uses Y value coordinates.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| seriesType | int | Series type. |

**Returns:**
boolean - True if uses otherwise false.
### isSeriesUsesValueCoordinate(int seriesType) {#isSeriesUsesValueCoordinate-int-}
```
public static boolean isSeriesUsesValueCoordinate(int seriesType)
```


Returns if specified series type uses value coordinates.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| seriesType | int | Series type. |

**Returns:**
boolean - True if uses otherwise false.
### isSeriesUsesBubbleSizeCoordinate(int seriesType) {#isSeriesUsesBubbleSizeCoordinate-int-}
```
public static boolean isSeriesUsesBubbleSizeCoordinate(int seriesType)
```


Returns if bubble size coordinates can be used for specified series type.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| seriesType | int | Series type. |

**Returns:**
boolean - True if can be used, otherwise false.
### hasSeriesTrendLines(int seriesType) {#hasSeriesTrendLines-int-}
```
public static boolean hasSeriesTrendLines(int seriesType)
```


Returns if there are series trend lines for specified series type.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| seriesType | int | Series type. |

**Returns:**
boolean - True if present otherwise false.
### isErrorBarsXAllowed(int seriesType) {#isErrorBarsXAllowed-int-}
```
public static boolean isErrorBarsXAllowed(int seriesType)
```


Returns if error bars X allowed for specified series type.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| seriesType | int | Series type. |

**Returns:**
boolean - True if allowed, otherwise false.
### isErrorBarsYAllowed(int seriesType) {#isErrorBarsYAllowed-int-}
```
public static boolean isErrorBarsYAllowed(int seriesType)
```


Returns if error bars Y allowed for specified series type.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| seriesType | int | Series type. |

**Returns:**
boolean - True if allowed, otherwise false.
