---
title: IChartDataPoint
second_title: Αναφορά API του Aspose.Slides για Java
description: Αναπαριστά σημείο δεδομένων σειράς.
type: docs
url: /el/com.aspose.slides/ichartdatapoint/
---
**Όλες οι Υλοποιημένες Διασυνδέσεις:**
[com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IChartDataPoint extends IActualLayout
```

Αναπαριστά το σημείο δεδομένων σειράς.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getXValue()](#getXValue--) | Επιστρέφει την τιμή x ενός σημείου δεδομένων διαγράμματος. |
| [getYValue()](#getYValue--) | Επιστρέφει την τιμή y ενός σημείου δεδομένων διαγράμματος. |
| [getBubbleSize()](#getBubbleSize--) | Επιστρέφει το μέγεθος της φούσκας ενός σημείου δεδομένων διαγράμματος. |
| [getValue()](#getValue--) | Επιστρέφει την τιμή ενός σημείου δεδομένων διαγράμματος. |
| [getCachedXValue()](#getCachedXValue--) | Επιστρέφει την αποθηκευμένη τιμή X ενός σημείου δεδομένων διαγράμματος. |
| [getCachedYValue()](#getCachedYValue--) | Επιστρέφει την αποθηκευμένη τιμή Y ενός σημείου δεδομένων διαγράμματος. |
| [getCachedValue()](#getCachedValue--) | Επιστρέφει την αποθηκευμένη τιμή ενός σημείου δεδομένων διαγράμματος. |
| [getCachedBubbleSize()](#getCachedBubbleSize--) | Επιστρέφει το αποθηκευμένο μέγεθος φούσκας ενός σημείου δεδομένων διαγράμματος. |
| [getSizeValue()](#getSizeValue--) | Επιστρέφει την τιμή μεγέθους ενός σημείου δεδομένων διαγράμματος. |
| [getColorValue()](#getColorValue--) | Επιστρέφει την τιμή χρώματος ενός σημείου δεδομένων διαγράμματος. |
| [getErrorBarsCustomValues()](#getErrorBarsCustomValues--) | Αναπαριστά τις τιμές των γραμμών σφάλματος σειράς στην περίπτωση τύπου προσαρμοσμένης τιμής. |
| [getLabel()](#getLabel--) | Αναπαριστά την ετικέτα του σημείου δεδομένων διαγράμματος. |
| [isBubble3D()](#isBubble3D--) | Καθορίζει ότι οι φούσκες έχουν εφαρμοσμένο εφέ 3Δ. |
| [setBubble3D(boolean value)](#setBubble3D-boolean-) | Καθορίζει ότι οι φούσκες έχουν εφαρμοσμένο εφέ 3Δ. |
| [getExplosion()](#getExplosion--) | Καθορίζει το ποσό κατά το οποίο το σημείο δεδομένων θα μετακινηθεί από το κέντρο του πίτα. |
| [setExplosion(int value)](#setExplosion-int-) | Καθορίζει το ποσό κατά το οποίο το σημείο δεδομένων θα μετακινηθεί από το κέντρο του πίτα. |
| [getFormat()](#getFormat--) | Αναπαριστά τις ιδιότητες μορφοποίησης. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | Αναπαριστά τις ιδιότητες μορφοποίησης. |
| [getMarker()](#getMarker--) | Καθορίζει έναν δείκτη δεδομένων. |
| [remove()](#remove--) | Αφαιρεί το DataPoint από τη σειρά διαγράμματος. |
| [getAutomaticDataPointColor()](#getAutomaticDataPointColor--) | Επιστρέφει ένα αυτόματο χρώμα του σημείου δεδομένων βάσει του δείκτη σειράς, του δείκτη σημείου δεδομένων, της ιδιότητας ParentSeriesGroup.IsColorVaried και του στυλ διαγράμματος. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Ιδιότητες του αντίστοιχου καταχώρησης υπομνήματος στην περίπτωση τύπου διαγράμματος από αυτή τη λίστα: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. |
| [getSetAsTotal()](#getSetAsTotal--) | Ορίζει το σημείο δεδομένων ως σύνολο. |
| [setSetAsTotal(boolean value)](#setSetAsTotal-boolean-) | Ορίζει το σημείο δεδομένων ως σύνολο. |
| [getInvertIfNegative()](#getInvertIfNegative--) | Καθορίζει ότι το σημείο δεδομένων θα αντιστρέψει τα χρώματά του εάν η τιμή είναι αρνητική. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | Καθορίζει ότι το σημείο δεδομένων θα αντιστρέψει τα χρώματά του εάν η τιμή είναι αρνητική. |
| [getDataPointLevels()](#getDataPointLevels--) | Επιστρέφει το δοχείο των επιπέδων σημείου δεδομένων. |
| [getIndex()](#getIndex--) | Καθορίζει σε ποια συλλογή παιδιών του γονέα εφαρμόζεται αυτό το σημείο δεδομένων. |

### getXValue() {#getXValue--}
```
public abstract IStringOrDoubleChartValue getXValue()
```

Επιστρέφει την τιμή x ενός σημείου δεδομένων διαγράμματος. Μόνο για ανάγνωση [IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue).

**Επιστρέφει:**
[IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue)
### getYValue() {#getYValue--}
```
public abstract IDoubleChartValue getYValue()
```

Επιστρέφει την τιμή y ενός σημείου δεδομένων διαγράμματος. Μόνο για ανάγνωση [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Επιστρέφει:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getBubbleSize() {#getBubbleSize--}
```
public abstract IDoubleChartValue getBubbleSize()
```

Επιστρέφει το μέγεθος της φούσκας ενός σημείου δεδομένων διαγράμματος. Μόνο για ανάγνωση [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Επιστρέφει:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getValue() {#getValue--}
```
public abstract IDoubleChartValue getValue()
```

Επιστρέφει την τιμή ενός σημείου δεδομένων διαγράμματος. Μόνο για ανάγνωση [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Επιστρέφει:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getCachedXValue() {#getCachedXValue--}
```
public abstract ICachedChartValue getCachedXValue()
```

Επιστρέφει την αποθηκευμένη τιμή X ενός σημείου δεδομένων διαγράμματος. Μόνο για ανάγνωση [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      for(IChartSeries series : chart.getChartData().getSeries())
>      {
>          // Εκτυπώνει όλες τις αποθηκευμένες τιμές X της σειράς διαγράμματος.
>          for (IChartDataPoint point : series.getDataPoints())
>              System.out.println(point.getCachedXValue().toDouble());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Επιστρέφει:**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)
### getCachedYValue() {#getCachedYValue--}
```
public abstract ICachedChartValue getCachedYValue()
```

Επιστρέφει την αποθηκευμένη τιμή Y ενός σημείου δεδομένων διαγράμματος. Μόνο για ανάγνωση [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      for(IChartSeries series : chart.getChartData().getSeries())
>      {
>          // Εκτυπώνει όλες τις αποθηκευμένες τιμές Y της σειράς διαγράμματος.
>          for (IChartDataPoint point : series.getDataPoints())
>              System.out.println(point.getCachedYValue().toDouble());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Επιστρέφει:**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)
### getCachedValue() {#getCachedValue--}
```
public abstract ICachedChartValue getCachedValue()
```

Επιστρέφει την αποθηκευμένη τιμή ενός σημείου δεδομένων διαγράμματος. Μόνο για ανάγνωση [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      for(IChartSeries series : chart.getChartData().getSeries())
>      {
>          // Εκτυπώνει όλες τις αποθηκευμένες τιμές της σειράς διαγράμματος.
>          for (IChartDataPoint point : series.getDataPoints())
>              System.out.println(point.getCachedValue().toDouble());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Επιστρέφει:**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)
### getCachedBubbleSize() {#getCachedBubbleSize--}
```
public abstract ICachedChartValue getCachedBubbleSize()
```

Επιστρέφει το αποθηκευμένο μέγεθος φούσκας ενός σημείου δεδομένων διαγράμματος. Μόνο για ανάγνωση [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      for(IChartSeries series : chart.getChartData().getSeries())
>      {
>          // Εκτυπώνει όλες τις αποθηκευμένες τιμές μεγέθους φούσκας της σειράς διαγράμματος.
>          for (IChartDataPoint point : series.getDataPoints())
>              System.out.println(point.getCachedBubbleSize().toDouble());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Επιστρέφει:**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)
### getSizeValue() {#getSizeValue--}
```
public abstract IDoubleChartValue getSizeValue()
```

Επιστρέφει την τιμή μεγέθους ενός σημείου δεδομένων διαγράμματος. Χρησιμοποιείται σε διαγράμματα Treemap και Sunburst. Μόνο για ανάγνωση [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Επιστρέφει:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getColorValue() {#getColorValue--}
```
public abstract IDoubleChartValue getColorValue()
```

Επιστρέφει την τιμή χρώματος ενός σημείου δεδομένων διαγράμματος. Χρησιμοποιείται σε διαγράμματα χάρτη. Μόνο για ανάγνωση [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Επιστρέφει:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getErrorBarsCustomValues() {#getErrorBarsCustomValues--}
```
public abstract IErrorBarsCustomValues getErrorBarsCustomValues()
```

Αναπαριστά τις τιμές των γραμμών σφάλματος σειράς στην περίπτωση τύπου προσαρμοσμένης τιμής. Μόνο για ανάγνωση [IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues).

**Επιστρέφει:**
[IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues)
### getLabel() {#getLabel--}
```
public abstract IDataLabel getLabel()
```

Αναπαριστά την ετικέτα του σημείου δεδομένων διαγράμματος. Μόνο για ανάγνωση [IDataLabel](../../com.aspose.slides/idatalabel).

**Επιστρέφει:**
[IDataLabel](../../com.aspose.slides/idatalabel)
### isBubble3D() {#isBubble3D--}
```
public abstract boolean isBubble3D()
```

Καθορίζει ότι οι φούσκες έχουν εφαρμοσμένο εφέ 3Δ. Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**
boolean
### setBubble3D(boolean value) {#setBubble3D-boolean-}
```
public abstract void setBubble3D(boolean value)
```

Καθορίζει ότι οι φούσκες έχουν εφαρμοσμένο εφέ 3Δ. Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getExplosion() {#getExplosion--}
```
public abstract int getExplosion()
```

Καθορίζει το ποσό κατά το οποίο το σημείο δεδομένων θα μετακινηθεί από το κέντρο του πίτα. Ανάγνωση/εγγραφή int.

**Επιστρέφει:**
int
### setExplosion(int value) {#setExplosion-int-}
```
public abstract void setExplosion(int value)
```

Καθορίζει το ποσό κατά το οποίο το σημείο δεδομένων θα μετακινηθεί από το κέντρο του πίτα. Ανάγνωση/εγγραφή int.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Αναπαριστά τις ιδιότητες μορφοποίησης. Ανάγνωση/εγγραφή [IFormat](../../com.aspose.slides/iformat).

**Επιστρέφει:**
[IFormat](../../com.aspose.slides/iformat)
### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public abstract void setFormat(IFormat value)
```

Αναπαριστά τις ιδιότητες μορφοποίησης. Ανάγνωση/εγγραφή [IFormat](../../com.aspose.slides/iformat).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |

### getMarker() {#getMarker--}
```
public abstract IMarker getMarker()
```

Καθορίζει έναν δείκτη δεδομένων. Μόνο για ανάγνωση [IMarker](../../com.aspose.slides/imarker).

**Επιστρέφει:**
[IMarker](../../com.aspose.slides/imarker)
### remove() {#remove--}
```
public abstract void remove()
```

Αφαιρεί το DataPoint από τη σειρά διαγράμματος.

### getAutomaticDataPointColor() {#getAutomaticDataPointColor--}
```
public abstract Color getAutomaticDataPointColor()
```

Επιστρέφει ένα αυτόματο χρώμα του σημείου δεδομένων βάσει του δείκτη σειράς, του δείκτη σημείου δεδομένων, της ιδιότητας ParentSeriesGroup.IsColorVaried και του στυλ διαγράμματος. Αυτό το χρώμα χρησιμοποιείται εξ ορισμού εάν το FillType είναι NotDefined.

**Επιστρέφει:**
java.awt.Color - Automatic color of data point java.awt.Color
### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public abstract ILegendEntryProperties getRelatedLegendEntry()
```

Ιδιότητες του αντίστοιχου καταχώρησης υπομνήματος στην περίπτωση τύπου διαγράμματος από αυτή τη λίστα: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. Μόνο για ανάγνωση [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**Επιστρέφει:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)
### getSetAsTotal() {#getSetAsTotal--}
```
public abstract boolean getSetAsTotal()
```

Ορίζει το σημείο δεδομένων ως σύνολο. Εφαρμόζεται μόνο για τύπο σειράς Waterfall.

**Επιστρέφει:**
boolean
### setSetAsTotal(boolean value) {#setSetAsTotal-boolean-}
```
public abstract void setSetAsTotal(boolean value)
```

Ορίζει το σημείο δεδομένων ως σύνολο. Εφαρμόζεται μόνο για τύπο σειράς Waterfall.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getInvertIfNegative() {#getInvertIfNegative--}
```
public abstract boolean getInvertIfNegative()
```

Καθορίζει ότι το σημείο δεδομένων θα αντιστρέψει τα χρώματά του εάν η τιμή είναι αρνητική. Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**
boolean
### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public abstract void setInvertIfNegative(boolean value)
```

Καθορίζει ότι το σημείο δεδομένων θα αντιστρέψει τα χρώματά του εάν η τιμή είναι αρνητική. Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getDataPointLevels() {#getDataPointLevels--}
```
public abstract IChartDataPointLevelsManager getDataPointLevels()
```

Επιστρέφει το δοχείο των επιπέδων σημείου δεδομένων. Εφαρμόζεται για σειρές Treeamp και Sunburst. Η αρίθμηση των επιπέδων σημείου δεδομένων ξεκινά από το μηδέν.

**Επιστρέφει:**
[IChartDataPointLevelsManager](../../com.aspose.slides/ichartdatapointlevelsmanager)
### getIndex() {#getIndex--}
```
public abstract long getIndex()
```

Καθορίζει σε ποια συλλογή παιδιών του γονέα εφαρμόζεται αυτό το σημείο δεδομένων. Μόνο για ανάγνωση long.

**Επιστρέφει:**
long