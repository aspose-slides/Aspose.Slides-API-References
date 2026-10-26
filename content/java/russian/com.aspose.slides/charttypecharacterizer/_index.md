---
title: ChartTypeCharacterizer
second_title: Справочник API Aspose.Slides для Java
description: Помощник для получения дополнительной информации о диаграммах и рядах по их ChartType.
type: docs
url: /ru/com.aspose.slides/charttypecharacterizer/
---
**Inheritance:**
java.lang.Object
```
public class ChartTypeCharacterizer
```

Вспомогательный класс для получения дополнительной информации о диаграммах и сериях по их ChartType.
## Constructors

| Constructor | Description |
| --- | --- |
| [ChartTypeCharacterizer()](#ChartTypeCharacterizer--) |  |
## Methods

| Method | Description |
| --- | --- |
| [isBar3DChart(int chartType)](#isBar3DChart-int-) | Возвращает true, если chartType является одним из подтипов bar3DChart (3D columns или bars). |
| [is2DChart(int chartType)](#is2DChart-int-) | Возвращает true, если chartType является одним из 2D chart types. |
| [is3DChart(int chartType)](#is3DChart-int-) | Возвращает true, если chartType является одним из 3D chart types. |
| [isChartTypeColumn(int chartType)](#isChartTypeColumn-int-) | Возвращает true, если chartType является одним из подтипов Column. |
| [isChartTypeLine(int chartType)](#isChartTypeLine-int-) | Возвращает true, если chartType является одним из подтипов Line. |
| [isChartTypePie(int chartType)](#isChartTypePie-int-) | Возвращает true, если chartType является одним из подтипов Pie. |
| [isChartTypeBar(int chartType)](#isChartTypeBar-int-) | Возвращает true, если chartType является одним из подтипов Bar. |
| [isChartTypeArea(int chartType)](#isChartTypeArea-int-) | Возвращает true, если chartType является одним из подтипов Area. |
| [isChartTypeScatter(int chartType)](#isChartTypeScatter-int-) | Возвращает true, если chartType является одним из подтипов Scatter. |
| [isChartTypeStock(int chartType)](#isChartTypeStock-int-) | Возвращает true, если chartType является одним из подтипов Stock. |
| [isChartTypeSurface(int chartType)](#isChartTypeSurface-int-) | Возвращает true, если chartType является одним из подтипов Surface. |
| [isChartTypeDoughnut(int chartType)](#isChartTypeDoughnut-int-) | Возвращает true, если chartType является одним из подтипов Doughnut. |
| [isChartTypeBubble(int chartType)](#isChartTypeBubble-int-) | Возвращает true, если chartType является одним из подтипов Bubble. |
| [isChartTypeRadar(int chartType)](#isChartTypeRadar-int-) | Возвращает true, если chartType является одним из подтипов Radar. |
| [isSeriesUsesXValueCoordinate(int seriesType)](#isSeriesUsesXValueCoordinate-int-) | Возвращает, если указанный series type использует координаты значения X. |
| [isSeriesUsesYValueCoordinate(int seriesType)](#isSeriesUsesYValueCoordinate-int-) | Возвращает, если указанный series type использует координаты значения Y. |
| [isSeriesUsesValueCoordinate(int seriesType)](#isSeriesUsesValueCoordinate-int-) | Возвращает, если указанный series type использует координаты значения. |
| [isSeriesUsesBubbleSizeCoordinate(int seriesType)](#isSeriesUsesBubbleSizeCoordinate-int-) | Возвращает, если координаты размера пузыря могут быть использованы для указанного series type. |
| [hasSeriesTrendLines(int seriesType)](#hasSeriesTrendLines-int-) | Возвращает, если для указанного series type существуют линии тренда серии. |
| [isErrorBarsXAllowed(int seriesType)](#isErrorBarsXAllowed-int-) | Возвращает, если для указанного series type разрешены погрешности X. |
| [isErrorBarsYAllowed(int seriesType)](#isErrorBarsYAllowed-int-) | Возвращает, если для указанного series type разрешены погрешности Y. |
### ChartTypeCharacterizer() {#ChartTypeCharacterizer--}
```
public ChartTypeCharacterizer()
```


### isBar3DChart(int chartType) {#isBar3DChart-int-}
```
public static boolean isBar3DChart(int chartType)
```


Возвращает true, если chartType является одним из подтипов bar3DChart (3D columns или bars).

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


Возвращает true, если chartType является одним из 2D chart types.

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


Возвращает true, если chartType является одним из 3D chart types.

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


Возвращает true, если chartType является одним из подтипов Column. Набор подтипов соответствует набору в PowerPoint (см. диалог «Change Chart Type» в PowerPoint): [ChartType.ClusteredColumn](../../com.aspose.slides/charttype\#ClusteredColumn), [ChartType.ClusteredColumn3D](../../com.aspose.slides/charttype\#ClusteredColumn3D), [ChartType.ClusteredCone](../../com.aspose.slides/charttype\#ClusteredCone), [ChartType.ClusteredCylinder](../../com.aspose.slides/charttype\#ClusteredCylinder), [ChartType.ClusteredPyramid](../../com.aspose.slides/charttype\#ClusteredPyramid), [ChartType.PercentsStackedColumn](../../com.aspose.slides/charttype\#PercentsStackedColumn), [ChartType.PercentsStackedColumn3D](../../com.aspose.slides/charttype\#PercentsStackedColumn3D), [ChartType.PercentsStackedCone](../../com.aspose.slides/charttype\#PercentsStackedCone), [ChartType.PercentsStackedCylinder](../../com.aspose.slides/charttype\#PercentsStackedCylinder), [ChartType.PercentsStackedPyramid](../../com.aspose.slides/charttype\#PercentsStackedPyramid), [ChartType.StackedColumn](../../com.aspose.slides/charttype\#StackedColumn), [ChartType.StackedColumn3D](../../com.aspose.slides/charttype\#StackedColumn3D), [ChartType.StackedCone](../../com.aspose.slides/charttype\#StackedCone), [ChartType.StackedCylinder](../../com.aspose.slides/charttype\#StackedCylinder), [ChartType.StackedPyramid](../../com.aspose.slides/charttype\#StackedPyramid), [ChartType.Column3D](../../com.aspose.slides/charttype\#Column3D), [ChartType.Cylinder3D](../../com.aspose.slides/charttype\#Cylinder3D), [ChartType.Cone3D](../../com.aspose.slides/charttype\#Cone3D), [ChartType.Pyramid3D](../../com.aspose.slides/charttype\#Pyramid3D).

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


Возвращает true, если chartType является одним из подтипов Line. Набор подтипов соответствует набору в PowerPoint (см. диалог «Change Chart Type» в PowerPoint): [ChartType.Line](../../com.aspose.slides/charttype\#Line), [ChartType.LineWithMarkers](../../com.aspose.slides/charttype\#LineWithMarkers), [ChartType.PercentsStackedLine](../../com.aspose.slides/charttype\#PercentsStackedLine), [ChartType.PercentsStackedLineWithMarkers](../../com.aspose.slides/charttype\#PercentsStackedLineWithMarkers), [ChartType.StackedLine](../../com.aspose.slides/charttype\#StackedLine), [ChartType.StackedLineWithMarkers](../../com.aspose.slides/charttype\#StackedLineWithMarkers), [ChartType.Line3D](../../com.aspose.slides/charttype\#Line3D).

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


Возвращает true, если chartType является одним из подтипов Pie. Набор подтипов соответствует набору в PowerPoint (см. диалог «Change Chart Type» в PowerPoint): [ChartType.BarOfPie](../../com.aspose.slides/charttype\#BarOfPie), [ChartType.ExplodedPie](../../com.aspose.slides/charttype\#ExplodedPie), [ChartType.ExplodedPie3D](../../com.aspose.slides/charttype\#ExplodedPie3D), [ChartType.Pie](../../com.aspose.slides/charttype\#Pie), [ChartType.Pie3D](../../com.aspose.slides/charttype\#Pie3D), [ChartType.PieOfPie](../../com.aspose.slides/charttype\#PieOfPie).

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


Возвращает true, если chartType является одним из подтипов Bar. Набор подтипов соответствует набору в PowerPoint (см. диалог «Change Chart Type» в PowerPoint): [ChartType.ClusteredBar](../../com.aspose.slides/charttype\#ClusteredBar), [ChartType.ClusteredBar3D](../../com.aspose.slides/charttype\#ClusteredBar3D), [ChartType.PercentsStackedBar](../../com.aspose.slides/charttype\#PercentsStackedBar), [ChartType.PercentsStackedBar3D](../../com.aspose.slides/charttype\#PercentsStackedBar3D), [ChartType.StackedBar](../../com.aspose.slides/charttype\#StackedBar), [ChartType.StackedBar3D](../../com.aspose.slides/charttype\#StackedBar3D), [ChartType.ClusteredHorizontalCone](../../com.aspose.slides/charttype\#ClusteredHorizontalCone), [ChartType.ClusteredHorizontalCylinder](../../com.aspose.slides/charttype\#ClusteredHorizontalCylinder), [ChartType.ClusteredHorizontalPyramid](../../com.aspose.slides/charttype\#ClusteredHorizontalPyramid), [ChartType.StackedHorizontalCone](../../com.aspose.slides/charttype\#StackedHorizontalCone), [ChartType.StackedHorizontalCylinder](../../com.aspose.slides/charttype\#StackedHorizontalCylinder), [ChartType.StackedHorizontalPyramid](../../com.aspose.slides/charttype\#StackedHorizontalPyramid), [ChartType.PercentsStackedHorizontalCone](../../com.aspose.slides/charttype\#PercentsStackedHorizontalCone), [ChartType.PercentsStackedHorizontalCylinder](../../com.aspose.slides/charttype\#PercentsStackedHorizontalCylinder), [ChartType.PercentsStackedHorizontalPyramid](../../com.aspose.slides/charttype\#PercentsStackedHorizontalPyramid).

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


Возвращает true, если chartType является одним из подтипов Area. Набор подтипов соответствует набору в PowerPoint (см. диалог «Change Chart Type» в PowerPoint): [ChartType.Area](../../com.aspose.slides/charttype\#Area), [ChartType.PercentsStackedArea](../../com.aspose.slides/charttype\#PercentsStackedArea), [ChartType.PercentsStackedArea3D](../../com.aspose.slides/charttype\#PercentsStackedArea3D), [ChartType.StackedArea](../../com.aspose.slides/charttype\#StackedArea), [ChartType.StackedArea3D](../../com.aspose.slides/charttype\#StackedArea3D), [ChartType.Area3D](../../com.aspose.slides/charttype\#Area3D).

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


Возвращает true, если chartType является одним из подтипов Scatter. Набор подтипов соответствует набору в PowerPoint (см. диалог «Change Chart Type» в PowerPoint): [ChartType.ScatterWithMarkers](../../com.aspose.slides/charttype\#ScatterWithMarkers), [ChartType.ScatterWithSmoothLines](../../com.aspose.slides/charttype\#ScatterWithSmoothLines), [ChartType.ScatterWithSmoothLinesAndMarkers](../../com.aspose.slides/charttype\#ScatterWithSmoothLinesAndMarkers), [ChartType.ScatterWithStraightLines](../../com.aspose.slides/charttype\#ScatterWithStraightLines), [ChartType.ScatterWithStraightLinesAndMarkers](../../com.aspose.slides/charttype\#ScatterWithStraightLinesAndMarkers).

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


Возвращает true, если chartType является одним из подтипов Stock. Набор подтипов соответствует набору в PowerPoint (см. диалог «Change Chart Type» в PowerPoint): [ChartType.HighLowClose](../../com.aspose.slides/charttype\#HighLowClose), [ChartType.OpenHighLowClose](../../com.aspose.slides/charttype\#OpenHighLowClose), [ChartType.VolumeHighLowClose](../../com.aspose.slides/charttype\#VolumeHighLowClose), [ChartType.VolumeOpenHighLowClose](../../com.aspose.slides/charttype\#VolumeOpenHighLowClose).

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


Возвращает true, если chartType является одним из подтипов Surface. Набор подтипов соответствует набору в PowerPoint (см. диалог «Change Chart Type» в PowerPoint): [ChartType.Surface3D](../../com.aspose.slides/charttype\#Surface3D), [ChartType.WireframeSurface3D](../../com.aspose.slides/charttype\#WireframeSurface3D), [ChartType.Contour](../../com.aspose.slides/charttype\#Contour), [ChartType.WireframeContour](../../com.aspose.slides/charttype\#WireframeContour).

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


Возвращает true, если chartType является одним из подтипов Doughnut. Набор подтипов соответствует набору в PowerPoint (см. диалог «Change Chart Type» в PowerPoint): [ChartType.Doughnut](../../com.aspose.slides/charttype\#Doughnut), [ChartType.ExplodedDoughnut](../../com.aspose.slides/charttype\#ExplodedDoughnut).

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


Возвращает true, если chartType является одним из подтипов Bubble. Набор подтипов соответствует набору в PowerPoint (см. диалог «Change Chart Type» в PowerPoint): [ChartType.Bubble](../../com.aspose.slides/charttype\#Bubble), [ChartType.BubbleWith3D](../../com.aspose.slides/charttype\#BubbleWith3D).

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


Возвращает true, если chartType является одним из подтипов Radar. Набор подтипов соответствует набору в PowerPoint (см. диалог «Change Chart Type» в PowerPoint): [ChartType.FilledRadar](../../com.aspose.slides/charttype\#FilledRadar), [ChartType.Radar](../../com.aspose.slides/charttype\#Radar), [ChartType.RadarWithMarkers](../../com.aspose.slides/charttype\#RadarWithMarkers).

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


Возвращает, если series type использует координаты значения X.

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


Возвращает, если series type использует координаты значения Y.

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


Возвращает, если series type использует координаты значения.

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


Возвращает, если координаты размера пузыря могут быть использованы для series type.

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


Возвращает, если для series type существуют линии тренда серии.

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


Возвращает, если для series type разрешены погрешности X.

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


Возвращает, если для series type разрешены погрешности Y.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| seriesType | int | Series type. |

**Returns:**
boolean - True if allowed, otherwise false.