---
title: ChartTypeCharacterizer
second_title: Aspose.Slides untuk Android via Referensi API Java
description: Pembantu untuk mendapatkan informasi tambahan tentang bagan dan seri berdasarkan ChartType-nya.
type: docs
url: /id/com.aspose.slides/charttypecharacterizer/
---
**Pewarisan:**
java.lang.Object
```
public class ChartTypeCharacterizer
```

Pembantu untuk mendapatkan informasi tambahan tentang bagan dan seri berdasarkan ChartType-nya.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [ChartTypeCharacterizer()](#ChartTypeCharacterizer--) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [isBar3DChart(int chartType)](#isBar3DChart-int-) | Mengembalikan true jika chartType adalah salah satu subtipe bar3DChart (kolom atau batang 3D). |
| [is2DChart(int chartType)](#is2DChart-int-) | Mengembalikan true jika chartType adalah salah satu tipe bagan 2D. |
| [is3DChart(int chartType)](#is3DChart-int-) | Mengembalikan true jika chartType adalah salah satu tipe bagan 3D. |
| [isChartTypeColumn(int chartType)](#isChartTypeColumn-int-) | Mengembalikan true jika chartType adalah salah satu subtipe Column. |
| [isChartTypeLine(int chartType)](#isChartTypeLine-int-) | Mengembalikan true jika chartType adalah salah satu subtipe Line. |
| [isChartTypePie(int chartType)](#isChartTypePie-int-) | Mengembalikan true jika chartType adalah salah satu subtipe Pie. |
| [isChartTypeBar(int chartType)](#isChartTypeBar-int-) | Mengembalikan true jika chartType adalah salah satu subtipe Bar. |
| [isChartTypeArea(int chartType)](#isChartTypeArea-int-) | Mengembalikan true jika chartType adalah salah satu subtipe Area. |
| [isChartTypeScatter(int chartType)](#isChartTypeScatter-int-) | Mengembalikan true jika chartType adalah salah satu subtipe Scatter. |
| [isChartTypeStock(int chartType)](#isChartTypeStock-int-) | Mengembalikan true jika chartType adalah salah satu subtipe Stock. |
| [isChartTypeSurface(int chartType)](#isChartTypeSurface-int-) | Mengembalikan true jika chartType adalah salah satu subtipe Surface. |
| [isChartTypeDoughnut(int chartType)](#isChartTypeDoughnut-int-) | Mengembalikan true jika chartType adalah salah satu subtipe Doughnut. |
| [isChartTypeBubble(int chartType)](#isChartTypeBubble-int-) | Mengembalikan true jika chartType adalah salah satu subtipe Bubble. |
| [isChartTypeRadar(int chartType)](#isChartTypeRadar-int-) | Mengembalikan true jika chartType adalah salah satu subtipe Radar. |
| [isSeriesUsesXValueCoordinate(int seriesType)](#isSeriesUsesXValueCoordinate-int-) | Mengembalikan jika tipe seri yang ditentukan menggunakan koordinat nilai X. |
| [isSeriesUsesYValueCoordinate(int seriesType)](#isSeriesUsesYValueCoordinate-int-) | Mengembalikan jika tipe seri yang ditentukan menggunakan koordinat nilai Y. |
| [isSeriesUsesValueCoordinate(int seriesType)](#isSeriesUsesValueCoordinate-int-) | Mengembalikan jika tipe seri yang ditentukan menggunakan koordinat nilai. |
| [isSeriesUsesBubbleSizeCoordinate(int seriesType)](#isSeriesUsesBubbleSizeCoordinate-int-) | Mengembalikan jika koordinat ukuran gelembung dapat digunakan untuk tipe seri yang ditentukan. |
| [hasSeriesTrendLines(int seriesType)](#hasSeriesTrendLines-int-) | Mengembalikan jika ada garis tren seri untuk tipe seri yang ditentukan. |
| [isErrorBarsXAllowed(int seriesType)](#isErrorBarsXAllowed-int-) | Mengembalikan jika bar galat X diizinkan untuk tipe seri yang ditentukan. |
| [isErrorBarsYAllowed(int seriesType)](#isErrorBarsYAllowed-int-) | Mengembalikan jika bar galat Y diizinkan untuk tipe seri yang ditentukan. |
### ChartTypeCharacterizer() {#ChartTypeCharacterizer--}
```
public ChartTypeCharacterizer()
```


### isBar3DChart(int chartType) {#isBar3DChart-int-}
```
public static boolean isBar3DChart(int chartType)
```


Mengembalikan true jika chartType adalah salah satu subtipe bar3DChart (kolom atau batang 3D).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| chartType | int |  |

**Mengembalikan:**
boolean
### is2DChart(int chartType) {#is2DChart-int-}
```
public static boolean is2DChart(int chartType)
```


Mengembalikan true jika chartType adalah salah satu tipe bagan 2D.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| chartType | int |  |

**Mengembalikan:**
boolean
### is3DChart(int chartType) {#is3DChart-int-}
```
public static boolean is3DChart(int chartType)
```


Mengembalikan true jika chartType adalah salah satu tipe bagan 3D.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| chartType | int |  |

**Mengembalikan:**
boolean
### isChartTypeColumn(int chartType) {#isChartTypeColumn-int-}
```
public static boolean isChartTypeColumn(int chartType)
```


Mengembalikan true jika chartType adalah salah satu subtipe Column. Set subtipe sesuai dengan set yang ada di PowerPoint (lihat dialog "Change Chart Type" di PowerPoint): [ChartType.ClusteredColumn](../../com.aspose.slides/charttype\#ClusteredColumn), [ChartType.ClusteredColumn3D](../../com.aspose.slides/charttype\#ClusteredColumn3D), [ChartType.ClusteredCone](../../com.aspose.slides/charttype\#ClusteredCone), [ChartType.ClusteredCylinder](../../com.aspose.slides/charttype\#ClusteredCylinder), [ChartType.ClusteredPyramid](../../com.aspose.slides/charttype\#ClusteredPyramid), [ChartType.PercentsStackedColumn](../../com.aspose.slides/charttype\#PercentsStackedColumn), [ChartType.PercentsStackedColumn3D](../../com.aspose.slides/charttype\#PercentsStackedColumn3D), [ChartType.PercentsStackedCone](../../com.aspose.slides/charttype\#PercentsStackedCone), [ChartType.PercentsStackedCylinder](../../com.aspose.slides/charttype\#PercentsStackedCylinder), [ChartType.PercentsStackedPyramid](../../com.aspose.slides/charttype\#PercentsStackedPyramid), [ChartType.StackedColumn](../../com.aspose.slides/charttype\#StackedColumn), [ChartType.StackedColumn3D](../../com.aspose.slides/charttype\#StackedColumn3D), [ChartType.StackedCone](../../com.aspose.slides/charttype\#StackedCone), [ChartType.StackedCylinder](../../com.aspose.slides/charttype\#StackedCylinder), [ChartType.StackedPyramid](../../com.aspose.slides/charttype\#StackedPyramid), [ChartType.Column3D](../../com.aspose.slides/charttype\#Column3D), [ChartType.Cylinder3D](../../com.aspose.slides/charttype\#Cylinder3D), [ChartType.Cone3D](../../com.aspose.slides/charttype\#Cone3D), [ChartType.Pyramid3D](../../com.aspose.slides/charttype\#Pyramid3D).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| chartType | int |  |

**Mengembalikan:**
boolean
### isChartTypeLine(int chartType) {#isChartTypeLine-int-}
```
public static boolean isChartTypeLine(int chartType)
```


Mengembalikan true jika chartType adalah salah satu subtipe Line. Set subtipe sesuai dengan set yang ada di PowerPoint (lihat dialog "Change Chart Type" di PowerPoint): [ChartType.Line](../../com.aspose.slides/charttype\#Line), [ChartType.LineWithMarkers](../../com.aspose.slides/charttype\#LineWithMarkers), [ChartType.PercentsStackedLine](../../com.aspose.slides/charttype\#PercentsStackedLine), [ChartType.PercentsStackedLineWithMarkers](../../com.aspose.slides/charttype\#PercentsStackedLineWithMarkers), [ChartType.StackedLine](../../com.aspose.slides/charttype\#StackedLine), [ChartType.StackedLineWithMarkers](../../com.aspose.slides/charttype\#StackedLineWithMarkers), [ChartType.Line3D](../../com.aspose.slides/charttype\#Line3D).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| chartType | int |  |

**Mengembalikan:**
boolean
### isChartTypePie(int chartType) {#isChartTypePie-int-}
```
public static boolean isChartTypePie(int chartType)
```


Mengembalikan true jika chartType adalah salah satu subtipe Pie. Set subtipe sesuai dengan set yang ada di PowerPoint (lihat dialog "Change Chart Type" di PowerPoint): [ChartType.BarOfPie](../../com.aspose.slides/charttype\#BarOfPie), [ChartType.ExplodedPie](../../com.aspose.slides/charttype\#ExplodedPie), [ChartType.ExplodedPie3D](../../com.aspose.slides/charttype\#ExplodedPie3D), [ChartType.Pie](../../com.aspose.slides/charttype\#Pie), [ChartType.Pie3D](../../com.aspose.slides/charttype\#Pie3D), [ChartType.PieOfPie](../../com.aspose.slides/charttype\#PieOfPie).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| chartType | int |  |

**Mengembalikan:**
boolean
### isChartTypeBar(int chartType) {#isChartTypeBar-int-}
```
public static boolean isChartTypeBar(int chartType)
```


Mengembalikan true jika chartType adalah salah satu subtipe Bar. Set subtipe sesuai dengan set yang ada di PowerPoint (lihat dialog "Change Chart Type" di PowerPoint): [ChartType.ClusteredBar](../../com.aspose.slides/charttype\#ClusteredBar), [ChartType.ClusteredBar3D](../../com.aspose.slides/charttype\#ClusteredBar3D), [ChartType.PercentsStackedBar](../../com.aspose.slides/charttype\#PercentsStackedBar), [ChartType.PercentsStackedBar3D](../../com.aspose.slides/charttype\#PercentsStackedBar3D), [ChartType.StackedBar](../../com.aspose.slides/charttype\#StackedBar), [ChartType.StackedBar3D](../../com.aspose.slides/charttype\#StackedBar3D), [ChartType.ClusteredHorizontalCone](../../com.aspose.slides/charttype\#ClusteredHorizontalCone), [ChartType.ClusteredHorizontalCylinder](../../com.aspose.slides/charttype\#ClusteredHorizontalCylinder), [ChartType.ClusteredHorizontalPyramid](../../com.aspose.slides/charttype\#ClusteredHorizontalPyramid), [ChartType.StackedHorizontalCone](../../com.aspose.slides/charttype\#StackedHorizontalCone), [ChartType.StackedHorizontalCylinder](../../com.aspose.slides/charttype\#StackedHorizontalCylinder), [ChartType.StackedHorizontalPyramid](../../com.aspose.slides/charttype\#StackedHorizontalPyramid), [ChartType.PercentsStackedHorizontalCone](../../com.aspose.slides/charttype\#PercentsStackedHorizontalCone), [ChartType.PercentsStackedHorizontalCylinder](../../com.aspose.slides/charttype\#PercentsStackedHorizontalCylinder), [ChartType.PercentsStackedHorizontalPyramid](../../com.aspose.slides/charttype\#PercentsStackedHorizontalPyramid).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| chartType | int |  |

**Mengembalikan:**
boolean
### isChartTypeArea(int chartType) {#isChartTypeArea-int-}
```
public static boolean isChartTypeArea(int chartType)
```


Mengembalikan true jika chartType adalah salah satu subtipe Area. Set subtipe sesuai dengan set yang ada di PowerPoint (lihat dialog "Change Chart Type" di PowerPoint): [ChartType.Area](../../com.aspose.slides/charttype\#Area), [ChartType.PercentsStackedArea](../../com.aspose.slides/charttype\#PercentsStackedArea), [ChartType.PercentsStackedArea3D](../../com.aspose.slides/charttype\#PercentsStackedArea3D), [ChartType.StackedArea](../../com.aspose.slides/charttype\#StackedArea), [ChartType.StackedArea3D](../../com.aspose.slides/charttype\#StackedArea3D), [ChartType.Area3D](../../com.aspose.slides/charttype\#Area3D).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| chartType | int |  |

**Mengembalikan:**
boolean
### isChartTypeScatter(int chartType) {#isChartTypeScatter-int-}
```
public static boolean isChartTypeScatter(int chartType)
```


Mengembalikan true jika chartType adalah salah satu subtipe Scatter. Set subtipe sesuai dengan set yang ada di PowerPoint (lihat dialog "Change Chart Type" di PowerPoint): [ChartType.ScatterWithMarkers](../../com.aspose.slides/charttype\#ScatterWithMarkers), [ChartType.ScatterWithSmoothLines](../../com.aspose.slides/charttype\#ScatterWithSmoothLines), [ChartType.ScatterWithSmoothLinesAndMarkers](../../com.aspose.slides/charttype\#ScatterWithSmoothLinesAndMarkers), [ChartType.ScatterWithStraightLines](../../com.aspose.slides/charttype\#ScatterWithStraightLines), [ChartType.ScatterWithStraightLinesAndMarkers](../../com.aspose.slides/charttype\#ScatterWithStraightLinesAndMarkers).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| chartType | int |  |

**Mengembalikan:**
boolean
### isChartTypeStock(int chartType) {#isChartTypeStock-int-}
```
public static boolean isChartTypeStock(int chartType)
```


Mengembalikan true jika chartType adalah salah satu subtipe Stock. Set subtipe sesuai dengan set yang ada di PowerPoint (lihat dialog "Change Chart Type" di PowerPoint): [ChartType.HighLowClose](../../com.aspose.slides/charttype\#HighLowClose), [ChartType.OpenHighLowClose](../../com.aspose.slides/charttype\#OpenHighLowClose), [ChartType.VolumeHighLowClose](../../com.aspose.slides/charttype\#VolumeHighLowClose), [ChartType.VolumeOpenHighLowClose](../../com.aspose.slides/charttype\#VolumeOpenHighLowClose).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| chartType | int |  |

**Mengembalikan:**
boolean
### isChartTypeSurface(int chartType) {#isChartTypeSurface-int-}
```
public static boolean isChartTypeSurface(int chartType)
```


Mengembalikan true jika chartType adalah salah satu subtipe Surface. Set subtipe sesuai dengan set yang ada di PowerPoint (lihat dialog "Change Chart Type" di PowerPoint): [ChartType.Surface3D](../../com.aspose.slides/charttype\#Surface3D), [ChartType.WireframeSurface3D](../../com.aspose.slides/charttype\#WireframeSurface3D), [ChartType.Contour](../../com.aspose.slides/charttype\#Contour), [ChartType.WireframeContour](../../com.aspose.slides/charttype\#WireframeContour).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| chartType | int |  |

**Mengembalikan:**
boolean
### isChartTypeDoughnut(int chartType) {#isChartTypeDoughnut-int-}
```
public static boolean isChartTypeDoughnut(int chartType)
```


Mengembalikan true jika chartType adalah salah satu subtipe Doughnut. Set subtipe sesuai dengan set yang ada di PowerPoint (lihat dialog "Change Chart Type" di PowerPoint): [ChartType.Doughnut](../../com.aspose.slides/charttype\#Doughnut), [ChartType.ExplodedDoughnut](../../com.aspose.slides/charttype\#ExplodedDoughnut).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| chartType | int |  |

**Mengembalikan:**
boolean
### isChartTypeBubble(int chartType) {#isChartTypeBubble-int-}
```
public static boolean isChartTypeBubble(int chartType)
```


Mengembalikan true jika chartType adalah salah satu subtipe Bubble. Set subtipe sesuai dengan set yang ada di PowerPoint (lihat dialog "Change Chart Type" di PowerPoint): [ChartType.Bubble](../../com.aspose.slides/charttype\#Bubble), [ChartType.BubbleWith3D](../../com.aspose.slides/charttype\#BubbleWith3D).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| chartType | int |  |

**Mengembalikan:**
boolean
### isChartTypeRadar(int chartType) {#isChartTypeRadar-int-}
```
public static boolean isChartTypeRadar(int chartType)
```


Mengembalikan true jika chartType adalah salah satu subtipe Radar. Set subtipe sesuai dengan set yang ada di PowerPoint (lihat dialog "Change Chart Type" di PowerPoint): [ChartType.FilledRadar](../../com.aspose.slides/charttype\#FilledRadar), [ChartType.Radar](../../com.aspose.slides/charttype\#Radar), [ChartType.RadarWithMarkers](../../com.aspose.slides/charttype\#RadarWithMarkers).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| chartType | int |  |

**Mengembalikan:**
boolean
### isSeriesUsesXValueCoordinate(int seriesType) {#isSeriesUsesXValueCoordinate-int-}
```
public static boolean isSeriesUsesXValueCoordinate(int seriesType)
```


Mengembalikan jika tipe seri yang ditentukan menggunakan koordinat nilai X.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| seriesType | int | Tipe seri. |

**Mengembalikan:**
boolean - True if uses otherwise false.
### isSeriesUsesYValueCoordinate(int seriesType) {#isSeriesUsesYValueCoordinate-int-}
```
public static boolean isSeriesUsesYValueCoordinate(int seriesType)
```


Mengembalikan jika tipe seri yang ditentukan menggunakan koordinat nilai Y.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| seriesType | int | Tipe seri. |

**Mengembalikan:**
boolean - True if uses otherwise false.
### isSeriesUsesValueCoordinate(int seriesType) {#isSeriesUsesValueCoordinate-int-}
```
public static boolean isSeriesUsesValueCoordinate(int seriesType)
```


Mengembalikan jika tipe seri yang ditentukan menggunakan koordinat nilai.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| seriesType | int | Tipe seri. |

**Mengembalikan:**
boolean - True if uses otherwise false.
### isSeriesUsesBubbleSizeCoordinate(int seriesType) {#isSeriesUsesBubbleSizeCoordinate-int-}
```
public static boolean isSeriesUsesBubbleSizeCoordinate(int seriesType)
```


Mengembalikan jika koordinat ukuran gelembung dapat digunakan untuk tipe seri yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| seriesType | int | Tipe seri. |

**Mengembalikan:**
boolean - True if can be used, otherwise false.
### hasSeriesTrendLines(int seriesType) {#hasSeriesTrendLines-int-}
```
public static boolean hasSeriesTrendLines(int seriesType)
```


Mengembalikan jika ada garis tren seri untuk tipe seri yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| seriesType | int | Tipe seri. |

**Mengembalikan:**
boolean - True if present otherwise false.
### isErrorBarsXAllowed(int seriesType) {#isErrorBarsXAllowed-int-}
```
public static boolean isErrorBarsXAllowed(int seriesType)
```


Mengembalikan jika bar galat X diizinkan untuk tipe seri yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| seriesType | int | Tipe seri. |

**Mengembalikan:**
boolean - True if allowed, otherwise false.
### isErrorBarsYAllowed(int seriesType) {#isErrorBarsYAllowed-int-}
```
public static boolean isErrorBarsYAllowed(int seriesType)
```


Mengembalikan jika bar galat Y diizinkan untuk tipe seri yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| seriesType | int | Tipe seri. |

**Mengembalikan:**
boolean - True if allowed, otherwise false.