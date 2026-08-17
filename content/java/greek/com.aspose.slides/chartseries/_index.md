---
title: ChartSeries
second_title: Αναφορά API Aspose.Slides για Java
description: Αντιπροσωπεύει μια σειρά γραφήματος.
type: docs
url: /el/com.aspose.slides/chartseries/
---
**Κληρονομικότητα:**
java.lang.Object

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IChartSeries](../../com.aspose.slides/ichartseries), com.aspose.slides.IDOMObject
```
public class ChartSeries implements IChartSeries, IDOMObject
```

Αναπαριστά μια σειρά γραφήματος.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getChart()](#getChart--) | Επιστρέφει το γονικό γράφημα. |
| [getExplosion()](#getExplosion--) | Η απόσταση ενός ανοικτού κομματιού πίτας από το κέντρο του διαγράμματος πίτας εκφράζεται ως ποσοστό της διαμέτρου της πίτας. |
| [setExplosion(int value)](#setExplosion-int-) | Η απόσταση ενός ανοικτού κομματιού πίτας από το κέντρο του διαγράμματος πίτας εκφράζεται ως ποσοστό της διαμέτρου της πίτας. |
| [getSmooth()](#getSmooth--) | Αναπαριστά εξομάλυνση καμπύλης. |
| [setSmooth(boolean value)](#setSmooth-boolean-) | Αναπαριστά εξομάλυνση καμπύλης. |
| [getName()](#getName--) | Επιστρέφει το όνομα της σειράς. |
| [getDataPoints()](#getDataPoints--) | Επιστρέφει τη συλλογή των σημείων δεδομένων αυτής της σειράς. |
| [getType()](#getType--) | Επιστρέφει έναν τύπο αυτής της σειράς. |
| [setType(int value)](#setType-int-) | Επιστρέφει έναν τύπο αυτής της σειράς. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | Δείχνει αν αυτή η σειρά εμφανίζεται στον δευτερεύοντα άξονα. |
| [setPlotOnSecondAxis(boolean value)](#setPlotOnSecondAxis-boolean-) | Δείχνει αν αυτή η σειρά εμφανίζεται στον δευτερεύοντα άξονα. |
| [getParentSeriesGroup()](#getParentSeriesGroup--) | ParentSeriesGroup. |
| [getFormat()](#getFormat--) | Επιστρέφει τη μορφή μιας σειράς. |
| [getOrder()](#getOrder--) | Επιστρέφει τη σειρά μιας σειράς. |
| [setOrder(int value)](#setOrder-int-) | Επιστρέφει τη σειρά μιας σειράς. |
| [getLabels()](#getLabels--) | Επιστρέφει τις Ετικέτες μιας σειράς. |
| [getTrendLines()](#getTrendLines--) | Συλλογή γραμμών τάσης σειράς. |
| [getErrorBarsXFormat()](#getErrorBarsXFormat--) | Αναπαριστά τις ErrorBars της σειράς με κατεύθυνση X. |
| [getErrorBarsYFormat()](#getErrorBarsYFormat--) | Αναπαριστά τις ErrorBars της σειράς με κατεύθυνση Y. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Αναπαριστά την καταχώρηση υπομνήματος σχετική με αυτή τη σειρά Μόνο ανάγνωση [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties). |
| [getNumberFormatOfValues()](#getNumberFormatOfValues--) | NumberFormatOfValues. |
| [setNumberFormatOfValues(String value)](#setNumberFormatOfValues-java.lang.String-) | NumberFormatOfValues. |
| [getNumberFormatOfXValues()](#getNumberFormatOfXValues--) | NumberFormatOfXValues. |
| [setNumberFormatOfXValues(String value)](#setNumberFormatOfXValues-java.lang.String-) | NumberFormatOfXValues. |
| [getNumberFormatOfYValues()](#getNumberFormatOfYValues--) | NumberFormatOfYValues. |
| [setNumberFormatOfYValues(String value)](#setNumberFormatOfYValues-java.lang.String-) | NumberFormatOfYValues. |
| [getNumberFormatOfBubbleSizes()](#getNumberFormatOfBubbleSizes--) | NumberFormatOfBubbleSizes. |
| [setNumberFormatOfBubbleSizes(String value)](#setNumberFormatOfBubbleSizes-java.lang.String-) | NumberFormatOfBubbleSizes. |
| [getMarker()](#getMarker--) | Marker. |
| [getBar3DShape()](#getBar3DShape--) | Καθορίζει το σχήμα μιας σειράς ενός 3-Δ ραβδίου γραφήματος. |
| [setBar3DShape(int value)](#setBar3DShape-int-) | Καθορίζει το σχήμα μιας σειράς ενός 3-Δ ραβδίου γραφήματος. |
| [getInvertIfNegative()](#getInvertIfNegative--) | Η σειρά μπάρας, στήλης ή φυσαλίδας αντιστρέφει τα χρώματά της εάν η τιμή είναι αρνητική. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | Η σειρά μπάρας, στήλης ή φυσαλίδας αντιστρέφει τα χρώματά της εάν η τιμή είναι αρνητική. |
| [getInvertedSolidFillColor()](#getInvertedSolidFillColor--) | Καθορίζει την αντιστροφή γεμάτου χρώματος για τη σειρά. |
| [getAutomaticSeriesColor()](#getAutomaticSeriesColor--) | Επιστρέφει ένα αυτόματο χρώμα σειράς βάσει του δείκτη της σειράς και του στυλ γραφήματος. |
| [getShowInnerPoints()](#getShowInnerPoints--) | Αναπαριστά εσωτερικά σημεία. |
| [setShowInnerPoints(boolean value)](#setShowInnerPoints-boolean-) | Αναπαριστά εσωτερικά σημεία. |
| [getShowOutlierPoints()](#getShowOutlierPoints--) | Αναπαριστά απομακρυσμένα σημεία. |
| [setShowOutlierPoints(boolean value)](#setShowOutlierPoints-boolean-) | Αναπαριστά απομακρυσμένα σημεία. |
| [getShowMeanMarkers()](#getShowMeanMarkers--) | Αναπαριστά δείκτες μέσου όρου. |
| [setShowMeanMarkers(boolean value)](#setShowMeanMarkers-boolean-) | Αναπαριστά δείκτες μέσου όρου. |
| [getShowMeanLine()](#getShowMeanLine--) | Αναπαριστά τη γραμμή μέσου όρου. |
| [setShowMeanLine(boolean value)](#setShowMeanLine-boolean-) | Αναπαριστά τη γραμμή μέσου όρου. |
| [getQuartileMethod()](#getQuartileMethod--) | Αναπαριστά τη μέθοδο τεταρτημορίου. |
| [setQuartileMethod(int value)](#setQuartileMethod-int-) | Αναπαριστά τη μέθοδο τεταρτημορίου. |
| [getShowConnectorLines()](#getShowConnectorLines--) | Αναπαριστά συνδετικές γραμμές. |
| [setShowConnectorLines(boolean value)](#setShowConnectorLines-boolean-) | Αναπαριστά συνδετικές γραμμές. |
| [getParentLabelLayout()](#getParentLabelLayout--) | Αναπαριστά τη διάταξη των ετικετών γονικής κατηγορίας. |
| [setParentLabelLayout(int value)](#setParentLabelLayout-int-) | Αναπαριστά τη διάταξη των ετικετών γονικής κατηγορίας. |
| [hasUpDownBars()](#hasUpDownBars--) | Καθορίζει εάν το διάγραμμα Γραμμής ή Stock έχει μπάρες ανοδικής/καθοδικής. |
| [getGapWidth()](#getGapWidth--) | Καθορίζει το κενό μεταξύ ομάδων μπαρών ή στηλών, ως ποσοστό του πλάτους της μπάρας ή της στήλης. |
| [getGapDepth()](#getGapDepth--) | Επιστρέφει ή ορίζει την απόσταση, ως ποσοστό του πλάτους δείκτη, μεταξύ των σειρών δεδομένων σε 3D διάγραμμα. |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | Καθορίζει τη γωνία του πρώτου κομματιού πίτας ή δακτυλίου διαγράμματος, σε μοίρες (δεξιόστροφα από την κορυφή, από 0 έως 360 μοίρες). |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | Καθορίζει το μέγεθος της τρύπας σε διάγραμμα δακτυλίου (μπορεί να είναι μεταξύ 10 και 90 τοις εκατό του μεγέθους της περιοχής σχεδίασης). |
| [getOverlap()](#getOverlap--) | Καθορίζει το πόσο οι μπάρες και οι στήλες επικαλύπτονται σε 2-Δ διαγράμματα, ως ποσοστό (από -100% έως 100%). |
| [getSecondPieSize()](#getSecondPieSize--) | Καθορίζει το μέγεθος του δεύτερου κομματιού πίτας ή μπάρας σε διάγραμμα πίτα-μέσα-πίτα ή μπάρα-μέσα-πίτα, ως ποσοστό του μεγέθους της πρώτης πίτας (μπορεί να είναι μεταξύ 5 και 200 τοις εκατό). |
| [hasSeriesLines()](#hasSeriesLines--) | Καθορίζει εάν υπάρχουν γραμμές σειράς για αυτή τη σειρά και τις συναφείς σειρές. |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | Καθορίζει πώς τα μεγέθη των φυσαλίδων αντιπροσωπεύονται στο διάγραμμα φυσαλίδων. |
| [getPieSplitPosition()](#getPieSplitPosition--) | Καθορίζει μια τιμή που θα χρησιμοποιηθεί για τον προσδιορισμό των σημείων δεδομένων που βρίσκονται στη δεύτερη πίτα ή μπάρα σε διάγραμμα πίτα-μέσα-πίτα ή μπάρα-μέσα-πίτα. |
| [getPieSplitBy()](#getPieSplitBy--) | Καθορίζει πώς να προσδιοριστεί ποια σημεία δεδομένων βρίσκονται στη δεύτερη πίτα ή μπάρα σε διάγραμμα πίτα-μέσα-πίτα ή μπάρα-μέσα-πίτα. |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | Οι προσαρμοσμένες πληροφορίες διαχωρισμού για διάγραμμα πίτα-μέσα-πίτα ή μπάρα-μέσα-πίτα με προσαρμοσμένο διαχωρισμό. |
| [isColorVaried()](#isColorVaried--) | Καθορίζει ότι κάθε δείκτη δεδομένων στη σειρά έχει διαφορετικό χρώμα. |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | Καθορίζει τον συντελεστή κλίμακας για το διάγραμμα φυσαλίδων (μπορεί να είναι μεταξύ 0 και 300 τοις εκατό του προεπιλεγμένου μεγέθους). |
| [getSlide()](#getSlide--) | Επιστρέφει τη γονική διαφάνεια (slide) ενός FillFormat. |
| [getPresentation()](#getPresentation--) | Επιστρέφει τη γονική παρουσίαση ενός FillFormat. |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Επιστρέφει το αντικείμενο Parent_Immediate. Μόνο ανάγνωση IDOMObject.

**Επιστρέφει:**
com.aspose.slides.IDOMObject

### getChart() {#getChart--}
```
public final IChart getChart()
```

Επιστρέφει το γονικό γράφημα. Μόνο ανάγνωση [IChart](../../com.aspose.slides/ichart).

**Επιστρέφει:**
[IChart](../../com.aspose.slides/ichart)

### getExplosion() {#getExplosion--}
```
public final int getExplosion()
```

Η απόσταση ενός ανοικτού κομματιού πίτας από το κέντρο του διαγράμματος πίτας εκφράζεται ως ποσοστό της διαμέτρου της πίτας. Ανάγνωση/εγγραφή int.

**Επιστρέφει:**
int

### setExplosion(int value) {#setExplosion-int-}
```
public final void setExplosion(int value)
```

Η απόσταση ενός ανοικτού κομματιού πίτας από το κέντρο του διαγράμματος πίτας εκφράζεται ως ποσοστό της διαμέτρου της πίτας. Ανάγνωση/εγγραφή int.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getSmooth() {#getSmooth--}
```
public final boolean getSmooth()
```

Αναπαριστά εξομάλυνση καμπύλης. True αν η εξομάλυνση καμπύλης είναι ενεργοποιημένη για το διάγραμμα γραμμής ή scatter. Εφαρμόζεται μόνο σε διαγράμματα γραμμής και scatter συνδεδεμένα με γραμμές. Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**
boolean

### setSmooth(boolean value) {#setSmooth-boolean-}
```
public final void setSmooth(boolean value)
```

Αντιπροσωπεί εξομάλυνση καμπύλης. True αν η εξομάλυνση καμπύλης είναι ενεργοποιημένη για το διάγραμμα γραμμής ή scatter. Εφαρμόζεται μόνο σε διαγράμματα γραμμής και scatter συνδεδεμένα με γραμμές. Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getName() {#getName--}
```
public final IStringChartValue getName()
```

Επιστρέφει το όνομα της σειράς. Μόνο ανάγνωση [IStringChartValue](../../com.aspose.slides/istringchartvalue).

**Επιστρέφει:**
[IStringChartValue](../../com.aspose.slides/istringchartvalue)

### getDataPoints() {#getDataPoints--}
```
public final IChartDataPointCollection getDataPoints()
```

Επιστρέφει τη συλλογή των σημείων δεδομένων αυτής της σειράς. Μόνο ανάγνωση [IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection).

**Επιστρέφει:**
[IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection)

### getType() {#getType--}
```
public final int getType()
```

Επιστρέφει έναν τύπο αυτής της σειράς. Ανάγνωση/εγγραφή [ChartType](../../com.aspose.slides/charttype).

**Επιστρέφει:**
int

### setType(int value) {#setType-int-}
```
public final void setType(int value)
```

Επιστρέφει έναν τύπο αυτής της σειράς. Ανάγνωση/εγγραφή [ChartType](../../com.aspose.slides/charttype).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public final boolean getPlotOnSecondAxis()
```

Δείχνει αν αυτή η σειρά εμφανίζεται στον δευτερεύοντα άξονα. Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**
boolean

### setPlotOnSecondAxis(boolean value) {#setPlotOnSecondAxis-boolean-}
```
public final void setPlotOnSecondAxis(boolean value)
```

Δείχνει αν αυτή η σειρά εμφανίζεται στον δευτερεύοντα άξονα. Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getParentSeriesGroup() {#getParentSeriesGroup--}
```
public final IChartSeriesGroup getParentSeriesGroup()
```

ParentSeriesGroup. Μόνο ανάγνωση [IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup).

**Επιστρέφει:**
[IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup)

### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

Επιστρέφει τη μορφή μιας σειράς. Μόνο ανάγνωση [IFormat](../../com.aspose.slides/iformat).

**Επιστρέφει:**
[IFormat](../../com.aspose.slides/iformat)

### getOrder() {#getOrder--}
```
public final int getOrder()
```

Επιστρέφει τη σειρά μιας σειράς. Ανάγνωση/εγγραφή int.

**Επιστρέφει:**
int

### setOrder(int value) {#setOrder-int-}
```
public final void setOrder(int value)
```

Επιστρέφει τη σειρά μιας σειράς. Ανάγνωση/εγγραφή int.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getLabels() {#getLabels--}
```
public final IDataLabelCollection getLabels()
```

Επιστρέφει τις Ετικέτες μιας σειράς. Μόνο ανάγνωση [IDataLabelCollection](../../com.aspose.slides/idatalabelcollection).

**Επιστρέφει:**
[IDataLabelCollection](../../com.aspose.slides/idatalabelcollection)

### getTrendLines() {#getTrendLines--}
```
public final ITrendlineCollection getTrendLines()
```

Συλλογή γραμμών τάσης σειράς. Μόνο ανάγνωση [ITrendlineCollection](../../com.aspose.slides/itrendlinecollection).

--------------------

Οι TrendLines είναι διαθέσιμες (δεν είναι null) για σειρές δεδομένων σε μη στοιβαγμένα 2-Δ area, bar, column, line, stock, xy (scatter) και bubble διαγράμματα. Μια γραμμή τάσης δεν είναι διαθέσιμη για σειρές δεδομένων σε οποιοδήποτε τύπο διαγράμματος που είναι στοιβαγμένος ή 3-Δ. Οι TrendLines δεν είναι επίσης διαθέσιμες για radar, pie, surface ή doughnut διαγράμματα.

**Επιστρέφει:**
[ITrendlineCollection](../../com.aspose.slides/itrendlinecollection)

### getErrorBarsXFormat() {#getErrorBarsXFormat--}
```
public final IErrorBarsFormat getErrorBarsXFormat()
```

Αναπαριστά τις ErrorBars της σειράς με κατεύθυνση X. Μόνο ανάγνωση [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat).

--------------------

Οι ErrorBars με κατεύθυνση X είναι διαθέσιμες για σειρές τύπου area, bar, scatter και bubble. Για όλους τους άλλους τύπους διαγράμματος αυτή η ιδιότητα επιστρέφει null (συμπεριλαμβανομένων των 3D διαγραμμάτων). Σε περίπτωση προσαρμοσμένων τιμών χρησιμοποιήστε τη συλλογή DataPoints για να καθορίσετε την τιμή (με την ιδιότητα ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues))).

**Επιστρέφει:**
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)

### getErrorBarsYFormat() {#getErrorBarsYFormat--}
```
public final IErrorBarsFormat getErrorBarsYFormat()
```

Αναπαριστά τις ErrorBars της σειράς με κατεύθυνση Y. Μόνο ανάγνωση [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat).

--------------------

Οι ErrorBars με κατεύθυνση Y είναι διαθέσιμες για σειρές τύπου area, bar, line, scatter και bubble. Για όλους τους άλλους τύπους διαγράμματος αυτή η ιδιότητα επιστρέφει null (συμπεριλαμβανομένων των 3D διαγραμμάτων). Σε περίπτωση προσαρμοσμένων τιμών χρησιμοποιήστε τη συλλογή DataPoints για να καθορίσετε την τιμή (με την ιδιότητα ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues))).

**Επιστρέφει:**
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)

### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public final ILegendEntryProperties getRelatedLegendEntry()
```

Αναπαριστά την καταχώρηση υπομνήματος σχετική με αυτή τη σειρά Μόνο ανάγνωση [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**Επιστρέφει:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)

### getNumberFormatOfValues() {#getNumberFormatOfValues--}
```
public final String getNumberFormatOfValues()
```

NumberFormatOfValues. Ανάγνωση/εγγραφή String.

**Επιστρέφει:**
java.lang.String

### setNumberFormatOfValues(String value) {#setNumberFormatOfValues-java.lang.String-}
```
public final void setNumberFormatOfValues(String value)
```

NumberFormatOfValues. Ανάγνωση/εγγραφή String.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |

### getNumberFormatOfXValues() {#getNumberFormatOfXValues--}
```
public final String getNumberFormatOfXValues()
```

NumberFormatOfXValues. Ανάγνωση/εγγραφή String.

**Επιστρέφει:**
java.lang.String

### setNumberFormatOfXValues(String value) {#setNumberFormatOfXValues-java.lang.String-}
```
public final void setNumberFormatOfXValues(String value)
```

NumberFormatOfXValues. Ανάγνωση/εγγραφή String.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |

### getNumberFormatOfYValues() {#getNumberFormatOfYValues--}
```
public final String getNumberFormatOfYValues()
```

NumberFormatOfYValues. Ανάγνωση/εγγραφή String.

**Επιστρέφει:**
java.lang.String

### setNumberFormatOfYValues(String value) {#setNumberFormatOfYValues-java.lang.String-}
```
public final void setNumberFormatOfYValues(String value)
```

NumberFormatOfYValues. Ανάγνωση/εγγραφή String.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |

### getNumberFormatOfBubbleSizes() {#getNumberFormatOfBubbleSizes--}
```
public final String getNumberFormatOfBubbleSizes()
```

NumberFormatOfBubbleSizes. Ανάγνωση/εγγραφή String.

**Επιστρέφει:**
java.lang.String

### setNumberFormatOfBubbleSizes(String value) {#setNumberFormatOfBubbleSizes-java.lang.String-}
```
public final void setNumberFormatOfBubbleSizes(String value)
```

NumberFormatOfBubbleSizes. Ανάγνωση/εγγραφή String.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |

### getMarker() {#getMarker--}
```
public final IMarker getMarker()
```

Marker. Μόνο ανάγνωση [IMarker](../../com.aspose.slides/imarker).

**Επιστρέφει:**
[IMarker](../../com.aspose.slides/imarker)

### getBar3DShape() {#getBar3DShape--}
```
public final int getBar3DShape()
```

Καθορίζει το σχήμα μιας σειράς ενός 3-Δ ραβδίου γραφήματος. Η αλλαγή της τιμής αυτής της ιδιότητας μπορεί να προκαλέσει αυτόματη αλλαγή του τύπου της σειράς. Ανάγνωση/εγγραφή [ChartShapeType](../../com.aspose.slides/chartshapetype).

**Επιστρέφει:**
int

### setBar3DShape(int value) {#setBar3DShape-int-}
```
public final void setBar3DShape(int value)
```

Καθορίζει το σχήμα μιας σειράς ενός 3-Δ ραβδίου γραφήματος. Η αλλαγή της τιμής αυτής της ιδιότητας μπορεί να προκαλέσει αυτόματη αλλαγή του τύπου της σειράς. Ανάγνωση/εγγραφή [ChartShapeType](../../com.aspose.slides/chartshapetype).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getInvertIfNegative() {#getInvertIfNegative--}
```
public final boolean getInvertIfNegative()
```

Καθορίζει ότι η σειρά μπάρας, στήλης ή φυσαλίδας αντιστρέφει τα χρώματά της εάν η τιμή είναι αρνητική. Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**
boolean

### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public final void setInvertIfNegative(boolean value)
```

Καθορίζει ότι η σειρά μπάρας, στήλης ή φυσαλίδας αντιστρέφει τα χρώματά της εάν η τιμή είναι αρνητική. Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getInvertedSolidFillColor() {#getInvertedSolidFillColor--}
```
public final IColorFormat getInvertedSolidFillColor()
```
Καθορίζει ανάστροφο γεμάτο χρώμα για τη σειρά. Για να εφαρμόσετε τη ρύθμιση χρώματος, ορίστε το FillType της μορφής σειράς σε FillType.Solid. Ανάγνωση/εγγραφή [ColorFormat](../../com.aspose.slides/colorformat).

**Επιστρέφει:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getAutomaticSeriesColor() {#getAutomaticSeriesColor--}
```
public final Color getAutomaticSeriesColor()
```

Επιστρέφει ένα αυτόματο χρώμα σειράς με βάση το δείκτη της σειράς και το στυλ γραφήματος. Αυτό το χρώμα χρησιμοποιείται από προεπιλογή εάν το FillType ισούται με NotDefined.

**Επιστρέφει:**
java.awt.Color - Το αντικείμενο java.awt.Color.

### getShowInnerPoints() {#getShowInnerPoints--}
```
public final boolean getShowInnerPoints()
```

Αναπαριστά τα εσωτερικά σημεία. Αληθές εάν τα εσωτερικά σημεία εμφανίζονται στο γράφημα BoxAndWhisker. Εφαρμόζεται μόνο σε γράφημα BoxAndWhisker. Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**
boolean

### setShowInnerPoints(boolean value) {#setShowInnerPoints-boolean-}
```
public final void setShowInnerPoints(boolean value)
```

Αναπαριστά τα εσωτερικά σημεία. Αληθές εάν τα εσωτερικά σημεία εμφανίζονται στο γράφημα BoxAndWhisker. Εφαρμόζεται μόνο σε γράφημα BoxAndWhisker. Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getShowOutlierPoints() {#getShowOutlierPoints--}
```
public final boolean getShowOutlierPoints()
```

Αναπαριστά τα εξαιρετικά σημεία. Αληθές εάν τα εξαιρετικά σημεία εμφανίζονται στο γράφημα BoxAndWhisker. Εφαρμόζεται μόνο σε γράφημα BoxAndWhisker. Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**
boolean

### setShowOutlierPoints(boolean value) {#setShowOutlierPoints-boolean-}
```
public final void setShowOutlierPoints(boolean value)
```

Αναπαριστά τα εξαιρετικά σημεία. Αληθές εάν τα εξαιρετικά σημεία εμφανίζονται στο γράφημα BoxAndWhisker. Εφαρμόζεται μόνο σε γράφημα BoxAndWhisker. Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getShowMeanMarkers() {#getShowMeanMarkers--}
```
public final boolean getShowMeanMarkers()
```

Αναπαριστά τους δείκτες μέσου όρου. Αληθές εάν οι δείκτες μέσου όρου εμφανίζονται στο γράφημα BoxAndWhisker. Εφαρμόζεται μόνο σε γράφημα BoxAndWhisker. Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**
boolean

### setShowMeanMarkers(boolean value) {#setShowMeanMarkers-boolean-}
```
public final void setShowMeanMarkers(boolean value)
```

Αναπαριστά τους δείκτες μέσου όρου. Αληθές εάν οι δείκτες μέσου όρου εμφανίζονται στο γράφημα BoxAndWhisker. Εφαρμόζεται μόνο σε γράφημα BoxAndWhisker. Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getShowMeanLine() {#getShowMeanLine--}
```
public final boolean getShowMeanLine()
```

Αναπαριστά τη γραμμή μέσου όρου. Αληθές εάν η γραμμή μέσου όρου εμφανίζεται στο γράφημα BoxAndWhisker. Εφαρμόζεται μόνο σε γράφημα BoxAndWhisker. Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**
boolean

### setShowMeanLine(boolean value) {#setShowMeanLine-boolean-}
```
public final void setShowMeanLine(boolean value)
```

Αναπαριστά τη γραμμή μέσου όρου. Αληθές εάν η γραμμή μέσου όρου εμφανίζεται στο γράφημα BoxAndWhisker. Εφαρμόζεται μόνο σε γράφημα BoxAndWhisker. Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getQuartileMethod() {#getQuartileMethod--}
```
public final int getQuartileMethod()
```

Αναπαριστά τη μέθοδο τεταρτημορίου. Εφαρμόζεται μόνο σε γράφημα BoxAndWhisker.

**Επιστρέφει:**
int

### setQuartileMethod(int value) {#setQuartileMethod-int-}
```
public final void setQuartileMethod(int value)
```

Αναπαριστά τη μέθοδο τεταρτημορίου. Εφαρμόζεται μόνο σε γράφημα BoxAndWhisker.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getShowConnectorLines() {#getShowConnectorLines--}
```
public final boolean getShowConnectorLines()
```

Αναπαριστά τις γραμμές σύνδεσης. Εφαρμόζεται μόνο σε γράφημα Waterfall.

**Επιστρέφει:**
boolean

### setShowConnectorLines(boolean value) {#setShowConnectorLines-boolean-}
```
public final void setShowConnectorLines(boolean value)
```

Αναπαριστά τις γραμμές σύνδεσης. Εφαρμόζεται μόνο σε γράφημα Waterfall.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getParentLabelLayout() {#getParentLabelLayout--}
```
public final int getParentLabelLayout()
```

Αναπαριστά τη διάταξη των ετικετών γονικής κατηγορίας. Εφαρμόζεται μόνο σε γράφημα Treemap.

**Επιστρέφει:**
int

### setParentLabelLayout(int value) {#setParentLabelLayout-int-}
```
public final void setParentLabelLayout(int value)
```

Αναπαριστά τη διάταξη των ετικετών γονικής κατηγορίας. Εφαρμόζεται μόνο σε γράφημα Treemap.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### hasUpDownBars() {#hasUpDownBars--}
```
public final boolean hasUpDownBars()
```

Καθορίζει εάν το γράφημα Line ή Stock έχει μπάρες ανοδικής/καθοδικής κίνησης. Αυτή είναι η ιδιότητα όχι μόνο αυτής της σειράς αλλά και όλων των σειρών της γονικής ομάδας σειρών – είναι προβολή της αντίστοιχης ιδιότητας ομάδας. Συνεπώς αυτή η ιδιότητα είναι μόνο-ανάγνωση. Χρησιμοποιήστε την ιδιότητα ParentSeriesGroup για πρόσβαση στη γονική ομάδα σειρών. Χρησιμοποιήστε την ιδιότητα ParentSeriesGroup.UpDownBars.HasUpDownBars για ανάγνωση/εγγραφή αλλαγής τιμής. Χρησιμοποιήτε την ιδιότητα ParentSeriesGroup.UpDownBars για μορφοποίηση των μπάρων ανοδικής/καθοδικής κίνησης. Μόνο-ανάγνωση boolean.

--------------------

Αυτή είναι η προβολή της ιδιότητας ParentSeriesGroup.UpDownBars.HasUpDownBars.

**Επιστρέφει:**
boolean

### getGapWidth() {#getGapWidth--}
```
public final int getGapWidth()
```

Καθορίζει το διάστημα μεταξύ ομάδων ράβδων ή στηλών, ως ποσοστό του πλάτους της ράβδου ή της στήλης. Αυτή είναι η ιδιότητα όχι μόνο αυτής της σειράς αλλά και όλων των σειρών της γονικής ομάδας σειρών – είναι προβολή της αντίστοιχης ιδιότητας ομάδας. Συνεπώς αυτή η ιδιότητα είναι μόνο-ανάγνωση. Χρησιμοποιήστε την ιδιότητα ParentSeriesGroup για πρόσβαση στη γονική ομάδα σειρών. Χρησιμοποιήστε την ιδιότητα ParentSeriesGroup.GapWidth για ανάγνωση/εγγραφή αλλαγής τιμής. Μόνο-ανάγνωση int.

--------------------

Αυτή είναι η προβολή της ιδιότητας ParentSeriesGroup.GapWidth.

**Επιστρέφει:**
int

### getGapDepth() {#getGapDepth--}
```
public final int getGapDepth()
```

Επιστρέφει ή ορίζει την απόσταση, ως ποσοστό του πλάτους του δείκτη, μεταξύ των σειρών δεδομένων σε 3D γράφημα. Αυτή είναι η ιδιότητα όχι μόνο αυτής της σειράς αλλά και όλων των σειρών της γονικής ομάδας σειρών – είναι προβολή της αντίστοιχης ιδιότητας ομάδας. Συνεπώς αυτή η ιδιότητα είναι μόνο-ανάγνωση. Χρησιμοποιήστε την ιδιότητα ParentSeriesGroup για πρόσβαση στη γονική ομάδα σειρών. Χρησιμοποιήστε την ιδιότητα ParentSeriesGroup.GapDepth για ανάγνωση/εγγραφή αλλαγής τιμής. Μόνο-ανάγνωση int.

--------------------

Αυτή είναι η προβολή της ιδιότητας ParentSeriesGroup.GapDepth.

**Επιστρέφει:**
int

### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public final int getFirstSliceAngle()
```

Καθορίζει τη γωνία του πρώτου τμήματος πίτας ή δακτυλίου, σε μοίρες (συμφυγώς από πάνω, από 0 έως 360 μοίρες). Αυτή είναι η ιδιότητα όχι μόνο αυτής της σειράς αλλά και όλων των σειρών της γονικής ομάδας σειρών – είναι προβολή της αντίστοιχης ιδιότητας ομάδας. Συνεπώς αυτή η ιδιότητα είναι μόνο-ανάγνωση. Χρησιμοποιήστε την ιδιότητα ParentSeriesGroup για πρόσβαση στη γονική ομάδα σειρών. Χρησιμοποιήστε την ιδιότητα ParentSeriesGroup.FirstSliceAngle για ανάγνωση/εγγραφή αλλαγής τιμής. Μόνο-ανάγνωση int.

--------------------

Αυτή είναι η προβολή της ιδιότητας ParentSeriesGroup.FirstSliceAngle.

**Επιστρέφει:**
int

### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public final byte getDoughnutHoleSize()
```

Καθορίζει το μέγεθος του κεντρικού τρύπας σε γράφημα δακτυλίου (μπορεί να είναι μεταξύ 10 και 90 τοις εκατό του μεγέθους της περιοχής σχεδίασης). Αυτή είναι η ιδιότητα όχι μόνο αυτής της σειράς αλλά και όλων των σειρών της γονικής ομάδας σειρών – είναι προβολή της αντίστοιχης ιδιότητας ομάδας. Συνεπώς αυτή η ιδιότητα είναι μόνο-ανάγνωση. Χρησιμοποιήστε την ιδιότητα ParentSeriesGroup για πρόσβαση στη γονική ομάδα σειρών. Χρησιμοποιήστε την ιδιότητα ParentSeriesGroup.DoughnutHoleSize για ανάγνωση/εγγραφή αλλαγής τιμής. Μόνο-ανάγνωση byte.

--------------------

Αυτή είναι η προβολή της ιδιότητας ParentSeriesGroup.DoughnutHoleSize.

**Επιστρέφει:**
byte

### getOverlap() {#getOverlap--}
```
public final byte getOverlap()
```

Καθορίζει το πόσο οι ράβδοι και οι στήλες επικαλύπτονται στα 2-Δ γράφηματα, ως ποσοστό (από -100% έως 100%). Αυτή είναι η ιδιότητα όχι μόνο αυτής της σειράς αλλά και όλων των σειρών της γονικής ομάδας σειρών. Είναι προβολή της αντίστοιχης ιδιότητας στην γονική ομάδα σειρών, επομένως αυτή η ιδιότητα είναι μόνο-ανάγνωση. Για αλλαγή της τιμής, χρησιμοποιήστε την ιδιότητα ParentSeriesGroup.Overlap για ανάγνωση/εγγραφή. Μόνο-ανάγνωση byte.

--------------------

Η επικαλυψη καθορίζει το βαθμό επικάλυψης ή απόκλισης μεταξύ ράβδων και στηλών ως ποσοστό του πλάτους τους:
- -100%: Μέγιστη απόσταση (οι ράβδοι είναι εντελώς διαχωρισμένες).
- 0%: Οι ράβδοι τοποθετούνται πλάι-πλάι χωρίς επικάλυψη ή απόσταση.
- 100%: Μέγιστη επικάλυψη (οι ράβδοι επικαλύπτονται πλήρως).
Αυτή είναι η προβολή της ιδιότητας ParentSeriesGroup.Overlap.

**Επιστρέφει:**
byte

### getSecondPieSize() {#getSecondPieSize--}
```
public final int getSecondPieSize()
```

Καθορίζει το μέγεθος της δεύτερης πίτας ή ράβδου σε γράφημα πίτας-πίτας ή ράβδου-πίτας, ως ποσοστό του μεγέθους της πρώτης πίτας (μπορεί να είναι μεταξύ 5 και 200 τοις εκατό). Αυτή είναι η ιδιότητα όχι μόνο αυτής της σειράς αλλά και όλων των σειρών της γονικής ομάδας σειρών – είναι προβολή της αντίστοιχης ιδιότητας ομάδας. Συνεπώς αυτή η ιδιότητα είναι μόνο-ανάγνωση. Χρησιμοποιήστε την ιδιότητα ParentSeriesGroup για πρόσβαση στη γονική ομάδα σειρών. Χρησιμοποιήστε την ιδιότητα ParentSeriesGroup.SecondPieSize για ανάγνωση/εγγραφή αλλαγής τιμής. Μόνο-ανάγνωση int.

--------------------

Αυτή είναι η προβολή της ιδιότητας ParentSeriesGroup.SecondPieSize.

**Επιστρέφει:**
int

### hasSeriesLines() {#hasSeriesLines--}
```
public final boolean hasSeriesLines()
```

Καθορίζει εάν υπάρχουν γραμμές σειράς για αυτή τη σειρά και τις συναφείς σειρές. Αυτή είναι η ιδιότητα όχι μόνο αυτής της σειράς αλλά και όλων των σειρών της γονικής ομάδας σειρών – είναι προβολή της αντίστοιχης ιδιότητας ομάδας. Συνεπώς αυτή η ιδιότητα είναι μόνο-ανάγνωση. Χρησιμοποιήστε την ιδιότητα ParentSeriesGroup για πρόσβαση στη γονική ομάδα σειρών. Χρησιμοποιήστε την ιδιότητα ParentSeriesGroup.HasSeriesLines για ανάγνωση/εγγραφή αλλαγής τιμής. Χρησιμοποιήστε την ιδιότητα ParentSeriesGroup.SeriesLinesFormat για μορφοποίηση των γραμμών σειράς. Μόνο-ανάγνωση boolean.

--------------------

Αυτή είναι η προβολή της ιδιότητας ParentSeriesGroup.HasSeriesLines.

**Επιστρέφει:**
boolean

### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public final int getBubbleSizeRepresentation()
```

Καθορίζει πώς αντιπροσωπεύονται οι τιμές μεγέθους φουσκών στο γράφημα φούσκας. Αυτή είναι η ιδιότητα όχι μόνο αυτής της σειράς αλλά και όλων των σειρών της γονικής ομάδας σειρών – είναι προβολή της αντίστοιχης ιδιότητας ομάδας. Συνεπώς αυτή η ιδιότητα είναι μόνο-ανάγνωση. Χρησιμοποιήστε την ιδιότητα ParentSeriesGroup για πρόσβαση στη γονική ομάδα σειρών. Χρησιμοποιήστε την ιδιότητα ParentSeriesGroup.BubbleSizeRepresentation για ανάγνωση/εγγραφή αλλαγής τιμής.

--------------------

Αυτή είναι η προβολή της ιδιότητας ParentSeriesGroup.BubbleSizeRepresentation.

**Επιστρέφει:**
int

### getPieSplitPosition() {#getPieSplitPosition--}
```
public final double getPieSplitPosition()
```

Καθορίζει μια τιμή που θα χρησιμοποιηθεί για τον προσδιορισμό του ποιου σημείου δεδομένων ανήκει στη δεύτερη πίτα ή ράβδο σε γράφημα πίτας-πίτας ή ράβδου-πίτας. Χρησιμοποιείται μαζί με την ιδιότητα PieSplitBy. Αυτή είναι η ιδιότητα όχι μόνο αυτής της σειράς αλλά και όλων των σειρών της γονικής ομάδας σειρών – είναι προβολή της αντίστοιχης ιδιότητας ομάδας. Συνεπώς αυτή η ιδιότητα είναι μόνο-ανάγνωση. Χρησιμοποιήστε την ιδιότητα ParentSeriesGroup για πρόσβαση στη γονική ομάδα σειρών. Χρησιμοποιήστε την ιδιότητα ParentSeriesGroup.PieSplitPosition για ανάγνωση/εγγραφή αλλαγής τιμής. Μόνο-ανάγνωση double.

--------------------

Αυτή είναι η προβολή της ιδιότητας ParentSeriesGroup.PieSplitPosition.

**Επιστρέφει:**
double

### getPieSplitBy() {#getPieSplitBy--}
```
public final int getPieSplitBy()
```

Καθορίζει πώς θα προσδιοριστεί ποιοι δείκτες δεδομένων ανήκουν στη δεύτερη πίτα ή ράβδο σε γράφημα πίτας-πίτας ή ράβδου-πίτας. Αυτή είναι η ιδιότητα όχι μόνο αυτής της σειράς αλλά και όλων των σειρών της γονικής ομάδας σειρών – είναι προβολή της αντίστοιχης ιδιότητας ομάδας. Συνεπώς αυτή η ιδιότητα είναι μόνο-ανάγνωση. Χρησιμοποιήστε την ιδιότητα ParentSeriesGroup για πρόσβαση στη γονική ομάδα σειρών. Χρησιμοποιήστε την ιδιότητα ParentSeriesGroup.PieSplitBy για ανάγνωση/εγγραφή αλλαγής τιμής. Μόνο-ανάγνωση [PieSplitType](../../com.aspose.slides/piesplittype).

--------------------

1) Αυτή είναι η προβολή της ιδιότητας ParentSeriesGroup.PieSplitBy. 2) Εάν η τιμή ιδιότητας είναι PieSplitType.Custom, μπορείτε να ορίσετε προσαρμοσμένες πληροφορίες διαχωρισμού με την ιδιότητα ParentSeriesGroup.PieSplitCustomPoints.

**Επιστρέφει:**
int

### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public final IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

Οι προσαρμοσμένες πληροφορίες διαχωρισμού για ένα γράφημα πίτας-πίτας ή ράβδου-πίτας με προσαρμοσμένο διαχωρισμό. Περιέχει τα σημεία δεδομένων που θα σχε绘στούν στη δεύτερη πίτα ή ράβδο. Αυτή είναι η ιδιότητα όχι μόνο αυτής της σειράς αλλά και όλων των σειρών της γονικής ομάδας σειρών – είναι προβολή της αντίστοιχης ιδιότητας ομάδας Μόνο-ανάγνωση [PieSplitCustomPointCollection](../../com.aspose.slides/piesplitcustompointcollection).

--------------------

Αυτή είναι η προβολή της ιδιότητας ParentSeriesGroup.PieSplitCustomPoints.

**Επιστρέφει:**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)

### isColorVaried() {#isColorVaried--}
```
public final boolean isColorVaried()
```
Specifies that each data marker in the series has a different color. This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property. And so this property is read-only. Use ParentSeriesGroup property for access to parent series group. Use ParentSeriesGroup.IsColorVaried read/write property for change value. Μόνο για ανάγνωση boolean.

--------------------

Αυτή είναι η προβολή της ιδιότητας ParentSeriesGroup.IsColorVaried.

**Επιστρέφει:**
boolean
### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public final int getBubbleSizeScale()
```

Specifies the scale factor for the bubble chart (can be between 0 and 300 percents of the default size). This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property. And so this property is read-only. Use ParentSeriesGroup property for access to parent series group. Use ParentSeriesGroup.BubbleSizeScale read/write property for change value.

--------------------

Αυτή είναι η προβολή της ιδιότητας ParentSeriesGroup.BubbleSizeScale.

**Επιστρέφει:**
int
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Επιστρέφει τη γονική διαφάνεια ενός FillFormat. Μόνο για ανάγνωση [BaseSlide](../../com.aspose.slides/baseslide).

**Επιστρέφει:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Επιστρέφει την γονική παρουσίαση ενός FillFormat. Μόνο για ανάγνωση [IPresentation](../../com.aspose.slides/ipresentation).

**Επιστρέφει:**
[IPresentation](../../com.aspose.slides/ipresentation)