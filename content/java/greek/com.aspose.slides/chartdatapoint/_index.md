---
title: ChartDataPoint
second_title: Αναφορά API Aspose.Slides για Java
description: Αντιπροσωπεύει το σημείο δεδομένων της σειράς.
type: docs
url: /el/com.aspose.slides/chartdatapoint/
---
**Κληρονομικότητα:**
java.lang.Object

**Όλες οι Υλοποιημένες Διασυνδέσεις:**
[com.aspose.slides.IChartDataPoint](../../com.aspose.slides/ichartdatapoint), com.aspose.slides.IDOMObject
```
public class ChartDataPoint implements IChartDataPoint, IDOMObject
```

Αντιπροσωπεύει το σημείο δεδομένων σειράς.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getXValue()](#getXValue--) | XValue. |
| [getYValue()](#getYValue--) | YValue. |
| [getBubbleSize()](#getBubbleSize--) | BubbleSize. |
| [getValue()](#getValue--) | Value. |
| [getSizeValue()](#getSizeValue--) | Επιστρέφει την τιμή μεγέθους του σημείου δεδομένων του διαγράμματος. |
| [getColorValue()](#getColorValue--) | Επιστρέφει την τιμή χρώματος του σημείου δεδομένων του διαγράμματος. |
| [getErrorBarsCustomValues()](#getErrorBarsCustomValues--) | Αντιπροσωπεύει τις τιμές των ραβδών σφάλματος σειράς σε περίπτωση προσαρμοσμένου τύπου τιμής. |
| [getLabel()](#getLabel--) | Label. |
| [isBubble3D()](#isBubble3D--) | Καθορίζει ότι οι φούσκες διαθέτουν τρισδιάστατη επίδραση. |
| [setBubble3D(boolean value)](#setBubble3D-boolean-) | Καθορίζει ότι οι φούσκες διαθέτουν τρισδιάστατη επίδραση. |
| [getExplosion()](#getExplosion--) | Καθορίζει το πόσο το σημείο δεδομένων θα μετακινηθεί από το κέντρο του πίτα. |
| [setExplosion(int value)](#setExplosion-int-) | Καθορίζει το πόσο το σημείο δεδομένων θα μετακινηθεί από το κέντρο του πίτα. |
| [getFormat()](#getFormat--) | Αντιπροσωπεύει τις ιδιότητες μορφοποίησης. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | Αντιπροσωπεύει τις ιδιότητες μορφοποίησης. |
| [getMarker()](#getMarker--) | Καθορίζει έναν σημειωτή δεδομένων. |
| [getSetAsTotal()](#getSetAsTotal--) | Ορίζει το σημείο δεδομένων ως σύνολο. |
| [setSetAsTotal(boolean value)](#setSetAsTotal-boolean-) | Ορίζει το σημείο δεδομένων ως σύνολο. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Ιδιότητες της αντίστοιχης καταχώρησης υπομνήματος στην περίπτωση τύπου διαγράμματος από αυτή τη λίστα: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. |
| [remove()](#remove--) | Αφαιρεί το DataPoint από τη σειρά του διαγράμματος. |
| [getDataPointLevels()](#getDataPointLevels--) | Επιστρέφει το δοχείο των επιπέδων του σημείου δεδομένων. |
| [getIndex()](#getIndex--) |    |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getAutomaticDataPointColor()](#getAutomaticDataPointColor--) | Επιστρέφει ένα αυτόματο χρώμα του σημείου δεδομένων βάσει του δείκτη σειράς, δείκτη σημείου δεδομένων, ιδιότητας ParentSeriesGroup.IsColorVaried και του στυλ διαγράμματος. |
| [getInvertIfNegative()](#getInvertIfNegative--) | Καθορίζει ότι το σημείο δεδομένων θα αντιστρέψει τα χρώματά του εάν η τιμή είναι αρνητική. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | Καθορίζει ότι το σημείο δεδομένων θα αντιστρέψει τα χρώματά του εάν η τιμή είναι αρνητική. |
| [getActualX()](#getActualX--) | Καθορίζει την πραγματική θέση x (αριστερά) του στοιχείου του διαγράμματος σε σχέση με την αριστερή άνω γωνία του διαγράμματος. |
| [getActualY()](#getActualY--) | Καθορίζει την πραγματική κορυφή του στοιχείου του διαγράμματος σε σχέση με την αριστερή άνω γωνία του διαγράμματος. |
| [getActualWidth()](#getActualWidth--) | Καθορίζει το πραγματικό πλάτος του στοιχείου του διαγράμματος. |
| [getActualHeight()](#getActualHeight--) | Καθορίζει το πραγματικό ύψος του στοιχείου του διαγράμματος. |
### getXValue() {#getXValue--}
```
public final IStringOrDoubleChartValue getXValue()
```

XValue. Μόνο για ανάγνωση [IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue).

**Επιστρέφει:**
[IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue)
### getYValue() {#getYValue--}
```
public final IDoubleChartValue getYValue()
```

YValue. Μόνο για ανάγνωση [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Επιστρέφει:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getBubbleSize() {#getBubbleSize--}
```
public final IDoubleChartValue getBubbleSize()
```

BubbleSize. Μόνο για ανάγνωση [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Επιστρέφει:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getValue() {#getValue--}
```
public final IDoubleChartValue getValue()
```

Value. Μόνο για ανάγνωση [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Επιστρέφει:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getSizeValue() {#getSizeValue--}
```
public final IDoubleChartValue getSizeValue()
```

Επιστρέφει την τιμή μεγέθους του σημείου δεδομένων του διαγράμματος. Χρησιμοποιείται με διαγράμματα Treemap και Sunburst. Μόνο για ανάγνωση [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Επισ Returns:**  
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getColorValue() {#getColorValue--}
```
public final IDoubleChartValue getColorValue()
```

Επιστρέφει την τιμή χρώματος του σημείου δεδομένων του διαγράμματος. Χρησιμοποιείται με διαγράμματα Χάρτη. Μόνο για ανάγνωση [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Επισ Returns:**  
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getErrorBarsCustomValues() {#getErrorBarsCustomValues--}
```
public final IErrorBarsCustomValues getErrorBarsCustomValues()
```

Αντιπροσωπεύει τις τιμές των ραβδών σφάλματος σειράς σε περίπτωση προσαρμοσμένου τύπου τιμής. Μόνο για ανάγνωση [IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues).

**Επισ Returns:**  
[IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues)
### getLabel() {#getLabel--}
```
public final IDataLabel getLabel()
```

Label. Μόνο για ανάγνωση [IDataLabel](../../com.aspose.slides/idatalabel).

**Επισ Returns:**  
[IDataLabel](../../com.aspose.slides/idatalabel)
### isBubble3D() {#isBubble3D--}
```
public final boolean isBubble3D()
```

Καθορίζει ότι οι φούσκες διαθέτουν τρισδιάστατη επίδραση. Αναγνώσιμη/εγγράψιμη boolean.

**Επισ Returns:**  
boolean
### setBubble3D(boolean value) {#setBubble3D-boolean-}
```
public final void setBubble3D(boolean value)
```

Καθορίζει ότι οι φούσκες διαθέτουν τρισδιάστατη επίδραση. Αναγνώσιμη/εγγράψιμη boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getExplosion() {#getExplosion--}
```
public final int getExplosion()
```

Καθορίζει το ποσό που το σημείο δεδομένων θα μετακινηθεί από το κέντρο του πίτα. Αναγνώσιμη/εγγράψιμη int.

**Επισ Returns:**  
int
### setExplosion(int value) {#setExplosion-int-}
```
public final void setExplosion(int value)
```

Καθορίζει το ποσό που το σημείο δεδομένων θα μετακινηθεί από το κέντρο του πίτα. Αναγνώσιμη/εγγράψιμη int.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

Αντιπροσωπεύει τις ιδιότητες μορφοποίησης. Αναγνώσιμη/εγγράψιμη [IFormat](../../com.aspose.slides/iformat).

**Επισ Returns:**  
[IFormat](../../com.aspose.slides/iformat)
### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public final void setFormat(IFormat value)
```

Αντιπροσωπεύει τις ιδιότητες μορφοποίησης. Αναγνώσιμη/εγγράψιμη [IFormat](../../com.aspose.slides/iformat).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |

### getMarker() {#getMarker--}
```
public final IMarker getMarker()
```

Καθορίζει έναν σημειωτή δεδομένων. Μόνο για ανάγνωση [IMarker](../../com.aspose.slides/imarker).

**Επισ Returns:**  
[IMarker](../../com.aspose.slides/imarker)
### getSetAsTotal() {#getSetAsTotal--}
```
public final boolean getSetAsTotal()
```

Ορίζει το σημείο δεδομένων ως σύνολο. Εφαρμόζεται μόνο για τύπο σειράς Waterfall.

**Επισ Returns:**  
boolean
### setSetAsTotal(boolean value) {#setSetAsTotal-boolean-}
```
public final void setSetAsTotal(boolean value)
```

Ορίζει το σημείο δεδομένων ως σύνολο. Εφαρμόζεται μόνο για τύπο σειράς Waterfall.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public final ILegendEntryProperties getRelatedLegendEntry()
```

Ιδιότητες της αντίστοιχης καταχώρησης υπομνήματος στην περίπτωση τύπου διαγράμματος από αυτή τη λίστα: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. Μόνο για ανάγνωση [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**Επισ Returns:**  
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

Επιστρέφει το δοχείο των επιπέδων του σημείου δεδομένων. Εφαρμόζεται για σειρές Treeamp και Sunburst. Η αρίθμηση επιπέδων σημείου δεδομένων αρχίζει από το μηδέν.

**Επισ Returns:**  
[IChartDataPointLevelsManager](../../com.aspose.slides/ichartdatapointlevelsmanager)
### getIndex() {#getIndex--}
```
public final long getIndex()
```

**Επισ Returns:**  
long
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Επισ Returns:  
Parent_Immediate object. Μόνο για ανάγνωση IDOMObject.

**Επισ Returns:**  
com.aspose.slides.IDOMObject
### getAutomaticDataPointColor() {#getAutomaticDataPointColor--}
```
public final Color getAutomaticDataPointColor()
```

Επισ Returns:  
ένα αυτόματο χρώμα του σημείου δεδομένων βάσει του δείκτη σειράς, δείκτη σημείου δεδομένων, ιδιότητας ParentSeriesGroup.IsColorVaried και του στυλ διαγράμματος. Αυτό το χρώμα χρησιμοποιείται εξ' όρισμα εάν το FillType είναι ίσο με NotDefined.

**Επισ Returns:**  
java.awt.Color
### getInvertIfNegative() {#getInvertIfNegative--}
```
public final boolean getInvertIfNegative()
```

Καθορίζει ότι το σημείο δεδομένων θα αντιστρέψει τα χρώματά του εάν η τιμή είναι αρνητική. Αναγνώσιμη/εγγράψιμη boolean.

**Επισ Returns:**  
boolean
### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public final void setInvertIfNegative(boolean value)
```

Καθορίζει ότι το σημείο δεδομένων θα αντιστρέψει τα χρώματά του εάν η τιμή είναι αρνητική. Αναγνώσιμη/εγγράψιμη boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getActualX() {#getActualX--}
```
public final float getActualX()
```

Καθορίζει την πραγματική θέση x (αριστερά) του στοιχείου του διαγράμματος σε σχέση με την αριστερή άνω γωνία του διαγράμματος. Καλέστε τη μέθοδο IChart.ValidateChartLayout() πριν λάβετε τις πραγματικές τιμές. Αναγνώσιμη float.

**Επισ Returns:**  
float
### getActualY() {#getActualY--}
```
public final float getActualY()
```

Καθορίζει την πραγματική κορυφή του στοιχείου του διαγράμματος σε σχέση με την αριστερή άνω γωνία του διαγράμματος. Καλέστε τη μέθοδο IChart.ValidateChartLayout() πριν λάβετε τις πραγματικές τιμές. Αναγνώσιμη float.

**Επισ Returns:**  
float
### getActualWidth() {#getActualWidth--}
```
public final float getActualWidth()
```

Καθορίζει το πραγματικό πλάτος του στοιχείου του διαγράμματος. Καλέστε τη μέθοδο IChart.ValidateChartLayout() πριν λάβετε τις πραγματικές τιμές. Αναγνώσιμη float.

**Επισ Returns:**  
float
### getActualHeight() {#getActualHeight--}
```
public final float getActualHeight()
```

Καθορίζει το πραγματικό ύψος του στοιχείου του διαγράμματος. Καλέστε τη μέθοδο IChart.ValidateChartLayout() πριν λάβετε τις πραγματικές τιμές. Αναγνώσιμη float.

**Επισ Returns:**  
float