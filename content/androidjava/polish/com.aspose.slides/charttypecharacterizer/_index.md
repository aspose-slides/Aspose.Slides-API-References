---
title: ChartTypeCharacterizer
second_title: Aspose.Slides dla Androida - odniesienie API Java
description: Pomocnik do uzyskiwania dodatkowych informacji o wykresach i seriach na podstawie ich ChartType.
type: docs
url: /pl/com.aspose.slides/charttypecharacterizer/
---
**Dziedziczenie:**
java.lang.Object
```
public class ChartTypeCharacterizer
```

Pomocnik do uzyskiwania dodatkowych informacji o wykresach i seriach na podstawie ich ChartType.
## Konstruktory

| Konstruktor | Opis |
| --- | --- |
| [ChartTypeCharacterizer()](#ChartTypeCharacterizer--) |  |
## Metody

| Metoda | Opis |
| --- | --- |
| [isBar3DChart(int chartType)](#isBar3DChart-int-) | Zwraca true, jeśli chartType jest jednym z podtypów bar3DChart (kolumny lub słupki 3D). |
| [is2DChart(int chartType)](#is2DChart-int-) | Zwraca true, jeśli chartType jest jednym z typów wykresów 2D. |
| [is3DChart(int chartType)](#is3DChart-int-) | Zwraca true, jeśli chartType jest jednym z typów wykresów 3D. |
| [isChartTypeColumn(int chartType)](#isChartTypeColumn-int-) | Zwraca true, jeśli chartType jest jednym z podtypów Column. |
| [isChartTypeLine(int chartType)](#isChartTypeLine-int-) | Zwraca true, jeśli chartType jest jednym z podtypów Line. |
| [isChartTypePie(int chartType)](#isChartTypePie-int-) | Zwraca true, jeśli chartType jest jednym z podtypów Pie. |
| [isChartTypeBar(int chartType)](#isChartTypeBar-int-) | Zwraca true, jeśli chartType jest jednym z podtypów Bar. |
| [isChartTypeArea(int chartType)](#isChartTypeArea-int-) | Zwraca true, jeśli chartType jest jednym z podtypów Area. |
| [isChartTypeScatter(int chartType)](#isChartTypeScatter-int-) | Zwraca true, jeśli chartType jest jednym z podtypów Scatter. |
| [isChartTypeStock(int chartType)](#isChartTypeStock-int-) | Zwraca true, jeśli chartType jest jednym z podtypów Stock. |
| [isChartTypeSurface(int chartType)](#isChartTypeSurface-int-) | Zwraca true, jeśli chartType jest jednym z podtypów Surface. |
| [isChartTypeDoughnut(int chartType)](#isChartTypeDoughnut-int-) | Zwraca true, jeśli chartType jest jednym z podtypów Doughnut. |
| [isChartTypeBubble(int chartType)](#isChartTypeBubble-int-) | Zwraca true, jeśli chartType jest jednym z podtypów Bubble. |
| [isChartTypeRadar(int chartType)](#isChartTypeRadar-int-) | Zwraca true, jeśli chartType jest jednym z podtypów Radar. |
| [isSeriesUsesXValueCoordinate(int seriesType)](#isSeriesUsesXValueCoordinate-int-) | Zwraca, czy określony typ serii używa współrzędnych wartości X. |
| [isSeriesUsesYValueCoordinate(int seriesType)](#isSeriesUsesYValueCoordinate-int-) | Zwraca, czy określony typ serii używa współrzędnych wartości Y. |
| [isSeriesUsesValueCoordinate(int seriesType)](#isSeriesUsesValueCoordinate-int-) | Zwraca, czy określony typ serii używa współrzędnych wartości. |
| [isSeriesUsesBubbleSizeCoordinate(int seriesType)](#isSeriesUsesBubbleSizeCoordinate-int-) | Zwraca, czy współrzędne rozmiaru bąbelka mogą być użyte dla określonego typu serii. |
| [hasSeriesTrendLines(int seriesType)](#hasSeriesTrendLines-int-) | Zwraca, czy istnieją linie trendu serii dla określonego typu serii. |
| [isErrorBarsXAllowed(int seriesType)](#isErrorBarsXAllowed-int-) | Zwraca, czy dopuszczalne są słupki błędów X dla określonego typu serii. |
| [isErrorBarsYAllowed(int seriesType)](#isErrorBarsYAllowed-int-) | Zwraca, czy dopuszczalne są słupki błędów Y dla określonego typu serii. |
### ChartTypeCharacterizer() {#ChartTypeCharacterizer--}
```
public ChartTypeCharacterizer()
```


### isBar3DChart(int chartType) {#isBar3DChart-int-}
```
public static boolean isBar3DChart(int chartType)
```


Zwraca true, jeśli chartType jest jednym z podtypów bar3DChart (kolumny lub słupki 3D).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| chartType | int |  |

**Zwraca:**
boolean
### is2DChart(int chartType) {#is2DChart-int-}
```
public static boolean is2DChart(int chartType)
```


Zwraca true, jeśli chartType jest jednym z typów wykresów 2D.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| chartType | int |  |

**Zwraca:**
boolean
### is3DChart(int chartType) {#is3DChart-int-}
```
public static boolean is3DChart(int chartType)
```


Zwraca true, jeśli chartType jest jednym z typów wykresów 3D.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| chartType | int |  |

**Zwraca:**
boolean
### isChartTypeColumn(int chartType) {#isChartTypeColumn-int-}
```
public static boolean isChartTypeColumn(int chartType)
```


Zwraca true, jeśli chartType jest jednym z podtypów Column. Zestaw podtypów odpowiada odpowiedniemu zestawowi w PowerPoint (zobacz okno dialogowe „Change Chart Type” w PowerPoint): [ChartType.ClusteredColumn](../../com.aspose.slides/charttype\#ClusteredColumn), [ChartType.ClusteredColumn3D](../../com.aspose.slides/charttype\#ClusteredColumn3D), [ChartType.ClusteredCone](../../com.aspose.slides/charttype\#ClusteredCone), [ChartType.ClusteredCylinder](../../com.aspose.slides/charttype\#ClusteredCylinder), [ChartType.ClusteredPyramid](../../com.aspose.slides/charttype\#ClusteredPyramid), [ChartType.PercentsStackedColumn](../../com.aspose.slides/charttype\#PercentsStackedColumn), [ChartType.PercentsStackedColumn3D](../../com.aspose.slides/charttype\#PercentsStackedColumn3D), [ChartType.PercentsStackedCone](../../com.aspose.slides/charttype\#PercentsStackedCone), [ChartType.PercentsStackedCylinder](../../com.aspose.slides/charttype\#PercentsStackedCylinder), [ChartType.PercentsStackedPyramid](../../com.aspose.slides/charttype\#PercentsStackedPyramid), [ChartType.StackedColumn](../../com.aspose.slides/charttype\#StackedColumn), [ChartType.StackedColumn3D](../../com.aspose.slides/charttype\#StackedColumn3D), [ChartType.StackedCone](../../com.aspose.slides/charttype\#StackedCone), [ChartType.StackedCylinder](../../com.aspose.slides/charttype\#StackedCylinder), [ChartType.StackedPyramid](../../com.aspose.slides/charttype\#StackedPyramid), [ChartType.Column3D](../../com.aspose.slides/charttype\#Column3D), [ChartType.Cylinder3D](../../com.aspose.slides/charttype\#Cylinder3D), [ChartType.Cone3D](../../com.aspose.slides/charttype\#Cone3D), [ChartType.Pyramid3D](../../com.aspose.slides/charttype\#Pyramid3D).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| chartType | int |  |

**Zwraca:**
boolean
### isChartTypeLine(int chartType) {#isChartTypeLine-int-}
```
public static boolean isChartTypeLine(int chartType)
```


Zwraca true, jeśli chartType jest jednym z podtypów Line. Zestaw podtypów odpowiada odpowiedniemu zestawowi w PowerPoint (zobacz okno dialogowe „Change Chart Type” w PowerPoint): [ChartType.Line](../../com.aspose.slides/charttype\#Line), [ChartType.LineWithMarkers](../../com.aspose.slides/charttype\#LineWithMarkers), [ChartType.PercentsStackedLine](../../com.aspose.slides/charttype\#PercentsStackedLine), [ChartType.PercentsStackedLineWithMarkers](../../com.aspose.slides/charttype\#PercentsStackedLineWithMarkers), [ChartType.StackedLine](../../com.aspose.slides/charttype\#StackedLine), [ChartType.StackedLineWithMarkers](../../com.aspose.slides/charttype\#StackedLineWithMarkers), [ChartType.Line3D](../../com.aspose.slides/charttype\#Line3D).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| chartType | int |  |

**Zwraca:**
boolean
### isChartTypePie(int chartType) {#isChartTypePie-int-}
```
public static boolean isChartTypePie(int chartType)
```


Zwraca true, jeśli chartType jest jednym z podtypów Pie. Zestaw podtypów odpowiada odpowiedniemu zestawowi w PowerPoint (zobacz okno dialogowe „Change Chart Type” w PowerPoint): [ChartType.BarOfPie](../../com.aspose.slides/charttype\#BarOfPie), [ChartType.ExplodedPie](../../com.aspose.slides/charttype\#ExplodedPie), [ChartType.ExplodedPie3D](../../com.aspose.slides/charttype\#ExplodedPie3D), [ChartType.Pie](../../com.aspose.slides/charttype\#Pie), [ChartType.Pie3D](../../com.aspose.slides/charttype\#Pie3D), [ChartType.PieOfPie](../../com.aspose.slides/charttype\#PieOfPie).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| chartType | int |  |

**Zwraca:**
boolean
### isChartTypeBar(int chartType) {#isChartTypeBar-int-}
```
public static boolean isChartTypeBar(int chartType)
```


Zwraca true, jeśli chartType jest jednym z podtypów Bar. Zestaw podtypów odpowiada odpowiedniemu zestawowi w PowerPoint (zobacz okno dialogowe „Change Chart Type” w PowerPoint): [ChartType.ClusteredBar](../../com.aspose.slides/charttype\#ClusteredBar), [ChartType.ClusteredBar3D](../../com.aspose.slides/charttype\#ClusteredBar3D), [ChartType.PercentsStackedBar](../../com.aspose.slides/charttype\#PercentsStackedBar), [ChartType.PercentsStackedBar3D](../../com.aspose.slides/charttype\#PercentsStackedBar3D), [ChartType.StackedBar](../../com.aspose.slides/charttype\#StackedBar), [ChartType.StackedBar3D](../../com.aspose.slides/charttype\#StackedBar3D), [ChartType.ClusteredHorizontalCone](../../com.aspose.slides/charttype\#ClusteredHorizontalCone), [ChartType.ClusteredHorizontalCylinder](../../com.aspose.slides/charttype\#ClusteredHorizontalCylinder), [ChartType.ClusteredHorizontalPyramid](../../com.aspose.slides/charttype\#ClusteredHorizontalPyramid), [ChartType.StackedHorizontalCone](../../com.aspose.slides/charttype\#StackedHorizontalCone), [ChartType.StackedHorizontalCylinder](../../com.aspose.slides/charttype\#StackedHorizontalCylinder), [ChartType.StackedHorizontalPyramid](../../com.aspose.slides/charttype\#StackedHorizontalPyramid), [ChartType.PercentsStackedHorizontalCone](../../com.aspose.slides/charttype\#PercentsStackedHorizontalCone), [ChartType.PercentsStackedHorizontalCylinder](../../com.aspose.slides/charttype\#PercentsStackedHorizontalCylinder), [ChartType.PercentsStackedHorizontalPyramid](../../com.aspose.slides/charttype\#PercentsStackedHorizontalPyramid).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| chartType | int |  |

**Zwraca:**
boolean
### isChartTypeArea(int chartType) {#isChartTypeArea-int-}
```
public static boolean isChartTypeArea(int chartType)
```


Zwraca true, jeśli chartType jest jednym z podtypów Area. Zestaw podtypów odpowiada odpowiedniemu zestawowi w PowerPoint (zobacz okno dialogowe „Change Chart Type” w PowerPoint): [ChartType.Area](../../com.aspose.slides/charttype\#Area), [ChartType.PercentsStackedArea](../../com.aspose.slides/charttype\#PercentsStackedArea), [ChartType.PercentsStackedArea3D](../../com.aspose.slides/charttype\#PercentsStackedArea3D), [ChartType.StackedArea](../../com.aspose.slides/charttype\#StackedArea), [ChartType.StackedArea3D](../../com.aspose.slides/charttype\#StackedArea3D), [ChartType.Area3D](../../com.aspose.slides/charttype\#Area3D).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| chartType | int |  |

**Zwraca:**
boolean
### isChartTypeScatter(int chartType) {#isChartTypeScatter-int-}
```
public static boolean isChartTypeScatter(int chartType)
```


Zwraca true, jeśli chartType jest jednym z podtypów Scatter. Zestaw podtypów odpowiada odpowiedniemu zestawowi w PowerPoint (zobacz okno dialogowe „Change Chart Type” w PowerPoint): [ChartType.ScatterWithMarkers](../../com.aspose.slides/charttype\#ScatterWithMarkers), [ChartType.ScatterWithSmoothLines](../../com.aspose.slides/charttype\#ScatterWithSmoothLines), [ChartType.ScatterWithSmoothLinesAndMarkers](../../com.aspose.slides/charttype\#ScatterWithSmoothLinesAndMarkers), [ChartType.ScatterWithStraightLines](../../com.aspose.slides/charttype\#ScatterWithStraightLines), [ChartType.ScatterWithStraightLinesAndMarkers](../../com.aspose.slides/charttype\#ScatterWithStraightLinesAndMarkers).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| chartType | int |  |

**Zwraca:**
boolean
### isChartTypeStock(int chartType) {#isChartTypeStock-int-}
```
public static boolean isChartTypeStock(int chartType)
```


Zwraca true, jeśli chartType jest jednym z podtypów Stock. Zestaw podtypów odpowiada odpowiedniemu zestawowi w PowerPoint (zobacz okno dialogowe „Change Chart Type” w PowerPoint): [ChartType.HighLowClose](../../com.aspose.slides/charttype\#HighLowClose), [ChartType.OpenHighLowClose](../../com.aspose.slides/charttype\#OpenHighLowClose), [ChartType.VolumeHighLowClose](../../com.aspose.slides/charttype\#VolumeHighLowClose), [ChartType.VolumeOpenHighLowClose](../../com.aspose.slides/charttype\#VolumeOpenHighLowClose).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| chartType | int |  |

**Zwraca:**
boolean
### isChartTypeSurface(int chartType) {#isChartTypeSurface-int-}
```
public static boolean isChartTypeSurface(int chartType)
```


Zwraca true, jeśli chartType jest jednym z podtypów Surface. Zestaw podtypów odpowiada odpowiedniemu zestawowi w PowerPoint (zobacz okno dialogowe „Change Chart Type” w PowerPoint): [ChartType.Surface3D](../../com.aspose.slides/charttype\#Surface3D), [ChartType.WireframeSurface3D](../../com.aspose.slides/charttype\#WireframeSurface3D), [ChartType.Contour](../../com.aspose.slides/charttype\#Contour), [ChartType.WireframeContour](../../com.aspose.slides/charttype\#WireframeContour).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| chartType | int |  |

**Zwraca:**
boolean
### isChartTypeDoughnut(int chartType) {#isChartTypeDoughnut-int-}
```
public static boolean isChartTypeDoughnut(int chartType)
```


Zwraca true, jeśli chartType jest jednym z podtypów Doughnut. Zestaw podtypów odpowiada odpowiedniemu zestawowi w PowerPoint (zobacz okno dialogowe „Change Chart Type” w PowerPoint): [ChartType.Doughnut](../../com.aspose.slides/charttype\#Doughnut), [ChartType.ExplodedDoughnut](../../com.aspose.slides/charttype\#ExplodedDoughnut).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| chartType | int |  |

**Zwraca:**
boolean
### isChartTypeBubble(int chartType) {#isChartTypeBubble-int-}
```
public static boolean isChartTypeBubble(int chartType)
```


Zwraca true, jeśli chartType jest jednym z podtypów Bubble. Zestaw podtypów odpowiada odpowiedniemu zestawowi w PowerPoint (zobacz okno dialogowe „Change Chart Type” w PowerPoint): [ChartType.Bubble](../../com.aspose.slides/charttype\#Bubble), [ChartType.BubbleWith3D](../../com.aspose.slides/charttype\#BubbleWith3D).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| chartType | int |  |

**Zwraca:**
boolean
### isChartTypeRadar(int chartType) {#isChartTypeRadar-int-}
```
public static boolean isChartTypeRadar(int chartType)
```


Zwraca true, jeśli chartType jest jednym z podtypów Radar. Zestaw podtypów odpowiada odpowiedniemu zestawowi w PowerPoint (zobacz okno dialogowe „Change Chart Type” w PowerPoint): [ChartType.FilledRadar](../../com.aspose.slides/charttype\#FilledRadar), [ChartType.Radar](../../com.aspose.slides/charttype\#Radar), [ChartType.RadarWithMarkers](../../com.aspose.slides/charttype\#RadarWithMarkers).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| chartType | int |  |

**Zwraca:**
boolean
### isSeriesUsesXValueCoordinate(int seriesType) {#isSeriesUsesXValueCoordinate-int-}
```
public static boolean isSeriesUsesXValueCoordinate(int seriesType)
```


Zwraca, czy określony typ serii używa współrzędnych wartości X.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| seriesType | int | Typ serii. |

**Zwraca:**
boolean - True jeśli używa, w przeciwnym razie false.
### isSeriesUsesYValueCoordinate(int seriesType) {#isSeriesUsesYValueCoordinate-int-}
```
public static boolean isSeriesUsesYValueCoordinate(int seriesType)
```


Zwraca, czy określony typ serii używa współrzędnych wartości Y.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| seriesType | int | Typ serii. |

**Zwraca:**
boolean - True jeśli używa, w przeciwnym razie false.
### isSeriesUsesValueCoordinate(int seriesType) {#isSeriesUsesValueCoordinate-int-}
```
public static boolean isSeriesUsesValueCoordinate(int seriesType)
```


Zwraca, czy określony typ serii używa współrzędnych wartości.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| seriesType | int | Typ serii. |

**Zwraca:**
boolean - True jeśli używa, w przeciwnym razie false.
### isSeriesUsesBubbleSizeCoordinate(int seriesType) {#isSeriesUsesBubbleSizeCoordinate-int-}
```
public static boolean isSeriesUsesBubbleSizeCoordinate(int seriesType)
```


Zwraca, czy współrzędne rozmiaru bąbelka mogą być użyte dla określonego typu serii.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| seriesType | int | Typ serii. |

**Zwraca:**
boolean - True jeśli może być użyte, w przeciwnym razie false.
### hasSeriesTrendLines(int seriesType) {#hasSeriesTrendLines-int-}
```
public static boolean hasSeriesTrendLines(int seriesType)
```


Zwraca, czy istnieją linie trendu serii dla określonego typu serii.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| seriesType | int | Typ serii. |

**Zwraca:**
boolean - True jeśli istnieją, w przeciwnym razie false.
### isErrorBarsXAllowed(int seriesType) {#isErrorBarsXAllowed-int-}
```
public static boolean isErrorBarsXAllowed(int seriesType)
```


Zwraca, czy słupki błędów X są dozwolone dla określonego typu serii.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| seriesType | int | Typ serii. |

**Zwraca:**
boolean - True jeśli dozwolone, w przeciwnym razie false.
### isErrorBarsYAllowed(int seriesType) {#isErrorBarsYAllowed-int-}
```
public static boolean isErrorBarsYAllowed(int seriesType)
```


Zwraca, czy słupki błędów Y są dozwolone dla określonego typu serii.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| seriesType | int | Typ serii. |

**Zwraca:**
boolean - True jeśli dozwolone, w przeciwnym razie false.