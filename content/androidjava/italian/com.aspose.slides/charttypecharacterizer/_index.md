---
title: ChartTypeCharacterizer
second_title: Aspose.Slides per Android via Riferimento API Java
description: Helper per ottenere informazioni aggiuntive sui grafici e sulle serie tramite il suo ChartType.
type: docs
url: /it/com.aspose.slides/charttypecharacterizer/
---
**Ereditarietà:**
java.lang.Object
```
public class ChartTypeCharacterizer
```

Helper per ottenere informazioni aggiuntive sui grafici e le serie tramite il suo ChartType.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [ChartTypeCharacterizer()](#ChartTypeCharacterizer--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [isBar3DChart(int chartType)](#isBar3DChart-int-) | Restituisce true se chartType è uno dei sottotipi bar3DChart (colonne 3D o barre). |
| [is2DChart(int chartType)](#is2DChart-int-) | Restituisce true se chartType è uno dei tipi di grafico 2D. |
| [is3DChart(int chartType)](#is3DChart-int-) | Restituisce true se chartType è uno dei tipi di grafico 3D. |
| [isChartTypeColumn(int chartType)](#isChartTypeColumn-int-) | Restituisce true se chartType è uno dei sottotipi Column. |
| [isChartTypeLine(int chartType)](#isChartTypeLine-int-) | Restituisce true se chartType è uno dei sottotipi Line. |
| [isChartTypePie(int chartType)](#isChartTypePie-int-) | Restituisce true se chartType è uno dei sottotipi Pie. |
| [isChartTypeBar(int chartType)](#isChartTypeBar-int-) | Restituisce true se chartType è uno dei sottotipi Bar. |
| [isChartTypeArea(int chartType)](#isChartTypeArea-int-) | Restituisce true se chartType è uno dei sottotipi Area. |
| [isChartTypeScatter(int chartType)](#isChartTypeScatter-int-) | Restituisce true se chartType è uno dei sottotipi Scatter. |
| [isChartTypeStock(int chartType)](#isChartTypeStock-int-) | Restituisce true se chartType è uno dei sottotipi Stock. |
| [isChartTypeSurface(int chartType)](#isChartTypeSurface-int-) | Restituisce true se chartType è uno dei sottotipi Surface. |
| [isChartTypeDoughnut(int chartType)](#isChartTypeDoughnut-int-) | Restituisce true se chartType è uno dei sottotipi Doughnut. |
| [isChartTypeBubble(int chartType)](#isChartTypeBubble-int-) | Restituisce true se chartType è uno dei sottotipi Bubble. |
| [isChartTypeRadar(int chartType)](#isChartTypeRadar-int-) | Restituisce true se chartType è uno dei sottotipi Radar. |
| [isSeriesUsesXValueCoordinate(int seriesType)](#isSeriesUsesXValueCoordinate-int-) | Restituisce se il tipo di serie specificato utilizza coordinate valore X. |
| [isSeriesUsesYValueCoordinate(int seriesType)](#isSeriesUsesYValueCoordinate-int-) | Restituisce se il tipo di serie specificato utilizza coordinate valore Y. |
| [isSeriesUsesValueCoordinate(int seriesType)](#isSeriesUsesValueCoordinate-int-) | Restituisce se il tipo di serie specificato utilizza coordinate valore. |
| [isSeriesUsesBubbleSizeCoordinate(int seriesType)](#isSeriesUsesBubbleSizeCoordinate-int-) | Restituisce se le coordinate della dimensione della bolla possono essere usate per il tipo di serie specificato. |
| [hasSeriesTrendLines(int seriesType)](#hasSeriesTrendLines-int-) | Restituisce se esistono linee di tendenza per il tipo di serie specificato. |
| [isErrorBarsXAllowed(int seriesType)](#isErrorBarsXAllowed-int-) | Restituisce se le barre di errore X sono consentite per il tipo di serie specificato. |
| [isErrorBarsYAllowed(int seriesType)](#isErrorBarsYAllowed-int-) | Restituisce se le barre di errore Y sono consentite per il tipo di serie specificato. |
### ChartTypeCharacterizer() {#ChartTypeCharacterizer--}
```
public ChartTypeCharacterizer()
```

### isBar3DChart(int chartType) {#isBar3DChart-int-}
```
public static boolean isBar3DChart(int chartType)
```

Restituisce true se chartType è uno dei sottotipi bar3DChart (colonne 3D o barre).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| chartType | int |  |

**Restituisce:**
boolean
### is2DChart(int chartType) {#is2DChart-int-}
```
public static boolean is2DChart(int chartType)
```

Restituisce true se chartType è uno dei tipi di grafico 2D.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| chartType | int |  |

**Restituisce:**
boolean
### is3DChart(int chartType) {#is3DChart-int-}
```
public static boolean is3DChart(int chartType)
```

Restituisce true se chartType è uno dei tipi di grafico 3D.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| chartType | int |  |

**Restituisce:**
boolean
### isChartTypeColumn(int chartType) {#isChartTypeColumn-int-}
```
public static boolean isChartTypeColumn(int chartType)
```

Restituisce true se chartType è uno dei sottotipi Column. Il set di sottotipi corrisponde al set appropriato in PowerPoint (vedi la finestra di dialogo "Change Chart Type" in PowerPoint): [ChartType.ClusteredColumn](../../com.aspose.slides/charttype\#ClusteredColumn), [ChartType.ClusteredColumn3D](../../com.aspose.slides/charttype\#ClusteredColumn3D), [ChartType.ClusteredCone](../../com.aspose.slides/charttype\#ClusteredCone), [ChartType.ClusteredCylinder](../../com.aspose.slides/charttype\#ClusteredCylinder), [ChartType.ClusteredPyramid](../../com.aspose.slides/charttype\#ClusteredPyramid), [ChartType.PercentsStackedColumn](../../com.aspose.slides/charttype\#PercentsStackedColumn), [ChartType.PercentsStackedColumn3D](../../com.aspose.slides/charttype\#PercentsStackedColumn3D), [ChartType.PercentsStackedCone](../../com.aspose.slides/charttype\#PercentsStackedCone), [ChartType.PercentsStackedCylinder](../../com.aspose.slides/charttype\#PercentsStackedCylinder), [ChartType.PercentsStackedPyramid](../../com.aspose.slides/charttype\#PercentsStackedPyramid), [ChartType.StackedColumn](../../com.aspose.slides/charttype\#StackedColumn), [ChartType.StackedColumn3D](../../com.aspose.slides/charttype\#StackedColumn3D), [ChartType.StackedCone](../../com.aspose.slides/charttype\#StackedCone), [ChartType.StackedCylinder](../../com.aspose.slides/charttype\#StackedCylinder), [ChartType.StackedPyramid](../../com.aspose.slides/charttype\#StackedPyramid), [ChartType.Column3D](../../com.aspose.slides/charttype\#Column3D), [ChartType.Cylinder3D](../../com.aspose.slides/charttype\#Cylinder3D), [ChartType.Cone3D](../../com.aspose.slides/charttype\#Cone3D), [ChartType.Pyramid3D](../../com.aspose.slides/charttype\#Pyramid3D).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| chartType | int |  |

**Restituisce:**
boolean
### isChartTypeLine(int chartType) {#isChartTypeLine-int-}
```
public static boolean isChartTypeLine(int chartType)
```

Restituisce true se chartType è uno dei sottotipi Line. Il set di sottotipi corrisponde al set appropriato in PowerPoint (vedi la finestra di dialogo "Change Chart Type" in PowerPoint): [ChartType.Line](../../com.aspose.slides/charttype\#Line), [ChartType.LineWithMarkers](../../com.aspose.slides/charttype\#LineWithMarkers), [ChartType.PercentsStackedLine](../../com.aspose.slides/charttype\#PercentsStackedLine), [ChartType.PercentsStackedLineWithMarkers](../../com.aspose.slides/charttype\#PercentsStackedLineWithMarkers), [ChartType.StackedLine](../../com.aspose.slides/charttype\#StackedLine), [ChartType.StackedLineWithMarkers](../../com.aspose.slides/charttype\#StackedLineWithMarkers), [ChartType.Line3D](../../com.aspose.slides/charttype\#Line3D).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| chartType | int |  |

**Restituisce:**
boolean
### isChartTypePie(int chartType) {#isChartTypePie-int-}
```
public static boolean isChartTypePie(int chartType)
```

Restituisce true se chartType è uno dei sottotipi Pie. Il set di sottotipi corrisponde al set appropriato in PowerPoint (vedi la finestra di dialogo "Change Chart Type" in PowerPoint): [ChartType.BarOfPie](../../com.aspose.slides/charttype\#BarOfPie), [ChartType.ExplodedPie](../../com.aspose.slides/charttype\#ExplodedPie), [ChartType.ExplodedPie3D](../../com.aspose.slides/charttype\#ExplodedPie3D), [ChartType.Pie](../../com.aspose.slides/charttype\#Pie), [ChartType.Pie3D](../../com.aspose.slides/charttype\#Pie3D), [ChartType.PieOfPie](../../com.aspose.slides/charttype\#PieOfPie).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| chartType | int |  |

**Restituisce:**
boolean
### isChartTypeBar(int chartType) {#isChartTypeBar-int-}
```
public static boolean isChartTypeBar(int chartType)
```

Restituisce true se chartType è uno dei sottotipi Bar. Il set di sottotipi corrisponde al set appropriato in PowerPoint (vedi la finestra di dialogo "Change Chart Type" in PowerPoint): [ChartType.ClusteredBar](../../com.aspose.slides/charttype\#ClusteredBar), [ChartType.ClusteredBar3D](../../com.aspose.slides/charttype\#ClusteredBar3D), [ChartType.PercentsStackedBar](../../com.aspose.slides/charttype\#PercentsStackedBar), [ChartType.PercentsStackedBar3D](../../com.aspose.slides/charttype\#PercentsStackedBar3D), [ChartType.StackedBar](../../com.aspose.slides/charttype\#StackedBar), [ChartType.StackedBar3D](../../com.aspose.slides/charttype\#StackedBar3D), [ChartType.ClusteredHorizontalCone](../../com.aspose.slides/charttype\#ClusteredHorizontalCone), [ChartType.ClusteredHorizontalCylinder](../../com.aspose.slides/charttype\#ClusteredHorizontalCylinder), [ChartType.ClusteredHorizontalPyramid](../../com.aspose.slides/charttype\#ClusteredHorizontalPyramid), [ChartType.StackedHorizontalCone](../../com.aspose.slides/charttype\#StackedHorizontalCone), [ChartType.StackedHorizontalCylinder](../../com.aspose.slides/charttype\#StackedHorizontalCylinder), [ChartType.StackedHorizontalPyramid](../../com.aspose.slides/charttype\#StackedHorizontalPyramid), [ChartType.PercentsStackedHorizontalCone](../../com.aspose.slides/charttype\#PercentsStackedHorizontalCone), [ChartType.PercentsStackedHorizontalCylinder](../../com.aspose.slides/charttype\#PercentsStackedHorizontalCylinder), [ChartType.PercentsStackedHorizontalPyramid](../../com.aspose.slides/charttype\#PercentsStackedHorizontalPyramid).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| chartType | int |  |

**Restituisce:**
boolean
### isChartTypeArea(int chartType) {#isChartTypeArea-int-}
```
public static boolean isChartTypeArea(int chartType)
```

Restituisce true se chartType è uno dei sottotipi Area. Il set di sottotipi corrisponde al set appropriato in PowerPoint (vedi la finestra di dialogo "Change Chart Type" in PowerPoint): [ChartType.Area](../../com.aspose.slides/charttype\#Area), [ChartType.PercentsStackedArea](../../com.aspose.slides/charttype\#PercentsStackedArea), [ChartType.PercentsStackedArea3D](../../com.aspose.slides/charttype\#PercentsStackedArea3D), [ChartType.StackedArea](../../com.aspose.slides/charttype\#StackedArea), [ChartType.StackedArea3D](../../com.aspose.slides/charttype\#StackedArea3D), [ChartType.Area3D](../../com.aspose.slides/charttype\#Area3D).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| chartType | int |  |

**Restituisce:**
boolean
### isChartTypeScatter(int chartType) {#isChartTypeScatter-int-}
```
public static boolean isChartTypeScatter(int chartType)
```

Restituisce true se chartType è uno dei sottotipi Scatter. Il set di sottotipi corrisponde al set appropriato in PowerPoint (vedi la finestra di dialogo "Change Chart Type" in PowerPoint): [ChartType.ScatterWithMarkers](../../com.aspose.slides/charttype\#ScatterWithMarkers), [ChartType.ScatterWithSmoothLines](../../com.aspose.slides/charttype\#ScatterWithSmoothLines), [ChartType.ScatterWithSmoothLinesAndMarkers](../../com.aspose.slides/charttype\#ScatterWithSmoothLinesAndMarkers), [ChartType.ScatterWithStraightLines](../../com.aspose.slides/charttype\#ScatterWithStraightLines), [ChartType.ScatterWithStraightLinesAndMarkers](../../com.aspose.slides/charttype\#ScatterWithStraightLinesAndMarkers).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| chartType | int |  |

**Restituisce:**
boolean
### isChartTypeStock(int chartType) {#isChartTypeStock-int-}
```
public static boolean isChartTypeStock(int chartType)
```

Restituisce true se chartType è uno dei sottotipi Stock. Il set di sottotipi corrisponde al set appropriato in PowerPoint (vedi la finestra di dialogo "Change Chart Type" in PowerPoint): [ChartType.HighLowClose](../../com.aspose.slides/charttype\#HighLowClose), [ChartType.OpenHighLowClose](../../com.aspose.slides/charttype\#OpenHighLowClose), [ChartType.VolumeHighLowClose](../../com.aspose.slides/charttype\#VolumeHighLowClose), [ChartType.VolumeOpenHighLowClose](../../com.aspose.slides/charttype\#VolumeOpenHighLowClose).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| chartType | int |  |

**Restituisce:**
boolean
### isChartTypeSurface(int chartType) {#isChartTypeSurface-int-}
```
public static boolean isChartTypeSurface(int chartType)
```

Restituisce true se chartType è uno dei sottotipi Surface. Il set di sottotipi corrisponde al set appropriato in PowerPoint (vedi la finestra di dialogo "Change Chart Type" in PowerPoint): [ChartType.Surface3D](../../com.aspose.slides/charttype\#Surface3D), [ChartType.WireframeSurface3D](../../com.aspose.slides/charttype\#WireframeSurface3D), [ChartType.Contour](../../com.aspose.slides/charttype\#Contour), [ChartType.WireframeContour](../../com.aspose.slides/charttype\#WireframeContour).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| chartType | int |  |

**Restituisce:**
boolean
### isChartTypeDoughnut(int chartType) {#isChartTypeDoughnut-int-}
```
public static boolean isChartTypeDoughnut(int chartType)
```

Restituisce true se chartType è uno dei sottotipi Doughnut. Il set di sottotipi corrisponde al set appropriato in PowerPoint (vedi la finestra di dialogo "Change Chart Type" in PowerPoint): [ChartType.Doughnut](../../com.aspose.slides/charttype\#Doughnut), [ChartType.ExplodedDoughnut](../../com.aspose.slides/charttype\#ExplodedDoughnut).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| chartType | int |  |

**Restituisce:**
boolean
### isChartTypeBubble(int chartType) {#isChartTypeBubble-int-}
```
public static boolean isChartTypeBubble(int chartType)
```

Restituisce true se chartType è uno dei sottotipi Bubble. Il set di sottotipi corrisponde al set appropriato in PowerPoint (vedi la finestra di dialogo "Change Chart Type" in PowerPoint): [ChartType.Bubble](../../com.aspose.slides/charttype\#Bubble), [ChartType.BubbleWith3D](../../com.aspose.slides/charttype\#BubbleWith3D).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| chartType | int |  |

**Restituisce:**
boolean
### isChartTypeRadar(int chartType) {#isChartTypeRadar-int-}
```
public static boolean isChartTypeRadar(int chartType)
```

Restituisce true se chartType è uno dei sottotipi Radar. Il set di sottotipi corrisponde al set appropriato in PowerPoint (vedi la finestra di dialogo "Change Chart Type" in PowerPoint): [ChartType.FilledRadar](../../com.aspose.slides/charttype\#FilledRadar), [ChartType.Radar](../../com.aspose.slides/charttype\#Radar), [ChartType.RadarWithMarkers](../../com.aspose.slides/charttype\#RadarWithMarkers).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| chartType | int |  |

**Restituisce:**
boolean
### isSeriesUsesXValueCoordinate(int seriesType) {#isSeriesUsesXValueCoordinate-int-}
```
public static boolean isSeriesUsesXValueCoordinate(int seriesType)
```

Restituisce se il tipo di serie specificato utilizza coordinate valore X.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| seriesType | int | Tipo di serie. |

**Restituisce:**
boolean - True if uses otherwise false.
### isSeriesUsesYValueCoordinate(int seriesType) {#isSeriesUsesYValueCoordinate-int-}
```
public static boolean isSeriesUsesYValueCoordinate(int seriesType)
```

Restituisce se il tipo di serie specificato utilizza coordinate valore Y.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| seriesType | int | Tipo di serie. |

**Restituisce:**
boolean - True if uses otherwise false.
### isSeriesUsesValueCoordinate(int seriesType) {#isSeriesUsesValueCoordinate-int-}
```
public static boolean isSeriesUsesValueCoordinate(int seriesType)
```

Restituisce se il tipo di serie specificato utilizza coordinate valore.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| seriesType | int | Tipo di serie. |

**Restituisce:**
boolean - True if uses otherwise false.
### isSeriesUsesBubbleSizeCoordinate(int seriesType) {#isSeriesUsesBubbleSizeCoordinate-int-}
```
public static boolean isSeriesUsesBubbleSizeCoordinate(int seriesType)
```

Restituisce se le coordinate della dimensione della bolla possono essere usate per il tipo di serie specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| seriesType | int | Tipo di serie. |

**Restituisce:**
boolean - True if can be used, otherwise false.
### hasSeriesTrendLines(int seriesType) {#hasSeriesTrendLines-int-}
```
public static boolean hasSeriesTrendLines(int seriesType)
```

Restituisce se esistono linee di tendenza per il tipo di serie specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| seriesType | int | Tipo di serie. |

**Restituisce:**
boolean - True if present otherwise false.
### isErrorBarsXAllowed(int seriesType) {#isErrorBarsXAllowed-int-}
```
public static boolean isErrorBarsXAllowed(int seriesType)
```

Restituisce se le barre di errore X sono consentite per il tipo di serie specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| seriesType | int | Tipo di serie. |

**Restituisce:**
boolean - True if allowed, otherwise false.
### isErrorBarsYAllowed(int seriesType) {#isErrorBarsYAllowed-int-}
```
public static boolean isErrorBarsYAllowed(int seriesType)
```

Restituisce se le barre di errore Y sono consentite per il tipo di serie specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| seriesType | int | Tipo di serie. |

**Restituisce:**
boolean - True if allowed, otherwise false.