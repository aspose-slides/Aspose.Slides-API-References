---
title: ChartTypeCharacterizer
second_title: Aspose.Slides pro Java – reference API
description: Pomocník pro získání dalších informací o grafech a sériích na základě jejich ChartType.
type: docs
url: /cs/com.aspose.slides/charttypecharacterizer/
---
**Dědičnost:**
java.lang.Object
```
public class ChartTypeCharacterizer
```

Pomocník pro získání dalších informací o grafech a sériích na základě jejich ChartType.
## Konstruktory

| Konstruktor | Popis |
| --- | --- |
| [ChartTypeCharacterizer()](#ChartTypeCharacterizer--) |  |
## Metody

| Metoda | Popis |
| --- | --- |
| [isBar3DChart(int chartType)](#isBar3DChart-int-) | Vrátí true, pokud je chartType jedním z podtypů bar3DChart (3D sloupce nebo pruhy). |
| [is2DChart(int chartType)](#is2DChart-int-) | Vrátí true, pokud je chartType jedním z 2D typů grafu. |
| [is3DChart(int chartType)](#is3DChart-int-) | Vrátí true, pokud je chartType jedním z 3D typů grafu. |
| [isChartTypeColumn(int chartType)](#isChartTypeColumn-int-) | Vrátí true, pokud je chartType jedním z podtypů Column. |
| [isChartTypeLine(int chartType)](#isChartTypeLine-int-) | Vrátí true, pokud je chartType jedním z podtypů Line. |
| [isChartTypePie(int chartType)](#isChartTypePie-int-) | Vrátí true, pokud je chartType jedním z podtypů Pie. |
| [isChartTypeBar(int chartType)](#isChartTypeBar-int-) | Vrátí true, pokud je chartType jedním z podtypů Bar. |
| [isChartTypeArea(int chartType)](#isChartTypeArea-int-) | Vrátí true, pokud je chartType jedním z podtypů Area. |
| [isChartTypeScatter(int chartType)](#isChartTypeScatter-int-) | Vrátí true, pokud je chartType jedním z podtypů Scatter. |
| [isChartTypeStock(int chartType)](#isChartTypeStock-int-) | Vrátí true, pokud je chartType jedním z podtypů Stock. |
| [isChartTypeSurface(int chartType)](#isChartTypeSurface-int-) | Vrátí true, pokud je chartType jedním z podtypů Surface. |
| [isChartTypeDoughnut(int chartType)](#isChartTypeDoughnut-int-) | Vrátí true, pokud je chartType jedním z podtypů Doughnut. |
| [isChartTypeBubble(int chartType)](#isChartTypeBubble-int-) | Vrátí true, pokud je chartType jedním z podtypů Bubble. |
| [isChartTypeRadar(int chartType)](#isChartTypeRadar-int-) | Vrátí true, pokud je chartType jedním z podtypů Radar. |
| [isSeriesUsesXValueCoordinate(int seriesType)](#isSeriesUsesXValueCoordinate-int-) | Vrací, zda zadaný typ series používá X souřadnice hodnot. |
| [isSeriesUsesYValueCoordinate(int seriesType)](#isSeriesUsesYValueCoordinate-int-) | Vrací, zda zadaný typ series používá Y souřadnice hodnot. |
| [isSeriesUsesValueCoordinate(int seriesType)](#isSeriesUsesValueCoordinate-int-) | Vrací, zda zadaný typ series používá souřadnice hodnot. |
| [isSeriesUsesBubbleSizeCoordinate(int seriesType)](#isSeriesUsesBubbleSizeCoordinate-int-) | Vrací, zda lze pro zadaný typ series použít souřadnice velikosti bublin. |
| [hasSeriesTrendLines(int seriesType)](#hasSeriesTrendLines-int-) | Vrací, zda existují trendové čáry série pro zadaný typ series. |
| [isErrorBarsXAllowed(int seriesType)](#isErrorBarsXAllowed-int-) | Vrací, zda jsou povoleny chybové pruhy X pro zadaný typ series. |
| [isErrorBarsYAllowed(int seriesType)](#isErrorBarsYAllowed-int-) | Vrací, zda jsou povoleny chybové pruhy Y pro zadaný typ series. |
### ChartTypeCharacterizer() {#ChartTypeCharacterizer--}
```
public ChartTypeCharacterizer()
```


### isBar3DChart(int chartType) {#isBar3DChart-int-}
```
public static boolean isBar3DChart(int chartType)
```

Vrátí true, pokud je chartType jedním z podtypů bar3DChart (3D sloupce nebo pruhy).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| chartType | int |  |

**Vrací:**
boolean
### is2DChart(int chartType) {#is2DChart-int-}
```
public static boolean is2DChart(int chartType)
```

Vrátí true, pokud je chartType jedním z 2D typů grafu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| chartType | int |  |

**Vrací:**
boolean
### is3DChart(int chartType) {#is3DChart-int-}
```
public static boolean is3DChart(int chartType)
```

Vrátí true, pokud je chartType jedním z 3D typů grafu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| chartType | int |  |

**Vrací:**
boolean
### isChartTypeColumn(int chartType) {#isChartTypeColumn-int-}
```
public static boolean isChartTypeColumn(int chartType)
```

Vrátí true, pokud je chartType jedním z podtypů Column. Množina podtypů odpovídá příslušné množině v PowerPointu (viz dialog "Change Chart Type" v PowerPointu): [ChartType.ClusteredColumn](../../com.aspose.slides/charttype\#ClusteredColumn), [ChartType.ClusteredColumn3D](../../com.aspose.slides/charttype\#ClusteredColumn3D), [ChartType.ClusteredCone](../../com.aspose.slides/charttype\#ClusteredCone), [ChartType.ClusteredCylinder](../../com.aspose.slides/charttype\#ClusteredCylinder), [ChartType.ClusteredPyramid](../../com.aspose.slides/charttype\#ClusteredPyramid), [ChartType.PercentsStackedColumn](../../com.aspose.slides/charttype\#PercentsStackedColumn), [ChartType.PercentsStackedColumn3D](../../com.aspose.slides/charttype\#PercentsStackedColumn3D), [ChartType.PercentsStackedCone](../../com.aspose.slides/charttype\#PercentsStackedCone), [ChartType.PercentsStackedCylinder](../../com.aspose.slides/charttype\#PercentsStackedCylinder), [ChartType.PercentsStackedPyramid](../../com.aspose.slides/charttype\#PercentsStackedPyramid), [ChartType.StackedColumn](../../com.aspose.slides/charttype\#StackedColumn), [ChartType.StackedColumn3D](../../com.aspose.slides/charttype\#StackedColumn3D), [ChartType.StackedCone](../../com.aspose.slides/charttype\#StackedCone), [ChartType.StackedCylinder](../../com.aspose.slides/charttype\#StackedCylinder), [ChartType.StackedPyramid](../../com.aspose.slides/charttype\#StackedPyramid), [ChartType.Column3D](../../com.aspose.slides/charttype\#Column3D), [ChartType.Cylinder3D](../../com.aspose.slides/charttype\#Cylinder3D), [ChartType.Cone3D](../../com.aspose.slides/charttype\#Cone3D), [ChartType.Pyramid3D](../../com.aspose.slides/charttype\#Pyramid3D).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| chartType | int |  |

**Vrací:**
boolean
### isChartTypeLine(int chartType) {#isChartTypeLine-int-}
```
public static boolean isChartTypeLine(int chartType)
```

Vrátí true, pokud je chartType jedním z podtypů Line. Množina podtypů odpovídá příslušné množině v PowerPointu (viz dialog "Change Chart Type" v PowerPointu): [ChartType.Line](../../com.aspose.slides/charttype\#Line), [ChartType.LineWithMarkers](../../com.aspose.slides/charttype\#LineWithMarkers), [ChartType.PercentsStackedLine](../../com.aspose.slides/charttype\#PercentsStackedLine), [ChartType.PercentsStackedLineWithMarkers](../../com.aspose.slides/charttype\#PercentsStackedLineWithMarkers), [ChartType.StackedLine](../../com.aspose.slides/charttype\#StackedLine), [ChartType.StackedLineWithMarkers](../../com.aspose.slides/charttype\#StackedLineWithMarkers), [ChartType.Line3D](../../com.aspose.slides/charttype\#Line3D).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| chartType | int |  |

**Vrací:**
boolean
### isChartTypePie(int chartType) {#isChartTypePie-int-}
```
public static boolean isChartTypePie(int chartType)
```

Vrátí true, pokud je chartType jedním z podtypů Pie. Množina podtypů odpovídá příslušné množině v PowerPointu (viz dialog "Change Chart Type" v PowerPointu): [ChartType.BarOfPie](../../com.aspose.slides/charttype\#BarOfPie), [ChartType.ExplodedPie](../../com.aspose.slides/charttype\#ExplodedPie), [ChartType.ExplodedPie3D](../../com.aspose.slides/charttype\#ExplodedPie3D), [ChartType.Pie](../../com.aspose.slides/charttype\#Pie), [ChartType.Pie3D](../../com.aspose.slides/charttype\#Pie3D), [ChartType.PieOfPie](../../com.aspose.slides/charttype\#PieOfPie).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| chartType | int |  |

**Vrací:**
boolean
### isChartTypeBar(int chartType) {#isChartTypeBar-int-}
```
public static boolean isChartTypeBar(int chartType)
```

Vrátí true, pokud je chartType jedním z podtypů Bar. Množina podtypů odpovídá příslušné množině v PowerPointu (viz dialog "Change Chart Type" v PowerPointu): [ChartType.ClusteredBar](../../com.aspose.slides/charttype\#ClusteredBar), [ChartType.ClusteredBar3D](../../com.aspose.slides/charttype\#ClusteredBar3D), [ChartType.PercentsStackedBar](../../com.aspose.slides/charttype\#PercentsStackedBar), [ChartType.PercentsStackedBar3D](../../com.aspose.slides/charttype\#PercentsStackedBar3D), [ChartType.StackedBar](../../com.aspose.slides/charttype\#StackedBar), [ChartType.StackedBar3D](../../com.aspose.slides/charttype\#StackedBar3D), [ChartType.ClusteredHorizontalCone](../../com.aspose.slides/charttype\#ClusteredHorizontalCone), [ChartType.ClusteredHorizontalCylinder](../../com.aspose.slides/charttype\#ClusteredHorizontalCylinder), [ChartType.ClusteredHorizontalPyramid](../../com.aspose.slides/charttype\#ClusteredHorizontalPyramid), [ChartType.StackedHorizontalCone](../../com.aspose.slides/charttype\#StackedHorizontalCone), [ChartType.StackedHorizontalCylinder](../../com.aspose.slides/charttype\#StackedHorizontalCylinder), [ChartType.StackedHorizontalPyramid](../../com.aspose.slides/charttype\#StackedHorizontalPyramid), [ChartType.PercentsStackedHorizontalCone](../../com.aspose.slides/charttype\#PercentsStackedHorizontalCone), [ChartType.PercentsStackedHorizontalCylinder](../../com.aspose.slides/charttype\#PercentsStackedHorizontalCylinder), [ChartType.PercentsStackedHorizontalPyramid](../../com.aspose.slides/charttype\#PercentsStackedHorizontalPyramid).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| chartType | int |  |

**Vrací:**
boolean
### isChartTypeArea(int chartType) {#isChartTypeArea-int-}
```
public static boolean isChartTypeArea(int chartType)
```

Vrátí true, pokud je chartType jedním z podtypů Area. Množina podtypů odpovídá příslušné množině v PowerPointu (viz dialog "Change Chart Type" v PowerPointu): [ChartType.Area](../../com.aspose.slides/charttype\#Area), [ChartType.PercentsStackedArea](../../com.aspose.slides/charttype\#PercentsStackedArea), [ChartType.PercentsStackedArea3D](../../com.aspose.slides/charttype\#PercentsStackedArea3D), [ChartType.StackedArea](../../com.aspose.slides/charttype\#StackedArea), [ChartType.StackedArea3D](../../com.aspose.slides/charttype\#StackedArea3D), [ChartType.Area3D](../../com.aspose.slides/charttype\#Area3D).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| chartType | int |  |

**Vrací:**
boolean
### isChartTypeScatter(int chartType) {#isChartTypeScatter-int-}
```
public static boolean isChartTypeScatter(int chartType)
```

Vrátí true, pokud je chartType jedním z podtypů Scatter. Množina podtypů odpovídá příslušné množině v PowerPointu (viz dialog "Change Chart Type" v PowerPointu): [ChartType.ScatterWithMarkers](../../com.aspose.slides/charttype\#ScatterWithMarkers), [ChartType.ScatterWithSmoothLines](../../com.aspose.slides/charttype\#ScatterWithSmoothLines), [ChartType.ScatterWithSmoothLinesAndMarkers](../../com.aspose.slides/charttype\#ScatterWithSmoothLinesAndMarkers), [ChartType.ScatterWithStraightLines](../../com.aspose.slides/charttype\#ScatterWithStraightLines), [ChartType.ScatterWithStraightLinesAndMarkers](../../com.aspose.slides/charttype\#ScatterWithStraightLinesAndMarkers).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| chartType | int |  |

**Vrací:**
boolean
### isChartTypeStock(int chartType) {#isChartTypeStock-int-}
```
public static boolean isChartTypeStock(int chartType)
```

Vrátí true, pokud je chartType jedním z podtypů Stock. Množina podtypů odpovídá příslušné množině v PowerPointu (viz dialog "Change Chart Type" v PowerPointu): [ChartType.HighLowClose](../../com.aspose.slides/charttype\#HighLowClose), [ChartType.OpenHighLowClose](../../com.aspose.slides/charttype\#OpenHighLowClose), [ChartType.VolumeHighLowClose](../../com.aspose.slides/charttype\#VolumeHighLowClose), [ChartType.VolumeOpenHighLowClose](../../com.aspose.slides/charttype\#VolumeOpenHighLowClose).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| chartType | int |  |

**Vrací:**
boolean
### isChartTypeSurface(int chartType) {#isChartTypeSurface-int-}
```
public static boolean isChartTypeSurface(int chartType)
```

Vrátí true, pokud je chartType jedním z podtypů Surface. Množina podtypů odpovídá příslušné množině v PowerPointu (viz dialog "Change Chart Type" v PowerPointu): [ChartType.Surface3D](../../com.aspose.slides/charttype\#Surface3D), [ChartType.WireframeSurface3D](../../com.aspose.slides/charttype\#WireframeSurface3D), [ChartType.Contour](../../com.aspose.slides/charttype\#Contour), [ChartType.WireframeContour](../../com.aspose.slides/charttype\#WireframeContour).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| chartType | int |  |

**Vrací:**
boolean
### isChartTypeDoughnut(int chartType) {#isChartTypeDoughnut-int-}
```
public static boolean isChartTypeDoughnut(int chartType)
```

Vrátí true, pokud je chartType jedním z podtypů Doughnut. Množina podtypů odpovídá příslušné množině v PowerPointu (viz dialog "Change Chart Type" v PowerPointu): [ChartType.Doughnut](../../com.aspose.slides/charttype\#Doughnut), [ChartType.ExplodedDoughnut](../../com.aspose.slides/charttype\#ExplodedDoughnut).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| chartType | int |  |

**Vrací:**
boolean
### isChartTypeBubble(int chartType) {#isChartTypeBubble-int-}
```
public static boolean isChartTypeBubble(int chartType)
```

Vrátí true, pokud je chartType jedním z podtypů Bubble. Množina podtypů odpovídá příslušné množině v PowerPointu (viz dialog "Change Chart Type" v PowerPointu): [ChartType.Bubble](../../com.aspose.slides/charttype\#Bubble), [ChartType.BubbleWith3D](../../com.aspose.slides/charttype\#BubbleWith3D).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| chartType | int |  |

**Vrací:**
boolean
### isChartTypeRadar(int chartType) {#isChartTypeRadar-int-}
```
public static boolean isChartTypeRadar(int chartType)
```

Vrátí true, pokud je chartType jedním z podtypů Radar. Množina podtypů odpovídá příslušné množině v PowerPointu (viz dialog "Change Chart Type" v PowerPointu): [ChartType.FilledRadar](../../com.aspose.slides/charttype\#FilledRadar), [ChartType.Radar](../../com.aspose.slides/charttype\#Radar), [ChartType.RadarWithMarkers](../../com.aspose.slides/charttype\#RadarWithMarkers).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| chartType | int |  |

**Vrací:**
boolean
### isSeriesUsesXValueCoordinate(int seriesType) {#isSeriesUsesXValueCoordinate-int-}
```
public static boolean isSeriesUsesXValueCoordinate(int seriesType)
```

Vrací, zda zadaný typ series používá X souřadnice hodnot.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| seriesType | int | Series type. |

**Vrací:**
boolean - True if uses otherwise false.
### isSeriesUsesYValueCoordinate(int seriesType) {#isSeriesUsesYValueCoordinate-int-}
```
public static boolean isSeriesUsesYValueCoordinate(int seriesType)
```

Vrací, zda zadaný typ series používá Y souřadnice hodnot.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| seriesType | int | Series type. |

**Vrací:**
boolean - True if uses otherwise false.
### isSeriesUsesValueCoordinate(int seriesType) {#isSeriesUsesValueCoordinate-int-}
```
public static boolean isSeriesUsesValueCoordinate(int seriesType)
```

Vrací, zda zadaný typ series používá souřadnice hodnot.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| seriesType | int | Series type. |

**Vrací:**
boolean - True if uses otherwise false.
### isSeriesUsesBubbleSizeCoordinate(int seriesType) {#isSeriesUsesBubbleSizeCoordinate-int-}
```
public static boolean isSeriesUsesBubbleSizeCoordinate(int seriesType)
```

Vrací, zda lze pro zadaný typ series použít souřadnice velikosti bublin.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| seriesType | int | Series type. |

**Vrací:**
boolean - True if can be used, otherwise false.
### hasSeriesTrendLines(int seriesType) {#hasSeriesTrendLines-int-}
```
public static boolean hasSeriesTrendLines(int seriesType)
```

Vrací, zda existují trendové čáry série pro zadaný typ series.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| seriesType | int | Series type. |

**Vrací:**
boolean - True if present otherwise false.
### isErrorBarsXAllowed(int seriesType) {#isErrorBarsXAllowed-int-}
```
public static boolean isErrorBarsXAllowed(int seriesType)
```

Vrací, zda jsou povoleny chybové pruhy X pro zadaný typ series.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| seriesType | int | Series type. |

**Vrací:**
boolean - True if allowed, otherwise false.
### isErrorBarsYAllowed(int seriesType) {#isErrorBarsYAllowed-int-}
```
public static boolean isErrorBarsYAllowed(int seriesType)
```

Vrací, zda jsou povoleny chybové pruhy Y pro zadaný typ series.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| seriesType | int | Series type. |

**Vrací:**
boolean - True if allowed, otherwise false.