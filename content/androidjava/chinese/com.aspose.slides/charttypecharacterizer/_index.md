---
title: ChartTypeCharacterizer
second_title: Aspose.Slides for Android via Java API 参考
description: 用于根据其 ChartType 获取图表和系列的附加信息的帮助类。
type: docs
url: /zh/com.aspose.slides/charttypecharacterizer/
---
**继承:**
java.lang.Object
```
public class ChartTypeCharacterizer
```

获取有关图表及其系列的附加信息的帮助类，依据其 ChartType。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [ChartTypeCharacterizer()](#ChartTypeCharacterizer--) |  |

## 方法

| 方法 | 描述 |
| --- | --- |
| [isBar3DChart(int chartType)](#isBar3DChart-int-) | 如果 chartType 是 bar3DChart 子类型（3D 列或条形）则返回 true。 |
| [is2DChart(int chartType)](#is2DChart-int-) | 如果 chartType 是 2D 图表类型之一则返回 true。 |
| [is3DChart(int chartType)](#is3DChart-int-) | 如果 chartType 是 3D 图表类型之一则返回 true。 |
| [isChartTypeColumn(int chartType)](#isChartTypeColumn-int-) | 如果 chartType 是 Column 子类型则返回 true。 |
| [isChartTypeLine(int chartType)](#isChartTypeLine-int-) | 如果 chartType 是 Line 子类型则返回 true。 |
| [isChartTypePie(int chartType)](#isChartTypePie-int-) | 如果 chartType 是 Pie 子类型则返回 true。 |
| [isChartTypeBar(int chartType)](#isChartTypeBar-int-) | 如果 chartType 是 Bar 子类型则返回 true。 |
| [isChartTypeArea(int chartType)](#isChartTypeArea-int-) | 如果 chartType 是 Area 子类型则返回 true。 |
| [isChartTypeScatter(int chartType)](#isChartTypeScatter-int-) | 如果 chartType 是 Scatter 子类型则返回 true。 |
| [isChartTypeStock(int chartType)](#isChartTypeStock-int-) | 如果 chartType 是 Stock 子类型则返回 true。 |
| [isChartTypeSurface(int chartType)](#isChartTypeSurface-int-) | 如果 chartType 是 Surface 子类型则返回 true。 |
| [isChartTypeDoughnut(int chartType)](#isChartTypeDoughnut-int-) | 如果 chartType 是 Doughnut 子类型则返回 true。 |
| [isChartTypeBubble(int chartType)](#isChartTypeBubble-int-) | 如果 chartType 是 Bubble 子类型则返回 true。 |
| [isChartTypeRadar(int chartType)](#isChartTypeRadar-int-) | 如果 chartType 是 Radar 子类型则返回 true。 |
| [isSeriesUsesXValueCoordinate(int seriesType)](#isSeriesUsesXValueCoordinate-int-) | 返回指定系列类型是否使用 X 值坐标。 |
| [isSeriesUsesYValueCoordinate(int seriesType)](#isSeriesUsesYValueCoordinate-int-) | 返回指定系列类型是否使用 Y 值坐标。 |
| [isSeriesUsesValueCoordinate(int seriesType)](#isSeriesUsesValueCoordinate-int-) | 返回指定系列类型是否使用值坐标。 |
| [isSeriesUsesBubbleSizeCoordinate(int seriesType)](#isSeriesUsesBubbleSizeCoordinate-int-) | 返回是否可以对指定系列类型使用气泡大小坐标。 |
| [hasSeriesTrendLines(int seriesType)](#hasSeriesTrendLines-int-) | 返回指定系列类型是否存在趋势线。 |
| [isErrorBarsXAllowed(int seriesType)](#isErrorBarsXAllowed-int-) | 返回指定系列类型的误差线 X 是否允许。 |
| [isErrorBarsYAllowed(int seriesType)](#isErrorBarsYAllowed-int-) | 返回指定系列类型的误差线 Y 是否允许。 |

### ChartTypeCharacterizer() {#ChartTypeCharacterizer--}
```
public ChartTypeCharacterizer()
```

### isBar3DChart(int chartType) {#isBar3DChart-int-}
```
public static boolean isBar3DChart(int chartType)
```

如果 chartType 是 bar3DChart 子类型（3D 列或条形）则返回 true。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| chartType | int |  |

**返回：**
boolean

### is2DChart(int chartType) {#is2DChart-int-}
```
public static boolean is2DChart(int chartType)
```

如果 chartType 是 2D 图表类型之一则返回 true。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| chartType | int |  |

**返回：**
boolean

### is3DChart(int chartType) {#is3DChart-int-}
```
public static boolean is3DChart(int chartType)
```

如果 chartType 是 3D 图表类型之一则返回 true。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| chartType | int |  |

**返回：**
boolean

### isChartTypeColumn(int chartType) {#isChartTypeColumn-int-}
```
public static boolean isChartTypeColumn(int chartType)
```

如果 chartType 是 Column 子类型则返回 true。子类型集合对应 PowerPoint 中的相应集合（参见 PowerPoint 中的“Change Chart Type”对话框）：[ChartType.ClusteredColumn](../../com.aspose.slides/charttype\#ClusteredColumn), [ChartType.ClusteredColumn3D](../../com.aspose.slides/charttype\#ClusteredColumn3D), [ChartType.ClusteredCone](../../com.aspose.slides/charttype\#ClusteredCone), [ChartType.ClusteredCylinder](../../com.aspose.slides/charttype\#ClusteredCylinder), [ChartType.ClusteredPyramid](../../com.aspose.slides/charttype\#ClusteredPyramid), [ChartType.PercentsStackedColumn](../../com.aspose.slides/charttype\#PercentsStackedColumn), [ChartType.PercentsStackedColumn3D](../../com.aspose.slides/charttype\#PercentsStackedColumn3D), [ChartType.PercentsStackedCone](../../com.aspose.slides/charttype\#PercentsStackedCone), [ChartType.PercentsStackedCylinder](../../com.aspose.slides/charttype\#PercentsStackedCylinder), [ChartType.PercentsStackedPyramid](../../com.aspose.slides/charttype\#PercentsStackedPyramid), [ChartType.StackedColumn](../../com.aspose.slides/charttype\#StackedColumn), [ChartType.StackedColumn3D](../../com.aspose.slides/charttype\#StackedColumn3D), [ChartType.StackedCone](../../com.aspose.slides/charttype\#StackedCone), [ChartType.StackedCylinder](../../com.aspose.slides/charttype\#StackedCylinder), [ChartType.StackedPyramid](../../com.aspose.slides/charttype\#StackedPyramid), [ChartType.Column3D](../../com.aspose.slides/charttype\#Column3D), [ChartType.Cylinder3D](../../com.aspose.slides/charttype\#Cylinder3D), [ChartType.Cone3D](../../com.aspose.slides/charttype\#Cone3D), [ChartType.Pyramid3D](../../com.aspose.slides/charttype\#Pyramid3D)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| chartType | int |  |

**返回：**
boolean

### isChartTypeLine(int chartType) {#isChartTypeLine-int-}
```
public static boolean isChartTypeLine(int chartType)
```

如果 chartType 是 Line 子类型则返回 true。子类型集合对应 PowerPoint 中的相应集合（参见 PowerPoint 中的“Change Chart Type”对话框）：[ChartType.Line](../../com.aspose.slides/charttype\#Line), [ChartType.LineWithMarkers](../../com.aspose.slides/charttype\#LineWithMarkers), [ChartType.PercentsStackedLine](../../com.aspose.slides/charttype\#PercentsStackedLine), [ChartType.PercentsStackedLineWithMarkers](../../com.aspose.slides/charttype\#PercentsStackedLineWithMarkers), [ChartType.StackedLine](../../com.aspose.slides/charttype\#StackedLine), [ChartType.StackedLineWithMarkers](../../com.aspose.slides/charttype\#StackedLineWithMarkers), [ChartType.Line3D](../../com.aspose.slides/charttype\#Line3D)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| chartType | int |  |

**返回：**
boolean

### isChartTypePie(int chartType) {#isChartTypePie-int-}
```
public static boolean isChartTypePie(int chartType)
```

如果 chartType 是 Pie 子类型则返回 true。子类型集合对应 PowerPoint 中的相应集合（参见 PowerPoint 中的“Change Chart Type”对话框）：[ChartType.BarOfPie](../../com.aspose.slides/charttype\#BarOfPie), [ChartType.ExplodedPie](../../com.aspose.slides/charttype\#ExplodedPie), [ChartType.ExplodedPie3D](../../com.aspose.slides/charttype\#ExplodedPie3D), [ChartType.Pie](../../com.aspose.slides/charttype\#Pie), [ChartType.Pie3D](../../com.aspose.slides/charttype\#Pie3D), [ChartType.PieOfPie](../../com.aspose.slides/charttype\#PieOfPie)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| chartType | int |  |

**返回：**
boolean

### isChartTypeBar(int chartType) {#isChartTypeBar-int-}
```
public static boolean isChartTypeBar(int chartType)
```

如果 chartType 是 Bar 子类型则返回 true。子类型集合对应 PowerPoint 中的相应集合（参见 PowerPoint 中的“Change Chart Type”对话框）：[ChartType.ClusteredBar](../../com.aspose.slides/charttype\#ClusteredBar), [ChartType.ClusteredBar3D](../../com.aspose.slides/charttype\#ClusteredBar3D), [ChartType.PercentsStackedBar](../../com.aspose.slides/charttype\#PercentsStackedBar), [ChartType.PercentsStackedBar3D](../../com.aspose.slides/charttype\#PercentsStackedBar3D), [ChartType.StackedBar](../../com.aspose.slides/charttype\#StackedBar), [ChartType.StackedBar3D](../../com.aspose.slides/charttype\#StackedBar3D), [ChartType.ClusteredHorizontalCone](../../com.aspose.slides/charttype\#ClusteredHorizontalCone), [ChartType.ClusteredHorizontalCylinder](../../com.aspose.slides/charttype\#ClusteredHorizontalCylinder), [ChartType.ClusteredHorizontalPyramid](../../com.aspose.slides/charttype\#ClusteredHorizontalPyramid), [ChartType.StackedHorizontalCone](../../com.aspose.slides/charttype\#StackedHorizontalCone), [ChartType.StackedHorizontalCylinder](../../com.aspose.slides/charttype\#StackedHorizontalCylinder), [ChartType.StackedHorizontalPyramid](../../com.aspose.slides/charttype\#StackedHorizontalPyramid), [ChartType.PercentsStackedHorizontalCone](../../com.aspose.slides/charttype\#PercentsStackedHorizontalCone), [ChartType.PercentsStackedHorizontalCylinder](../../com.aspose.slides/charttype\#PercentsStackedHorizontalCylinder), [ChartType.PercentsStackedHorizontalPyramid](../../com.aspose.slides/charttype\#PercentsStackedHorizontalPyramid)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| chartType | int |  |

**返回：**
boolean

### isChartTypeArea(int chartType) {#isChartTypeArea-int-}
```
public static boolean isChartTypeArea(int chartType)
```

如果 chartType 是 Area 子类型则返回 true。子类型集合对应 PowerPoint 中的相应集合（参见 PowerPoint 中的“Change Chart Type”对话框）：[ChartType.Area](../../com.aspose.slides/charttype\#Area), [ChartType.PercentsStackedArea](../../com.aspose.slides/charttype\#PercentsStackedArea), [ChartType.PercentsStackedArea3D](../../com.aspose.slides/charttype\#PercentsStackedArea3D), [ChartType.StackedArea](../../com.aspose.slides/charttype\#StackedArea), [ChartType.StackedArea3D](../../com.aspose.slides/charttype\#StackedArea3D), [ChartType.Area3D](../../com.aspose.slides/charttype\#Area3D)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| chartType | int |  |

**返回：**
boolean

### isChartTypeScatter(int chartType) {#isChartTypeScatter-int-}
```
public static boolean isChartTypeScatter(int chartType)
```

如果 chartType 是 Scatter 子类型则返回 true。子类型集合对应 PowerPoint 中的相应集合（参见 PowerPoint 中的“Change Chart Type”对话框）：[ChartType.ScatterWithMarkers](../../com.aspose.slides/charttype\#ScatterWithMarkers), [ChartType.ScatterWithSmoothLines](../../com.aspose.slides/charttype\#ScatterWithSmoothLines), [ChartType.ScatterWithSmoothLinesAndMarkers](../../com.aspose.slides/charttype\#ScatterWithSmoothLinesAndMarkers), [ChartType.ScatterWithStraightLines](../../com.aspose.slides/charttype\#ScatterWithStraightLines), [ChartType.ScatterWithStraightLinesAndMarkers](../../com.aspose.slides/charttype\#ScatterWithStraightLinesAndMarkers)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| chartType | int |  |

**返回：**
boolean

### isChartTypeStock(int chartType) {#isChartTypeStock-int-}
```
public static boolean isChartTypeStock(int chartType)
```

如果 chartType 是 Stock 子类型则返回 true。子类型集合对应 PowerPoint 中的相应集合（参见 PowerPoint 中的“Change Chart Type”对话框）：[ChartType.HighLowClose](../../com.aspose.slides/charttype\#HighLowClose), [ChartType.OpenHighLowClose](../../com.aspose.slides/charttype\#OpenHighLowClose), [ChartType.VolumeHighLowClose](../../com.aspose.slides/charttype\#VolumeHighLowClose), [ChartType.VolumeOpenHighLowClose](../../com.aspose.slides/charttype\#VolumeOpenHighLowClose)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| chartType | int |  |

**返回：**
boolean

### isChartTypeSurface(int chartType) {#isChartTypeSurface-int-}
```
public static boolean isChartTypeSurface(int chartType)
```

如果 chartType 是 Surface 子类型则返回 true。子类型集合对应 PowerPoint 中的相应集合（参见 PowerPoint 中的“Change Chart Type”对话框）：[ChartType.Surface3D](../../com.aspose.slides/charttype\#Surface3D), [ChartType.WireframeSurface3D](../../com.aspose.slides/charttype\#WireframeSurface3D), [ChartType.Contour](../../com.aspose.slides/charttype\#Contour), [ChartType.WireframeContour](../../com.aspose.slides/charttype\#WireframeContour)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| chartType | int |  |

**返回：**
boolean

### isChartTypeDoughnut(int chartType) {#isChartTypeDoughnut-int-}
```
public static boolean isChartTypeDoughnut(int chartType)
```

如果 chartType 是 Doughnut 子类型则返回 true。子类型集合对应 PowerPoint 中的相应集合（参见 PowerPoint 中的“Change Chart Type”对话框）：[ChartType.Doughnut](../../com.aspose.slides/charttype\#Doughnut), [ChartType.ExplodedDoughnut](../../com.aspose.slides/charttype\#ExplodedDoughnut)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| chartType | int |  |

**返回：**
boolean

### isChartTypeBubble(int chartType) {#isChartTypeBubble-int-}
```
public static boolean isChartTypeBubble(int chartType)
```

如果 chartType 是 Bubble 子类型则返回 true。子类型集合对应 PowerPoint 中的相应集合（参见 PowerPoint 中的“Change Chart Type”对话框）：[ChartType.Bubble](../../com.aspose.slides/charttype\#Bubble), [ChartType.BubbleWith3D](../../com.aspose.slides/charttype\#BubbleWith3D)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| chartType | int |  |

**返回：**
boolean

### isChartTypeRadar(int chartType) {#isChartTypeRadar-int-}
```
public static boolean isChartTypeRadar(int chartType)
```

如果 chartType 是 Radar 子类型则返回 true。子类型集合对应 PowerPoint 中的相应集合（参见 PowerPoint 中的“Change Chart Type”对话框）：[ChartType.FilledRadar](../../com.aspose.slides/charttype\#FilledRadar), [ChartType.Radar](../../com.aspose.slides/charttype\#Radar), [ChartType.RadarWithMarkers](../../com.aspose.slides/charttype\#RadarWithMarkers)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| chartType | int |  |

**返回：**
boolean

### isSeriesUsesXValueCoordinate(int seriesType) {#isSeriesUsesXValueCoordinate-int-}
```
public static boolean isSeriesUsesXValueCoordinate(int seriesType)
```

如果指定的 series type 使用 X 值坐标则返回。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| seriesType | int | Series type. |

**返回：**
boolean - True if uses otherwise false.

### isSeriesUsesYValueCoordinate(int seriesType) {#isSeriesUsesYValueCoordinate-int-}
```
public static boolean isSeriesUsesYValueCoordinate(int seriesType)
```

如果指定的 series type 使用 Y 值坐标则返回。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| seriesType | int | Series type. |

**返回：**
boolean - True if uses otherwise false.

### isSeriesUsesValueCoordinate(int seriesType) {#isSeriesUsesValueCoordinate-int-}
```
public static boolean isSeriesUsesValueCoordinate(int seriesType)
```

如果指定的 series type 使用值坐标则返回。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| seriesType | int | Series type. |

**返回：**
boolean - True if uses otherwise false.

### isSeriesUsesBubbleSizeCoordinate(int seriesType) {#isSeriesUsesBubbleSizeCoordinate-int-}
```
public static boolean isSeriesUsesBubbleSizeCoordinate(int seriesType)
```

如果可以对指定的 series type 使用气泡大小坐标则返回。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| seriesType | int | Series type. |

**返回：**
boolean - True if can be used, otherwise false.

### hasSeriesTrendLines(int seriesType) {#hasSeriesTrendLines-int-}
```
public static boolean hasSeriesTrendLines(int seriesType)
```

如果指定的 series type 存在趋势线则返回。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| seriesType | int | Series type. |

**返回：**
boolean - True if present otherwise false.

### isErrorBarsXAllowed(int seriesType) {#isErrorBarsXAllowed-int-}
```
public static boolean isErrorBarsXAllowed(int seriesType)
```

如果指定的 series type 允许误差线 X 则返回。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| seriesType | int | Series type. |

**返回：**
boolean - True if allowed, otherwise false.

### isErrorBarsYAllowed(int seriesType) {#isErrorBarsYAllowed-int-}
```
public static boolean isErrorBarsYAllowed(int seriesType)
```

如果指定的 series type 允许误差线 Y 则返回。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| seriesType | int | Series type. |

**返回：**
boolean - True if allowed, otherwise false.