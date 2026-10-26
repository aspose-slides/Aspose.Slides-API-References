---
title: ChartTypeCharacterizer
second_title: Aspose.Slides für Android über Java API Referenz
description: Hilfswerkzeug zum Abrufen zusätzlicher Informationen über Diagramme und Serien anhand ihres ChartType.
type: docs
url: /de/com.aspose.slides/charttypecharacterizer/
---
**Vererbung:**  
java.lang.Object  
```
public class ChartTypeCharacterizer
```

Hilfswerkzeug zum Abrufen zusätzlicher Informationen über Diagramme und Serien anhand ihres ChartType.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [ChartTypeCharacterizer()](#ChartTypeCharacterizer--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [isBar3DChart(int chartType)](#isBar3DChart-int-) | Gibt true zurück, wenn chartType einer der bar3DChart-Subtypen ist (3D-Säulen oder Balken). |
| [is2DChart(int chartType)](#is2DChart-int-) | Gibt true zurück, wenn chartType einer der 2D-Diagrammtypen ist. |
| [is3DChart(int chartType)](#is3DChart-int-) | Gibt true zurück, wenn chartType einer der 3D-Diagrammtypen ist. |
| [isChartTypeColumn(int chartType)](#isChartTypeColumn-int-) | Gibt true zurück, wenn chartType einer der Column-Subtypen ist. |
| [isChartTypeLine(int chartType)](#isChartTypeLine-int-) | Gibt true zurück, wenn chartType einer der Line-Subtypen ist. |
| [isChartTypePie(int chartType)](#isChartTypePie-int-) | Gibt true zurück, wenn chartType einer der Pie-Subtypen ist. |
| [isChartTypeBar(int chartType)](#isChartTypeBar-int-) | Gibt true zurück, wenn chartType einer der Bar-Subtypen ist. |
| [isChartTypeArea(int chartType)](#isChartTypeArea-int-) | Gibt true zurück, wenn chartType einer der Area-Subtypen ist. |
| [isChartTypeScatter(int chartType)](#isChartTypeScatter-int-) | Gibt true zurück, wenn chartType einer der Scatter-Subtypen ist. |
| [isChartTypeStock(int chartType)](#isChartTypeStock-int-) | Gibt true zurück, wenn chartType einer der Stock-Subtypen ist. |
| [isChartTypeSurface(int chartType)](#isChartTypeSurface-int-) | Gibt true zurück, wenn chartType einer der Surface-Subtypen ist. |
| [isChartTypeDoughnut(int chartType)](#isChartTypeDoughnut-int-) | Gibt true zurück, wenn chartType einer der Doughnut-Subtypen ist. |
| [isChartTypeBubble(int chartType)](#isChartTypeBubble-int-) | Gibt true zurück, wenn chartType einer der Bubble-Subtypen ist. |
| [isChartTypeRadar(int chartType)](#isChartTypeRadar-int-) | Gibt true zurück, wenn chartType einer der Radar-Subtypen ist. |
| [isSeriesUsesXValueCoordinate(int seriesType)](#isSeriesUsesXValueCoordinate-int-) | Gibt zurück, ob der angegebene Serientyp X-Wertkoordinaten verwendet. |
| [isSeriesUsesYValueCoordinate(int seriesType)](#isSeriesUsesYValueCoordinate-int-) | Gibt zurück, ob der angegebene Serientyp Y-Wertkoordinaten verwendet. |
| [isSeriesUsesValueCoordinate(int seriesType)](#isSeriesUsesValueCoordinate-int-) | Gibt zurück, ob der angegebene Serientyp Wertkoordinaten verwendet. |
| [isSeriesUsesBubbleSizeCoordinate(int seriesType)](#isSeriesUsesBubbleSizeCoordinate-int-) | Gibt zurück, ob Blasengrößenkoordinaten für den angegebenen Serientyp verwendet werden können. |
| [hasSeriesTrendLines(int seriesType)](#hasSeriesTrendLines-int-) | Gibt zurück, ob Trendlinien für den angegebenen Serientyp vorhanden sind. |
| [isErrorBarsXAllowed(int seriesType)](#isErrorBarsXAllowed-int-) | Gibt zurück, ob Fehlerindikatoren X für den angegebenen Serientyp erlaubt sind. |
| [isErrorBarsYAllowed(int seriesType)](#isErrorBarsYAllowed-int-) | Gibt zurück, ob Fehlerindikatoren Y für den angegebenen Serientyp erlaubt sind. |
### ChartTypeCharacterizer() {#ChartTypeCharacterizer--}
```
public ChartTypeCharacterizer()
```


### isBar3DChart(int chartType) {#isBar3DChart-int-}
```
public static boolean isBar3DChart(int chartType)
```


Gibt true zurück, wenn chartType einer der bar3DChart-Subtypen ist (3D-Säulen oder Balken).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| chartType | int |  |

**Rückgabewert:**
boolean
### is2DChart(int chartType) {#is2DChart-int-}
```
public static boolean is2DChart(int chartType)
```


Gibt true zurück, wenn chartType einer der 2D-Diagrammtypen ist.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| chartType | int |  |

**Rückgabewert:**
boolean
### is3DChart(int chartType) {#is3DChart-int-}
```
public static boolean is3DChart(int chartType)
```


Gibt true zurück, wenn chartType einer der 3D-Diagrammtypen ist.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| chartType | int |  |

**Rückgabewert:**
boolean
### isChartTypeColumn(int chartType) {#isChartTypeColumn-int-}
```
public static boolean isChartTypeColumn(int chartType)
```


Gibt true zurück, wenn chartType einer der Column-Subtypen ist. Der Subtypensatz entspricht dem entsprechenden Satz in PowerPoint (siehe Dialog „Diagrammtyp ändern“ in PowerPoint): [ChartType.ClusteredColumn](../../com.aspose.slides/charttype\#ClusteredColumn), [ChartType.ClusteredColumn3D](../../com.aspose.slides/charttype\#ClusteredColumn3D), [ChartType.ClusteredCone](../../com.aspose.slides/charttype\#ClusteredCone), [ChartType.ClusteredCylinder](../../com.aspose.slides/charttype\#ClusteredCylinder), [ChartType.ClusteredPyramid](../../com.aspose.slides/charttype\#ClusteredPyramid), [ChartType.PercentsStackedColumn](../../com.aspose.slides/charttype\#PercentsStackedColumn), [ChartType.PercentsStackedColumn3D](../../com.aspose.slides/charttype\#PercentsStackedColumn3D), [ChartType.PercentsStackedCone](../../com.aspose.slides/charttype\#PercentsStackedCone), [ChartType.PercentsStackedCylinder](../../com.aspose.slides/charttype\#PercentsStackedCylinder), [ChartType.PercentsStackedPyramid](../../com.aspose.slides/charttype\#PercentsStackedPyramid), [ChartType.StackedColumn](../../com.aspose.slides/charttype\#StackedColumn), [ChartType.StackedColumn3D](../../com.aspose.slides/charttype\#StackedColumn3D), [ChartType.StackedCone](../../com.aspose.slides/charttype\#StackedCone), [ChartType.StackedCylinder](../../com.aspose.slides/charttype\#StackedCylinder), [ChartType.StackedPyramid](../../com.aspose.slides/charttype\#StackedPyramid), [ChartType.Column3D](../../com.aspose.slides/charttype\#Column3D), [ChartType.Cylinder3D](../../com.aspose.slides/charttype\#Cylinder3D), [ChartType.Cone3D](../../com.aspose.slides/charttype\#Cone3D), [ChartType.Pyramid3D](../../com.aspose.slides/charttype\#Pyramid3D).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| chartType | int |  |

**Rückgabewert:**
boolean
### isChartTypeLine(int chartType) {#isChartTypeLine-int-}
```
public static boolean isChartTypeLine(int chartType)
```


Gibt true zurück, wenn chartType einer der Line-Subtypen ist. Der Subtypensatz entspricht dem entsprechenden Satz in PowerPoint (siehe Dialog „Diagrammtyp ändern“ in PowerPoint): [ChartType.Line](../../com.aspose.slides/charttype\#Line), [ChartType.LineWithMarkers](../../com.aspose.slides/charttype\#LineWithMarkers), [ChartType.PercentsStackedLine](../../com.aspose.slides/charttype\#PercentsStackedLine), [ChartType.PercentsStackedLineWithMarkers](../../com.aspose.slides/charttype\#PercentsStackedLineWithMarkers), [ChartType.StackedLine](../../com.aspose.slides/charttype\#StackedLine), [ChartType.StackedLineWithMarkers](../../com.aspose.slides/charttype\#StackedLineWithMarkers), [ChartType.Line3D](../../com.aspose.slides/charttype\#Line3D).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| chartType | int |  |

**Rückgabewert:**
boolean
### isChartTypePie(int chartType) {#isChartTypePie-int-}
```
public static boolean isChartTypePie(int chartType)
```


Gibt true zurück, wenn chartType einer der Pie-Subtypen ist. Der Subtypensatz entspricht dem entsprechenden Satz in PowerPoint (siehe Dialog „Diagrammtyp ändern“ in PowerPoint): [ChartType.BarOfPie](../../com.aspose.slides/charttype\#BarOfPie), [ChartType.ExplodedPie](../../com.aspose.slides/charttype\#ExplodedPie), [ChartType.ExplodedPie3D](../../com.aspose.slides/charttype\#ExplodedPie3D), [ChartType.Pie](../../com.aspose.slides/charttype\#Pie), [ChartType.Pie3D](../../com.aspose.slides/charttype\#Pie3D), [ChartType.PieOfPie](../../com.aspose.slides/charttype\#PieOfPie).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| chartType | int |  |

**Rückgabewert:**
boolean
### isChartTypeBar(int chartType) {#isChartTypeBar-int-}
```
public static boolean isChartTypeBar(int chartType)
```


Gibt true zurück, wenn chartType einer der Bar-Subtypen ist. Der Subtypensatz entspricht dem entsprechenden Satz in PowerPoint (siehe Dialog „Diagrammtyp ändern“ in PowerPoint): [ChartType.ClusteredBar](../../com.aspose.slides/charttype\#ClusteredBar), [ChartType.ClusteredBar3D](../../com.aspose.slides/charttype\#ClusteredBar3D), [ChartType.PercentsStackedBar](../../com.aspose.slides/charttype\#PercentsStackedBar), [ChartType.PercentsStackedBar3D](../../com.aspose.slides/charttype\#PercentsStackedBar3D), [ChartType.StackedBar](../../com.aspose.slides/charttype\#StackedBar), [ChartType.StackedBar3D](../../com.aspose.slides/charttype\#StackedBar3D), [ChartType.ClusteredHorizontalCone](../../com.aspose.slides/charttype\#ClusteredHorizontalCone), [ChartType.ClusteredHorizontalCylinder](../../com.aspose.slides/charttype\#ClusteredHorizontalCylinder), [ChartType.ClusteredHorizontalPyramid](../../com.aspose.slides/charttype\#ClusteredHorizontalPyramid), [ChartType.StackedHorizontalCone](../../com.aspose.slides/charttype\#StackedHorizontalCone), [ChartType.StackedHorizontalCylinder](../../com.aspose.slides/charttype\#StackedHorizontalCylinder), [ChartType.StackedHorizontalPyramid](../../com.aspose.slides/charttype\#StackedHorizontalPyramid), [ChartType.PercentsStackedHorizontalCone](../../com.aspose.slides/charttype\#PercentsStackedHorizontalCone), [ChartType.PercentsStackedHorizontalCylinder](../../com.aspose.slides/charttype\#PercentsStackedHorizontalCylinder), [ChartType.PercentsStackedHorizontalPyramid](../../com.aspose.slides/charttype\#PercentsStackedHorizontalPyramid).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| chartType | int |  |

**Rückgabewert:**
boolean
### isChartTypeArea(int chartType) {#isChartTypeArea-int-}
```
public static boolean isChartTypeArea(int chartType)
```


Gibt true zurück, wenn chartType einer der Area-Subtypen ist. Der Subtypensatz entspricht dem entsprechenden Satz in PowerPoint (siehe Dialog „Diagrammtyp ändern“ in PowerPoint): [ChartType.Area](../../com.aspose.slides/charttype\#Area), [ChartType.PercentsStackedArea](../../com.aspose.slides/charttype\#PercentsStackedArea), [ChartType.PercentsStackedArea3D](../../com.aspose.slides/charttype\#PercentsStackedArea3D), [ChartType.StackedArea](../../com.aspose.slides/charttype\#StackedArea), [ChartType.StackedArea3D](../../com.aspose.slides/charttype\#StackedArea3D), [ChartType.Area3D](../../com.aspose.slides/charttype\#Area3D).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| chartType | int |  |

**Rückgabewert:**
boolean
### isChartTypeScatter(int chartType) {#isChartTypeScatter-int-}
```
public static boolean isChartTypeScatter(int chartType)
```


Gibt true zurück, wenn chartType einer der Scatter-Subtypen ist. Der Subtypensatz entspricht dem entsprechenden Satz in PowerPoint (siehe Dialog „Diagrammtyp ändern“ in PowerPoint): [ChartType.ScatterWithMarkers](../../com.aspose.slides/charttype\#ScatterWithMarkers), [ChartType.ScatterWithSmoothLines](../../com.aspose.slides/charttype\#ScatterWithSmoothLines), [ChartType.ScatterWithSmoothLinesAndMarkers](../../com.aspose.slides/charttype\#ScatterWithSmoothLinesAndMarkers), [ChartType.ScatterWithStraightLines](../../com.aspose.slides/charttype\#ScatterWithStraightLines), [ChartType.ScatterWithStraightLinesAndMarkers](../../com.aspose.slides/charttype\#ScatterWithStraightLinesAndMarkers).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| chartType | int |  |

**Rückgabewert:**
boolean
### isChartTypeStock(int chartType) {#isChartTypeStock-int-}
```
public static boolean isChartTypeStock(int chartType)
```


Gibt true zurück, wenn chartType einer der Stock-Subtypen ist. Der Subtypensatz entspricht dem entsprechenden Satz in PowerPoint (siehe Dialog „Diagrammtyp ändern“ in PowerPoint): [ChartType.HighLowClose](../../com.aspose.slides/charttype\#HighLowClose), [ChartType.OpenHighLowClose](../../com.aspose.slides/charttype\#OpenHighLowClose), [ChartType.VolumeHighLowClose](../../com.aspose.slides/charttype\#VolumeHighLowClose), [ChartType.VolumeOpenHighLowClose](../../com.aspose.slides/charttype\#VolumeOpenHighLowClose).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| chartType | int |  |

**Rückgabewert:**
boolean
### isChartTypeSurface(int chartType) {#isChartTypeSurface-int-}
```
public static boolean isChartTypeSurface(int chartType)
```


Gibt true zurück, wenn chartType einer der Surface-Subtypen ist. Der Subtypensatz entspricht dem entsprechenden Satz in PowerPoint (siehe Dialog „Diagrammtyp ändern“ in PowerPoint): [ChartType.Surface3D](../../com.aspose.slides/charttype\#Surface3D), [ChartType.WireframeSurface3D](../../com.aspose.slides/charttype\#WireframeSurface3D), [ChartType.Contour](../../com.aspose.slides/charttype\#Contour), [ChartType.WireframeContour](../../com.aspose.slides/charttype\#WireframeContour).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| chartType | int |  |

**Rückgabewert:**
boolean
### isChartTypeDoughnut(int chartType) {#isChartTypeDoughnut-int-}
```
public static boolean isChartTypeDoughnut(int chartType)
```


Gibt true zurück, wenn chartType einer der Doughnut-Subtypen ist. Der Subtypensatz entspricht dem entsprechenden Satz in PowerPoint (siehe Dialog „Diagrammtyp ändern“ in PowerPoint): [ChartType.Doughnut](../../com.aspose.slides/charttype\#Doughnut), [ChartType.ExplodedDoughnut](../../com.aspose.slides/charttype\#ExplodedDoughnut).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| chartType | int |  |

**Rückgabewert:**
boolean
### isChartTypeBubble(int chartType) {#isChartTypeBubble-int-}
```
public static boolean isChartTypeBubble(int chartType)
```


Gibt true zurück, wenn chartType einer der Bubble-Subtypen ist. Der Subtypensatz entspricht dem entsprechenden Satz in PowerPoint (siehe Dialog „Diagrammtyp ändern“ in PowerPoint): [ChartType.Bubble](../../com.aspose.slides/charttype\#Bubble), [ChartType.BubbleWith3D](../../com.aspose.slides/charttype\#BubbleWith3D).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| chartType | int |  |

**Rückgabewert:**
boolean
### isChartTypeRadar(int chartType) {#isChartTypeRadar-int-}
```
public static boolean isChartTypeRadar(int chartType)
```


Gibt true zurück, wenn chartType einer der Radar-Subtypen ist. Der Subtypensatz entspricht dem entsprechenden Satz in PowerPoint (siehe Dialog „Diagrammtyp ändern“ in PowerPoint): [ChartType.FilledRadar](../../com.aspose.slides/charttype\#FilledRadar), [ChartType.Radar](../../com.aspose.slides/charttype\#Radar), [ChartType.RadarWithMarkers](../../com.aspose.slides/charttype\#RadarWithMarkers).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| chartType | int |  |

**Rückgabewert:**
boolean
### isSeriesUsesXValueCoordinate(int seriesType) {#isSeriesUsesXValueCoordinate-int-}
```
public static boolean isSeriesUsesXValueCoordinate(int seriesType)
```


Gibt zurück, ob der angegebene Serientyp X-Wertkoordinaten verwendet.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| seriesType | int | Serientyp. |

**Rückgabewert:**
boolean - True if uses otherwise false.
### isSeriesUsesYValueCoordinate(int seriesType) {#isSeriesUsesYValueCoordinate-int-}
```
public static boolean isSeriesUsesYValueCoordinate(int seriesType)
```


Gibt zurück, ob der angegebene Serientyp Y-Wertkoordinaten verwendet.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| seriesType | int | Serientyp. |

**Rückgabewert:**
boolean - True if uses otherwise false.
### isSeriesUsesValueCoordinate(int seriesType) {#isSeriesUsesValueCoordinate-int-}
```
public static boolean isSeriesUsesValueCoordinate(int seriesType)
```


Gibt zurück, ob der angegebene Serientyp Wertkoordinaten verwendet.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| seriesType | int | Serientyp. |

**Rückgabewert:**
boolean - True if uses otherwise false.
### isSeriesUsesBubbleSizeCoordinate(int seriesType) {#isSeriesUsesBubbleSizeCoordinate-int-}
```
public static boolean isSeriesUsesBubbleSizeCoordinate(int seriesType)
```


Gibt zurück, ob Blasengrößenkoordinaten für den angegebenen Serientyp verwendet werden können.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| seriesType | int | Serientyp. |

**Rückgabewert:**
boolean - True if can be used, otherwise false.
### hasSeriesTrendLines(int seriesType) {#hasSeriesTrendLines-int-}
```
public static boolean hasSeriesTrendLines(int seriesType)
```


Gibt zurück, ob Trendlinien für den angegebenen Serientyp vorhanden sind.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| seriesType | int | Serientyp. |

**Rückgabewert:**
boolean - True if present otherwise false.
### isErrorBarsXAllowed(int seriesType) {#isErrorBarsXAllowed-int-}
```
public static boolean isErrorBarsXAllowed(int seriesType)
```


Gibt zurück, ob Fehlerindikatoren X für den angegebenen Serientyp erlaubt sind.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| seriesType | int | Serientyp. |

**Rückgabewert:**
boolean - True if allowed, otherwise false.
### isErrorBarsYAllowed(int seriesType) {#isErrorBarsYAllowed-int-}
```
public static boolean isErrorBarsYAllowed(int seriesType)
```


Gibt zurück, ob Fehlerindikatoren Y für den angegebenen Serientyp erlaubt sind.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| seriesType | int | Serientyp. |

**Rückgabewert:**
boolean - True if allowed, otherwise false.