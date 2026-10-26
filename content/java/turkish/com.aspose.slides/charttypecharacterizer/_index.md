---
title: ChartTypeCharacterizer
second_title: Aspose.Slides for Java API Referansı
description: ChartType kullanarak grafikler ve seriler hakkında ek bilgi almak için yardımcı.
type: docs
url: /tr/com.aspose.slides/charttypecharacterizer/
---
**Inheritance:**
java.lang.Object
```
public class ChartTypeCharacterizer
```

ChartType kullanarak grafikler ve seriler hakkında ek bilgi almak için yardımcı.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [ChartTypeCharacterizer()](#ChartTypeCharacterizer--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [isBar3DChart(int chartType)](#isBar3DChart-int-) | chartType, bar3DChart alt türlerinden biriyse true döndürür (3D sütunlar veya çubuklar). |
| [is2DChart(int chartType)](#is2DChart-int-) | chartType, 2D grafik türlerinden biriyse true döndürür. |
| [is3DChart(int chartType)](#is3DChart-int-) | chartType, 3D grafik türlerinden biriyse true döndürür. |
| [isChartTypeColumn(int chartType)](#isChartTypeColumn-int-) | chartType, Column alt türlerinden biriyse true döndürür. |
| [isChartTypeLine(int chartType)](#isChartTypeLine-int-) | chartType, Line alt türlerinden biriyse true döndürür. |
| [isChartTypePie(int chartType)](#isChartTypePie-int-) | chartType, Pie alt türlerinden biriyse true döndürür. |
| [isChartTypeBar(int chartType)](#isChartTypeBar-int-) | chartType, Bar alt türlerinden biriyse true döndürür. |
| [isChartTypeArea(int chartType)](#isChartTypeArea-int-) | chartType, Area alt türlerinden biriyse true döndürür. |
| [isChartTypeScatter(int chartType)](#isChartTypeScatter-int-) | chartType, Scatter alt türlerinden biriyse true döndürür. |
| [isChartTypeStock(int chartType)](#isChartTypeStock-int-) | chartType, Stock alt türlerinden biriyse true döndürür. |
| [isChartTypeSurface(int chartType)](#isChartTypeSurface-int-) | chartType, Surface alt türlerinden biriyse true döndürür. |
| [isChartTypeDoughnut(int chartType)](#isChartTypeDoughnut-int-) | chartType, Doughnut alt türlerinden biriyse true döndürür. |
| [isChartTypeBubble(int chartType)](#isChartTypeBubble-int-) | chartType, Bubble alt türlerinden biriyse true döndürür. |
| [isChartTypeRadar(int chartType)](#isChartTypeRadar-int-) | chartType, Radar alt türlerinden biriyse true döndürür. |
| [isSeriesUsesXValueCoordinate(int seriesType)](#isSeriesUsesXValueCoordinate-int-) | Belirtilen seri tipi X değer koordinatlarını kullanıyorsa true döndürür. |
| [isSeriesUsesYValueCoordinate(int seriesType)](#isSeriesUsesYValueCoordinate-int-) | Belirtilen seri tipi Y değer koordinatlarını kullanıyorsa true döndürür. |
| [isSeriesUsesValueCoordinate(int seriesType)](#isSeriesUsesValueCoordinate-int-) | Belirtilen seri tipi değer koordinatlarını kullanıyorsa true döndürür. |
| [isSeriesUsesBubbleSizeCoordinate(int seriesType)](#isSeriesUsesBubbleSizeCoordinate-int-) | Belirtilen seri tipi için baloncuk boyutu koordinatları kullanılabiliyorsa true döndürür. |
| [hasSeriesTrendLines(int seriesType)](#hasSeriesTrendLines-int-) | Belirtilen seri tipi için seri trend çizgileri varsa true döndürür. |
| [isErrorBarsXAllowed(int seriesType)](#isErrorBarsXAllowed-int-) | Belirtilen seri tipi için X hata çubukları izinliyse true döndürür. |
| [isErrorBarsYAllowed(int seriesType)](#isErrorBarsYAllowed-int-) | Belirtilen seri tipi için Y hata çubukları izinliyse true döndürür. |
### ChartTypeCharacterizer() {#ChartTypeCharacterizer--}
```
public ChartTypeCharacterizer()
```


### isBar3DChart(int chartType) {#isBar3DChart-int-}
```
public static boolean isBar3DChart(int chartType)
```


chartType, bar3DChart alt türlerinden biriyse true döndürür (3D sütunlar veya çubuklar).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| chartType | int |  |

**Döndürür:**
boolean
### is2DChart(int chartType) {#is2DChart-int-}
```
public static boolean is2DChart(int chartType)
```


chartType, 2D grafik türlerinden biriyse true döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| chartType | int |  |

**Döndürür:**
boolean
### is3DChart(int chartType) {#is3DChart-int-}
```
public static boolean is3DChart(int chartType)
```


chartType, 3D grafik türlerinden biriyse true döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| chartType | int |  |

**Döndürür:**
boolean
### isChartTypeColumn(int chartType) {#isChartTypeColumn-int-}
```
public static boolean isChartTypeColumn(int chartType)
```


chartType, Column alt türlerinden biriyse true döndürür. Alt türler kümesi, PowerPoint'teki uygun kümeye karşılık gelir ("Change Chart Type" iletişim kutusuna bakınız): [ChartType.ClusteredColumn](../../com.aspose.slides/charttype\#ClusteredColumn), [ChartType.ClusteredColumn3D](../../com.aspose.slides/charttype\#ClusteredColumn3D), [ChartType.ClusteredCone](../../com.aspose.slides/charttype\#ClusteredCone), [ChartType.ClusteredCylinder](../../com.aspose.slides/charttype\#ClusteredCylinder), [ChartType.ClusteredPyramid](../../com.aspose.slides/charttype\#ClusteredPyramid), [ChartType.PercentsStackedColumn](../../com.aspose.slides/charttype\#PercentsStackedColumn), [ChartType.PercentsStackedColumn3D](../../com.aspose.slides/charttype\#PercentsStackedColumn3D), [ChartType.PercentsStackedCone](../../com.aspose.slides/charttype\#PercentsStackedCone), [ChartType.PercentsStackedCylinder](../../com.aspose.slides/charttype\#PercentsStackedCylinder), [ChartType.PercentsStackedPyramid](../../com.aspose.slides/charttype\#PercentsStackedPyramid), [ChartType.StackedColumn](../../com.aspose.slides/charttype\#StackedColumn), [ChartType.StackedColumn3D](../../com.aspose.slides/charttype\#StackedColumn3D), [ChartType.StackedCone](../../com.aspose.slides/charttype\#StackedCone), [ChartType.StackedCylinder](../../com.aspose.slides/charttype\#StackedCylinder), [ChartType.StackedPyramid](../../com.aspose.slides/charttype\#StackedPyramid), [ChartType.Column3D](../../com.aspose.slides/charttype\#Column3D), [ChartType.Cylinder3D](../../com.aspose.slides/charttype\#Cylinder3D), [ChartType.Cone3D](../../com.aspose.slides/charttype\#Cone3D), [ChartType.Pyramid3D](../../com.aspose.slides/charttype\#Pyramid3D).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| chartType | int |  |

**Döndürür:**
boolean
### isChartTypeLine(int chartType) {#isChartTypeLine-int-}
```
public static boolean isChartTypeLine(int chartType)
```


chartType, Line alt türlerinden biriyse true döndürür. Alt türler kümesi, PowerPoint'teki uygun kümeye karşılık gelir ("Change Chart Type" iletişim kutusuna bakınız): [ChartType.Line](../../com.aspose.slides/charttype\#Line), [ChartType.LineWithMarkers](../../com.aspose.slides/charttype\#LineWithMarkers), [ChartType.PercentsStackedLine](../../com.aspose.slides/charttype\#PercentsStackedLine), [ChartType.PercentsStackedLineWithMarkers](../../com.aspose.slides/charttype\#PercentsStackedLineWithMarkers), [ChartType.StackedLine](../../com.aspose.slides/charttype\#StackedLine), [ChartType.StackedLineWithMarkers](../../com.aspose.slides/charttype\#StackedLineWithMarkers), [ChartType.Line3D](../../com.aspose.slides/charttype\#Line3D).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| chartType | int |  |

**Döndürür:**
boolean
### isChartTypePie(int chartType) {#isChartTypePie-int-}
```
public static boolean isChartTypePie(int chartType)
```


chartType, Pie alt türlerinden biriyse true döndürür. Alt türler kümesi, PowerPoint'teki uygun kümeye karşılık gelir ("Change Chart Type" iletişim kutusuna bakınız): [ChartType.BarOfPie](../../com.aspose.slides/charttype\#BarOfPie), [ChartType.ExplodedPie](../../com.aspose.slides/charttype\#ExplodedPie), [ChartType.ExplodedPie3D](../../com.aspose.slides/charttype\#ExplodedPie3D), [ChartType.Pie](../../com.aspose.slides/charttype\#Pie), [ChartType.Pie3D](../../com.aspose.slides/charttype\#Pie3D), [ChartType.PieOfPie](../../com.aspose.slides/charttype\#PieOfPie).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| chartType | int |  |

**Döndürür:**
boolean
### isChartTypeBar(int chartType) {#isChartTypeBar-int-}
```
public static boolean isChartTypeBar(int chartType)
```


chartType, Bar alt türlerinden biriyse true döndürür. Alt türler kümesi, PowerPoint'teki uygun kümeye karşılık gelir ("Change Chart Type" iletişim kutusuna bakınız): [ChartType.ClusteredBar](../../com.aspose.slides/charttype\#ClusteredBar), [ChartType.ClusteredBar3D](../../com.aspose.slides/charttype\#ClusteredBar3D), [ChartType.PercentsStackedBar](../../com.aspose.slides/charttype\#PercentsStackedBar), [ChartType.PercentsStackedBar3D](../../com.aspose.slides/charttype\#PercentsStackedBar3D), [ChartType.StackedBar](../../com.aspose.slides/charttype\#StackedBar), [ChartType.StackedBar3D](../../com.aspose.slides/charttype\#StackedBar3D), [ChartType.ClusteredHorizontalCone](../../com.aspose.slides/charttype\#ClusteredHorizontalCone), [ChartType.ClusteredHorizontalCylinder](../../com.aspose.slides/charttype\#ClusteredHorizontalCylinder), [ChartType.ClusteredHorizontalPyramid](../../com.aspose.slides/charttype\#ClusteredHorizontalPyramid), [ChartType.StackedHorizontalCone](../../com.aspose.slides/charttype\#StackedHorizontalCone), [ChartType.StackedHorizontalCylinder](../../com.aspose.slides/charttype\#StackedHorizontalCylinder), [ChartType.StackedHorizontalPyramid](../../com.aspose.slides/charttype\#StackedHorizontalPyramid), [ChartType.PercentsStackedHorizontalCone](../../com.aspose.slides/charttype\#PercentsStackedHorizontalCone), [ChartType.PercentsStackedHorizontalCylinder](../../com.aspose.slides/charttype\#PercentsStackedHorizontalCylinder), [ChartType.PercentsStackedHorizontalPyramid](../../com.aspose.slides/charttype\#PercentsStackedHorizontalPyramid).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| chartType | int |  |

**Döndürür:**
boolean
### isChartTypeArea(int chartType) {#isChartTypeArea-int-}
```
public static boolean isChartTypeArea(int chartType)
```


chartType, Area alt türlerinden biriyse true döndürür. Alt türler kümesi, PowerPoint'teki uygun kümeye karşılık gelir ("Change Chart Type" iletişim kutusuna bakınız): [ChartType.Area](../../com.aspose.slides/charttype\#Area), [ChartType.PercentsStackedArea](../../com.aspose.slides/charttype\#PercentsStackedArea), [ChartType.PercentsStackedArea3D](../../com.aspose.slides/charttype\#PercentsStackedArea3D), [ChartType.StackedArea](../../com.aspose.slides/charttype\#StackedArea), [ChartType.StackedArea3D](../../com.aspose.slides/charttype\#StackedArea3D), [ChartType.Area3D](../../com.aspose.slides/charttype\#Area3D).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| chartType | int |  |

**Döndürür:**
boolean
### isChartTypeScatter(int chartType) {#isChartTypeScatter-int-}
```
public static boolean isChartTypeScatter(int chartType)
```


chartType, Scatter alt türlerinden biriyse true döndürür. Alt türler kümesi, PowerPoint'teki uygun kümeye karşılık gelir ("Change Chart Type" iletişim kutusuna bakınız): [ChartType.ScatterWithMarkers](../../com.aspose.slides/charttype\#ScatterWithMarkers), [ChartType.ScatterWithSmoothLines](../../com.aspose.slides/charttype\#ScatterWithSmoothLines), [ChartType.ScatterWithSmoothLinesAndMarkers](../../com.aspose.slides/charttype\#ScatterWithSmoothLinesAndMarkers), [ChartType.ScatterWithStraightLines](../../com.aspose.slides/charttype\#ScatterWithStraightLines), [ChartType.ScatterWithStraightLinesAndMarkers](../../com.aspose.slides/charttype\#ScatterWithStraightLinesAndMarkers).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| chartType | int |  |

**Döndürür:**
boolean
### isChartTypeStock(int chartType) {#isChartTypeStock-int-}
```
public static boolean isChartTypeStock(int chartType)
```


chartType, Stock alt türlerinden biriyse true döndürür. Alt türler kümesi, PowerPoint'teki uygun kümeye karşılık gelir ("Change Chart Type" iletişim kutusuna bakınız): [ChartType.HighLowClose](../../com.aspose.slides/charttype\#HighLowClose), [ChartType.OpenHighLowClose](../../com.aspose.slides/charttype\#OpenHighLowClose), [ChartType.VolumeHighLowClose](../../com.aspose.slides/charttype\#VolumeHighLowClose), [ChartType.VolumeOpenHighLowClose](../../com.aspose.slides/charttype\#VolumeOpenHighLowClose).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| chartType | int |  |

**Döndürür:**
boolean
### isChartTypeSurface(int chartType) {#isChartTypeSurface-int-}
```
public static boolean isChartTypeSurface(int chartType)
```


chartType, Surface alt türlerinden biriyse true döndürür. Alt türler kümesi, PowerPoint'teki uygun kümeye karşılık gelir ("Change Chart Type" iletişim kutusuna bakınız): [ChartType.Surface3D](../../com.aspose.slides/charttype\#Surface3D), [ChartType.WireframeSurface3D](../../com.aspose.slides/charttype\#WireframeSurface3D), [ChartType.Contour](../../com.aspose.slides/charttype\#Contour), [ChartType.WireframeContour](../../com.aspose.slides/charttype\#WireframeContour).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| chartType | int |  |

**Döndürür:**
boolean
### isChartTypeDoughnut(int chartType) {#isChartTypeDoughnut-int-}
```
public static boolean isChartTypeDoughnut(int chartType)
```


chartType, Doughnut alt türlerinden biriyse true döndürür. Alt türler kümesi, PowerPoint'teki uygun kümeye karşılık gelir ("Change Chart Type" iletişim kutusuna bakınız): [ChartType.Doughnut](../../com.aspose.slides/charttype\#Doughnut), [ChartType.ExplodedDoughnut](../../com.aspose.slides/charttype\#ExplodedDoughnut).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| chartType | int |  |

**Döndürür:**
boolean
### isChartTypeBubble(int chartType) {#isChartTypeBubble-int-}
```
public static boolean isChartTypeBubble(int chartType)
```


chartType, Bubble alt türlerinden biriyse true döndürür. Alt türler kümesi, PowerPoint'teki uygun kümeye karşılık gelir ("Change Chart Type" iletişim kutusuna bakınız): [ChartType.Bubble](../../com.aspose.slides/charttype\#Bubble), [ChartType.BubbleWith3D](../../com.aspose.slides/charttype\#BubbleWith3D).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| chartType | int |  |

**Döndürür:**
boolean
### isChartTypeRadar(int chartType) {#isChartTypeRadar-int-}
```
public static boolean isChartTypeRadar(int chartType)
```


chartType, Radar alt türlerinden biriyse true döndürür. Alt türler kümesi, PowerPoint'teki uygun kümeye karşılık gelir ("Change Chart Type" iletişim kutusuna bakınız): [ChartType.FilledRadar](../../com.aspose.slides/charttype\#FilledRadar), [ChartType.Radar](../../com.aspose.slides/charttype\#Radar), [ChartType.RadarWithMarkers](../../com.aspose.slides/charttype\#RadarWithMarkers).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| chartType | int |  |

**Döndürür:**
boolean
### isSeriesUsesXValueCoordinate(int seriesType) {#isSeriesUsesXValueCoordinate-int-}
```
public static boolean isSeriesUsesXValueCoordinate(int seriesType)
```


Belirtilen seri tipi X değer koordinatlarını kullanıyorsa true döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| seriesType | int | Series type. |

**Döndürür:**
boolean - True if uses otherwise false.
### isSeriesUsesYValueCoordinate(int seriesType) {#isSeriesUsesYValueCoordinate-int-}
```
public static boolean isSeriesUsesYValueCoordinate(int seriesType)
```


Belirtilen seri tipi Y değer koordinatlarını kullanıyorsa true döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| seriesType | int | Series type. |

**Döndürür:**
boolean - True if uses otherwise false.
### isSeriesUsesValueCoordinate(int seriesType) {#isSeriesUsesValueCoordinate-int-}
```
public static boolean isSeriesUsesValueCoordinate(int seriesType)
```


Belirtilen seri tipi değer koordinatlarını kullanıyorsa true döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| seriesType | int | Series type. |

**Döndürür:**
boolean - True if uses otherwise false.
### isSeriesUsesBubbleSizeCoordinate(int seriesType) {#isSeriesUsesBubbleSizeCoordinate-int-}
```
public static boolean isSeriesUsesBubbleSizeCoordinate(int seriesType)
```


Belirtilen seri tipi için baloncuk boyutu koordinatları kullanılabiliyorsa true döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| seriesType | int | Series type. |

**Döndürür:**
boolean - True if can be used, otherwise false.
### hasSeriesTrendLines(int seriesType) {#hasSeriesTrendLines-int-}
```
public static boolean hasSeriesTrendLines(int seriesType)
```


Belirtilen seri tipi için seri trend çizgileri varsa true döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| seriesType | int | Series type. |

**Döndürür:**
boolean - True if present otherwise false.
### isErrorBarsXAllowed(int seriesType) {#isErrorBarsXAllowed-int-}
```
public static boolean isErrorBarsXAllowed(int seriesType)
```


Belirtilen seri tipi için X hata çubukları izinliyse true döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| seriesType | int | Series type. |

**Döndürür:**
boolean - True if allowed, otherwise false.
### isErrorBarsYAllowed(int seriesType) {#isErrorBarsYAllowed-int-}
```
public static boolean isErrorBarsYAllowed(int seriesType)
```


Belirtilen seri tipi için Y hata çubukları izinliyse true döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| seriesType | int | Series type. |

**Döndürür:**
boolean - True if allowed, otherwise false.