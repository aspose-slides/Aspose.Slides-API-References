---
title: ChartTypeCharacterizer
second_title: Αναφορά API του Aspose.Slides για Java
description: Βοηθός για λήψη πρόσθετων πληροφοριών σχετικά με διαγράμματα και σειρές με βάση το ChartType τους.
type: docs
url: /el/com.aspose.slides/charttypecharacterizer/
---
**Κληρονομικότητα:**
java.lang.Object
```
public class ChartTypeCharacterizer
```

Βοηθός για λήψη πρόσθετων πληροφοριών σχετικά με διαγράμματα και σειρές με βάση το ChartType τους.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [ChartTypeCharacterizer()](#ChartTypeCharacterizer--) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [isBar3DChart(int chartType)](#isBar3DChart-int-) | Return true if chartType is one of bar3DChart subtypes (3D columns or bars). |
| [is2DChart(int chartType)](#is2DChart-int-) | Return true if chartType is one of 2D chart types. |
| [is3DChart(int chartType)](#is3DChart-int-) | Return true if chartType is one of 3D chart types. |
| [isChartTypeColumn(int chartType)](#isChartTypeColumn-int-) | Return true if chartType is one of Column subtypes. |
| [isChartTypeLine(int chartType)](#isChartTypeLine-int-) | Return true if chartType is one of Line subtypes. |
| [isChartTypePie(int chartType)](#isChartTypePie-int-) | Return true if chartType is one of Pie subtypes. |
| [isChartTypeBar(int chartType)](#isChartTypeBar-int-) | Return true if chartType is one of Bar subtypes. |
| [isChartTypeArea(int chartType)](#isChartTypeArea-int-) | Return true if chartType is one of Area subtypes. |
| [isChartTypeScatter(int chartType)](#isChartTypeScatter-int-) | Return true if chartType is one of Scatter subtypes. |
| [isChartTypeStock(int chartType)](#isChartTypeStock-int-) | Return true if chartType is one of Stock subtypes. |
| [isChartTypeSurface(int chartType)](#isChartTypeSurface-int-) | Return true if chartType is one of Surface subtypes. |
| [isChartTypeDoughnut(int chartType)](#isChartTypeDoughnut-int-) | Return true if chartType is one of Doughnut subtypes. |
| [isChartTypeBubble(int chartType)](#isChartTypeBubble-int-) | Return true if chartType is one of Bubble subtypes. |
| [isChartTypeRadar(int chartType)](#isChartTypeRadar-int-) | Return true if chartType is one of Radar subtypes. |
| [isSeriesUsesXValueCoordinate(int seriesType)](#isSeriesUsesXValueCoordinate-int-) | Returns if specified series type uses X value coordinates. |
| [isSeriesUsesYValueCoordinate(int seriesType)](#isSeriesUsesYValueCoordinate-int-) | Returns if specified series type uses Y value coordinates. |
| [isSeriesUsesValueCoordinate(int seriesType)](#isSeriesUsesValueCoordinate-int-) | Returns if specified series type uses value coordinates. |
| [isSeriesUsesBubbleSizeCoordinate(int seriesType)](#isSeriesUsesBubbleSizeCoordinate-int-) | Returns if bubble size coordinates can be used for specified series type. |
| [hasSeriesTrendLines(int seriesType)](#hasSeriesTrendLines-int-) | Returns if there are series trend lines for specified series type. |
| [isErrorBarsXAllowed(int seriesType)](#isErrorBarsXAllowed-int-) | Returns if error bars X allowed for specified series type. |
| [isErrorBarsYAllowed(int seriesType)](#isErrorBarsYAllowed-int-) | Returns if error bars Y allowed for specified series type. |
### ChartTypeCharacterizer() {#ChartTypeCharacterizer--}
```
public ChartTypeCharacterizer()
```


### isBar3DChart(int chartType) {#isBar3DChart-int-}
```
public static boolean isBar3DChart(int chartType)
```

Επιστρέφει true αν το chartType είναι ένα από τα υποείδη bar3DChart (στήλες 3D ή ράβδοι).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| chartType | int |  |

**Επιστρέφει:**
boolean
### is2DChart(int chartType) {#is2DChart-int-}
```
public static boolean is2DChart(int chartType)
```

Επιστρέφει true αν το chartType είναι ένας από τους τύπους διαγραμμάτων 2D.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| chartType | int |  |

**Επιστρέφει:**
boolean
### is3DChart(int chartType) {#is3DChart-int-}
```
public static boolean is3DChart(int chartType)
```

Επιστρέφει true αν το chartType είναι ένας από τους τύπους διαγραμμάτων 3D.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| chartType | int |  |

**Επιστρέφει:**
boolean
### isChartTypeColumn(int chartType) {#isChartTypeColumn-int-}
```
public static boolean isChartTypeColumn(int chartType)
```

Επιστρέφει true αν το chartType είναι ένα από τα υποείδη Column. Το σύνολο υποτύπων αντιστοιχεί στο κατάλληλο σύνολο στο PowerPoint (δείτε το διάλογο "Change Chart Type" στο PowerPoint): [ChartType.ClusteredColumn](../../com.aspose.slides/charttype\#ClusteredColumn), [ChartType.ClusteredColumn3D](../../com.aspose.slides/charttype\#ClusteredColumn3D), [ChartType.ClusteredCone](../../com.aspose.slides/charttype\#ClusteredCone), [ChartType.ClusteredCylinder](../../com.aspose.slides/charttype\#ClusteredCylinder), [ChartType.ClusteredPyramid](../../com.aspose.slides/charttype\#ClusteredPyramid), [ChartType.PercentsStackedColumn](../../com.aspose.slides/charttype\#PercentsStackedColumn), [ChartType.PercentsStackedColumn3D](../../com.aspose.slides/charttype\#PercentsStackedColumn3D), [ChartType.PercentsStackedCone](../../com.aspose.slides/charttype\#PercentsStackedCone), [ChartType.PercentsStackedCylinder](../../com.aspose.slides/charttype\#PercentsStackedCylinder), [ChartType.PercentsStackedPyramid](../../com.aspose.slides/charttype\#PercentsStackedPyramid), [ChartType.StackedColumn](../../com.aspose.slides/charttype\#StackedColumn), [ChartType.StackedColumn3D](../../com.aspose.slides/charttype\#StackedColumn3D), [ChartType.StackedCone](../../com.aspose.slides/charttype\#StackedCone), [ChartType.StackedCylinder](../../com.aspose.slides/charttype\#StackedCylinder), [ChartType.StackedPyramid](../../com.aspose.slides/charttype\#StackedPyramid), [ChartType.Column3D](../../com.aspose.slides/charttype\#Column3D), [ChartType.Cylinder3D](../../com.aspose.slides/charttype\#Cylinder3D), [ChartType.Cone3D](../../com.aspose.slides/charttype\#Cone3D), [ChartType.Pyramid3D](../../com.aspose.slides/charttype\#Pyramid3D).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| chartType | int |  |

**Επιστρέφει:**
boolean
### isChartTypeLine(int chartType) {#isChartTypeLine-int-}
```
public static boolean isChartTypeLine(int chartType)
```

Επιστρέφει true αν το chartType είναι ένα από τα υποείδη Line. Το σύνολο υποτύπων αντιστοιχεί στο κατάλληλο σύνολο στο PowerPoint (δείτε το διάλογο "Change Chart Type" στο PowerPoint): [ChartType.Line](../../com.aspose.slides/charttype\#Line), [ChartType.LineWithMarkers](../../com.aspose.slides/charttype\#LineWithMarkers), [ChartType.PercentsStackedLine](../../com.aspose.slides/charttype\#PercentsStackedLine), [ChartType.PercentsStackedLineWithMarkers](../../com.aspose.slides/charttype\#PercentsStackedLineWithMarkers), [ChartType.StackedLine](../../com.aspose.slides/charttype\#StackedLine), [ChartType.StackedLineWithMarkers](../../com.aspose.slides/charttype\#StackedLineWithMarkers), [ChartType.Line3D](../../com.aspose.slides/charttype\#Line3D).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| chartType | int |  |

**Επιστρέφει:**
boolean
### isChartTypePie(int chartType) {#isChartTypePie-int-}
```
public static boolean isChartTypePie(int chartType)
```

Επιστρέφει true αν το chartType είναι ένα από τα υποείδη Pie. Το σύνολο υποτύπων αντιστοιχεί στο κατάλληλο σύνολο στο PowerPoint (δείτε το διάλογο "Change Chart Type" στο PowerPoint): [ChartType.BarOfPie](../../com.aspose.slides/charttype\#BarOfPie), [ChartType.ExplodedPie](../../com.aspose.slides/charttype\#ExplodedPie), [ChartType.ExplodedPie3D](../../com.aspose.slides/charttype\#ExplodedPie3D), [ChartType.Pie](../../com.aspose.slides/charttype\#Pie), [ChartType.Pie3D](../../com.aspose.slides/charttype\#Pie3D), [ChartType.PieOfPie](../../com.aspose.slides/charttype\#PieOfPie).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| chartType | int |  |

**Επιστρέφει:**
boolean
### isChartTypeBar(int chartType) {#isChartTypeBar-int-}
```
public static boolean isChartTypeBar(int chartType)
```

Επιστρέφει true αν το chartType είναι ένα από τα υποείδη Bar. Το σύνολο υποτύπων αντιστοιχεί στο κατάλληλο σύνολο στο PowerPoint (δείτε το διάλογο "Change Chart Type" στο PowerPoint): [ChartType.ClusteredBar](../../com.aspose.slides/charttype\#ClusteredBar), [ChartType.ClusteredBar3D](../../com.aspose.slides/charttype\#ClusteredBar3D), [ChartType.PercentsStackedBar](../../com.aspose.slides/charttype\#PercentsStackedBar), [ChartType.PercentsStackedBar3D](../../com.aspose.slides/charttype\#PercentsStackedBar3D), [ChartType.StackedBar](../../com.aspose.slides/charttype\#StackedBar), [ChartType.StackedBar3D](../../com.aspose.slides/charttype\#StackedBar3D), [ChartType.ClusteredHorizontalCone](../../com.aspose.slides/charttype\#ClusteredHorizontalCone), [ChartType.ClusteredHorizontalCylinder](../../com.aspose.slides/charttype\#ClusteredHorizontalCylinder), [ChartType.ClusteredHorizontalPyramid](../../com.aspose.slides/charttype\#ClusteredHorizontalPyramid), [ChartType.StackedHorizontalCone](../../com.aspose.slides/charttype\#StackedHorizontalCone), [ChartType.StackedHorizontalCylinder](../../com.aspose.slides/charttype\#StackedHorizontalCylinder), [ChartType.StackedHorizontalPyramid](../../com.aspose.slides/charttype\#StackedHorizontalPyramid), [ChartType.PercentsStackedHorizontalCone](../../com.aspose.slides/charttype\#PercentsStackedHorizontalCone), [ChartType.PercentsStackedHorizontalCylinder](../../com.aspose.slides/charttype\#PercentsStackedHorizontalCylinder), [ChartType.PercentsStackedHorizontalPyramid](../../com.aspose.slides/charttype\#PercentsStackedHorizontalPyramid).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| chartType | int |  |

**Επιστρέφει:**
boolean
### isChartTypeArea(int chartType) {#isChartTypeArea-int-}
```
public static boolean isChartTypeArea(int chartType)
```

Επιστρέφει true αν το chartType είναι ένα από τα υποείδη Area. Το σύνολο υποτύπων αντιστοιχεί στο κατάλληλο σύνολο στο PowerPoint (δείτε το διάλογο "Change Chart Type" στο PowerPoint): [ChartType.Area](../../com.aspose.slides/charttype\#Area), [ChartType.PercentsStackedArea](../../com.aspose.slides/charttype\#PercentsStackedArea), [ChartType.PercentsStackedArea3D](../../com.aspose.slides/charttype\#PercentsStackedArea3D), [ChartType.StackedArea](../../com.aspose.slides/charttype\#StackedArea), [ChartType.StackedArea3D](../../com.aspose.slides/charttype\#StackedArea3D), [ChartType.Area3D](../../com.aspose.slides/charttype\#Area3D).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| chartType | int |  |

**Επιστρέφει:**
boolean
### isChartTypeScatter(int chartType) {#isChartTypeScatter-int-}
```
public static boolean isChartTypeScatter(int chartType)
```

Επιστρέφει true αν το chartType είναι ένα από τα υποείδη Scatter. Το σύνολο υποτύπων αντιστοιχεί στο κατάλληλο σύνολο στο PowerPoint (δείτε το διάλογο "Change Chart Type" στο PowerPoint): [ChartType.ScatterWithMarkers](../../com.aspose.slides/charttype\#ScatterWithMarkers), [ChartType.ScatterWithSmoothLines](../../com.aspose.slides/charttype\#ScatterWithSmoothLines), [ChartType.ScatterWithSmoothLinesAndMarkers](../../com.aspose.slides/charttype\#ScatterWithSmoothLinesAndMarkers), [ChartType.ScatterWithStraightLines](../../com.aspose.slides/charttype\#ScatterWithStraightLines), [ChartType.ScatterWithStraightLinesAndMarkers](../../com.aspose.slides/charttype\#ScatterWithStraightLinesAndMarkers).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| chartType | int |  |

**Επιστρέφει:**
boolean
### isChartTypeStock(int chartType) {#isChartTypeStock-int-}
```
public static boolean isChartTypeStock(int chartType)
```

Επιστρέφει true αν το chartType είναι ένα από τα υποείδη Stock. Το σύνολο υποτύπων αντιστοιχεί στο κατάλληλο σύνολο στο PowerPoint (δείτε το διάλογο "Change Chart Type" στο PowerPoint): [ChartType.HighLowClose](../../com.aspose.slides/charttype\#HighLowClose), [ChartType.OpenHighLowClose](../../com.aspose.slides/charttype\#OpenHighLowClose), [ChartType.VolumeHighLowClose](../../com.aspose.slides/charttype\#VolumeHighLowClose), [ChartType.VolumeOpenHighLowClose](../../com.aspose.slides/charttype\#VolumeOpenHighLowClose).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| chartType | int |  |

**Επιστρέφει:**
boolean
### isChartTypeSurface(int chartType) {#isChartTypeSurface-int-}
```
public static boolean isChartTypeSurface(int chartType)
```

Επιστρέφει true αν το chartType είναι ένα από τα υποείδη Surface. Το σύνολο υποτύπων αντιστοιχεί στο κατάλληλο σύνολο στο PowerPoint (δείτε το διάλογο "Change Chart Type" στο PowerPoint): [ChartType.Surface3D](../../com.aspose.slides/charttype\#Surface3D), [ChartType.WireframeSurface3D](../../com.aspose.slides/charttype\#WireframeSurface3D), [ChartType.Contour](../../com.aspose.slides/charttype\#Contour), [ChartType.WireframeContour](../../com.aspose.slides/charttype\#WireframeContour).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| chartType | int |  |

**Επιστρέφει:**
boolean
### isChartTypeDoughnut(int chartType) {#isChartTypeDoughnut-int-}
```
public static boolean isChartTypeDoughnut(int chartType)
```

Επιστρέφει true αν το chartType είναι ένα από τα υποείδη Doughnut. Το σύνολο υποτύπων αντιστοιχεί στο κατάλληλο σύνολο στο PowerPoint (δείτε το διάλογο "Change Chart Type" στο PowerPoint): [ChartType.Doughnut](../../com.aspose.slides/charttype\#Doughnut), [ChartType.ExplodedDoughnut](../../com.aspose.slides/charttype\#ExplodedDoughnut).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| chartType | int |  |

**Επιστρέφει:**
boolean
### isChartTypeBubble(int chartType) {#isChartTypeBubble-int-}
```
public static boolean isChartTypeBubble(int chartType)
```

Επιστρέφει true αν το chartType είναι ένα από τα υποείδη Bubble. Το σύνολο υποτύπων αντιστοιχεί στο κατάλληλο σύνολο στο PowerPoint (δείτε το διάλογο "Change Chart Type" στο PowerPoint): [ChartType.Bubble](../../com.aspose.slides/charttype\#Bubble), [ChartType.BubbleWith3D](../../com.aspose.slides/charttype\#BubbleWith3D).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| chartType | int |  |

**Επιστρέφει:**
boolean
### isChartTypeRadar(int chartType) {#isChartTypeRadar-int-}
```
public static boolean isChartTypeRadar(int chartType)
```

Επιστρέφει true αν το chartType είναι ένα από τα υποείδη Radar. Το σύνολο υποτύπων αντιστοιχεί στο κατάλληλο σύνολο στο PowerPoint (δείτε το διάλογο "Change Chart Type" στο PowerPoint): [ChartType.FilledRadar](../../com.aspose.slides/charttype\#FilledRadar), [ChartType.Radar](../../com.aspose.slides/charttype\#Radar), [ChartType.RadarWithMarkers](../../com.aspose.slides/charttype\#RadarWithMarkers).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| chartType | int |  |

**Επιστρέφει:**
boolean
### isSeriesUsesXValueCoordinate(int seriesType) {#isSeriesUsesXValueCoordinate-int-}
```
public static boolean isSeriesUsesXValueCoordinate(int seriesType)
```

Επιστρέφει αν ο καθορισμένος τύπος σειράς χρησιμοποιεί συντεταγμένες τιμής X.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| seriesType | int | Τύπος σειράς. |

**Επιστρέφει:**
boolean - True αν χρησιμοποιείται αλλιώς false.
### isSeriesUsesYValueCoordinate(int seriesType) {#isSeriesUsesYValueCoordinate-int-}
```
public static boolean isSeriesUsesYValueCoordinate(int seriesType)
```

Επιστρέφει αν ο καθορισμένος τύπος σειράς χρησιμοποιεί συντεταγμένες τιμής Y.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| seriesType | int | Τύπος σειράς. |

**Επιστρέφει:**
boolean - True αν χρησιμοποιείται αλλιώς false.
### isSeriesUsesValueCoordinate(int seriesType) {#isSeriesUsesValueCoordinate-int-}
```
public static boolean isSeriesUsesValueCoordinate(int seriesType)
```

Επιστρέφει αν ο καθορισμένος τύπος σειράς χρησιμοποιεί συντεταγμένες τιμής.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| seriesType | int | Τύπος σειράς. |

**Επιστρέφει:**
boolean - True αν χρησιμοποιείται αλλιώς false.
### isSeriesUsesBubbleSizeCoordinate(int seriesType) {#isSeriesUsesBubbleSizeCoordinate-int-}
```
public static boolean isSeriesUsesBubbleSizeCoordinate(int seriesType)
```

Επιστρέφει αν οι συντεταγμένες μεγέθους φυσαλίδας μπορούν να χρησιμοποιηθούν για τον καθορισμένο τύπο σειράς.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| seriesType | int | Τύπος σειράς. |

**Επιστρέφει:**
boolean - True αν μπορεί να χρησιμοποιηθεί, αλλιώς false.
### hasSeriesTrendLines(int seriesType) {#hasSeriesTrendLines-int-}
```
public static boolean hasSeriesTrendLines(int seriesType)
```

Επιστρέφει αν υπάρχουν γραμμές τάσεων σειράς για τον καθορισμένο τύπο σειράς.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| seriesType | int | Τύπος σειράς. |

**Επιστρέφει:**
boolean - True αν υπάρχουν, αλλιώς false.
### isErrorBarsXAllowed(int seriesType) {#isErrorBarsXAllowed-int-}
```
public static boolean isErrorBarsXAllowed(int seriesType)
```

Επιστρέφει αν είναι επιτρεπτές οι γραμμές σφάλματος X για τον καθορισμένο τύπο σειράς.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| seriesType | int | Τύπος σειράς. |

**Επιστρέφει:**
boolean - True αν επιτρέπεται, αλλιώς false.
### isErrorBarsYAllowed(int seriesType) {#isErrorBarsYAllowed-int-}
```
public static boolean isErrorBarsYAllowed(int seriesType)
```

Επιστρέφει αν είναι επιτρεπτές οι γραμμές σφάλματος Y για τον καθορισμένο τύπο σειράς.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| seriesType | int | Τύπος σειράς. |

**Επιστρέφει:**
boolean - True αν επιτρέπεται, αλλιώς false.