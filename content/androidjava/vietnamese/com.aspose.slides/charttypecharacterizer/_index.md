---
title: ChartTypeCharacterizer
second_title: Aspose.Slides cho Android thông qua Tham chiếu API Java
description: Trợ lý để lấy thông tin bổ sung về biểu đồ và chuỗi dựa trên ChartType của chúng.
type: docs
url: /vi/com.aspose.slides/charttypecharacterizer/
---
**Kế thừa:**
java.lang.Object
```
public class ChartTypeCharacterizer
```

Trợ lý để lấy thông tin bổ sung về biểu đồ và chuỗi dựa trên ChartType của chúng.
## Hàm khởi tạo

| Hàm khởi tạo | Mô tả |
| --- | --- |
| [ChartTypeCharacterizer()](#ChartTypeCharacterizer--) |  |
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [isBar3DChart(int chartType)](#isBar3DChart-int-) | Trả về true nếu chartType là một trong các kiểu phụ bar3DChart (cột 3D hoặc thanh). |
| [is2DChart(int chartType)](#is2DChart-int-) | Trả về true nếu chartType là một trong các loại biểu đồ 2D. |
| [is3DChart(int chartType)](#is3DChart-int-) | Trả về true nếu chartType là một trong các loại biểu đồ 3D. |
| [isChartTypeColumn(int chartType)](#isChartTypeColumn-int-) | Trả về true nếu chartType là một trong các kiểu phụ Column. |
| [isChartTypeLine(int chartType)](#isChartTypeLine-int-) | Trả về true nếu chartType là một trong các kiểu phụ Line. |
| [isChartTypePie(int chartType)](#isChartTypePie-int-) | Trả về true nếu chartType là một trong các kiểu phụ Pie. |
| [isChartTypeBar(int chartType)](#isChartTypeBar-int-) | Trả về true nếu chartType là một trong các kiểu phụ Bar. |
| [isChartTypeArea(int chartType)](#isChartTypeArea-int-) | Trả về true nếu chartType là một trong các kiểu phụ Area. |
| [isChartTypeScatter(int chartType)](#isChartTypeScatter-int-) | Trả về true nếu chartType là một trong các kiểu phụ Scatter. |
| [isChartTypeStock(int chartType)](#isChartTypeStock-int-) | Trả về true nếu chartType là một trong các kiểu phụ Stock. |
| [isChartTypeSurface(int chartType)](#isChartTypeSurface-int-) | Trả về true nếu chartType là một trong các kiểu phụ Surface. |
| [isChartTypeDoughnut(int chartType)](#isChartTypeDoughnut-int-) | Trả về true nếu chartType là một trong các kiểu phụ Doughnut. |
| [isChartTypeBubble(int chartType)](#isChartTypeBubble-int-) | Trả về true nếu chartType là một trong các kiểu phụ Bubble. |
| [isChartTypeRadar(int chartType)](#isChartTypeRadar-int-) | Trả về true nếu chartType là một trong các kiểu phụ Radar. |
| [isSeriesUsesXValueCoordinate(int seriesType)](#isSeriesUsesXValueCoordinate-int-) | Trả về nếu loại series được chỉ định sử dụng tọa độ giá trị X. |
| [isSeriesUsesYValueCoordinate(int seriesType)](#isSeriesUsesYValueCoordinate-int-) | Trả về nếu loại series được chỉ định sử dụng tọa độ giá trị Y. |
| [isSeriesUsesValueCoordinate(int seriesType)](#isSeriesUsesValueCoordinate-int-) | Trả về nếu loại series được chỉ định sử dụng tọa độ giá trị. |
| [isSeriesUsesBubbleSizeCoordinate(int seriesType)](#isSeriesUsesBubbleSizeCoordinate-int-) | Trả về nếu tọa độ kích thước bong bóng có thể được sử dụng cho loại series được chỉ định. |
| [hasSeriesTrendLines(int seriesType)](#hasSeriesTrendLines-int-) | Trả về nếu có đường xu hướng series cho loại series được chỉ định. |
| [isErrorBarsXAllowed(int seriesType)](#isErrorBarsXAllowed-int-) | Trả về nếu thanh lỗi X được cho phép cho loại series được chỉ định. |
| [isErrorBarsYAllowed(int seriesType)](#isErrorBarsYAllowed-int-) | Trả về nếu thanh lỗi Y được cho phép cho loại series được chỉ định. |
### ChartTypeCharacterizer() {#ChartTypeCharacterizer--}
```
public ChartTypeCharacterizer()
```

### isBar3DChart(int chartType) {#isBar3DChart-int-}
```
public static boolean isBar3DChart(int chartType)
```

Trả về true nếu chartType là một trong các kiểu phụ bar3DChart (cột 3D hoặc thanh).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| chartType | int |  |

**Trả về:**
boolean
### is2DChart(int chartType) {#is2DChart-int-}
```
public static boolean is2DChart(int chartType)
```

Trả về true nếu chartType là một trong các loại biểu đồ 2D.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| chartType | int |  |

**Trả về:**
boolean
### is3DChart(int chartType) {#is3DChart-int-}
```
public static boolean is3DChart(int chartType)
```

Trả về true nếu chartType là một trong các loại biểu đồ 3D.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| chartType | int |  |

**Trả về:**
boolean
### isChartTypeColumn(int chartType) {#isChartTypeColumn-int-}
```
public static boolean isChartTypeColumn(int chartType)
```

Trả về true nếu chartType là một trong các kiểu phụ Column. Tập hợp các kiểu phụ tương ứng với tập hợp trong PowerPoint (xem hộp thoại "Change Chart Type" trong PowerPoint): [ChartType.ClusteredColumn](../../com.aspose.slides/charttype\#ClusteredColumn), [ChartType.ClusteredColumn3D](../../com.aspose.slides/charttype\#ClusteredColumn3D), [ChartType.ClusteredCone](../../com.aspose.slides/charttype\#ClusteredCone), [ChartType.ClusteredCylinder](../../com.aspose.slides/charttype\#ClusteredCylinder), [ChartType.ClusteredPyramid](../../com.aspose.slides/charttype\#ClusteredPyramid), [ChartType.PercentsStackedColumn](../../com.aspose.slides/charttype\#PercentsStackedColumn), [ChartType.PercentsStackedColumn3D](../../com.aspose.slides/charttype\#PercentsStackedColumn3D), [ChartType.PercentsStackedCone](../../com.aspose.slides/charttype\#PercentsStackedCone), [ChartType.PercentsStackedCylinder](../../com.aspose.slides/charttype\#PercentsStackedCylinder), [ChartType.PercentsStackedPyramid](../../com.aspose.slides/charttype\#PercentsStackedPyramid), [ChartType.StackedColumn](../../com.aspose.slides/charttype\#StackedColumn), [ChartType.StackedColumn3D](../../com.aspose.slides/charttype\#StackedColumn3D), [ChartType.StackedCone](../../com.aspose.slides/charttype\#StackedCone), [ChartType.StackedCylinder](../../com.aspose.slides/charttype\#StackedCylinder), [ChartType.StackedPyramid](../../com.aspose.slides/charttype\#StackedPyramid), [ChartType.Column3D](../../com.aspose.slides/charttype\#Column3D), [ChartType.Cylinder3D](../../com.aspose.slides/charttype\#Cylinder3D), [ChartType.Cone3D](../../com.aspose.slides/charttype\#Cone3D), [ChartType.Pyramid3D](../../com.aspose.slides/charttype\#Pyramid3D).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| chartType | int |  |

**Trả về:**
boolean
### isChartTypeLine(int chartType) {#isChartTypeLine-int-}
```
public static boolean isChartTypeLine(int chartType)
```

Trả về true nếu chartType là một trong các kiểu phụ Line. Tập hợp các kiểu phụ tương ứng với tập hợp trong PowerPoint (xem hộp thoại "Change Chart Type" trong PowerPoint): [ChartType.Line](../../com.aspose.slides/charttype\#Line), [ChartType.LineWithMarkers](../../com.aspose.slides/charttype\#LineWithMarkers), [ChartType.PercentsStackedLine](../../com.aspose.slides/charttype\#PercentsStackedLine), [ChartType.PercentsStackedLineWithMarkers](../../com.aspose.slides/charttype\#PercentsStackedLineWithMarkers), [ChartType.StackedLine](../../com.aspose.slides/charttype\#StackedLine), [ChartType.StackedLineWithMarkers](../../com.aspose.slides/charttype\#StackedLineWithMarkers), [ChartType.Line3D](../../com.aspose.slides/charttype\#Line3D).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| chartType | int |  |

**Trả về:**
boolean
### isChartTypePie(int chartType) {#isChartTypePie-int-}
```
public static boolean isChartTypePie(int chartType)
```

Trả về true nếu chartType là một trong các kiểu phụ Pie. Tập hợp các kiểu phụ tương ứng với tập hợp trong PowerPoint (xem hộp thoại "Change Chart Type" trong PowerPoint): [ChartType.BarOfPie](../../com.aspose.slides/charttype\#BarOfPie), [ChartType.ExplodedPie](../../com.aspose.slides/charttype\#ExplodedPie), [ChartType.ExplodedPie3D](../../com.aspose.slides/charttype\#ExplodedPie3D), [ChartType.Pie](../../com.aspose.slides/charttype\#Pie), [ChartType.Pie3D](../../com.aspose.slides/charttype\#Pie3D), [ChartType.PieOfPie](../../com.aspose.slides/charttype\#PieOfPie).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| chartType | int |  |

**Trả về:**
boolean
### isChartTypeBar(int chartType) {#isChartTypeBar-int-}
```
public static boolean isChartTypeBar(int chartType)
```

Trả về true nếu chartType là một trong các kiểu phụ Bar. Tập hợp các kiểu phụ tương ứng với tập hợp trong PowerPoint (xem hộp thoại "Change Chart Type" trong PowerPoint): [ChartType.ClusteredBar](../../com.aspose.slides/charttype\#ClusteredBar), [ChartType.ClusteredBar3D](../../com.aspose.slides/charttype\#ClusteredBar3D), [ChartType.PercentsStackedBar](../../com.aspose.slides/charttype\#PercentsStackedBar), [ChartType.PercentsStackedBar3D](../../com.aspose.slides/charttype\#PercentsStackedBar3D), [ChartType.StackedBar](../../com.aspose.slides/charttype\#StackedBar), [ChartType.StackedBar3D](../../com.aspose.slides/charttype\#StackedBar3D), [ChartType.ClusteredHorizontalCone](../../com.aspose.slides/charttype\#ClusteredHorizontalCone), [ChartType.ClusteredHorizontalCylinder](../../com.aspose.slides/charttype\#ClusteredHorizontalCylinder), [ChartType.ClusteredHorizontalPyramid](../../com.aspose.slides/charttype\#ClusteredHorizontalPyramid), [ChartType.StackedHorizontalCone](../../com.aspose.slides/charttype\#StackedHorizontalCone), [ChartType.StackedHorizontalCylinder](../../com.aspose.slides/charttype\#StackedHorizontalCylinder), [ChartType.StackedHorizontalPyramid](../../com.aspose.slides/charttype\#StackedHorizontalPyramid), [ChartType.PercentsStackedHorizontalCone](../../com.aspose.slides/charttype\#PercentsStackedHorizontalCone), [ChartType.PercentsStackedHorizontalCylinder](../../com.aspose.slides/charttype\#PercentsStackedHorizontalCylinder), [ChartType.PercentsStackedHorizontalPyramid](../../com.aspose.slides/charttype\#PercentsStackedHorizontalPyramid).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| chartType | int |  |

**Trả về:**
boolean
### isChartTypeArea(int chartType) {#isChartTypeArea-int-}
```
public static boolean isChartTypeArea(int chartType)
```

Trả về true nếu chartType là một trong các kiểu phụ Area. Tập hợp các kiểu phụ tương ứng với tập hợp trong PowerPoint (xem hộp thoại "Change Chart Type" trong PowerPoint): [ChartType.Area](../../com.aspose.slides/charttype\#Area), [ChartType.PercentsStackedArea](../../com.aspose.slides/charttype\#PercentsStackedArea), [ChartType.PercentsStackedArea3D](../../com.aspose.slides/charttype\#PercentsStackedArea3D), [ChartType.StackedArea](../../com.aspose.slides/charttype\#StackedArea), [ChartType.StackedArea3D](../../com.aspose.slides/charttype\#StackedArea3D), [ChartType.Area3D](../../com.aspose.slides/charttype\#Area3D).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| chartType | int |  |

**Trả về:**
boolean
### isChartTypeScatter(int chartType) {#isChartTypeScatter-int-}
```
public static boolean isChartTypeScatter(int chartType)
```

Trả về true nếu chartType là một trong các kiểu phụ Scatter. Tập hợp các kiểu phụ tương ứng với tập hợp trong PowerPoint (xem hộp thoại "Change Chart Type" trong PowerPoint): [ChartType.ScatterWithMarkers](../../com.aspose.slides/charttype\#ScatterWithMarkers), [ChartType.ScatterWithSmoothLines](../../com.aspose.slides/charttype\#ScatterWithSmoothLines), [ChartType.ScatterWithSmoothLinesAndMarkers](../../com.aspose.slides/charttype\#ScatterWithSmoothLinesAndMarkers), [ChartType.ScatterWithStraightLines](../../com.aspose.slides/charttype\#ScatterWithStraightLines), [ChartType.ScatterWithStraightLinesAndMarkers](../../com.aspose.slides/charttype\#ScatterWithStraightLinesAndMarkers).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| chartType | int |  |

**Trả về:**
boolean
### isChartTypeStock(int chartType) {#isChartTypeStock-int-}
```
public static boolean isChartTypeStock(int chartType)
```

Trả về true nếu chartType là một trong các kiểu phụ Stock. Tập hợp các kiểu phụ tương ứng với tập hợp trong PowerPoint (xem hộp thoại "Change Chart Type" trong PowerPoint): [ChartType.HighLowClose](../../com.aspose.slides/charttype\#HighLowClose), [ChartType.OpenHighLowClose](../../com.aspose.slides/charttype\#OpenHighLowClose), [ChartType.VolumeHighLowClose](../../com.aspose.slides/charttype\#VolumeHighLowClose), [ChartType.VolumeOpenHighLowClose](../../com.aspose.slides/charttype\#VolumeOpenHighLowClose).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| chartType | int |  |

**Trả về:**
boolean
### isChartTypeSurface(int chartType) {#isChartTypeSurface-int-}
```
public static boolean isChartTypeSurface(int chartType)
```

Trả về true nếu chartType là một trong các kiểu phụ Surface. Tập hợp các kiểu phụ tương ứng với tập hợp trong PowerPoint (xem hộp thoại "Change Chart Type" trong PowerPoint): [ChartType.Surface3D](../../com.aspose.slides/charttype\#Surface3D), [ChartType.WireframeSurface3D](../../com.aspose.slides/charttype\#WireframeSurface3D), [ChartType.Contour](../../com.aspose.slides/charttype\#Contour), [ChartType.WireframeContour](../../com.aspose.slides/charttype\#WireframeContour).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| chartType | int |  |

**Trả về:**
boolean
### isChartTypeDoughnut(int chartType) {#isChartTypeDoughnut-int-}
```
public static boolean isChartTypeDoughnut(int chartType)
```

Trả về true nếu chartType là một trong các kiểu phụ Doughnut. Tập hợp các kiểu phụ tương ứng với tập hợp trong PowerPoint (xem hộp thoại "Change Chart Type" trong PowerPoint): [ChartType.Doughnut](../../com.aspose.slides/charttype\#Doughnut), [ChartType.ExplodedDoughnut](../../com.aspose.slides/charttype\#ExplodedDoughnut).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| chartType | int |  |

**Trả về:**
boolean
### isChartTypeBubble(int chartType) {#isChartTypeBubble-int-}
```
public static boolean isChartTypeBubble(int chartType)
```

Trả về true nếu chartType là một trong các kiểu phụ Bubble. Tập hợp các kiểu phụ tương ứng với tập hợp trong PowerPoint (xem hộp thoại "Change Chart Type" trong PowerPoint): [ChartType.Bubble](../../com.aspose.slides/charttype\#Bubble), [ChartType.BubbleWith3D](../../com.aspose.slides/charttype\#BubbleWith3D).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| chartType | int |  |

**Trả về:**
boolean
### isChartTypeRadar(int chartType) {#isChartTypeRadar-int-}
```
public static boolean isChartTypeRadar(int chartType)
```

Trả về true nếu chartType là một trong các kiểu phụ Radar. Tập hợp các kiểu phụ tương ứng với tập hợp trong PowerPoint (xem hộp thoại "Change Chart Type" trong PowerPoint): [ChartType.FilledRadar](../../com.aspose.slides/charttype\#FilledRadar), [ChartType.Radar](../../com.aspose.slides/charttype\#Radar), [ChartType.RadarWithMarkers](../../com.aspose.slides/charttype\#RadarWithMarkers).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| chartType | int |  |

**Trả về:**
boolean
### isSeriesUsesXValueCoordinate(int seriesType) {#isSeriesUsesXValueCoordinate-int-}
```
public static boolean isSeriesUsesXValueCoordinate(int seriesType)
```

Trả về nếu loại series được chỉ định sử dụng tọa độ giá trị X.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| seriesType | int | Loại series. |

**Trả về:**
boolean - True nếu sử dụng, ngược lại false.
### isSeriesUsesYValueCoordinate(int seriesType) {#isSeriesUsesYValueCoordinate-int-}
```
public static boolean isSeriesUsesYValueCoordinate(int seriesType)
```

Trả về nếu loại series được chỉ định sử dụng tọa độ giá trị Y.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| seriesType | int | Loại series. |

**Trả về:**
boolean - True nếu sử dụng, ngược lại false.
### isSeriesUsesValueCoordinate(int seriesType) {#isSeriesUsesValueCoordinate-int-}
```
public static boolean isSeriesUsesValueCoordinate(int seriesType)
```

Trả về nếu loại series được chỉ định sử dụng tọa độ giá trị.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| seriesType | int | Loại series. |

**Trả về:**
boolean - True nếu sử dụng, ngược lại false.
### isSeriesUsesBubbleSizeCoordinate(int seriesType) {#isSeriesUsesBubbleSizeCoordinate-int-}
```
public static boolean isSeriesUsesBubbleSizeCoordinate(int seriesType)
```

Trả về nếu tọa độ kích thước bong bóng có thể được sử dụng cho loại series được chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| seriesType | int | Loại series. |

**Trả về:**
boolean - True nếu có thể sử dụng, ngược lại false.
### hasSeriesTrendLines(int seriesType) {#hasSeriesTrendLines-int-}
```
public static boolean hasSeriesTrendLines(int seriesType)
```

Trả về nếu có đường xu hướng series cho loại series được chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| seriesType | int | Loại series. |

**Trả về:**
boolean - True nếu có, ngược lại false.
### isErrorBarsXAllowed(int seriesType) {#isErrorBarsXAllowed-int-}
```
public static boolean isErrorBarsXAllowed(int seriesType)
```

Trả về nếu thanh lỗi X được cho phép cho loại series được chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| seriesType | int | Loại series. |

**Trả về:**
boolean - True nếu cho phép, ngược lại false.
### isErrorBarsYAllowed(int seriesType) {#isErrorBarsYAllowed-int-}
```
public static boolean isErrorBarsYAllowed(int seriesType)
```

Trả về nếu thanh lỗi Y được cho phép cho loại series được chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| seriesType | int | Loại series. |

**Trả về:**
boolean - True nếu cho phép, ngược lại false.