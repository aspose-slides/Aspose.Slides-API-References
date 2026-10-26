---
title: ChartTypeCharacterizer
second_title: Referencia de API Java de Aspose.Slides para Android
description: Ayudante para obtener información adicional sobre gráficos y series mediante su ChartType.
type: docs
url: /es/com.aspose.slides/charttypecharacterizer/
---
**Herencia:**
java.lang.Object
```
public class ChartTypeCharacterizer
```

Ayudante para obtener información adicional sobre gráficos y series mediante su ChartType.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [ChartTypeCharacterizer()](#ChartTypeCharacterizer--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [isBar3DChart(int chartType)](#isBar3DChart-int-) | Devuelve true si chartType es uno de los subtipos bar3DChart (columnas o barras 3D). |
| [is2DChart(int chartType)](#is2DChart-int-) | Devuelve true si chartType es uno de los tipos de gráfico 2D. |
| [is3DChart(int chartType)](#is3DChart-int-) | Devuelve true si chartType es uno de los tipos de gráfico 3D. |
| [isChartTypeColumn(int chartType)](#isChartTypeColumn-int-) | Devuelve true si chartType es uno de los subtipos Column. |
| [isChartTypeLine(int chartType)](#isChartTypeLine-int-) | Devuelve true si chartType es uno de los subtipos Line. |
| [isChartTypePie(int chartType)](#isChartTypePie-int-) | Devuelve true si chartType es uno de los subtipos Pie. |
| [isChartTypeBar(int chartType)](#isChartTypeBar-int-) | Devuelve true si chartType es uno de los subtipos Bar. |
| [isChartTypeArea(int chartType)](#isChartTypeArea-int-) | Devuelve true si chartType es uno de los subtipos Area. |
| [isChartTypeScatter(int chartType)](#isChartTypeScatter-int-) | Devuelve true si chartType es uno de los subtipos Scatter. |
| [isChartTypeStock(int chartType)](#isChartTypeStock-int-) | Devuelve true si chartType es uno de los subtipos Stock. |
| [isChartTypeSurface(int chartType)](#isChartTypeSurface-int-) | Devuelve true si chartType es uno de los subtipos Surface. |
| [isChartTypeDoughnut(int chartType)](#isChartTypeDoughnut-int-) | Devuelve true si chartType es uno de los subtipos Doughnut. |
| [isChartTypeBubble(int chartType)](#isChartTypeBubble-int-) | Devuelve true si chartType es uno de los subtipos Bubble. |
| [isChartTypeRadar(int chartType)](#isChartTypeRadar-int-) | Devuelve true si chartType es uno de los subtipos Radar. |
| [isSeriesUsesXValueCoordinate(int seriesType)](#isSeriesUsesXValueCoordinate-int-) | Devuelve si el tipo de serie especificado usa coordenadas de valor X. |
| [isSeriesUsesYValueCoordinate(int seriesType)](#isSeriesUsesYValueCoordinate-int-) | Devuelve si el tipo de serie especificado usa coordenadas de valor Y. |
| [isSeriesUsesValueCoordinate(int seriesType)](#isSeriesUsesValueCoordinate-int-) | Devuelve si el tipo de serie especificado usa coordenadas de valor. |
| [isSeriesUsesBubbleSizeCoordinate(int seriesType)](#isSeriesUsesBubbleSizeCoordinate-int-) | Devuelve si se pueden usar coordenadas de tamaño de burbuja para el tipo de serie especificado. |
| [hasSeriesTrendLines(int seriesType)](#hasSeriesTrendLines-int-) | Devuelve si existen líneas de tendencia de serie para el tipo de serie especificado. |
| [isErrorBarsXAllowed(int seriesType)](#isErrorBarsXAllowed-int-) | Devuelve si se permiten barras de error X para el tipo de serie especificado. |
| [isErrorBarsYAllowed(int seriesType)](#isErrorBarsYAllowed-int-) | Devuelve si se permiten barras de error Y para el tipo de serie especificado. |
### ChartTypeCharacterizer() {#ChartTypeCharacterizer--}
```
public ChartTypeCharacterizer()
```


### isBar3DChart(int chartType) {#isBar3DChart-int-}
```
public static boolean isBar3DChart(int chartType)
```


Devuelve true si chartType es uno de los subtipos bar3DChart (columnas o barras 3D).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| chartType | int |  |

**Devuelve:**
boolean
### is2DChart(int chartType) {#is2DChart-int-}
```
public static boolean is2DChart(int chartType)
```


Devuelve true si chartType es uno de los tipos de gráfico 2D.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| chartType | int |  |

**Devuelve:**
boolean
### is3DChart(int chartType) {#is3DChart-int-}
```
public static boolean is3DChart(int chartType)
```


Devuelve true si chartType es uno de los tipos de gráfico 3D.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| chartType | int |  |

**Devuelve:**
boolean
### isChartTypeColumn(int chartType) {#isChartTypeColumn-int-}
```
public static boolean isChartTypeColumn(int chartType)
```


Devuelve true si chartType es uno de los subtipos Column. El conjunto de subtipos corresponde al conjunto apropiado en PowerPoint (ver diálogo "Change Chart Type" en PowerPoint): [ChartType.ClusteredColumn](../../com.aspose.slides/charttype\#ClusteredColumn), [ChartType.ClusteredColumn3D](../../com.aspose.slides/charttype\#ClusteredColumn3D), [ChartType.ClusteredCone](../../com.aspose.slides/charttype\#ClusteredCone), [ChartType.ClusteredCylinder](../../com.aspose.slides/charttype\#ClusteredCylinder), [ChartType.ClusteredPyramid](../../com.aspose.slides/charttype\#ClusteredPyramid), [ChartType.PercentsStackedColumn](../../com.aspose.slides/charttype\#PercentsStackedColumn), [ChartType.PercentsStackedColumn3D](../../com.aspose.slides/charttype\#PercentsStackedColumn3D), [ChartType.PercentsStackedCone](../../com.aspose.slides/charttype\#PercentsStackedCone), [ChartType.PercentsStackedCylinder](../../com.aspose.slides/charttype\#PercentsStackedCylinder), [ChartType.PercentsStackedPyramid](../../com.aspose.slides/charttype\#PercentsStackedPyramid), [ChartType.StackedColumn](../../com.aspose.slides/charttype\#StackedColumn), [ChartType.StackedColumn3D](../../com.aspose.slides/charttype\#StackedColumn3D), [ChartType.StackedCone](../../com.aspose.slides/charttype\#StackedCone), [ChartType.StackedCylinder](../../com.aspose.slides/charttype\#StackedCylinder), [ChartType.StackedPyramid](../../com.aspose.slides/charttype\#StackedPyramid), [ChartType.Column3D](../../com.aspose.slides/charttype\#Column3D), [ChartType.Cylinder3D](../../com.aspose.slides/charttype\#Cylinder3D), [ChartType.Cone3D](../../com.aspose.slides/charttype\#Cone3D), [ChartType.Pyramid3D](../../com.aspose.slides/charttype\#Pyramid3D).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| chartType | int |  |

**Devuelve:**
boolean
### isChartTypeLine(int chartType) {#isChartTypeLine-int-}
```
public static boolean isChartTypeLine(int chartType)
```


Devuelve true si chartType es uno de los subtipos Line. El conjunto de subtipos corresponde al conjunto apropiado en PowerPoint (ver diálogo "Change Chart Type" en PowerPoint): [ChartType.Line](../../com.aspose.slides/charttype\#Line), [ChartType.LineWithMarkers](../../com.aspose.slides/charttype\#LineWithMarkers), [ChartType.PercentsStackedLine](../../com.aspose.slides/charttype\#PercentsStackedLine), [ChartType.PercentsStackedLineWithMarkers](../../com.aspose.slides/charttype\#PercentsStackedLineWithMarkers), [ChartType.StackedLine](../../com.aspose.slides/charttype\#StackedLine), [ChartType.StackedLineWithMarkers](../../com.aspose.slides/charttype\#StackedLineWithMarkers), [ChartType.Line3D](../../com.aspose.slides/charttype\#Line3D).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| chartType | int |  |

**Devuelve:**
boolean
### isChartTypePie(int chartType) {#isChartTypePie-int-}
```
public static boolean isChartTypePie(int chartType)
```


Devuelve true si chartType es uno de los subtipos Pie. El conjunto de subtipos corresponde al conjunto apropiado en PowerPoint (ver diálogo "Change Chart Type" en PowerPoint): [ChartType.BarOfPie](../../com.aspose.slides/charttype\#BarOfPie), [ChartType.ExplodedPie](../../com.aspose.slides/charttype\#ExplodedPie), [ChartType.ExplodedPie3D](../../com.aspose.slides/charttype\#ExplodedPie3D), [ChartType.Pie](../../com.aspose.slides/charttype\#Pie), [ChartType.Pie3D](../../com.aspose.slides/charttype\#Pie3D), [ChartType.PieOfPie](../../com.aspose.slides/charttype\#PieOfPie).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| chartType | int |  |

**Devuelve:**
boolean
### isChartTypeBar(int chartType) {#isChartTypeBar-int-}
```
public static boolean isChartTypeBar(int chartType)
```


Devuelve true si chartType es uno de los subtipos Bar. El conjunto de subtipos corresponde al conjunto apropiado en PowerPoint (ver diálogo "Change Chart Type" en PowerPoint): [ChartType.ClusteredBar](../../com.aspose.slides/charttype\#ClusteredBar), [ChartType.ClusteredBar3D](../../com.aspose.slides/charttype\#ClusteredBar3D), [ChartType.PercentsStackedBar](../../com.aspose.slides/charttype\#PercentsStackedBar), [ChartType.PercentsStackedBar3D](../../com.aspose.slides/charttype\#PercentsStackedBar3D), [ChartType.StackedBar](../../com.aspose.slides/charttype\#StackedBar), [ChartType.StackedBar3D](../../com.aspose.slides/charttype\#StackedBar3D), [ChartType.ClusteredHorizontalCone](../../com.aspose.slides/charttype\#ClusteredHorizontalCone), [ChartType.ClusteredHorizontalCylinder](../../com.aspose.slides/charttype\#ClusteredHorizontalCylinder), [ChartType.ClusteredHorizontalPyramid](../../com.aspose.slides/charttype\#ClusteredHorizontalPyramid), [ChartType.StackedHorizontalCone](../../com.aspose.slides/charttype\#StackedHorizontalCone), [ChartType.StackedHorizontalCylinder](../../com.aspose.slides/charttype\#StackedHorizontalCylinder), [ChartType.StackedHorizontalPyramid](../../com.aspose.slides/charttype\#StackedHorizontalPyramid), [ChartType.PercentsStackedHorizontalCone](../../com.aspose.slides/charttype\#PercentsStackedHorizontalCone), [ChartType.PercentsStackedHorizontalCylinder](../../com.aspose.slides/charttype\#PercentsStackedHorizontalCylinder), [ChartType.PercentsStackedHorizontalPyramid](../../com.aspose.slides/charttype\#PercentsStackedHorizontalPyramid).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| chartType | int |  |

**Devuelve:**
boolean
### isChartTypeArea(int chartType) {#isChartTypeArea-int-}
```
public static boolean isChartTypeArea(int chartType)
```


Devuelve true si chartType es uno de los subtipos Area. El conjunto de subtipos corresponde al conjunto apropiado en PowerPoint (ver diálogo "Change Chart Type" en PowerPoint): [ChartType.Area](../../com.aspose.slides/charttype\#Area), [ChartType.PercentsStackedArea](../../com.aspose.slides/charttype\#PercentsStackedArea), [ChartType.PercentsStackedArea3D](../../com.aspose.slides/charttype\#PercentsStackedArea3D), [ChartType.StackedArea](../../com.aspose.slides/charttype\#StackedArea), [ChartType.StackedArea3D](../../com.aspose.slides/charttype\#StackedArea3D), [ChartType.Area3D](../../com.aspose.slides/charttype\#Area3D).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| chartType | int |  |

**Devuelve:**
boolean
### isChartTypeScatter(int chartType) {#isChartTypeScatter-int-}
```
public static boolean isChartTypeScatter(int chartType)
```


Devuelve true si chartType es uno de los subtipos Scatter. El conjunto de subtipos corresponde al conjunto apropiado en PowerPoint (ver diálogo "Change Chart Type" en PowerPoint): [ChartType.ScatterWithMarkers](../../com.aspose.slides/charttype\#ScatterWithMarkers), [ChartType.ScatterWithSmoothLines](../../com.aspose.slides/charttype\#ScatterWithSmoothLines), [ChartType.ScatterWithSmoothLinesAndMarkers](../../com.aspose.slides/charttype\#ScatterWithSmoothLinesAndMarkers), [ChartType.ScatterWithStraightLines](../../com.aspose.slides/charttype\#ScatterWithStraightLines), [ChartType.ScatterWithStraightLinesAndMarkers](../../com.aspose.slides/charttype\#ScatterWithStraightLinesAndMarkers).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| chartType | int |  |

**Devuelve:**
boolean
### isChartTypeStock(int chartType) {#isChartTypeStock-int-}
```
public static boolean isChartTypeStock(int chartType)
```


Devuelve true si chartType es uno de los subtipos Stock. El conjunto de subtipos corresponde al conjunto apropiado en PowerPoint (ver diálogo "Change Chart Type" en PowerPoint): [ChartType.HighLowClose](../../com.aspose.slides/charttype\#HighLowClose), [ChartType.OpenHighLowClose](../../com.aspose.slides/charttype\#OpenHighLowClose), [ChartType.VolumeHighLowClose](../../com.aspose.slides/charttype\#VolumeHighLowClose), [ChartType.VolumeOpenHighLowClose](../../com.aspose.slides/charttype\#VolumeOpenHighLowClose).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| chartType | int |  |

**Devuelve:**
boolean
### isChartTypeSurface(int chartType) {#isChartTypeSurface-int-}
```
public static boolean isChartTypeSurface(int chartType)
```


Devuelve true si chartType es uno de los subtipos Surface. El conjunto de subtipos corresponde al conjunto apropiado en PowerPoint (ver diálogo "Change Chart Type" en PowerPoint): [ChartType.Surface3D](../../com.aspose.slides/charttype\#Surface3D), [ChartType.WireframeSurface3D](../../com.aspose.slides/charttype\#WireframeSurface3D), [ChartType.Contour](../../com.aspose.slides/charttype\#Contour), [ChartType.WireframeContour](../../com.aspose.slides/charttype\#WireframeContour).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| chartType | int |  |

**Devuelve:**
boolean
### isChartTypeDoughnut(int chartType) {#isChartTypeDoughnut-int-}
```
public static boolean isChartTypeDoughnut(int chartType)
```


Devuelve true si chartType es uno de los subtipos Doughnut. El conjunto de subtipos corresponde al conjunto apropiado en PowerPoint (ver diálogo "Change Chart Type" en PowerPoint): [ChartType.Doughnut](../../com.aspose.slides/charttype\#Doughnut), [ChartType.ExplodedDoughnut](../../com.aspose.slides/charttype\#ExplodedDoughnut).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| chartType | int |  |

**Devuelve:**
boolean
### isChartTypeBubble(int chartType) {#isChartTypeBubble-int-}
```
public static boolean isChartTypeBubble(int chartType)
```


Devuelve true si chartType es uno de los subtipos Bubble. El conjunto de subtipos corresponde al conjunto apropiado en PowerPoint (ver diálogo "Change Chart Type" en PowerPoint): [ChartType.Bubble](../../com.aspose.slides/charttype\#Bubble), [ChartType.BubbleWith3D](../../com.aspose.slides/charttype\#BubbleWith3D).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| chartType | int |  |

**Devuelve:**
boolean
### isChartTypeRadar(int chartType) {#isChartTypeRadar-int-}
```
public static boolean isChartTypeRadar(int chartType)
```


Devuelve true si chartType es uno de los subtipos Radar. El conjunto de subtipos corresponde al conjunto apropiado en PowerPoint (ver diálogo "Change Chart Type" en PowerPoint): [ChartType.FilledRadar](../../com.aspose.slides/charttype\#FilledRadar), [ChartType.Radar](../../com.aspose.slides/charttype\#Radar), [ChartType.RadarWithMarkers](../../com.aspose.slides/charttype\#RadarWithMarkers).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| chartType | int |  |

**Devuelve:**
boolean
### isSeriesUsesXValueCoordinate(int seriesType) {#isSeriesUsesXValueCoordinate-int-}
```
public static boolean isSeriesUsesXValueCoordinate(int seriesType)
```


Devuelve si el tipo de serie especificado usa coordenadas de valor X.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| seriesType | int | Tipo de serie. |

**Devuelve:**
boolean - True si usa, de lo contrario false.
### isSeriesUsesYValueCoordinate(int seriesType) {#isSeriesUsesYValueCoordinate-int-}
```
public static boolean isSeriesUsesYValueCoordinate(int seriesType)
```


Devuelve si el tipo de serie especificado usa coordenadas de valor Y.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| seriesType | int | Tipo de serie. |

**Devuelve:**
boolean - True si usa, de lo contrario false.
### isSeriesUsesValueCoordinate(int seriesType) {#isSeriesUsesValueCoordinate-int-}
```
public static boolean isSeriesUsesValueCoordinate(int seriesType)
```


Devuelve si el tipo de serie especificado usa coordenadas de valor.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| seriesType | int | Tipo de serie. |

**Devuelve:**
boolean - True si usa, de lo contrario false.
### isSeriesUsesBubbleSizeCoordinate(int seriesType) {#isSeriesUsesBubbleSizeCoordinate-int-}
```
public static boolean isSeriesUsesBubbleSizeCoordinate(int seriesType)
```


Devuelve si se pueden usar coordenadas de tamaño de burbuja para el tipo de serie especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| seriesType | int | Tipo de serie. |

**Devuelve:**
boolean - True si se pueden usar, de lo contrario false.
### hasSeriesTrendLines(int seriesType) {#hasSeriesTrendLines-int-}
```
public static boolean hasSeriesTrendLines(int seriesType)
```


Devuelve si existen líneas de tendencia de serie para el tipo de serie especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| seriesType | int | Tipo de serie. |

**Devuelve:**
boolean - True si están presentes, de lo contrario false.
### isErrorBarsXAllowed(int seriesType) {#isErrorBarsXAllowed-int-}
```
public static boolean isErrorBarsXAllowed(int seriesType)
```


Devuelve si se permiten barras de error X para el tipo de serie especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| seriesType | int | Tipo de serie. |

**Devuelve:**
boolean - True si está permitido, de lo contrario false.
### isErrorBarsYAllowed(int seriesType) {#isErrorBarsYAllowed-int-}
```
public static boolean isErrorBarsYAllowed(int seriesType)
```


Devuelve si se permiten barras de error Y para el tipo de serie especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| seriesType | int | Tipo de serie. |

**Devuelve:**
boolean - True si está permitido, de lo contrario false.