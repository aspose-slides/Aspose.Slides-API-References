---
title: ChartDataPoint
second_title: Aspose.Slides για Android μέσω Java API Reference
description: Αναπαριστά το σημείο δεδομένων της σειράς.
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

Αναπαριστά το σημείο δεδομένων της σειράς.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getXValue()](#getXValue--) | XValue. |
| [getYValue()](#getYValue--) | YValue. |
| [getBubbleSize()](#getBubbleSize--) | BubbleSize. |
| [getValue()](#getValue--) | Value. |
| [getSizeValue()](#getSizeValue--) | Επιστρέφει την τιμή μεγέθους του σημείου δεδομένων του διαγράμματος. |
| [getColorValue()](#getColorValue--) | Επιστρέφει την τιμή χρώματος του σημείου δεδομένων του διαγράμματος. |
| [getErrorBarsCustomValues()](#getErrorBarsCustomValues--) | Αναπαριστά τις τιμές των ράβδων σφάλματος της σειράς σε περίπτωση τύπου Custom value. |
| [getLabel()](#getLabel--) | Label. |
| [isBubble3D()](#isBubble3D--) | Καθορίζει ότι οι φούσκες έχουν εφαρμοσμένο 3-Δ εφέ. |
| [setBubble3D(boolean value)](#setBubble3D-boolean-) | Καθορίζει ότι οι φούσκες έχουν εφαρμοσμένο 3-Δ εφέ. |
| [getExplosion()](#getExplosion--) | Καθορίζει το ποσό κατά το οποίο το σημείο δεδομένων θα μετακινηθεί από το κέντρο του πίτας. |
| [setExplosion(int value)](#setExplosion-int-) | Καθορίζει το ποσό κατά το οποίο το σημείο δεδομένων θα μετακινηθεί από το κέντρο του πίτας. |
| [getFormat()](#getFormat--) | Αναπαριστά τις ιδιότητες μορφοποίησης. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | Αναπαριστά τις ιδιότητες μορφοποίησης. |
| [getMarker()](#getMarker--) | Καθορίζει έναν δείκτη δεδομένων. |
| [getSetAsTotal()](#getSetAsTotal--) | Ορίζει το σημείο δεδομένων ως σύνολο. |
| [setSetAsTotal(boolean value)](#setSetAsTotal-boolean-) | Ορίζει το σημείο δεδομένων ως σύνολο. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Ιδιότητες της αντίστοιχης καταχώρησης υπομνήματος σε περίπτωση τύπου διαγράμματος από τη λίστα: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. |
| [remove()](#remove--) | Αφαιρεί το DataPoint από τη σειρά του διαγράμματος. |
| [getDataPointLevels()](#getDataPointLevels--) | Επιστρέφει το δοχείο των επιπέδων σημείου δεδομένων. |
| [getIndex()](#getIndex--) |    |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getAutomaticDataPointColor()](#getAutomaticDataPointColor--) | Επιστρέφει ένα αυτόματο χρώμα του σημείου δεδομένων βάσει δείκτη σειράς, δείκτη σημείου δεδομένων, ιδιότητας ParentSeriesGroup.IsColorVaried και στυλ διαγράμματος. |
| [getInvertIfNegative()](#getInvertIfNegative--) | Καθορίζει ότι το σημείο δεδομένων θα αντιστρέψει τα χρώματά του εάν η τιμή είναι αρνητική. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | Καθορίζει ότι το σημείο δεδομένων θα αντιστρέψει τα χρώματά του εάν η τιμή είναι αρνητική. |
| [getActualX()](#getActualX--) | Καθορίζει την πραγματική τοποθεσία x (αριστερά) του στοιχείου διαγράμματος σε σχέση με την επάνω αριστερή γωνία του διαγράμματος. |
| [getActualY()](#getActualY--) | Καθορίζει το πραγματικό επάνω μέρος του στοιχείου διαγράμματος σε σχέση με την επάνω αριστερή γωνία του διαγράμματος. |
| [getActualWidth()](#getActualWidth--) | Καθορίζει το πραγματικό πλάτος του στοιχείου διαγράμματος. |
| [getActualHeight()](#getActualHeight--) | Καθορίζει το πραγματικό ύψος του στοιχείου διαγράμματος. |

### getXValue() {#getXValue--}
```
public final IStringOrDoubleChartValue getXValue()
```

XValue. Μόνο-ανάγνωση [IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue).

**Επιστρέφει:**
[IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue)

### getYValue() {#getYValue--}
```
public final IDoubleChartValue getYValue()
```

YValue. Μόνο-ανάγνωση [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Επιστρέφει:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getBubbleSize() {#getBubbleSize--}
```
public final IDoubleChartValue getBubbleSize()
```

BubbleSize. Μόνο-ανάγνωση [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Επιστρέφει:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getValue() {#getValue--}
```
public final IDoubleChartValue getValue()
```

Value. Μόνο-ανάγνωση [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Επιστρέφει:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getSizeValue() {#getSizeValue--}
```
public final IDoubleChartValue getSizeValue()
```

Επιστρέφει την τιμή μεγέθους του σημείου δεδομένων του διαγράμματος. Χρησιμοποιείται με διαγράμματα Treemap και Sunburst. Μόνο-ανάγνωση [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Επιστρέφει:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getColorValue() {#getColorValue--}
```
public final IDoubleChartValue getColorValue()
```

Επιστρέφει την τιμή χρώματος του σημείου δεδομένων του διαγράμματος. Χρησιμοποιείται με διαγράμματα χάρτη. Μόνο-ανάγνωση [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Επιστρέφει:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getErrorBarsCustomValues() {#getErrorBarsCustomValues--}
```
public final IErrorBarsCustomValues getErrorBarsCustomValues()
```

Αναπαριστά τις τιμές των ράβδων σφάλματος της σειράς σε περίπτωση τύπου Custom value. Μόνο-ανάγνωση [IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues).

**Επιστρέφει:**
[IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues)

### getLabel() {#getLabel--}
```
public final IDataLabel getLabel()
```

Label. Μόνο-ανάγνωση [IDataLabel](../../com.aspose.slides/idatalabel).

**Επιστρέφει:**
[IDataLabel](../../com.aspose.slides/idatalabel)

### isBubble3D() {#isBubble3D--}
```
public final boolean isBubble3D()
```

Καθορίζει ότι οι φούσκες έχουν εφαρμοσμένο 3-Δ εφέ. Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**
boolean

### setBubble3D(boolean value) {#setBubble3D-boolean-}
```
public final void setBubble3D(boolean value)
```

Καθορίζει ότι οι φούσκες έχουν εφαρμοσμένο 3-Δ εφέ. Ανάγνωση/εγγραφή boolean.

**Παράμεetri:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getExplosion() {#getExplosion--}
```
public final int getExplosion()
```

Καθορίζει το ποσό κατά το οποίο το σημείο δεδομένων θα μετακινηθεί από το κέντρο του πίτας. Ανάγνωση/εγγραφή int.

**Επιστρέφει:**
int

### setExplosion(int value) {#setExplosion-int-}
```
public final void setExplosion(int value)
```

Καθορίζει το ποσό κατά το οποίο το σημείο δεδομένων θα μετακινηθεί από το κέντρο του πίτας. Ανάγνωση/εγγραφή int.

**Παράμεetri:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

Αναπαριστά τις ιδιότητες μορφοποίησης. Ανάγνωση/εγγραφή [IFormat](../../com.aspose.slides/iformat).

**Επιστρέφει:**
[IFormat](../../com.aspose.slides/iformat)

### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public final void setFormat(IFormat value)
```

Αναπαριστά τις ιδιότητες μορφοποίησης. Ανάγνωση/εγγραφή [IFormat](../../com.aspose.slides/iformat).

**Παράμεetri:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |

### getMarker() {#getMarker--}
```
public final IMarker getMarker()
```

Καθορίζει έναν δείκτη δεδομένων. Μόνο-ανάγνωση [IMarker](../../com.aspose.slides/imarker).

**Επιστρέφει:**
[IMarker](../../com.aspose.slides/imarker)

### getSetAsTotal() {#getSetAsTotal--}
```
public final boolean getSetAsTotal()
```

Ορίζει το σημείο δεδομένων ως σύνολο. Εφαρμόζεται μόνο για τύπο σειράς Waterfall.

**Επιστρέφει:**
boolean

### setSetAsTotal(boolean value) {#setSetAsTotal-boolean-}
```
public final void setSetAsTotal(boolean value)
```

Ορίζει το σημείο δεδομένων ως σύνολο. Εφαρμόζεται μόνο για τύπο σειράς Waterfall.

**Παράμεetri:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public final ILegendEntryProperties getRelatedLegendEntry()
```

Ιδιότητες της αντίστοιχης καταχώρησης υπομνήματος σε περίπτωση τύπου διαγράμματος από τη λίστα: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. Μόνο-ανάγνωση [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**Επιστρέφει:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)

### remove() {#remove--}
```
public final void remove()
```

Αφαιρεί το DataPoint από τη σειρά του διαγράμματος.

### getDataPointLevels() {#getDataPointLevels--}
```
public final IChartDataPointLevelsManager getDataPointLevels()
```

Επιστρέφει το δοχείο των επιπέδων σημείου δεδομένων. Εφαρμόζεται για σειρές Treeamp και Sunburst. Η αρίθμηση επιπέδων σημείου δεδομένων ξεκινά από το μηδέν.

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

Επιστρέφει το αντικείμενο Parent_Immediate. Μόνο-ανάγνωση IDOMObject.

**Επιστρέφει:**
com.aspose.slides.IDOMObject

### getAutomaticDataPointColor() {#getAutomaticDataPointColor--}
```
public final Integer getAutomaticDataPointColor()
```

Επιστρέφει ένα αυτόματο χρώμα του σημείου δεδομένων βάσει δείκτη σειράς, δείκτη σημείου δεδομένων, ιδιότητας ParentSeriesGroup.IsColorVaried και στυλ διαγράμματος. Αυτό το χρώμα χρησιμοποιείται εξ ορισμού εάν FillType ισούται με NotDefined.

**Επιστρέφει:**
java.lang.Integer

### getInvertIfNegative() {#getInvertIfNegative--}
```
public final boolean getInvertIfNegative()
```

Καθορίζει ότι το σημείο δεδομένων θα αντιστρέψει τα χρώματά του εάν η τιμή είναι αρνητική. Ανάγωση/εγγραφή boolean.

**Επιστρέφει:**
boolean

### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public final void setInvertIfNegative(boolean value)
```

Καθορίζει ότι το σημείο δεδομένων θα αντιστρέψει τα χρώματά του εάν η τιμή είναι αρνητική. Ανάγωση/εγγραφή boolean.

**Παράμεetri:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getActualX() {#getActualX--}
```
public final float getActualX()
```

Καθορίζει την πραγματική τοποθεσία x (αριστερά) του στοιχείου διαγράμματος σε σχέση με την επάνω αριστερή γωνία του διαγράμματος. Κλήστε τη μέθοδο IChart.ValidateChartLayout() πριν για να λάβετε τις πραγματικές τιμές. Μόνο-ανάγνωση float.

**Επιστρέφει:**
float

### getActualY() {#getActualY--}
```
public final float getActualY()
```

Καθορίζει το πραγματικό επάνω μέρος του στοιχείου διαγράμματος σε σχέση με την επάνω αριστερή γωνία του διαγράμματος. Κλήστε τη μέθοδο IChart.ValidateChartLayout() πριν για να λάβετε τις πραγματικές τιμές. Μόνο-ανάγνωση float.

**Επιστρέφει:**
float

### getActualWidth() {#getActualWidth--}
```
public final float getActualWidth()
```

Καθορίζει το πραγματικό πλάτος του στοιχείου διαγράμματος. Κλήστε τη μέθοδο IChart.ValidateChartLayout() πριν για να λάβετε τις πραγματικές τιμές. Μόνο-ανάγνωση float.

**Επιστρέφει:**
float

### getActualHeight() {#getActualHeight--}
```
public final float getActualHeight()
```

Καθορίζει το πραγματικό ύψος του στοιχείου διαγράμματος. Κλήστε τη μέθοδο IChart.ValidateChartLayout() πριν για να λάβετε τις πραγματικές τιμές. Μόνο-ανάγνωση float.

**Επιστρέφει:**
float