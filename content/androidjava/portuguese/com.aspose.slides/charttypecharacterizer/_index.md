---
title: ChartTypeCharacterizer
second_title: Aspose.Slides para Android via Referência da API Java
description: Auxiliar para obter informações adicionais sobre gráficos e séries pelo seu ChartType.
type: docs
url: /pt/com.aspose.slides/charttypecharacterizer/
---
**Herança:**
java.lang.Object
```
public class ChartTypeCharacterizer
```

Auxiliar para obter informações adicionais sobre gráficos e séries pelo seu ChartType.
## Construtores

| Construtor | Descrição |
| --- | --- |
| [ChartTypeCharacterizer()](#ChartTypeCharacterizer--) |  |
## Métodos

| Método | Descrição |
| --- | --- |
| [isBar3DChart(int chartType)](#isBar3DChart-int-) | Retorna true se chartType for um dos subtipos bar3DChart (colunas ou barras 3D). |
| [is2DChart(int chartType)](#is2DChart-int-) | Retorna true se chartType for um dos tipos de gráfico 2D. |
| [is3DChart(int chartType)](#is3DChart-int-) | Retorna true se chartType for um dos tipos de gráfico 3D. |
| [isChartTypeColumn(int chartType)](#isChartTypeColumn-int-) | Retorna true se chartType for um dos subtipos Column. |
| [isChartTypeLine(int chartType)](#isChartTypeLine-int-) | Retorna true se chartType for um dos subtipos Line. |
| [isChartTypePie(int chartType)](#isChartTypePie-int-) | Retorna true se chartType for um dos subtipos Pie. |
| [isChartTypeBar(int chartType)](#isChartTypeBar-int-) | Retorna true se chartType for um dos subtipos Bar. |
| [isChartTypeArea(int chartType)](#isChartTypeArea-int-) | Retorna true se chartType for um dos subtipos Area. |
| [isChartTypeScatter(int chartType)](#isChartTypeScatter-int-) | Retorna true se chartType for um dos subtipos Scatter. |
| [isChartTypeStock(int chartType)](#isChartTypeStock-int-) | Retorna true se chartType for um dos subtipos Stock. |
| [isChartTypeSurface(int chartType)](#isChartTypeSurface-int-) | Retorna true se chartType for um dos subtipos Surface. |
| [isChartTypeDoughnut(int chartType)](#isChartTypeDoughnut-int-) | Retorna true se chartType for um dos subtipos Doughnut. |
| [isChartTypeBubble(int chartType)](#isChartTypeBubble-int-) | Retorna true se chartType for um dos subtipos Bubble. |
| [isChartTypeRadar(int chartType)](#isChartTypeRadar-int-) | Retorna true se chartType for um dos subtipos Radar. |
| [isSeriesUsesXValueCoordinate(int seriesType)](#isSeriesUsesXValueCoordinate-int-) | Retorna se o tipo de série especificado usa coordenadas de valor X. |
| [isSeriesUsesYValueCoordinate(int seriesType)](#isSeriesUsesYValueCoordinate-int-) | Retorna se o tipo de série especificado usa coordenadas de valor Y. |
| [isSeriesUsesValueCoordinate(int seriesType)](#isSeriesUsesValueCoordinate-int-) | Retorna se o tipo de série especificado usa coordenadas de valor. |
| [isSeriesUsesBubbleSizeCoordinate(int seriesType)](#isSeriesUsesBubbleSizeCoordinate-int-) | Retorna se as coordenadas de tamanho de bolha podem ser usadas para o tipo de série especificado. |
| [hasSeriesTrendLines(int seriesType)](#hasSeriesTrendLines-int-) | Retorna se há linhas de tendência de série para o tipo de série especificado. |
| [isErrorBarsXAllowed(int seriesType)](#isErrorBarsXAllowed-int-) | Retorna se barras de erro X são permitidas para o tipo de série especificado. |
| [isErrorBarsYAllowed(int seriesType)](#isErrorBarsYAllowed-int-) | Retorna se barras de erro Y são permitidas para o tipo de série especificado. |
### ChartTypeCharacterizer() {#ChartTypeCharacterizer--}
```
public ChartTypeCharacterizer()
```


### isBar3DChart(int chartType) {#isBar3DChart-int-}
```
public static boolean isBar3DChart(int chartType)
```


Retorna true se chartType for um dos subtipos bar3DChart (colunas ou barras 3D).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| chartType | int |  |

**Retorna:**
boolean
### is2DChart(int chartType) {#is2DChart-int-}
```
public static boolean is2DChart(int chartType)
```


Retorna true se chartType for um dos tipos de gráfico 2D.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| chartType | int |  |

**Retorna:**
boolean
### is3DChart(int chartType) {#is3DChart-int-}
```
public static boolean is3DChart(int chartType)
```


Retorna true se chartType for um dos tipos de gráfico 3D.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| chartType | int |  |

**Retorna:**
boolean
### isChartTypeColumn(int chartType) {#isChartTypeColumn-int-}
```
public static boolean isChartTypeColumn(int chartType)
```


Retorna true se chartType for um dos subtipos Column. O conjunto de subtipos corresponde ao conjunto apropriado no PowerPoint (veja a caixa de diálogo "Change Chart Type" no PowerPoint): [ChartType.ClusteredColumn](../../com.aspose.slides/charttype\#ClusteredColumn), [ChartType.ClusteredColumn3D](../../com.aspose.slides/charttype\#ClusteredColumn3D), [ChartType.ClusteredCone](../../com.aspose.slides/charttype\#ClusteredCone), [ChartType.ClusteredCylinder](../../com.aspose.slides/charttype\#ClusteredCylinder), [ChartType.ClusteredPyramid](../../com.aspose.slides/charttype\#ClusteredPyramid), [ChartType.PercentsStackedColumn](../../com.aspose.slides/charttype\#PercentsStackedColumn), [ChartType.PercentsStackedColumn3D](../../com.aspose.slides/charttype\#PercentsStackedColumn3D), [ChartType.PercentsStackedCone](../../com.aspose.slides/charttype\#PercentsStackedCone), [ChartType.PercentsStackedCylinder](../../com.aspose.slides/charttype\#PercentsStackedCylinder), [ChartType.PercentsStackedPyramid](../../com.aspose.slides/charttype\#PercentsStackedPyramid), [ChartType.StackedColumn](../../com.aspose.slides/charttype\#StackedColumn), [ChartType.StackedColumn3D](../../com.aspose.slides/charttype\#StackedColumn3D), [ChartType.StackedCone](../../com.aspose.slides/charttype\#StackedCone), [ChartType.StackedCylinder](../../com.aspose.slides/charttype\#StackedCylinder), [ChartType.StackedPyramid](../../com.aspose.slides/charttype\#StackedPyramid), [ChartType.Column3D](../../com.aspose.slides/charttype\#Column3D), [ChartType.Cylinder3D](../../com.aspose.slides/charttype\#Cylinder3D), [ChartType.Cone3D](../../com.aspose.slides/charttype\#Cone3D), [ChartType.Pyramid3D](../../com.aspose.slides/charttype\#Pyramid3D).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| chartType | int |  |

**Retorna:**
boolean
### isChartTypeLine(int chartType) {#isChartTypeLine-int-}
```
public static boolean isChartTypeLine(int chartType)
```


Retorna true se chartType for um dos subtipos Line. O conjunto de subtipos corresponde ao conjunto apropriado no PowerPoint (veja a caixa de diálogo "Change Chart Type" no PowerPoint): [ChartType.Line](../../com.aspose.slides/charttype\#Line), [ChartType.LineWithMarkers](../../com.aspose.slides/charttype\#LineWithMarkers), [ChartType.PercentsStackedLine](../../com.aspose.slides/charttype\#PercentsStackedLine), [ChartType.PercentsStackedLineWithMarkers](../../com.aspose.slides/charttype\#PercentsStackedLineWithMarkers), [ChartType.StackedLine](../../com.aspose.slides/charttype\#StackedLine), [ChartType.StackedLineWithMarkers](../../com.aspose.slides/charttype\#StackedLineWithMarkers), [ChartType.Line3D](../../com.aspose.slides/charttype\#Line3D).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| chartType | int |  |

**Retorna:**
boolean
### isChartTypePie(int chartType) {#isChartTypePie-int-}
```
public static boolean isChartTypePie(int chartType)
```


Retorna true se chartType for um dos subtipos Pie. O conjunto de subtipos corresponde ao conjunto apropriado no PowerPoint (veja a caixa de diálogo "Change Chart Type" no PowerPoint): [ChartType.BarOfPie](../../com.aspose.slides/charttype\#BarOfPie), [ChartType.ExplodedPie](../../com.aspose.slides/charttype\#ExplodedPie), [ChartType.ExplodedPie3D](../../com.aspose.slides/charttype\#ExplodedPie3D), [ChartType.Pie](../../com.aspose.slides/charttype\#Pie), [ChartType.Pie3D](../../com.aspose.slides/charttype\#Pie3D), [ChartType.PieOfPie](../../com.aspose.slides/charttype\#PieOfPie).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| chartType | int |  |

**Retorna:**
boolean
### isChartTypeBar(int chartType) {#isChartTypeBar-int-}
```
public static boolean isChartTypeBar(int chartType)
```


Retorna true se chartType for um dos subtipos Bar. O conjunto de subtipos corresponde ao conjunto apropriado no PowerPoint (veja a caixa de diálogo "Change Chart Type" no PowerPoint): [ChartType.ClusteredBar](../../com.aspose.slides/charttype\#ClusteredBar), [ChartType.ClusteredBar3D](../../com.aspose.slides/charttype\#ClusteredBar3D), [ChartType.PercentsStackedBar](../../com.aspose.slides/charttype\#PercentsStackedBar), [ChartType.PercentsStackedBar3D](../../com.aspose.slides/charttype\#PercentsStackedBar3D), [ChartType.StackedBar](../../com.aspose.slides/charttype\#StackedBar), [ChartType.StackedBar3D](../../com.aspose.slides/charttype\#StackedBar3D), [ChartType.ClusteredHorizontalCone](../../com.aspose.slides/charttype\#ClusteredHorizontalCone), [ChartType.ClusteredHorizontalCylinder](../../com.aspose.slides/charttype\#ClusteredHorizontalCylinder), [ChartType.ClusteredHorizontalPyramid](../../com.aspose.slides/charttype\#ClusteredHorizontalPyramid), [ChartType.StackedHorizontalCone](../../com.aspose.slides/charttype\#StackedHorizontalCone), [ChartType.StackedHorizontalCylinder](../../com.aspose.slides/charttype\#StackedHorizontalCylinder), [ChartType.StackedHorizontalPyramid](../../com.aspose.slides/charttype\#StackedHorizontalPyramid), [ChartType.PercentsStackedHorizontalCone](../../com.aspose.slides/charttype\#PercentsStackedHorizontalCone), [ChartType.PercentsStackedHorizontalCylinder](../../com.aspose.slides/charttype\#PercentsStackedHorizontalCylinder), [ChartType.PercentsStackedHorizontalPyramid](../../com.aspose.slides/charttype\#PercentsStackedHorizontalPyramid).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| chartType | int |  |

**Retorna:**
boolean
### isChartTypeArea(int chartType) {#isChartTypeArea-int-}
```
public static boolean isChartTypeArea(int chartType)
```


Retorna true se chartType for um dos subtipos Area. O conjunto de subtipos corresponde ao conjunto apropriado no PowerPoint (veja a caixa de diálogo "Change Chart Type" no PowerPoint): [ChartType.Area](../../com.aspose.slides/charttype\#Area), [ChartType.PercentsStackedArea](../../com.aspose.slides/charttype\#PercentsStackedArea), [ChartType.PercentsStackedArea3D](../../com.aspose.slides/charttype\#PercentsStackedArea3D), [ChartType.StackedArea](../../com.aspose.slides/charttype\#StackedArea), [ChartType.StackedArea3D](../../com.aspose.slides/charttype\#StackedArea3D), [ChartType.Area3D](../../com.aspose.slides/charttype\#Area3D).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| chartType | int |  |

**Retorna:**
boolean
### isChartTypeScatter(int chartType) {#isChartTypeScatter-int-}
```
public static boolean isChartTypeScatter(int chartType)
```


Retorna true se chartType for um dos subtipos Scatter. O conjunto de subtipos corresponde ao conjunto apropriado no PowerPoint (veja a caixa de diálogo "Change Chart Type" no PowerPoint): [ChartType.ScatterWithMarkers](../../com.aspose.slides/charttype\#ScatterWithMarkers), [ChartType.ScatterWithSmoothLines](../../com.aspose.slides/charttype\#ScatterWithSmoothLines), [ChartType.ScatterWithSmoothLinesAndMarkers](../../com.aspose.slides/charttype\#ScatterWithSmoothLinesAndMarkers), [ChartType.ScatterWithStraightLines](../../com.aspose.slides/charttype\#ScatterWithStraightLines), [ChartType.ScatterWithStraightLinesAndMarkers](../../com.aspose.slides/charttype\#ScatterWithStraightLinesAndMarkers).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| chartType | int |  |

**Retorna:**
boolean
### isChartTypeStock(int chartType) {#isChartTypeStock-int-}
```
public static boolean isChartTypeStock(int chartType)
```


Retorna true se chartType for um dos subtipos Stock. O conjunto de subtipos corresponde ao conjunto apropriado no PowerPoint (veja a caixa de diálogo "Change Chart Type" no PowerPoint): [ChartType.HighLowClose](../../com.aspose.slides/charttype\#HighLowClose), [ChartType.OpenHighLowClose](../../com.aspose.slides/charttype\#OpenHighLowClose), [ChartType.VolumeHighLowClose](../../com.aspose.slides/charttype\#VolumeHighLowClose), [ChartType.VolumeOpenHighLowClose](../../com.aspose.slides/charttype\#VolumeOpenHighLowClose).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| chartType | int |  |

**Retorna:**
boolean
### isChartTypeSurface(int chartType) {#isChartTypeSurface-int-}
```
public static boolean isChartTypeSurface(int chartType)
```


Retorna true se chartType for um dos subtipos Surface. O conjunto de subtipos corresponde ao conjunto apropriado no PowerPoint (veja a caixa de diálogo "Change Chart Type" no PowerPoint): [ChartType.Surface3D](../../com.aspose.slides/charttype\#Surface3D), [ChartType.WireframeSurface3D](../../com.aspose.slides/charttype\#WireframeSurface3D), [ChartType.Contour](../../com.aspose.slides/charttype\#Contour), [ChartType.WireframeContour](../../com.aspose.slides/charttype\#WireframeContour).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| chartType | int |  |

**Retorna:**
boolean
### isChartTypeDoughnut(int chartType) {#isChartTypeDoughnut-int-}
```
public static boolean isChartTypeDoughnut(int chartType)
```


Retorna true se chartType for um dos subtipos Doughnut. O conjunto de subtipos corresponde ao conjunto apropriado no PowerPoint (veja a caixa de diálogo "Change Chart Type" no PowerPoint): [ChartType.Doughnut](../../com.aspose.slides/charttype\#Doughnut), [ChartType.ExplodedDoughnut](../../com.aspose.slides/charttype\#ExplodedDoughnut).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| chartType | int |  |

**Retorna:**
boolean
### isChartTypeBubble(int chartType) {#isChartTypeBubble-int-}
```
public static boolean isChartTypeBubble(int chartType)
```


Retorna true se chartType for um dos subtipos Bubble. O conjunto de subtipos corresponde ao conjunto apropriado no PowerPoint (veja a caixa de diálogo "Change Chart Type" no PowerPoint): [ChartType.Bubble](../../com.aspose.slides/charttype\#Bubble), [ChartType.BubbleWith3D](../../com.aspose.slides/charttype\#BubbleWith3D).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| chartType | int |  |

**Retorna:**
boolean
### isChartTypeRadar(int chartType) {#isChartTypeRadar-int-}
```
public static boolean isChartTypeRadar(int chartType)
```


Retorna true se chartType for um dos subtipos Radar. O conjunto de subtipos corresponde ao conjunto apropriado no PowerPoint (veja a caixa de diálogo "Change Chart Type" no PowerPoint): [ChartType.FilledRadar](../../com.aspose.slides/charttype\#FilledRadar), [ChartType.Radar](../../com.aspose.slides/charttype\#Radar), [ChartType.RadarWithMarkers](../../com.aspose.slides/charttype\#RadarWithMarkers).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| chartType | int |  |

**Retorna:**
boolean
### isSeriesUsesXValueCoordinate(int seriesType) {#isSeriesUsesXValueCoordinate-int-}
```
public static boolean isSeriesUsesXValueCoordinate(int seriesType)
```


Retorna se o tipo de série especificado usa coordenadas de valor X.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| seriesType | int | Tipo de série. |

**Retorna:**
boolean - True se usa, caso contrário false.
### isSeriesUsesYValueCoordinate(int seriesType) {#isSeriesUsesYValueCoordinate-int-}
```
public static boolean isSeriesUsesYValueCoordinate(int seriesType)
```


Retorna se o tipo de série especificado usa coordenadas de valor Y.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| seriesType | int | Tipo de série. |

**Retorna:**
boolean - True se usa, caso contrário false.
### isSeriesUsesValueCoordinate(int seriesType) {#isSeriesUsesValueCoordinate-int-}
```
public static boolean isSeriesUsesValueCoordinate(int seriesType)
```


Retorna se o tipo de série especificado usa coordenadas de valor.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| seriesType | int | Tipo de série. |

**Retorna:**
boolean - True se usa, caso contrário false.
### isSeriesUsesBubbleSizeCoordinate(int seriesType) {#isSeriesUsesBubbleSizeCoordinate-int-}
```
public static boolean isSeriesUsesBubbleSizeCoordinate(int seriesType)
```


Retorna se as coordenadas de tamanho de bolha podem ser usadas para o tipo de série especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| seriesType | int | Tipo de série. |

**Retorna:**
boolean - True se pode ser usada, caso contrário false.
### hasSeriesTrendLines(int seriesType) {#hasSeriesTrendLines-int-}
```
public static boolean hasSeriesTrendLines(int seriesType)
```


Retorna se há linhas de tendência de série para o tipo de série especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| seriesType | int | Tipo de série. |

**Retorna:**
boolean - True se presentes, caso contrário false.
### isErrorBarsXAllowed(int seriesType) {#isErrorBarsXAllowed-int-}
```
public static boolean isErrorBarsXAllowed(int seriesType)
```


Retorna se barras de erro X são permitidas para o tipo de série especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| seriesType | int | Tipo de série. |

**Retorna:**
boolean - True se permitidas, caso contrário false.
### isErrorBarsYAllowed(int seriesType) {#isErrorBarsYAllowed-int-}
```
public static boolean isErrorBarsYAllowed(int seriesType)
```


Retorna se barras de erro Y são permitidas para o tipo de série especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| seriesType | int | Tipo de série. |

**Retorna:**
boolean - True se permitidas, caso contrário false.