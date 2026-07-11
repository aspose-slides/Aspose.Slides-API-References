---
title: ChartTypeCharacterizer
second_title: Aspose.Slides для Android через Java API Справка
description: Помощник для получения дополнительной информации о диаграммах и рядах по их ChartType.
type: docs
url: /ru/com.aspose.slides/charttypecharacterizer/
---
**Наследование:**
java.lang.Object
```
public class ChartTypeCharacterizer
```

Вспомогательный класс для получения дополнительной информации о диаграммах и сериях по их ChartType.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [ChartTypeCharacterizer()](#ChartTypeCharacterizer--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [isBar3DChart(int chartType)](#isBar3DChart-int-) | Возвращает true, если chartType является одним из подтипов bar3DChart (3D столбцы или полосы). |
| [is2DChart(int chartType)](#is2DChart-int-) | Возвращает true, если chartType является одним из 2D типов диаграмм. |
| [is3DChart(int chartType)](#is3DChart-int-) | Возвращает true, если chartType является одним из 3D типов диаграмм. |
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
| [isSeriesUsesXValueCoordinate(int seriesType)](#isSeriesUsesXValueCoordinate-int-) | Возвращает, использует ли указанный тип серии координаты значений X. |
| [isSeriesUsesYValueCoordinate(int seriesType)](#isSeriesUsesYValueCoordinate-int-) | Возвращает, использует ли указанный тип серии координаты значений Y. |
| [isSeriesUsesValueCoordinate(int seriesType)](#isSeriesUsesValueCoordinate-int-) | Возвращает, использует ли указанный тип серии координаты значений. |
| [isSeriesUsesBubbleSizeCoordinate(int seriesType)](#isSeriesUsesBubbleSizeCoordinate-int-) | Возвращает, могут ли координаты размера пузыря использоваться для указанного типа серии. |
| [hasSeriesTrendLines(int seriesType)](#hasSeriesTrendLines-int-) | Возвращает, существуют ли линии тренда серии для указанного типа серии. |
| [isErrorBarsXAllowed(int seriesType)](#isErrorBarsXAllowed-int-) | Возвращает, разрешены ли линии ошибок X для указанного типа серии. |
| [isErrorBarsYAllowed(int seriesType)](#isErrorBarsYAllowed-int-) | Возвращает, разрешены ли линии ошибок Y для указанного типа серии. |
### ChartTypeCharacterizer() {#ChartTypeCharacterizer--}
```
public ChartTypeCharacterizer()
```


### isBar3DChart(int chartType) {#isBar3DChart-int-}
```
public static boolean isBar3DChart(int chartType)
```


Возвращает true, если chartType является одним из подтипов bar3DChart (3D столбцы или полосы).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| chartType | int |  |

**Возвращаемое значение:**
boolean
### is2DChart(int chartType) {#is2DChart-int-}
```
public static boolean is2DChart(int chartType)
```


Возвращает true, если chartType является одним из 2D типов диаграмм.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| chartType | int |  |

**Возвращаемое значение:**
boolean
### is3DChart(int chartType) {#is3DChart-int-}
```
public static boolean is3DChart(int chartType)
```


Возвращает true, если chartType является одним из 3D типов диаграмм.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| chartType | int |  |

**Возвращаемое значение:**
boolean
### isChartTypeColumn(int chartType) {#isChartTypeColumn-int-}
```
public static boolean isChartTypeColumn(int chartType)
```


Возвращает true, если chartType является одним из подтипов Column. Набор подтипов соответствует соответствующему набору в PowerPoint (см. диалог "Change Chart Type" в PowerPoint): [ChartType.ClusteredColumn](../../com.aspose.slides/charttype\#ClusteredColumn), [ChartType.ClusteredColumn3D](../../com.aspose.slides/charttype\#ClusteredColumn3D), [ChartType.ClusteredCone](../../com.aspose.slides/charttype\#ClusteredCone), [ChartType.ClusteredCylinder](../../com.aspose.slides/charttype\#ClusteredCylinder), [ChartType.ClusteredPyramid](../../com.aspose.slides/charttype\#ClusteredPyramid), [ChartType.PercentsStackedColumn](../../com.aspose.slides/charttype\#PercentsStackedColumn), [ChartType.PercentsStackedColumn3D](../../com.aspose.slides/charttype\#PercentsStackedColumn3D), [ChartType.PercentsStackedCone](../../com.aspose.slides/charttype\#PercentsStackedCone), [ChartType.PercentsStackedCylinder](../../com.aspose.slides/charttype\#PercentsStackedCylinder), [ChartType.PercentsStackedPyramid](../../com.aspose.slides/charttype\#PercentsStackedPyramid), [ChartType.StackedColumn](../../com.aspose.slides/charttype\#StackedColumn), [ChartType.StackedColumn3D](../../com.aspose.slides/charttype\#StackedColumn3D), [ChartType.StackedCone](../../com.aspose.slides/charttype\#StackedCone), [ChartType.StackedCylinder](../../com.aspose.slides/charttype\#StackedCylinder), [ChartType.StackedPyramid](../../com.aspose.slides/charttype\#StackedPyramid), [ChartType.Column3D](../../com.aspose.slides/charttype\#Column3D), [ChartType.Cylinder3D](../../com.aspose.slides/charttype\#Cylinder3D), [ChartType.Cone3D](../../com.aspose.slides/charttype\#Cone3D), [ChartType.Pyramid3D](../../com.aspose.slides/charttype\#Pyramid3D).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| chartType | int |  |

**Возвращаемое значение:**
boolean
### isChartTypeLine(int chartType) {#isChartTypeLine-int-}
```
public static boolean isChartTypeLine(int chartType)
```


Возвращает true, если chartType является одним из подтипов Line. Набор подтипов соответствует соответствующему набору в PowerPoint (см. диалог "Change Chart Type" в PowerPoint): [ChartType.Line](../../com.aspose.slides/charttype\#Line), [ChartType.LineWithMarkers](../../com.aspose.slides/charttype\#LineWithMarkers), [ChartType.PercentsStackedLine](../../com.aspose.slides/charttype\#PercentsStackedLine), [ChartType.PercentsStackedLineWithMarkers](../../com.aspose.slides/charttype\#PercentsStackedLineWithMarkers), [ChartType.StackedLine](../../com.aspose.slides/charttype\#StackedLine), [ChartType.StackedLineWithMarkers](../../com.aspose.slides/charttype\#StackedLineWithMarkers), [ChartType.Line3D](../../com.aspose.slides/charttype\#Line3D).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| chartType | int |  |

**Возвращаемое значение:**
boolean
### isChartTypePie(int chartType) {#isChartTypePie-int-}
```
public static boolean isChartTypePie(int chartType)
```


Возвращает true, если chartType является одним из подтипов Pie. Набор подтипов соответствует соответствующему набору в PowerPoint (см. диалог "Change Chart Type" в PowerPoint): [ChartType.BarOfPie](../../com.aspose.slides/charttype\#BarOfPie), [ChartType.ExplodedPie](../../com.aspose.slides/charttype\#ExplodedPie), [ChartType.ExplodedPie3D](../../com.aspose.slides/charttype\#ExplodedPie3D), [ChartType.Pie](../../com.aspose.slides/charttype\#Pie), [ChartType.Pie3D](../../com.aspose.slides/charttype\#Pie3D), [ChartType.PieOfPie](../../com.aspose.slides/charttype\#PieOfPie).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| chartType | int |  |

**Возвращаемое значение:**
boolean
### isChartTypeBar(int chartType) {#isChartTypeBar-int-}
```
public static boolean isChartTypeBar(int chartType)
```


Возвращает true, если chartType является одним из подтипов Bar. Набор подтипов соответствует соответствующему набору в PowerPoint (см. диалог "Change Chart Type" в PowerPoint): [ChartType.ClusteredBar](../../com.aspose.slides/charttype\#ClusteredBar), [ChartType.ClusteredBar3D](../../com.aspose.slides/charttype\#ClusteredBar3D), [ChartType.PercentsStackedBar](../../com.aspose.slides/charttype\#PercentsStackedBar), [ChartType.PercentsStackedBar3D](../../com.aspose.slides/charttype\#PercentsStackedBar3D), [ChartType.StackedBar](../../com.aspose.slides/charttype\#StackedBar), [ChartType.StackedBar3D](../../com.aspose.slides/charttype\#StackedBar3D), [ChartType.ClusteredHorizontalCone](../../com.aspose.slides/charttype\#ClusteredHorizontalCone), [ChartType.ClusteredHorizontalCylinder](../../com.aspose.slides/charttype\#ClusteredHorizontalCylinder), [ChartType.ClusteredHorizontalPyramid](../../com.aspose.slides/charttype\#ClusteredHorizontalPyramid), [ChartType.StackedHorizontalCone](../../com.aspose.slides/charttype\#StackedHorizontalCone), [ChartType.StackedHorizontalCylinder](../../com.aspose.slides/charttype\#StackedHorizontalCylinder), [ChartType.StackedHorizontalPyramid](../../com.aspose.slides/charttype\#StackedHorizontalPyramid), [ChartType.PercentsStackedHorizontalCone](../../com.aspose.slides/charttype\#PercentsStackedHorizontalCone), [ChartType.PercentsStackedHorizontalCylinder](../../com.aspose.slides/charttype\#PercentsStackedHorizontalCylinder), [ChartType.PercentsStackedHorizontalPyramid](../../com.aspose.slides/charttype\#PercentsStackedHorizontalPyramid).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| chartType | int |  |

**Возвращаемое значение:**
boolean
### isChartTypeArea(int chartType) {#isChartTypeArea-int-}
```
public static boolean isChartTypeArea(int chartType)
```


Возвращает true, если chartType является одним из подтипов Area. Набор подтипов соответствует соответствующему набору в PowerPoint (см. диалог "Change Chart Type" в PowerPoint): [ChartType.Area](../../com.aspose.slides/charttype\#Area), [ChartType.PercentsStackedArea](../../com.aspose.slides/charttype\#PercentsStackedArea), [ChartType.PercentsStackedArea3D](../../com.aspose.slides/charttype\#PercentsStackedArea3D), [ChartType.StackedArea](../../com.aspose.slides/charttype\#StackedArea), [ChartType.StackedArea3D](../../com.aspose.slides/charttype\#StackedArea3D), [ChartType.Area3D](../../com.aspose.slides/charttype\#Area3D).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| chartType | int |  |

**Возвращаемое значение:**
boolean
### isChartTypeScatter(int chartType) {#isChartTypeScatter-int-}
```
public static boolean isChartTypeScatter(int chartType)
```


Возвращает true, если chartType является одним из подтипов Scatter. Набор подтипов соответствует соответствующему набору в PowerPoint (см. диалог "Change Chart Type" в PowerPoint): [ChartType.ScatterWithMarkers](../../com.aspose.slides/charttype\#ScatterWithMarkers), [ChartType.ScatterWithSmoothLines](../../com.aspose.slides/charttype\#ScatterWithSmoothLines), [ChartType.ScatterWithSmoothLinesAndMarkers](../../com.aspose.slides/charttype\#ScatterWithSmoothLinesAndMarkers), [ChartType.ScatterWithStraightLines](../../com.aspose.slides/charttype\#ScatterWithStraightLines), [ChartType.ScatterWithStraightLinesAndMarkers](../../com.aspose.slides/charttype\#ScatterWithStraightLinesAndMarkers).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| chartType | int |  |

**Возвращаемое значение:**
boolean
### isChartTypeStock(int chartType) {#isChartTypeStock-int-}
```
public static boolean isChartTypeStock(int chartType)
```


Возвращает true, если chartType является одним из подтипов Stock. Набор подтипов соответствует соответствующему набору в PowerPoint (см. диалог "Change Chart Type" в PowerPoint): [ChartType.HighLowClose](../../com.aspose.slides/charttype\#HighLowClose), [ChartType.OpenHighLowClose](../../com.aspose.slides/charttype\#OpenHighLowClose), [ChartType.VolumeHighLowClose](../../com.aspose.slides/charttype\#VolumeHighLowClose), [ChartType.VolumeOpenHighLowClose](../../com.aspose.slides/charttype\#VolumeOpenHighLowClose).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| chartType | int |  |

**Возвращаемое значение:**
boolean
### isChartTypeSurface(int chartType) {#isChartTypeSurface-int-}
```
public static boolean isChartTypeSurface(int chartType)
```


Возвращает true, если chartType является одним из подтипов Surface. Набор подтипов соответствует соответствующему набору в PowerPoint (см. диалог "Change Chart Type" в PowerPoint): [ChartType.Surface3D](../../com.aspose.slides/charttype\#Surface3D), [ChartType.WireframeSurface3D](../../com.aspose.slides/charttype\#WireframeSurface3D), [ChartType.Contour](../../com.aspose.slides/charttype\#Contour), [ChartType.WireframeContour](../../com.aspose.slides/charttype\#WireframeContour).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| chartType | int |  |

**Возвращаемое значение:**
boolean
### isChartTypeDoughnut(int chartType) {#isChartTypeDoughnut-int-}
```
public static boolean isChartTypeDoughnut(int chartType)
```


Возвращает true, если chartType является одним из подтипов Doughnut. Набор подтипов соответствует соответствующему набору в PowerPoint (см. диалог "Change Chart Type" в PowerPoint): [ChartType.Doughnut](../../com.aspose.slides/charttype\#Doughnut), [ChartType.ExplodedDoughnut](../../com.aspose.slides/charttype\#ExplodedDoughnut).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| chartType | int |  |

**Возвращаемое значение:**
boolean
### isChartTypeBubble(int chartType) {#isChartTypeBubble-int-}
```
public static boolean isChartTypeBubble(int chartType)
```


Возвращает true, если chartType является одним из подтипов Bubble. Набор подтипов соответствует соответствующему набору в PowerPoint (см. диалог "Change Chart Type" в PowerPoint): [ChartType.Bubble](../../com.aspose.slides/charttype\#Bubble), [ChartType.BubbleWith3D](../../com.aspose.slides/charttype\#BubbleWith3D).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| chartType | int |  |

**Возвращаемое значение:**
boolean
### isChartTypeRadar(int chartType) {#isChartTypeRadar-int-}
```
public static boolean isChartTypeRadar(int chartType)
```


Возвращает true, если chartType является одним из подтипов Radar. Набор подтипов соответствует соответствующему набору в PowerPoint (см. диалог "Change Chart Type" в PowerPoint): [ChartType.FilledRadar](../../com.aspose.slides/charttype\#FilledRadar), [ChartType.Radar](../../com.aspose.slides/charttype\#Radar), [ChartType.RadarWithMarkers](../../com.aspose.slides/charttype\#RadarWithMarkers).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| chartType | int |  |

**Возвращаемое значение:**
boolean
### isSeriesUsesXValueCoordinate(int seriesType) {#isSeriesUsesXValueCoordinate-int-}
```
public static boolean isSeriesUsesXValueCoordinate(int seriesType)
```


Возвращает, использует ли указанный тип серии координаты значений X.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| seriesType | int | Series type. |

**Возвращаемое значение:**
boolean - True if uses otherwise false.
### isSeriesUsesYValueCoordinate(int seriesType) {#isSeriesUsesYValueCoordinate-int-}
```
public static boolean isSeriesUsesYValueCoordinate(int seriesType)
```


Возвращает, использует ли указанный тип серии координаты значений Y.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| seriesType | int | Series type. |

**Возвращаемое значение:**
boolean - True if uses otherwise false.
### isSeriesUsesValueCoordinate(int seriesType) {#isSeriesUsesValueCoordinate-int-}
```
public static boolean isSeriesUsesValueCoordinate(int seriesType)
```


Возвращает, использует ли указанный тип серии координаты значений.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| seriesType | int | Series type. |

**Возвращаемое значение:**
boolean - True if uses otherwise false.
### isSeriesUsesBubbleSizeCoordinate(int seriesType) {#isSeriesUsesBubbleSizeCoordinate-int-}
```
public static boolean isSeriesUsesBubbleSizeCoordinate(int seriesType)
```


Возвращает, могут ли координаты размера пузыря использоваться для указанного типа серии.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| seriesType | int | Series type. |

**Возвращаемое значение:**
boolean - True if can be used, otherwise false.
### hasSeriesTrendLines(int seriesType) {#hasSeriesTrendLines-int-}
```
public static boolean hasSeriesTrendLines(int seriesType)
```


Возвращает, существуют ли линии тренда серии для указанного типа серии.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| seriesType | int | Series type. |

**Возвращаемое значение:**
boolean - True if present otherwise false.
### isErrorBarsXAllowed(int seriesType) {#isErrorBarsXAllowed-int-}
```
public static boolean isErrorBarsXAllowed(int seriesType)
```


Возвращает, разрешены ли линии ошибок X для указанного типа серии.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| seriesType | int | Series type. |

**Возвращаемое значение:**
boolean - True if allowed, otherwise false.
### isErrorBarsYAllowed(int seriesType) {#isErrorBarsYAllowed-int-}
```
public static boolean isErrorBarsYAllowed(int seriesType)
```


Возвращает, разрешены ли линии ошибок Y для указанного типа серии.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| seriesType | int | Series type. |

**Возвращаемое значение:**
boolean - True if allowed, otherwise false.