---
title: IChartDataPoint
second_title: Aspose.Slides για Java Αναφορά API
description: Αναπαριστά σημείο δεδομένων σειράς.
type: docs
url: /el/com.aspose.slides/ichartdatapoint/
---
**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IChartDataPoint extends IActualLayout
```

Αναπαριστά σημείο δεδομένων σειράς.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getXValue()](#getXValue--) | Επιστρέφει την τιμή x του σημείου δεδομένων διαγράμματος. |
| [getYValue()](#getYValue--) | Επιστρέφει την τιμή y του σημείου δεδομένων διαγράμματος. |
| [getBubbleSize()](#getBubbleSize--) | Επιστρέφει το μέγεθος φυσαλίδας του σημείου δεδομένων διαγράμματος. |
| [getValue()](#getValue--) | Επιστρέφει την τιμή του σημείου δεδομένων διαγράμματος. |
| [getSizeValue()](#getSizeValue--) | Επιστρέφει τη μέτρηση μεγέθους του σημείου δεδομένων διαγράμματος. |
| [getColorValue()](#getColorValue--) | Επιστρέφει την τιμή χρώματος του σημείου δεδομένων διαγράμματος. |
| [getErrorBarsCustomValues()](#getErrorBarsCustomValues--) | Αναπαριστά τιμές γραμμών σφαλμάτων σειράς στην περίπτωση τύπου Custom. |
| [getLabel()](#getLabel--) | Αναπαριστά την ετικέτα του σημείου δεδομένων διαγράμματος. |
| [isBubble3D()](#isBubble3D--) | Καθορίζει ότι οι φυσαλίδες έχουν εφαρμοσμένο εφέ 3Δ. |
| [setBubble3D(boolean value)](#setBubble3D-boolean-) | Καθορίζει ότι οι φυσαλίδες έχουν εφαρμοσμένο εφέ 3Δ. |
| [getExplosion()](#getExplosion--) | Καθορίζει το ποσό με το οποίο το σημείο δεδομένων θα μετακινηθεί από το κέντρο του πίτας. |
| [setExplosion(int value)](#setExplosion-int-) | Καθορίζει το ποσό με το οποίο το σημείο δεδομένων θα μετακινηθεί από το κέντρο του πίτας. |
| [getFormat()](#getFormat--) | Αναπαριστά τις ιδιότητες μορφοποίησης. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | Αναπαριστά τις ιδιότητες μορφοποίησης. |
| [getMarker()](#getMarker--) | Καθορίζει μια ένδειξη δεδομένων. |
| [remove()](#remove--) | Καταργεί το DataPoint από τη σειρά διαγράμματος. |
| [getAutomaticDataPointColor()](#getAutomaticDataPointColor--) | Επιστρέφει ένα αυτόματο χρώμα του σημείου δεδομένων βάσει δείκτη σειράς, δείκτη σημείου δεδομένων, ιδιότητας ParentSeriesGroup.IsColorVaried και στυλ διαγράμματος. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Ιδιότητες της αντίστοιχης εγγραφής υπομνήματος σε περίπτωση τύπου διαγράμματος από αυτή τη λίστα: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. |
| [getSetAsTotal()](#getSetAsTotal--) | Ορίζει το σημείο δεδομένων ως σύνολο. |
| [setSetAsTotal(boolean value)](#setSetAsTotal-boolean-) | Ορίζει το σημείο δεδομένων ως σύνολο. |
| [getInvertIfNegative()](#getInvertIfNegative--) | Καθορίζει ότι το σημείο δεδομένων θα αντιστροφή των χρωμάτων του εάν η τιμή είναι αρνητική. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | Καθορίζει ότι το σημείο δεδομένων θα αντιστροφή των χρωμάτων του εάν η τιμή είναι αρνητική. |
| [getDataPointLevels()](#getDataPointLevels--) | Επιστρέφει το κοντέινερ των επιπέδων του σημείου δεδομένων. |
| [getIndex()](#getIndex--) | Καθορίζει σε ποια συλλογή παιδιών του γονέα εφαρμόζεται αυτό το σημείο δεδομένων. |
### getXValue() {#getXValue--}
```
public abstract IStringOrDoubleChartValue getXValue()
```


Επιστρέφει την τιμή x του σημείου δεδομένων διαγράμματος. Μόνο για ανάγνωση [IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue).

**Επιστρέφει:**
[IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue)
### getYValue() {#getYValue--}
```
public abstract IDoubleChartValue getYValue()
```


Επιστρέφει την τιμή y του σημείου δεδομένων διαγράμματος. Μόνο για ανάγνωση [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Επιστρέφει:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getBubbleSize() {#getBubbleSize--}
```
public abstract IDoubleChartValue getBubbleSize()
```


Επιστρέφει το μέγεθος φυσαλίδας του σημείου δεδομένων διαγράμματος. Μόνο για ανάγνωση [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Επιστρέφει:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getValue() {#getValue--}
```
public abstract IDoubleChartValue getValue()
```


Επιστρέφει την τιμή του σημείου δεδομένων διαγράμματος. Μόνο για ανάγνωση [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Επιστρέφει:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getSizeValue() {#getSizeValue--}
```
public abstract IDoubleChartValue getSizeValue()
```


Επιστρέφει τη μέτρηση μεγέθους του σημείου δεδομένων διαγράμματος. Χρησιμοποιείται με διαγράμματα Treemap και Sunburst. Μόνο για ανάγνωση [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Επιστρέφει:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getColorValue() {#getColorValue--}
```
public abstract IDoubleChartValue getColorValue()
```


Επιστρέφει την τιμή χρώματος του σημείου δεδομένων διαγράμματος. Χρησιμοποιείται με διαγράμματα Map. Μόνο για ανάγνωση [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Επιστρέφει:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getErrorBarsCustomValues() {#getErrorBarsCustomValues--}
```
public abstract IErrorBarsCustomValues getErrorBarsCustomValues()
```


Αναπαριστά τιμές γραμμών σφαλμάτων σειράς στην περίπτωση τύπου Custom. Μόνο για ανάγνωση [IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues).

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


Καθορίζει ότι οι φυσαλίδες έχουν εφαρμοσμένο εφέ 3Δ. Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**
boolean
### setBubble3D(boolean value) {#setBubble3D-boolean-}
```
public abstract void setBubble3D(boolean value)
```


Καθορίζει ότι οι φυσαλίδες έχουν εφαρμοσμένο εφέ 3Δ. Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getExplosion() {#getExplosion--}
```
public abstract int getExplosion()
```


Καθορίζει το ποσό με το οποίο το σημείο δεδομένων θα μετακινηθεί από το κέντρο του πίτας. Ανάγνωση/εγγραφή int.

**Επιστρέφει:**
int
### setExplosion(int value) {#setExplosion-int-}
```
public abstract void setExplosion(int value)
```


Καθορίζει το ποσό με το οποίο το σημείο δεδομένων θα μετακινηθεί από το κέντρο του πίτας. Ανάγνωση/εγγραφή int.

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


Καθορίζει μια ένδειξη δεδομένων. Μόνο για ανάγνωση [IMarker](../../com.aspose.slides/imarker).

**Επιστρέφει:**
[IMarker](../../com.aspose.slides/imarker)
### remove() {#remove--}
```
public abstract void remove()
```


Καταργεί το DataPoint από τη σειρά διαγράμματος.

### getAutomaticDataPointColor() {#getAutomaticDataPointColor--}
```
public abstract Color getAutomaticDataPointColor()
```


Επιστρέφει ένα αυτόματο χρώμα του σημείου δεδομένων βάσει δείκτη σειράς, δείκτη σημείου δεδομένων, ιδιότητας ParentSeriesGroup.IsColorVaried και στυλ διαγράμματος. Αυτό το χρώμα χρησιμοποιείται εξ' όρισμα εάν το FillType ισούται με NotDefined.

**Επιστρέφει:**
java.awt.Color - Automatic color of data point java.awt.Color
### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public abstract ILegendEntryProperties getRelatedLegendEntry()
```


Ιδιότητες της αντίστοιχης εγγραφής υπομνήματος σε περίπτωση τύπου διαγράμματος από αυτή τη λίστα: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. Μόνο για ανάγνωση [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

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


Καθορίζει ότι το σημείο δεδομένων θα αντιστροφή των χρωμάτων του εάν η τιμή είναι αρνητική. Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**
boolean
### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public abstract void setInvertIfNegative(boolean value)
```


Καθορίζει ότι το σημείο δεδομένων θα αντιστροφή των χρωμάτων του εάν η τιμή είναι αρνητική. Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getDataPointLevels() {#getDataPointLevels--}
```
public abstract IChartDataPointLevelsManager getDataPointLevels()
```


Επιστρέφει το κοντέινερ των επιπέδων του σημείου δεδομένων. Εφαρμόζεται για σειρές Treeamp και Sunburst. Η αρίθμηση επιπέδων σημείου δεδομένων είναι μηδενική.

**Επιστρέφει:**
[IChartDataPointLevelsManager](../../com.aspose.slides/ichartdatapointlevelsmanager)
### getIndex() {#getIndex--}
```
public abstract long getIndex()
```


Καθορίζει σε ποια συλλογή παιδιών του γονέα εφαρμόζεται αυτό το σημείο δεδομένων. Ανάγνωση long.

**Επιστρέφει:**
long