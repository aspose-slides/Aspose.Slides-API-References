---
title: ChartDataPoint
second_title: Aspose.Slides για την Αναφορά API της Java
description: Αντιπροσωπεύει το σημείο δεδομένων σειράς.
type: docs
url: /el/com.aspose.slides/chartdatapoint/
---
**Κληρονομικότητα:**
java.lang.Object

**Όλες οι υλοποιημένες διεπαφές:**
[com.aspose.slides.IChartDataPoint](../../com.aspose.slides/ichartdatapoint), com.aspose.slides.IDOMObject
```
public class ChartDataPoint implements IChartDataPoint, IDOMObject
```

Αντιπροσωπεύει σημείο δεδομένων σειράς.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getXValue()](#getXValue--) | XValue. |
| [getYValue()](#getYValue--) | YValue. |
| [getBubbleSize()](#getBubbleSize--) | BubbleSize. |
| [getValue()](#getValue--) | Value. |
| [getSizeValue()](#getSizeValue--) | Επιστρέφει την τιμή μεγέθους του σημείου δεδομένων διαγράμματος. |
| [getColorValue()](#getColorValue--) | Επιστρέφει την τιμή χρώματος του σημείου δεδομένων διαγράμματος. |
| [getErrorBarsCustomValues()](#getErrorBarsCustomValues--) | Αντιπροσωπεύει τις τιμές των ράβδων σφάλματος σειράς στην περίπτωση τύπου τιμής Custom. |
| [getLabel()](#getLabel--) | Label. |
| [isBubble3D()](#isBubble3D--) | Καθορίζει ότι οι φούσκες έχουν εφαρμοσμένο τρισδιάστατο εφέ. |
| [setBubble3D(boolean value)](#setBubble3D-boolean-) | Καθορίζει ότι οι φούσκες έχουν εφαρμοσμένο τρισδιάστατο εφέ. |
| [getExplosion()](#getExplosion--) | Καθορίζει το ποσό που το σημείο δεδομένων θα μετακινηθεί από το κέντρο του πίτας. |
| [setExplosion(int value)](#setExplosion-int-) | Καθορίζει το ποσό που το σημείο δεδομένων θα μετακινηθεί από το κέντρο του πίτας. |
| [getFormat()](#getFormat--) | Αντιπροσωπεύει τις ιδιότητες μορφοποίησης. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | Αντιπροσωπεύει τις ιδιότητες μορφοποίησης. |
| [getMarker()](#getMarker--) | Καθορίζει έναν δείκτη δεδομένων. |
| [getSetAsTotal()](#getSetAsTotal--) | Ορίζει το σημείο δεδομένων ως συνολικό. |
| [setSetAsTotal(boolean value)](#setSetAsTotal-boolean-) | Ορίζει το σημείο δεδομένων ως συνολικό. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Ιδιότητες της αντίστοιχης εγγραφής υπομνήματος στην περίπτωση τύπου διαγράμματος από αυτή τη λίστα: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. |
| [remove()](#remove--) | Αφαιρεί το DataPoint από τη σειρά διαγράμματος. |
| [getDataPointLevels()](#getDataPointLevels--) | Επιστρέφει το δοχείο επιπέδων σημείου δεδομένων. |
| [getIndex()](#getIndex--) |    |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getAutomaticDataPointColor()](#getAutomaticDataPointColor--) | Επιστρέφει ένα αυτόματο χρώμα σημείου δεδομένων βασισμένο στον δείκτη σειράς, στον δείκτη σημείου δεδομένων, στην ιδιότητα ParentSeriesGroup.IsColorVaried και στο στυλ διαγράμματος. |
| [getInvertIfNegative()](#getInvertIfNegative--) | Καθορίζει ότι το σημείο δεδομένων θα αντιστρέψει τα χρώματά του εάν η τιμή είναι αρνητική. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | Καθορίζει ότι το σημείο δεδομένων θα αντιστρέψει τα χρώματά του εάν η τιμή είναι αρνητική. |
| [getCachedValue()](#getCachedValue--) | Αποκτά την αποθηκευμένη τιμή ενός σημείου δεδομένων διαγράμματος. |
| [getCachedXValue()](#getCachedXValue--) | Αποκτά την αποθηκευμένη τιμή X ενός σημείου δεδομένων διαγράμματος. |
| [getCachedYValue()](#getCachedYValue--) | Αποκτά την αποθηκευμένη τιμή Y ενός σημείου δεδομένων διαγράμματος. |
| [getCachedBubbleSize()](#getCachedBubbleSize--) | Αποκτά το αποθηκευμένο μέγεθος φούσκας ενός σημείου δεδομένων διαγράμματος. |
| [getActualX()](#getActualX--) | Καθορίζει την πραγματική θέση x (αριστερά) του στοιχείου διαγράμματος σε σχέση με την αριστερή άνω γωνία του διαγράμματος. |
| [getActualY()](#getActualY--) | Καθορίζει το πραγματικό πάνω μέρος του στοιχείου διαγράμματος σε σχέση με την αριστερή άνω γωνία του διαγράμματος. |
| [getActualWidth()](#getActualWidth--) | Καθορίζει το πραγματικό πλάτος του στοιχείου διαγράμματος. |
| [getActualHeight()](#getActualHeight--) | Καθορίζει το πραγματικό ύψος του στοιχείου διαγράμματος. |

### getXValue() {#getXValue--}
```
public final IStringOrDoubleChartValue getXValue()
```

XValue. Μόνο ανάγνωση [IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue).

**Επιστρέφει:**
[IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue)

### getYValue() {#getYValue--}
```
public final IDoubleChartValue getYValue()
```

YValue. Μόνο ανάγνωση [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Επιστρέφει:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getBubbleSize() {#getBubbleSize--}
```
public final IDoubleChartValue getBubbleSize()
```

BubbleSize. Μόνο ανάγνωση [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Επιστρέφει:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getValue() {#getValue--}
```
public final IDoubleChartValue getValue()
```

Value. Μόνο ανάγνωση [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Επιστρέφει:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getSizeValue() {#getSizeValue--}
```
public final IDoubleChartValue getSizeValue()
```

Επιστρέφει την τιμή μεγέθους του σημείου δεδομένων διαγράμματος. Χρησιμοποιείται με διαγράμματα Treemap και Sunburst. Μόνο ανάγνωση [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Επιστρέφει:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getColorValue() {#getColorValue--}
```
public final IDoubleChartValue getColorValue()
```

Επιστρέφει την τιμή χρώματος του σημείου δεδομένων διαγράμματος. Χρησιμοποιείται με διαγράμματα Χάρτη. Μόνο ανάγνωση [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Επιστρέφει:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getErrorBarsCustomValues() {#getErrorBarsCustomValues--}
```
public final IErrorBarsCustomValues getErrorBarsCustomValues()
```

Αντιπροσωπεύει τις τιμές των ράβδων σφάλματος σειράς στην περίπτωση τύπου τιμής Custom. Μόνο ανάγνωση [IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues).

**Επιστρέφει:**
[IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues)

### getLabel() {#getLabel--}
```
public final IDataLabel getLabel()
```

Label. Μόνο ανάγνωση [IDataLabel](../../com.aspose.slides/idatalabel).

**Επιστρέφει:**
[IDataLabel](../../com.aspose.slides/idatalabel)

### isBubble3D() {#isBubble3D--}
```
public final boolean isBubble3D()
```

Καθορίζει ότι οι φούσκες έχουν εφαρμοσμένο τρισδιάστατο εφέ. Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**
boolean

### setBubble3D(boolean value) {#setBubble3D-boolean-}
```
public final void setBubble3D(boolean value)
```

Καθορίζει ότι οι φούσκες έχουν εφαρμοσμένο τρισδιάστατο εφέ. Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getExplosion() {#getExplosion--}
```
public final int getExplosion()
```

Καθορίζει το ποσό που το σημείο δεδομένων θα μετακινηθεί από το κέντρο του πίτας. Ανάγνωση/εγγραφή int.

**Επιστρέφει:**
int

### setExplosion(int value) {#setExplosion-int-}
```
public final void setExplosion(int value)
```

Καθορίζει το ποσό που το σημείο δεδομένων θα μετακινηθεί από το κέντρο του πίτας. Ανάγνωση/εγγραφή int.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

Αντιπροσωπεύει τις ιδιότητες μορφοποίησης. Ανάγνωση/εγγραφή [IFormat](../../com.aspose.slides/iformat).

**Επιστρέφει:**
[IFormat](../../com.aspose.slides/iformat)

### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public final void setFormat(IFormat value)
```

Αντιπροσωπεύει τις ιδιότητες μορφοποίησης. Ανάγνωση/εγγραφή [IFormat](../../com.aspose.slides/iformat).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |

### getMarker() {#getMarker--}
```
public final IMarker getMarker()
```

Καθορίζει έναν δείκτη δεδομένων. Μόνο ανάγνωση [IMarker](../../com.aspose.slides/imarker).

**Επιστρέφει:**
[IMarker](../../com.aspose.slides/imarker)

### getSetAsTotal() {#getSetAsTotal--}
```
public final boolean getSetAsTotal()
```

Ορίζει το σημείο δεδομένων ως συνολικό. Εφαρμόζεται μόνο για τύπο σειράς Waterfall.

**Επιστρέφει:**
boolean

### setSetAsTotal(boolean value) {#setSetAsTotal-boolean-}
```
public final void setSetAsTotal(boolean value)
```

Ορίζει το σημείο δεδομένων ως συνολικό. Εφαρμόζεται μόνο για τύπο σειράς Waterfall.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public final ILegendEntryProperties getRelatedLegendEntry()
```

Ιδιότητες της αντίστοιχης εγγραφής υπομνήματος στην περίπτωση τύπου διαγράμματος από αυτή τη λίστα: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. Μόνο ανάγνωση [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**Επιστρέφει:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)

### remove() {#remove--}
```
public final void remove()
```

Αφαιρεί το DataPoint από τη σειρά διαγράμματος.

### getDataPointLevels() {#getDataPointLevels--}
```
public final IChartDataPointLevelsManager getDataPointLevels()
```

Επιστρέφει το δοχείο επιπέδων σημείου δεδομένων. Εφαρμόζεται για σειρές Treeamp και Sunburst. Η αρίθμηση επιπέδων σημείου δεδομένων ξεκινά από το μηδέν.

**Επιστρέφει:**
[IChartDataPointLevelsManager](../../com.aspose.slides/ichartdatapointlevelsmanager)

### getIndex() {#getIndex--}
```
public final long getIndex()
```

  

**Επιστρέφει:**
long

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Επιστρέφει το αντικείμενο Parent_Immediate. Μόνο ανάγνωση IDOMObject.

**Επιστρέφει:**
com.aspose.slides.IDOMObject

### getAutomaticDataPointColor() {#getAutomaticDataPointColor--}
```
public final Color getAutomaticDataPointColor()
```

Επιστρέφει ένα αυτόματο χρώμα σημείου δεδομένων βασισμένο στον δείκτη σειράς, στον δείκτη σημείου δεδομένων, στην ιδιότητα ParentSeriesGroup.IsColorVaried και στο στυλ διαγράμματος. Αυτό το χρώμα χρησιμοποιείται εξ ορισμού εάν το FillType είναι NotDefined.

**Επιστρέφει:**
java.awt.Color

### getInvertIfNegative() {#getInvertIfNegative--}
```
public final boolean getInvertIfNegative()
```

Καθορίζει ότι το σημείο δεδομένων θα αντιστρέψει τα χρώματά του εάν η τιμή είναι αρνητική. Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**
boolean

### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public final void setInvertIfNegative(boolean value)
```

Καθορίζει ότι το σημείο δεδομένων θα αντιστρέψει τα χρώματά του εάν η τιμή είναι αρνητική. Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getCachedValue() {#getCachedValue--}
```
public final ICachedChartValue getCachedValue()
```

Αποκτά την αποθηκευμένη τιμή ενός σημείου δεδομένων διαγράμματος. Μόνο ανάγνωση [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

--------------------

> ``` 
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      for(IChartSeries series : chart.getChartData().getSeries())
>      {
>          // Εκτυπώστε όλες τις αποθηκευμένες τιμές της σειράς του διαγράμματος.
>          for (IChartDataPoint point : series.getDataPoints())
>              System.out.println(point.getCachedValue().toDouble());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Επιστρέφει:**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)

### getCachedXValue() {#getCachedXValue--}
```
public final ICachedChartValue getCachedXValue()
```

Αποκτά την αποθηκευμένη τιμή X ενός σημείου δεδομένων διαγράμματος. Μόνο ανάγνωση [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

--------------------

> ``` 
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      for(IChartSeries series : chart.getChartData().getSeries())
>      {
>          // Εκτυπώστε όλες τις αποθηκευμένες τιμές X της σειράς του διαγράμματος.
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
public final ICachedChartValue getCachedYValue()
```

Αποκτά την αποθηκευμένη τιμή Y ενός σημείου δεδομένων διαγράμματος. Μόνο ανάγνωση [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

--------------------

> ``` 
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      for(IChartSeries series : chart.getChartData().getSeries())
>      {
>          // Εκτυπώστε όλες τις αποθηκευμένες τιμές Y της σειράς του διαγράμματος.
>          for (IChartDataPoint point : series.getDataPoints())
>              System.out.println(point.getCachedYValue().toDouble());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Επιστρέφει:**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)

### getCachedBubbleSize() {#getCachedBubbleSize--}
```
public final ICachedChartValue getCachedBubbleSize()
```

Αποκτά το αποθηκευμένο μέγεθος φούσκας ενός σημείου δεδομένων διαγράμματος. Μόνο ανάγνωση [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

--------------------

> ``` 
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      for(IChartSeries series : chart.getChartData().getSeries())
>      {
>          // Εκτυπώστε όλες τις αποθηκευμένες τιμές μεγέθους φούσκας της σειράς του διαγράμματος.
>          for (IChartDataPoint point : series.getDataPoints())
>              System.out.println(point.getCachedBubbleSize().toDouble());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Επιστρέφει:**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)

### getActualX() {#getActualX--}
```
public final float getActualX()
```

Καθορίζει την πραγματική θέση x (αριστερά) του στοιχείου διαγράμματος σε σχέση με την αριστερή άνω γωνία του διαγράμματος. Καλέστε τη μέθοδο IChart.ValidateChartLayout() πριν για να λάβετε τις πραγματικές τιμές. Ανάγνωση float.

**Επιστρέφει:**
float

### getActualY() {#getActualY--}
```
public final float getActualY()
```

Καθορίζει το πραγματικό πάνω μέρος του στοιχείου διαγράμματος σε σχέση με την αριστερή άνω γωνία του διαγράμματος. Καλέστε τη μέθοδο IChart.ValidateChartLayout() πριν για να λάβετε τις πραγματικές τιμές. Ανάγνωση float.

**Επιστρέφει:**
float

### getActualWidth() {#getActualWidth--}
```
public final float getActualWidth()
```

Καθορίζει το πραγματικό πλάτος του στοιχείου διαγράμματος. Καλέστε τη μέθοδο IChart.ValidateChartLayout() πριν για να λάβετε τις πραγματικές τιμές. Ανάγνωση float.

**Επιστρέφει:**
float

### getActualHeight() {#getActualHeight--}
```
public final float getActualHeight()
```

Καθορίζει το πραγματικό ύψος του στοιχείου διαγράμματος. Καλέστε τη μέθοδο IChart.ValidateChartLayout() πριν για να λάβετε τις πραγματικές τιμές. Ανάγνωση float.

**Επιστρέφει:**
float