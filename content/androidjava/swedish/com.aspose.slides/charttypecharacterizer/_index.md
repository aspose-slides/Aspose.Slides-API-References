---
title: ChartTypeCharacterizer
second_title: Aspose.Slides för Android via Java API-referens
description: Hjälp för att hämta ytterligare information om diagram och serier via dess ChartType.
type: docs
url: /sv/com.aspose.slides/charttypecharacterizer/
---
**Arv:**
java.lang.Object
```
public class ChartTypeCharacterizer
```

Hjälp för att hämta ytterligare information om diagram och serier via sin ChartType.
## Konstruktorer

| Konstruktor | Beskrivning |
| --- | --- |
| [ChartTypeCharacterizer()](#ChartTypeCharacterizer--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [isBar3DChart(int chartType)](#isBar3DChart-int-) | Returnerar true om chartType är en av bar3DChart-undertyperna (3D-kolumner eller staplar). |
| [is2DChart(int chartType)](#is2DChart-int-) | Returnerar true om chartType är en av 2D-diagramtyperna. |
| [is3DChart(int chartType)](#is3DChart-int-) | Returnerar true om chartType är en av 3D-diagramtyperna. |
| [isChartTypeColumn(int chartType)](#isChartTypeColumn-int-) | Returnerar true om chartType är en av Column-undertyperna. |
| [isChartTypeLine(int chartType)](#isChartTypeLine-int-) | Returnerar true om chartType är en av Line-undertyperna. |
| [isChartTypePie(int chartType)](#isChartTypePie-int-) | Returnerar true om chartType är en av Pie-undertyperna. |
| [isChartTypeBar(int chartType)](#isChartTypeBar-int-) | Returnerar true om chartType är en av Bar-undertyperna. |
| [isChartTypeArea(int chartType)](#isChartTypeArea-int-) | Returnerar true om chartType är en av Area-undertyperna. |
| [isChartTypeScatter(int chartType)](#isChartTypeScatter-int-) | Returnerar true om chartType är en av Scatter-undertyperna. |
| [isChartTypeStock(int chartType)](#isChartTypeStock-int-) | Returnerar true om chartType är en av Stock-undertyperna. |
| [isChartTypeSurface(int chartType)](#isChartTypeSurface-int-) | Returnerar true om chartType är en av Surface-undertyperna. |
| [isChartTypeDoughnut(int chartType)](#isChartTypeDoughnut-int-) | Returnerar true om chartType är en av Doughnut-undertyperna. |
| [isChartTypeBubble(int chartType)](#isChartTypeBubble-int-) | Returnerar true om chartType är en av Bubble-undertyperna. |
| [isChartTypeRadar(int chartType)](#isChartTypeRadar-int-) | Returnerar true om chartType är en av Radar-undertyperna. |
| [isSeriesUsesXValueCoordinate(int seriesType)](#isSeriesUsesXValueCoordinate-int-) | Returnerar om den angivna serietypen använder X-värdekoordinater. |
| [isSeriesUsesYValueCoordinate(int seriesType)](#isSeriesUsesYValueCoordinate-int-) | Returnerar om den angivna serietypen använder Y-värdekoordinater. |
| [isSeriesUsesValueCoordinate(int seriesType)](#isSeriesUsesValueCoordinate-int-) | Returnerar om den angivna serietypen använder värdekoordinater. |
| [isSeriesUsesBubbleSizeCoordinate(int seriesType)](#isSeriesUsesBubbleSizeCoordinate-int-) | Returnerar om bubbelstorlekskoordinater kan användas för den angivna serietypen. |
| [hasSeriesTrendLines(int seriesType)](#hasSeriesTrendLines-int-) | Returnerar om det finns trendlinjer för den angivna serietypen. |
| [isErrorBarsXAllowed(int seriesType)](#isErrorBarsXAllowed-int-) | Returnerar om felstaplar X är tillåtna för den angivna serietypen. |
| [isErrorBarsYAllowed(int seriesType)](#isErrorBarsYAllowed-int-) | Returnerar om felstaplar Y är tillåtna för den angivna serietypen. |
### ChartTypeCharacterizer() {#ChartTypeCharacterizer--}
```
public ChartTypeCharacterizer()
```


### isBar3DChart(int chartType) {#isBar3DChart-int-}
```
public static boolean isBar3DChart(int chartType)
```


Returnerar true om chartType är en av bar3DChart-undertyperna (3D-kolumner eller staplar).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| chartType | int |  |

**Returnerar:**
boolean
### is2DChart(int chartType) {#is2DChart-int-}
```
public static boolean is2DChart(int chartType)
```


Returnerar true om chartType är en av 2D-diagramtyperna.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| chartType | int |  |

**Returnerar:**
boolean
### is3DChart(int chartType) {#is3DChart-int-}
```
public static boolean is3DChart(int chartType)
```


Returnerar true om chartType är en av 3D-diagramtyperna.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| chartType | int |  |

**Returnerar:**
boolean
### isChartTypeColumn(int chartType) {#isChartTypeColumn-int-}
```
public static boolean isChartTypeColumn(int chartType)
```


Returnerar true om chartType är en av Column-undertyperna. Undertypsuppsättningen motsvarar den lämpliga uppsättningen i PowerPoint (se dialogrutan "Change Chart Type" i PowerPoint): [ChartType.ClusteredColumn](../../com.aspose.slides/charttype\#ClusteredColumn), [ChartType.ClusteredColumn3D](../../com.aspose.slides/charttype\#ClusteredColumn3D), [ChartType.ClusteredCone](../../com.aspose.slides/charttype\#ClusteredCone), [ChartType.ClusteredCylinder](../../com.aspose.slides/charttype\#ClusteredCylinder), [ChartType.ClusteredPyramid](../../com.aspose.slides/charttype\#ClusteredPyramid), [ChartType.PercentsStackedColumn](../../com.aspose.slides/charttype\#PercentsStackedColumn), [ChartType.PercentsStackedColumn3D](../../com.aspose.slides/charttype\#PercentsStackedColumn3D), [ChartType.PercentsStackedCone](../../com.aspose.slides/charttype\#PercentsStackedCone), [ChartType.PercentsStackedCylinder](../../com.aspose.slides/charttype\#PercentsStackedCylinder), [ChartType.PercentsStackedPyramid](../../com.aspose.slides/charttype\#PercentsStackedPyramid), [ChartType.StackedColumn](../../com.aspose.slides/charttype\#StackedColumn), [ChartType.StackedColumn3D](../../com.aspose.slides/charttype\#StackedColumn3D), [ChartType.StackedCone](../../com.aspose.slides/charttype\#StackedCone), [ChartType.StackedCylinder](../../com.aspose.slides/charttype\#StackedCylinder), [ChartType.StackedPyramid](../../com.aspose.slides/charttype\#StackedPyramid), [ChartType.Column3D](../../com.aspose.slides/charttype\#Column3D), [ChartType.Cylinder3D](../../com.aspose.slides/charttype\#Cylinder3D), [ChartType.Cone3D](../../com.aspose.slides/charttype\#Cone3D), [ChartType.Pyramid3D](../../com.aspose.slides/charttype\#Pyramid3D).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| chartType | int |  |

**Returnerar:**
boolean
### isChartTypeLine(int chartType) {#isChartTypeLine-int-}
```
public static boolean isChartTypeLine(int chartType)
```


Returnerar true om chartType är en av Line-undertyperna. Undertypsuppsättningen motsvarar den lämpliga uppsättningen i PowerPoint (se dialogrutan "Change Chart Type" i PowerPoint): [ChartType.Line](../../com.aspose.slides/charttype\#Line), [ChartType.LineWithMarkers](../../com.aspose.slides/charttype\#LineWithMarkers), [ChartType.PercentsStackedLine](../../com.aspose.slides/charttype\#PercentsStackedLine), [ChartType.PercentsStackedLineWithMarkers](../../com.aspose.slides/charttype\#PercentsStackedLineWithMarkers), [ChartType.StackedLine](../../com.aspose.slides/charttype\#StackedLine), [ChartType.StackedLineWithMarkers](../../com.aspose.slides/charttype\#StackedLineWithMarkers), [ChartType.Line3D](../../com.aspose.slides/charttype\#Line3D).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| chartType | int |  |

**Returnerar:**
boolean
### isChartTypePie(int chartType) {#isChartTypePie-int-}
```
public static boolean isChartTypePie(int chartType)
```


Returnerar true om chartType är en av Pie-undertyperna. Undertypsuppsättningen motsvarar den lämpliga uppsättningen i PowerPoint (se dialogrutan "Change Chart Type" i PowerPoint): [ChartType.BarOfPie](../../com.aspose.slides/charttype\#BarOfPie), [ChartType.ExplodedPie](../../com.aspose.slides/charttype\#ExplodedPie), [ChartType.ExplodedPie3D](../../com.aspose.slides/charttype\#ExplodedPie3D), [ChartType.Pie](../../com.aspose.slides/charttype\#Pie), [ChartType.Pie3D](../../com.aspose.slides/charttype\#Pie3D), [ChartType.PieOfPie](../../com.aspose.slides/charttype\#PieOfPie).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| chartType | int |  |

**Returnerar:**
boolean
### isChartTypeBar(int chartType) {#isChartTypeBar-int-}
```
public static boolean isChartTypeBar(int chartType)
```


Returnerar true om chartType är en av Bar-undertyperna. Undertypsuppsättningen motsvarar den lämpliga uppsättningen i PowerPoint (se dialogrutan "Change Chart Type" i PowerPoint): [ChartType.ClusteredBar](../../com.aspose.slides/charttype\#ClusteredBar), [ChartType.ClusteredBar3D](../../com.aspose.slides/charttype\#ClusteredBar3D), [ChartType.PercentsStackedBar](../../com.aspose.slides/charttype\#PercentsStackedBar), [ChartType.PercentsStackedBar3D](../../com.aspose.slides/charttype\#PercentsStackedBar3D), [ChartType.StackedBar](../../com.aspose.slides/charttype\#StackedBar), [ChartType.StackedBar3D](../../com.aspose.slides/charttype\#StackedBar3D), [ChartType.ClusteredHorizontalCone](../../com.aspose.slides/charttype\#ClusteredHorizontalCone), [ChartType.ClusteredHorizontalCylinder](../../com.aspose.slides/charttype\#ClusteredHorizontalCylinder), [ChartType.ClusteredHorizontalPyramid](../../com.aspose.slides/charttype\#ClusteredHorizontalPyramid), [ChartType.StackedHorizontalCone](../../com.aspose.slides/charttype\#StackedHorizontalCone), [ChartType.StackedHorizontalCylinder](../../com.aspose.slides/charttype\#StackedHorizontalCylinder), [ChartType.StackedHorizontalPyramid](../../com.aspose.slides/charttype\#StackedHorizontalPyramid), [ChartType.PercentsStackedHorizontalCone](../../com.aspose.slides/charttype\#PercentsStackedHorizontalCone), [ChartType.PercentsStackedHorizontalCylinder](../../com.aspose.slides/charttype\#PercentsStackedHorizontalCylinder), [ChartType.PercentsStackedHorizontalPyramid](../../com.aspose.slides/charttype\#PercentsStackedHorizontalPyramid).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| chartType | int |  |

**Returnerar:**
boolean
### isChartTypeArea(int chartType) {#isChartTypeArea-int-}
```
public static boolean isChartTypeArea(int chartType)
```


Returnerar true om chartType är en av Area-undertyperna. Undertypsuppsättningen motsvarar den lämpliga uppsättningen i PowerPoint (se dialogrutan "Change Chart Type" i PowerPoint): [ChartType.Area](../../com.aspose.slides/charttype\#Area), [ChartType.PercentsStackedArea](../../com.aspose.slides/charttype\#PercentsStackedArea), [ChartType.PercentsStackedArea3D](../../com.aspose.slides/charttype\#PercentsStackedArea3D), [ChartType.StackedArea](../../com.aspose.slides/charttype\#StackedArea), [ChartType.StackedArea3D](../../com.aspose.slides/charttype\#StackedArea3D), [ChartType.Area3D](../../com.aspose.slides/charttype\#Area3D).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| chartType | int |  |

**Returnerar:**
boolean
### isChartTypeScatter(int chartType) {#isChartTypeScatter-int-}
```
public static boolean isChartTypeScatter(int chartType)
```


Returnerar true om chartType är en av Scatter-undertyperna. Undertypsuppsättningen motsvarar den lämpliga uppsättningen i PowerPoint (se dialogrutan "Change Chart Type" i PowerPoint): [ChartType.ScatterWithMarkers](../../com.aspose.slides/charttype\#ScatterWithMarkers), [ChartType.ScatterWithSmoothLines](../../com.aspose.slides/charttype\#ScatterWithSmoothLines), [ChartType.ScatterWithSmoothLinesAndMarkers](../../com.aspose.slides/charttype\#ScatterWithSmoothLinesAndMarkers), [ChartType.ScatterWithStraightLines](../../com.aspose.slides/charttype\#ScatterWithStraightLines), [ChartType.ScatterWithStraightLinesAndMarkers](../../com.aspose.slides/charttype\#ScatterWithStraightLinesAndMarkers).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| chartType | int |  |

**Returnerar:**
boolean
### isChartTypeStock(int chartType) {#isChartTypeStock-int-}
```
public static boolean isChartTypeStock(int chartType)
```


Returnerar true om chartType är en av Stock-undertyperna. Undertypsuppsättningen motsvarar den lämpliga uppsättningen i PowerPoint (se dialogrutan "Change Chart Type" i PowerPoint): [ChartType.HighLowClose](../../com.aspose.slides/charttype\#HighLowClose), [ChartType.OpenHighLowClose](../../com.aspose.slides/charttype\#OpenHighLowClose), [ChartType.VolumeHighLowClose](../../com.aspose.slides/charttype\#VolumeHighLowClose), [ChartType.VolumeOpenHighLowClose](../../com.aspose.slides/charttype\#VolumeOpenHighLowClose).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| chartType | int |  |

**Returnerar:**
boolean
### isChartTypeSurface(int chartType) {#isChartTypeSurface-int-}
```
public static boolean isChartTypeSurface(int chartType)
```


Returnerar true om chartType är en av Surface-undertyperna. Undertypsuppsättningen motsvarar den lämpliga uppsättningen i PowerPoint (se dialogrutan "Change Chart Type" i PowerPoint): [ChartType.Surface3D](../../com.aspose.slides/charttype\#Surface3D), [ChartType.WireframeSurface3D](../../com.aspose.slides/charttype\#WireframeSurface3D), [ChartType.Contour](../../com.aspose.slides/charttype\#Contour), [ChartType.WireframeContour](../../com.aspose.slides/charttype\#WireframeContour).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| chartType | int |  |

**Returnerar:**
boolean
### isChartTypeDoughnut(int chartType) {#isChartTypeDoughnut-int-}
```
public static boolean isChartTypeDoughnut(int chartType)
```


Returnerar true om chartType är en av Doughnut-undertyperna. Undertypsuppsättningen motsvarar den lämpliga uppsättningen i PowerPoint (se dialogrutan "Change Chart Type" i PowerPoint): [ChartType.Doughnut](../../com.aspose.slides/charttype\#Doughnut), [ChartType.ExplodedDoughnut](../../com.aspose.slides/charttype\#ExplodedDoughnut).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| chartType | int |  |

**Returnerar:**
boolean
### isChartTypeBubble(int chartType) {#isChartTypeBubble-int-}
```
public static boolean isChartTypeBubble(int chartType)
```


Returnerar true om chartType är en av Bubble-undertyperna. Undertypsuppsättningen motsvarar den lämpliga uppsättningen i PowerPoint (se dialogrutan "Change Chart Type" i PowerPoint): [ChartType.Bubble](../../com.aspose.slides/charttype\#Bubble), [ChartType.BubbleWith3D](../../com.aspose.slides/charttype\#BubbleWith3D).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| chartType | int |  |

**Returnerar:**
boolean
### isChartTypeRadar(int chartType) {#isChartTypeRadar-int-}
```
public static boolean isChartTypeRadar(int chartType)
```


Returnerar true om chartType är en av Radar-undertyperna. Undertypsuppsättningen motsvarar den lämpliga uppsättningen i PowerPoint (se dialogrutan "Change Chart Type" i PowerPoint): [ChartType.FilledRadar](../../com.aspose.slides/charttype\#FilledRadar), [ChartType.Radar](../../com.aspose.slides/charttype\#Radar), [ChartType.RadarWithMarkers](../../com.aspose.slides/charttype\#RadarWithMarkers).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| chartType | int |  |

**Returnerar:**
boolean
### isSeriesUsesXValueCoordinate(int seriesType) {#isSeriesUsesXValueCoordinate-int-}
```
public static boolean isSeriesUsesXValueCoordinate(int seriesType)
```


Returnerar om den angivna serietypen använder X-värdekoordinater.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| seriesType | int | Series type. |

**Returnerar:**
boolean - True if uses otherwise false.
### isSeriesUsesYValueCoordinate(int seriesType) {#isSeriesUsesYValueCoordinate-int-}
```
public static boolean isSeriesUsesYValueCoordinate(int seriesType)
```


Returnerar om den angivna serietypen använder Y-värdekoordinater.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| seriesType | int | Series type. |

**Returnerar:**
boolean - True if uses otherwise false.
### isSeriesUsesValueCoordinate(int seriesType) {#isSeriesUsesValueCoordinate-int-}
```
public static boolean isSeriesUsesValueCoordinate(int seriesType)
```


Returnerar om den angivna serietypen använder värdekoordinater.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| seriesType | int | Series type. |

**Returnerar:**
boolean - True if uses otherwise false.
### isSeriesUsesBubbleSizeCoordinate(int seriesType) {#isSeriesUsesBubbleSizeCoordinate-int-}
```
public static boolean isSeriesUsesBubbleSizeCoordinate(int seriesType)
```


Returnerar om bubbelstorlekskoordinater kan användas för den angivna serietypen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| seriesType | int | Series type. |

**Returnerar:**
boolean - True if can be used, otherwise false.
### hasSeriesTrendLines(int seriesType) {#hasSeriesTrendLines-int-}
```
public static boolean hasSeriesTrendLines(int seriesType)
```


Returnerar om det finns trendlinjer för den angivna serietypen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| seriesType | int | Series type. |

**Returnerar:**
boolean - True if present otherwise false.
### isErrorBarsXAllowed(int seriesType) {#isErrorBarsXAllowed-int-}
```
public static boolean isErrorBarsXAllowed(int seriesType)
```


Returnerar om felstaplar X är tillåtna för den angivna serietypen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| seriesType | int | Series type. |

**Returnerar:**
boolean - True if allowed, otherwise false.
### isErrorBarsYAllowed(int seriesType) {#isErrorBarsYAllowed-int-}
```
public static boolean isErrorBarsYAllowed(int seriesType)
```


Returnerar om felstaplar Y är tillåtna för den angivna serietypen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| seriesType | int | Series type. |

**Returnerar:**
boolean - True if allowed, otherwise false.