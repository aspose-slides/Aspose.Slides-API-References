---
title: IChartDataPoint
second_title: Aspose.Slides για Android μέσω Java API Αναφορά
description: Αντιπροσωπεύει το σημείο δεδομένων σειράς.
type: docs
url: /el/com.aspose.slides/ichartdatapoint/
---
**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IChartDataPoint extends IActualLayout
```

Αντιπροσωπεύει το σημείο δεδομένων σειράς.
## Μεθόδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getXValue()](#getXValue--) | Επιστρέφει την τιμή x του σημείου δεδομένων γραφήματος. |
| [getYValue()](#getYValue--) | Επιστρέφει την τιμή y του σημείου δεδομένων γραφήματος. |
| [getBubbleSize()](#getBubbleSize--) | Επιστρέφει το μέγεθος φυσαλίδας του σημείου δεδομένων γραφήματος. |
| [getValue()](#getValue--) | Επιστρέφει την τιμή του σημείου δεδομένων γραφήματος. |
| [getSizeValue()](#getSizeValue--) | Επιστρέφει την τιμή μεγέθους του σημείου δεδομένων γραφήματος. |
| [getColorValue()](#getColorValue--) | Επιστρέφει την τιμή χρώματος του σημείου δεδομένων γραφήματος. |
| [getErrorBarsCustomValues()](#getErrorBarsCustomValues--) | Αντιπροσωπεύει τις τιμές σφαλμάτων σειράς σε περίπτωση τύπου τιμής Custom. |
| [getLabel()](#getLabel--) | Αντιπροσωπεύει την ετικέτα του σημείου δεδομένων γραφήματος. |
| [isBubble3D()](#isBubble3D--) | Καθορίζει ότι οι φουσκί έχουν εφαρμοσμένο εφέ 3Δ. |
| [setBubble3D(boolean value)](#setBubble3D-boolean-) | Καθορίζει ότι οι φουσκί έχουν εφαρμοσμένο εφέ 3Δ. |
| [getExplosion()](#getExplosion--) | Καθορίζει το ποσό κατά το οποίο το σημείο δεδομένων θα μετακινηθεί από το κέντρο της πίτας. |
| [setExplosion(int value)](#setExplosion-int-) | Καθορίζει το ποσό κατά το οποίο το σημείο δεδομένων θα μετακινηθεί από το κέντρο της πίτας. |
| [getFormat()](#getFormat--) | Αντιπροσωπεύει τις ιδιότητες μορφοποίησης. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | Αντιπροσωπεύει τις ιδιότητες μορφοποίησης. |
| [getMarker()](#getMarker--) | Καθορίζει έναν δείκτη δεδομένων. |
| [remove()](#remove--) | Αφαιρεί το DataPoint από τη σειρά γραφήματος. |
| [getAutomaticDataPointColor()](#getAutomaticDataPointColor--) | Επιστρέφει αυτόματο χρώμα του σημείου δεδομένων βάσει δείκτη σειράς, δείκτη σημείου δεδομένων, ιδιότητας ParentSeriesGroup.IsColorVaried και στυλ γραφήματος. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Ιδιότητες της αντίστοιχης καταχώρισης υπομνήματος στην περίπτωση τύπου γραφήματος από αυτή τη λίστα: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. |
| [getSetAsTotal()](#getSetAsTotal--) | Ορίζει το σημείο δεδομένων ως σύνολο. |
| [setSetAsTotal(boolean value)](#setSetAsTotal-boolean-) | Ορίζει το σημείο δεδομένων ως σύνολο. |
| [getInvertIfNegative()](#getInvertIfNegative--) | Καθορίζει ότι το σημείο δεδομένων θα αντιστρέψει τα χρώματά του αν η τιμή είναι αρνητική. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | Καθορίζει ότι το σημείο δεδομένων θα αντιστρέψει τα χρώματά του αν η τιμή είναι αρνητική. |
| [getDataPointLevels()](#getDataPointLevels--) | Επιστρέφει το κοντέινερ των επιπέδων του σημείου δεδομένων. |
| [getIndex()](#getIndex--) | Καθορίζει σε ποιο σύνολο παιδιών του γονέα ανήκει αυτό το σημείο δεδομένων. |

### getXValue() {#getXValue--}
```
public abstract IStringOrDoubleChartValue getXValue()
```


Επιστρέφει την τιμή x του σημείου δεδομένων γραφήματος. Μόνο για ανάγνωση [IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue).

**Επιστρέφει:**
[IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue)
### getYValue() {#getYValue--}
```
public abstract IDoubleChartValue getYValue()
```


Επιστρέφει την τιμή y του σημείου δεδομένων γραφήματος. Μόνο για ανάγνωση [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Επιστρέφει:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getBubbleSize() {#getBubbleSize--}
```
public abstract IDoubleChartValue getBubbleSize()
```


Επιστρέφει το μέγεθος φυσαλίδας του σημείου δεδομένων γραφήματος. Μόνο για ανάγνωση [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Επιστρέφει:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getValue() {#getValue--}
```
public abstract IDoubleChartValue getValue()
```


Επιστρέφει την τιμή του σημείου δεδομένων γραφήματος. Μόνο για ανάγνωση [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Επιστρέφει:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getSizeValue() {#getSizeValue--}
```
public abstract IDoubleChartValue getSizeValue()
```


Επιστρέφει την τιμή μεγέθους του σημείου δεδομένων γραφήματος. Χρησιμοποιείται με γραφήματα Treemap και Sunburst. Μόνο για ανάγνωση [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Επιστρέφει:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getColorValue() {#getColorValue--}
```
public abstract IDoubleChartValue getColorValue()
```


Επιστρέφει την τιμή χρώματος του σημείου δεδομένων γραφήματος. Χρησιμοποιείται με χάρτες. Μόνο για ανάγνωση [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Επιστρέφει:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getErrorBarsCustomValues() {#getErrorBarsCustomValues--}
```
public abstract IErrorBarsCustomValues getErrorBarsCustomValues()
```


Αντιπροσωπεύει τις τιμές σφαλμάτων σειράς σε περίπτωση τύπου τιμής Custom. Μόνο για ανάγνωση [IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues).

**Επιστρέφει:**
[IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues)
### getLabel() {#getLabel--}
```
public abstract IDataLabel getLabel()
```


Αντιπροσωπεύει την ετικέτα του σημείου δεδομένων γραφήματος. Μόνο για ανάγνωση [IDataLabel](../../com.aspose.slides/idatalabel).

**Επιστρέφει:**
[IDataLabel](../../com.aspose.slides/idatalabel)
### isBubble3D() {#isBubble3D--}
```
public abstract boolean isBubble3D()
```


Καθορίζει ότι οι φουσκί έχουν εφαρμοσμένο εφέ 3Δ. Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**
boolean
### setBubble3D(boolean value) {#setBubble3D-boolean-}
```
public abstract void setBubble3D(boolean value)
```


Καθορίζει ότι οι φουσκί έχουν εφαρμοσμένο εφέ 3Δ. Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getExplosion() {#getExplosion--}
```
public abstract int getExplosion()
```


Καθορίζει το ποσό κατά το οποίο το σημείο δεδομένων θα μετακινηθεί από το κέντρο της πίτας. Ανάγνωση/εγγραφή int.

**Επιστρέφει:**
int
### setExplosion(int value) {#setExplosion-int-}
```
public abstract void setExplosion(int value)
```


Καθορίζει το ποσό κατά το οποίο το σημείο δεδομένων θα μετακινηθεί από το κέντρο της πίτας. Ανάγνωση/εγγραφή int.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```


Αντιπροσωπεύει τις ιδιότητες μορφοποίησης. Ανάγνωση/εγγραφή [IFormat](../../com.aspose.slides/iformat).

**Επιστρέφει:**
[IFormat](../../com.aspose.slides/iformat)
### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public abstract void setFormat(IFormat value)
```


Αντιπροσωπεύει τις ιδιότητες μορφοποίησης. Ανάγνωση/εγγραφή [IFormat](../../com.aspose.slides/iformat).

**Παράμετροι:**
| Parameter | Type | Description |
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


Αφαιρεί το DataPoint από τη σειρά γραφήματος.

### getAutomaticDataPointColor() {#getAutomaticDataPointColor--}
```
public abstract Integer getAutomaticDataPointColor()
```


Επιστρέφει αυτόματο χρώμα του σημείου δεδομένων βάσει δείκτη σειράς, δείκτη σημείου δεδομένων, ιδιότητας ParentSeriesGroup.IsColorVaried και στυλ γραφήματος. Αυτό το χρώμα χρησιμοποιείται εξ'ορισμού εάν FillType είναι NotDefined.

**Επιστρέφει:**
java.lang.Integer - Automatic color of data point java.lang.Integer
### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public abstract ILegendEntryProperties getRelatedLegendEntry()
```


Ιδιότητες της αντίστοιχης καταχώρισης υπομνήματος στην περίπτωση τύπου γραφήματος από αυτή τη λίστα: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. Μόνο για ανάγνωση [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**Επιστρέφει:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)
### getSetAsTotal() {#getSetAsTotal--}
```
public abstract boolean getSetAsTotal()
```


Ορίζει το σημείο δεδομένων ως σύνολο. Εφαρμόζεται μόνο σε τύπο σειράς Waterfall.

**Επιστρέφει:**
boolean
### setSetAsTotal(boolean value) {#setSetAsTotal-boolean-}
```
public abstract void setSetAsTotal(boolean value)
```


Ορίζει το σημείο δεδομένων ως σύνολο. Εφαρμόζεται μόνο σε τύπο σειράς Waterfall.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getInvertIfNegative() {#getInvertIfNegative--}
```
public abstract boolean getInvertIfNegative()
```


Καθορίζει ότι το σημείο δεδομένων θα αντιστρέψει τα χρώματά του αν η τιμή είναι αρνητική. Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**
boolean
### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public abstract void setInvertIfNegative(boolean value)
```


Καθορίζει ότι το σημείο δεδομένων θα αντιστρέψει τα χρώματά του αν η τιμή είναι αρνητική. Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Parameter | Type | Description |
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


Καθορίζει σε ποιο σύνολο παιδιών του γονέα ανήκει αυτό το σημείο δεδομένων. Ανάγνωση long.

**Επιστρέφει:**
long