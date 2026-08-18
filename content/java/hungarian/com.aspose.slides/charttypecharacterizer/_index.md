---
title: ChartTypeCharacterizer
second_title: Aspose.Slides Java API hivatkozás
description: Segédprogram a diagramok és sorozatok további információinak lekéréséhez a ChartType alapján.
type: docs
url: /hu/com.aspose.slides/charttypecharacterizer/
---
**Inheritance:**
java.lang.Object
```
public class ChartTypeCharacterizer
```

Segédprogram a diagramok és sorozatok további információinak lekéréséhez a ChartType alapján.
## Constructors

| Konstruktor | Leírás |
| --- | --- |
| [ChartTypeCharacterizer()](#ChartTypeCharacterizer--) |  |
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [isBar3DChart(int chartType)](#isBar3DChart-int-) | Igaz értéket ad vissza, ha a chartType a bar3DChart al-típusok (3D oszlopok vagy sávok) egyike. |
| [is2DChart(int chartType)](#is2DChart-int-) | Igaz értéket ad vissza, ha a chartType a 2D diagramtípusok egyike. |
| [is3DChart(int chartType)](#is3DChart-int-) | Igaz értéket ad vissza, ha a chartType a 3D diagramtípusok egyike. |
| [isChartTypeColumn(int chartType)](#isChartTypeColumn-int-) | Igaz értéket ad vissza, ha a chartType a Column al-típusok egyike. |
| [isChartTypeLine(int chartType)](#isChartTypeLine-int-) | Igaz értéket ad vissza, ha a chartType a Line al-típusok egyike. |
| [isChartTypePie(int chartType)](#isChartTypePie-int-) | Igaz értéket ad vissza, ha a chartType a Pie al-típusok egyike. |
| [isChartTypeBar(int chartType)](#isChartTypeBar-int-) | Igaz értéket ad vissza, ha a chartType a Bar al-típusok egyike. |
| [isChartTypeArea(int chartType)](#isChartTypeArea-int-) | Igaz értéket ad vissza, ha a chartType az Area al-típusok egyike. |
| [isChartTypeScatter(int chartType)](#isChartTypeScatter-int-) | Igaz értéket ad vissza, ha a chartType a Scatter al-típusok egyike. |
| [isChartTypeStock(int chartType)](#isChartTypeStock-int-) | Igaz értéket ad vissza, ha a chartType a Stock al-típusok egyike. |
| [isChartTypeSurface(int chartType)](#isChartTypeSurface-int-) | Igaz értéket ad vissza, ha a chartType a Surface al-típusok egyike. |
| [isChartTypeDoughnut(int chartType)](#isChartTypeDoughnut-int-) | Igaz értéket ad vissza, ha a chartType a Doughnut al-típusok egyike. |
| [isChartTypeBubble(int chartType)](#isChartTypeBubble-int-) | Igaz értéket ad vissza, ha a chartType a Bubble al-típusok egyike. |
| [isChartTypeRadar(int chartType)](#isChartTypeRadar-int-) | Igaz értéket ad vissza, ha a chartType a Radar al-típusok egyike. |
| [isSeriesUsesXValueCoordinate(int seriesType)](#isSeriesUsesXValueCoordinate-int-) | Visszaadja, ha a megadott sorozattípus X értékkordinátákat használ. |
| [isSeriesUsesYValueCoordinate(int seriesType)](#isSeriesUsesYValueCoordinate-int-) | Visszaadja, ha a megadott sorozattípus Y értékkordinátákat használ. |
| [isSeriesUsesValueCoordinate(int seriesType)](#isSeriesUsesValueCoordinate-int-) | Visszaadja, ha a megadott sorozattípus értékkordinátákat használ. |
| [isSeriesUsesBubbleSizeCoordinate(int seriesType)](#isSeriesUsesBubbleSizeCoordinate-int-) | Visszaadja, ha a buborékméret-koordináták használhatók a megadott sorozattípushoz. |
| [hasSeriesTrendLines(int seriesType)](#hasSeriesTrendLines-int-) | Visszaadja, ha a megadott sorozattípushoz trendvonalak tartoznak. |
| [isErrorBarsXAllowed(int seriesType)](#isErrorBarsXAllowed-int-) | Visszaadja, ha az X hibasávok engedélyezettek a megadott sorozattípusban. |
| [isErrorBarsYAllowed(int seriesType)](#isErrorBarsYAllowed-int-) | Visszaadja, ha az Y hibasávok engedélyezettek a megadott sorozattípusban. |
### ChartTypeCharacterizer() {#ChartTypeCharacterizer--}
```
public ChartTypeCharacterizer()
```

### isBar3DChart(int chartType) {#isBar3DChart-int-}
```
public static boolean isBar3DChart(int chartType)
```

Igaz értéket ad vissza, ha a chartType a bar3DChart al-típusok (3D oszlopok vagy sávok) egyike.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| chartType | int |  |

**Visszatér:**
boolean
### is2DChart(int chartType) {#is2DChart-int-}
```
public static boolean is2DChart(int chartType)
```

Igaz értéket ad vissza, ha a chartType a 2D diagramtípusok egyike.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| chartType | int |  |

**Visszatér:**
boolean
### is3DChart(int chartType) {#is3DChart-int-}
```
public static boolean is3DChart(int chartType)
```

Igaz értéket ad vissza, ha a chartType a 3D diagramtípusok egyike.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| chartType | int |  |

**Visszatér:**
boolean
### isChartTypeColumn(int chartType) {#isChartTypeColumn-int-}
```
public static boolean isChartTypeColumn(int chartType)
```

Igaz értéket ad vissza, ha a chartType a Column al-típusok egyike. Az al-típusok halmaza a PowerPoint megfelelő halmazának felel meg (lásd a PowerPoint „Diagram típusának módosítása” párbeszédpanelt): [ChartType.ClusteredColumn](../../com.aspose.slides/charttype\#ClusteredColumn), [ChartType.ClusteredColumn3D](../../com.aspose.slides/charttype\#ClusteredColumn3D), [ChartType.ClusteredCone](../../com.aspose.slides/charttype\#ClusteredCone), [ChartType.ClusteredCylinder](../../com.aspose.slides/charttype\#ClusteredCylinder), [ChartType.ClusteredPyramid](../../com.aspose.slides/charttype\#ClusteredPyramid), [ChartType.PercentsStackedColumn](../../com.aspose.slides/charttype\#PercentsStackedColumn), [ChartType.PercentsStackedColumn3D](../../com.aspose.slides/charttype\#PercentsStackedColumn3D), [ChartType.PercentsStackedCone](../../com.aspose.slides/charttype\#PercentsStackedCone), [ChartType.PercentsStackedCylinder](../../com.aspose.slides/charttype\#PercentsStackedCylinder), [ChartType.PercentsStackedPyramid](../../com.aspose.slides/charttype\#PercentsStackedPyramid), [ChartType.StackedColumn](../../com.aspose.slides/charttype\#StackedColumn), [ChartType.StackedColumn3D](../../com.aspose.slides/charttype\#StackedColumn3D), [ChartType.StackedCone](../../com.aspose.slides/charttype\#StackedCone), [ChartType.StackedCylinder](../../com.aspose.slides/charttype\#StackedCylinder), [ChartType.StackedPyramid](../../com.aspose.slides/charttype\#StackedPyramid), [ChartType.Column3D](../../com.aspose.slides/charttype\#Column3D), [ChartType.Cylinder3D](../../com.aspose.slides/charttype\#Cylinder3D), [ChartType.Cone3D](../../com.aspose.slides/charttype\#Cone3D), [ChartType.Pyramid3D](../../com.aspose.slides/charttype\#Pyramid3D).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| chartType | int |  |

**Visszatér:**
boolean
### isChartTypeLine(int chartType) {#isChartTypeLine-int-}
```
public static boolean isChartTypeLine(int chartType)
```

Igaz értéket ad vissza, ha a chartType a Line al-típusok egyike. Az al-típusok halmaza a PowerPoint megfelelő halmazának felel meg (lásd a PowerPoint „Diagram típusának módosítása” párbeszédpanelt): [ChartType.Line](../../com.aspose.slides/charttype\#Line), [ChartType.LineWithMarkers](../../com.aspose.slides/charttype\#LineWithMarkers), [ChartType.PercentsStackedLine](../../com.aspose.slides/charttype\#PercentsStackedLine), [ChartType.PercentsStackedLineWithMarkers](../../com.aspose.slides/charttype\#PercentsStackedLineWithMarkers), [ChartType.StackedLine](../../com.aspose.slides/charttype\#StackedLine), [ChartType.StackedLineWithMarkers](../../com.aspose.slides/charttype\#StackedLineWithMarkers), [ChartType.Line3D](../../com.aspose.slides/charttype\#Line3D).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| chartType | int |  |

**Visszatér:**
boolean
### isChartTypePie(int chartType) {#isChartTypePie-int-}
```
public static boolean isChartTypePie(int chartType)
```

Igaz értéket ad vissza, ha a chartType a Pie al-típusok egyike. Az al-típusok halmaza a PowerPoint megfelelő halmazának felel meg (lásd a PowerPoint „Diagram típusának módosítása” párbeszédpanelt): [ChartType.BarOfPie](../../com.aspose.slides/charttype\#BarOfPie), [ChartType.ExplodedPie](../../com.aspose.slides/charttype\#ExplodedPie), [ChartType.ExplodedPie3D](../../com.aspose.slides/charttype\#ExplodedPie3D), [ChartType.Pie](../../com.aspose.slides/charttype\#Pie), [ChartType.Pie3D](../../com.aspose.slides/charttype\#Pie3D), [ChartType.PieOfPie](../../com.aspose.slides/charttype\#PieOfPie).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| chartType | int |  |

**Visszatér:**
boolean
### isChartTypeBar(int chartType) {#isChartTypeBar-int-}
```
public static boolean isChartTypeBar(int chartType)
```

Igaz értéket ad vissza, ha a chartType a Bar al-típusok egyike. Az al-típusok halmaza a PowerPoint megfelelő halmazának felel meg (lásd a PowerPoint „Diagram típusának módosítása” párbeszédpanelt): [ChartType.ClusteredBar](../../com.aspose.slides/charttype\#ClusteredBar), [ChartType.ClusteredBar3D](../../com.aspose.slides/charttype\#ClusteredBar3D), [ChartType.PercentsStackedBar](../../com.aspose.slides/charttype\#PercentsStackedBar), [ChartType.PercentsStackedBar3D](../../com.aspose.slides/charttype\#PercentsStackedBar3D), [ChartType.StackedBar](../../com.aspose.slides/charttype\#StackedBar), [ChartType.StackedBar3D](../../com.aspose.slides/charttype\#StackedBar3D), [ChartType.ClusteredHorizontalCone](../../com.aspose.slides/charttype\#ClusteredHorizontalCone), [ChartType.ClusteredHorizontalCylinder](../../com.aspose.slides/charttype\#ClusteredHorizontalCylinder), [ChartType.ClusteredHorizontalPyramid](../../com.aspose.slides/charttype\#ClusteredHorizontalPyramid), [ChartType.StackedHorizontalCone](../../com.aspose.slides/charttype\#StackedHorizontalCone), [ChartType.StackedHorizontalCylinder](../../com.aspose.slides/charttype\#StackedHorizontalCylinder), [ChartType.StackedHorizontalPyramid](../../com.aspose.slides/charttype\#StackedHorizontalPyramid), [ChartType.PercentsStackedHorizontalCone](../../com.aspose.slides/charttype\#PercentsStackedHorizontalCone), [ChartType.PercentsStackedHorizontalCylinder](../../com.aspose.slides/charttype\#PercentsStackedHorizontalCylinder), [ChartType.PercentsStackedHorizontalPyramid](../../com.aspose.slides/charttype\#PercentsStackedHorizontalPyramid).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| chartType | int |  |

**Visszatér:**
boolean
### isChartTypeArea(int chartType) {#isChartTypeArea-int-}
```
public static boolean isChartTypeArea(int chartType)
```

Igaz értéket ad vissza, ha a chartType az Area al-típusok egyike. Az al-típusok halmaza a PowerPoint megfelelő halmazának felel meg (lásd a PowerPoint „Diagram típusának módosítása” párbeszédpanelt): [ChartType.Area](../../com.aspose.slides/charttype\#Area), [ChartType.PercentsStackedArea](../../com.aspose.slides/charttype\#PercentsStackedArea), [ChartType.PercentsStackedArea3D](../../com.aspose.slides/charttype\#PercentsStackedArea3D), [ChartType.StackedArea](../../com.aspose.slides/charttype\#StackedArea), [ChartType.StackedArea3D](../../com.aspose.slides/charttype\#StackedArea3D), [ChartType.Area3D](../../com.aspose.slides/charttype\#Area3D).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| chartType | int |  |

**Visszatér:**
boolean
### isChartTypeScatter(int chartType) {#isChartTypeScatter-int-}
```
public static boolean isChartTypeScatter(int chartType)
```

Igaz értéket ad vissza, ha a chartType a Scatter al-típusok egyike. Az al-típusok halmaza a PowerPoint megfelelő halmazának felel meg (lásd a PowerPoint „Diagram típusának módosítása” párbeszédpanelt): [ChartType.ScatterWithMarkers](../../com.aspose.slides/charttype\#ScatterWithMarkers), [ChartType.ScatterWithSmoothLines](../../com.aspose.slides/charttype\#ScatterWithSmoothLines), [ChartType.ScatterWithSmoothLinesAndMarkers](../../com.aspose.slides/charttype\#ScatterWithSmoothLinesAndMarkers), [ChartType.ScatterWithStraightLines](../../com.aspose.slides/charttype\#ScatterWithStraightLines), [ChartType.ScatterWithStraightLinesAndMarkers](../../com.aspose.slides/charttype\#ScatterWithStraightLinesAndMarkers).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| chartType | int |  |

**Visszatér:**
boolean
### isChartTypeStock(int chartType) {#isChartTypeStock-int-}
```
public static boolean isChartTypeStock(int chartType)
```

Igaz értéket ad vissza, ha a chartType a Stock al-típusok egyike. Az al-típusok halmaza a PowerPoint megfelelő halmazának felel meg (lásd a PowerPoint „Diagram típusának módosítása” párbeszédpanelt): [ChartType.HighLowClose](../../com.aspose.slides/charttype\#HighLowClose), [ChartType.OpenHighLowClose](../../com.aspose.slides/charttype\#OpenHighLowClose), [ChartType.VolumeHighLowClose](../../com.aspose.slides/charttype\#VolumeHighLowClose), [ChartType.VolumeOpenHighLowClose](../../com.aspose.slides/charttype\#VolumeOpenHighLowClose).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| chartType | int |  |

**Visszatér:**
boolean
### isChartTypeSurface(int chartType) {#isChartTypeSurface-int-}
```
public static boolean isChartTypeSurface(int chartType)
```

Igaz értéket ad vissza, ha a chartType a Surface al-típusok egyike. Az al-típusok halmaza a PowerPoint megfelelő halmazának felel meg (lásd a PowerPoint „Diagram típusának módosítása” párbeszédpanelt): [ChartType.Surface3D](../../com.aspose.slides/charttype\#Surface3D), [ChartType.WireframeSurface3D](../../com.aspose.slides/charttype\#WireframeSurface3D), [ChartType.Contour](../../com.aspose.slides/charttype\#Contour), [ChartType.WireframeContour](../../com.aspose.slides/charttype\#WireframeContour).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| chartType | int |  |

**Visszatér:**
boolean
### isChartTypeDoughnut(int chartType) {#isChartTypeDoughnut-int-}
```
public static boolean isChartTypeDoughnut(int chartType)
```

Igaz értéket ad vissza, ha a chartType a Doughnut al-típusok egyike. Az al-típusok halmaza a PowerPoint megfelelő halmazának felel meg (lásd a PowerPoint „Diagram típusának módosítása” párbeszédpanelt): [ChartType.Doughnut](../../com.aspose.slides/charttype\#Doughnut), [ChartType.ExplodedDoughnut](../../com.aspose.slides/charttype\#ExplodedDoughnut).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| chartType | int |  |

**Visszatér:**
boolean
### isChartTypeBubble(int chartType) {#isChartTypeBubble-int-}
```
public static boolean isChartTypeBubble(int chartType)
```

Igaz értéket ad vissza, ha a chartType a Bubble al-típusok egyike. Az al-típusok halmaza a PowerPoint megfelelő halmazának felel meg (lásd a PowerPoint „Diagram típusának módosítása” párbeszédpanelt): [ChartType.Bubble](../../com.aspose.slides/charttype\#Bubble), [ChartType.BubbleWith3D](../../com.aspose.slides/charttype\#BubbleWith3D).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| chartType | int |  |

**Visszatér:**
boolean
### isChartTypeRadar(int chartType) {#isChartTypeRadar-int-}
```
public static boolean isChartTypeRadar(int chartType)
```

Igaz értéket ad vissza, ha a chartType a Radar al-típusok egyike. Az al-típusok halmaza a PowerPoint megfelelő halmazának felel meg (lásd a PowerPoint „Diagram típusának módosítása” párbeszédpanelt): [ChartType.FilledRadar](../../com.aspose.slides/charttype\#FilledRadar), [ChartType.Radar](../../com.aspose.slides/charttype\#Radar), [ChartType.RadarWithMarkers](../../com.aspose.slides/charttype\#RadarWithMarkers).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| chartType | int |  |

**Visszatér:**
boolean
### isSeriesUsesXValueCoordinate(int seriesType) {#isSeriesUsesXValueCoordinate-int-}
```
public static boolean isSeriesUsesXValueCoordinate(int seriesType)
```

Visszaadja, ha a megadott sorozattípus X értékkordinátákat használ.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| seriesType | int | Sorozattípus. |

**Visszatér:**
boolean - True if uses otherwise false.
### isSeriesUsesYValueCoordinate(int seriesType) {#isSeriesUsesYValueCoordinate-int-}
```
public static boolean isSeriesUsesYValueCoordinate(int seriesType)
```

Visszaadja, ha a megadott sorozattípus Y értékkordinátákat használ.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| seriesType | int | Sorozattípus. |

**Visszatér:**
boolean - True if uses otherwise false.
### isSeriesUsesValueCoordinate(int seriesType) {#isSeriesUsesValueCoordinate-int-}
```
public static boolean isSeriesUsesValueCoordinate(int seriesType)
```

Visszaadja, ha a megadott sorozattípus értékkordinátákat használ.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| seriesType | int | Sorozattípus. |

**Visszatér:**
boolean - True if uses otherwise false.
### isSeriesUsesBubbleSizeCoordinate(int seriesType) {#isSeriesUsesBubbleSizeCoordinate-int-}
```
public static boolean isSeriesUsesBubbleSizeCoordinate(int seriesType)
```

Visszaadja, ha a buborékméret-koordináták használhatók a megadott sorozattípushoz.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| seriesType | int | Sorozattípus. |

**Visszatér:**
boolean - True if can be used, otherwise false.
### hasSeriesTrendLines(int seriesType) {#hasSeriesTrendLines-int-}
```
public static boolean hasSeriesTrendLines(int seriesType)
```

Visszaadja, ha a megadott sorozattípushoz trendvonalak tartoznak.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| seriesType | int | Sorozattípus. |

**Visszatér:**
boolean - True if present otherwise false.
### isErrorBarsXAllowed(int seriesType) {#isErrorBarsXAllowed-int-}
```
public static boolean isErrorBarsXAllowed(int seriesType)
```

Visszaadja, ha az X hibasávok engedélyezettek a megadott sorozattípusban.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| seriesType | int | Sorozattípus. |

**Visszatér:**
boolean - True if allowed, otherwise false.
### isErrorBarsYAllowed(int seriesType) {#isErrorBarsYAllowed-int-}
```
public static boolean isErrorBarsYAllowed(int seriesType)
```

Visszaadja, ha az Y hibasávok engedélyezettek a megadott sorozattípusban.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| seriesType | int | Sorozattípus. |

**Visszatér:**
boolean - True if allowed, otherwise false.