---
title: ChartSeries
second_title: Aspose.Slides για Android μέσω αναφοράς Java API
description: Αναπαριστά μια σειρά διαγράμματος.
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

Αναπαριστά μια σειρά διαγράμματος.

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getChart()](#getChart--) | Επιστρέφει το γονικό διάγραμμα. |
| [getExplosion()](#getExplosion--) | Η απόσταση ενός ανοιχτού κομματιού πίτας από το κέντρο του διαγράμματος πίτας εκφράζεται ως ποσοστό της διαμέτρου της πίτας. |
| [setExplosion(int value)](#setExplosion-int-) | Η απόσταση ενός ανοιχτού κομματιού πίτας από το κέντρο του διαγράμματος πίτας εκφράζεται ως ποσοστό της διαμέτρου της πίτας. |
| [getSmooth()](#getSmooth--) | Αναπαριστά εξομάλυνση καμπύλης. |
| [setSmooth(boolean value)](#setSmooth-boolean-) | Αναπαριστά εξομάλυνση καμπύλης. |
| [getName()](#getName--) | Επιστρέφει το όνομα της σειράς. |
| [getDataPoints()](#getDataPoints--) | Επιστρέφει τη συλλογή των σημείων δεδομένων αυτής της σειράς. |
| [getType()](#getType--) | Επιστρέφει έναν τύπο αυτής της σειράς. |
| [setType(int value)](#setType-int-) | Επιστρέφει έναν τύπο αυτής της σειράς. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | Δείχνει αν αυτή η σειρά σχεδιάζεται στον δευτερογενή άξονα. |
| [setPlotOnSecondAxis(boolean value)](#setPlotOnSecondAxis-boolean-) | Δείχνει αν αυτή η σειρά σχεδιάζεται στον δευτερογενή άξονα. |
| [getParentSeriesGroup()](#getParentSeriesGroup--) | ParentSeriesGroup. |
| [getFormat()](#getFormat--) | Επιστρέφει τη μορφή μιας σειράς. |
| [getOrder()](#getOrder--) | Επιστρέφει τη σειρά μιας σειράς. |
| [setOrder(int value)](#setOrder-int-) | Επιστρέφει τη σειρά μιας σειράς. |
| [getLabels()](#getLabels--) | Επιστρέφει τις ετικέτες μιας σειράς. |
| [getTrendLines()](#getTrendLines--) | Συλλογή γραμμών τάσης σειράς. |
| [getErrorBarsXFormat()](#getErrorBarsXFormat--) | Αναπαριστά τις ErrorBars της σειράς με κατεύθυνση X. |
| [getErrorBarsYFormat()](#getErrorBarsYFormat--) | Αναπαριστά τις ErrorBars της σειράς με κατεύθυνση Y. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Αναπαριστά την καταχώρηση υπομνήματος που σχετίζεται με αυτή τη σειρά Μόνο για ανάγνωση [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties). |
| [getNumberFormatOfValues()](#getNumberFormatOfValues--) | NumberFormatOfValues. |
| [setNumberFormatOfValues(String value)](#setNumberFormatOfValues-java.lang.String-) | NumberFormatOfValues. |
| [getNumberFormatOfXValues()](#getNumberFormatOfXValues--) | NumberFormatOfXValues. |
| [setNumberFormatOfXValues(String value)](#setNumberFormatOfXValues-java.lang.String-) | NumberFormatOfXValues. |
| [getNumberFormatOfYValues()](#getNumberFormatOfYValues--) | NumberFormatOfYValues. |
| [setNumberFormatOfYValues(String value)](#setNumberFormatOfYValues-java.lang.String-) | NumberFormatOfYValues. |
| [getNumberFormatOfBubbleSizes()](#getNumberFormatOfBubbleSizes--) | NumberFormatOfBubbleSizes. |
| [setNumberFormatOfBubbleSizes(String value)](#setNumberFormatOfBubbleSizes-java.lang.String-) | NumberFormatOfBubbleSizes. |
| [getMarker()](#getMarker--) | Marker. |
| [getBar3DShape()](#getBar3DShape--) | Καθορίζει το σχήμα μιας σειράς σε διάγραμμα 3-Δ ράβδων. |
| [setBar3DShape(int value)](#setBar3DShape-int-) | Καθορίζει το σχήμα μιας σειράς σε διάγραμμα 3-Δ ράβδων. |
| [getInvertIfNegative()](#getInvertIfNegative--) | Καθορίζει ότι η σειρά ράβδου, στήλης ή φούσκας θα αντιστρέψει τα χρώματά της εάν η τιμή είναι αρνητική. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | Καθορίζει ότι η σειρά ράβδου, στήλης ή φούσκας θα αντιστρέψει τα χρώματά της εάν η τιμή είναι αρνητική. |
| [getInvertedSolidFillColor()](#getInvertedSolidFillColor--) | Καθορίζει την αντιστροφή του συμπαγούς χρώματος για τη σειρά. |
| [getAutomaticSeriesColor()](#getAutomaticSeriesColor--) | Επιστρέφει αυτόματο χρώμα σειράς βάσει του δείκτη σειράς και του στυλ διαγράμματος. |
| [getShowInnerPoints()](#getShowInnerPoints--) | Αναπαριστά εσωτερικά σημεία. |
| [setShowInnerPoints(boolean value)](#setShowInnerPoints-boolean-) | Αναπαριστά εσωτερικά σημεία. |
| [getShowOutlierPoints()](#getShowOutlierPoints--) | Αναπαριστά ακραία σημεία. |
| [setShowOutlierPoints(boolean value)](#setShowOutlierPoints-boolean-) | Αναπαριστά ακραία σημεία. |
| [getShowMeanMarkers()](#getShowMeanMarkers--) | Αναπαριστά δείκτες μέσου όρου. |
| [setShowMeanMarkers(boolean value)](#setShowMeanMarkers-boolean-) | Αναπαριστά δείκτες μέσου όρου. |
| [getShowMeanLine()](#getShowMeanLine--) | Αναπαριστά τη γραμμή μέσου. |
| [setShowMeanLine(boolean value)](#setShowMeanLine-boolean-) | Αναπαριστά τη γραμμή μέσου. |
| [getQuartileMethod()](#getQuartileMethod--) | Αναπαριστά τη μέθοδο τεταρτοδείκτη. |
| [setQuartileMethod(int value)](#setQuartileMethod-int-) | Αναπαριστά τη μέθοδο τεταρτοδείκτη. |
| [getShowConnectorLines()](#getShowConnectorLines--) | Αναπαριστά γραμμές σύνδεσης. |
| [setShowConnectorLines(boolean value)](#setShowConnectorLines-boolean-) | Αναπαριστά γραμμές σύνδεσης. |
| [getParentLabelLayout()](#getParentLabelLayout--) | Αναπαριστά τη διάταξη των ετικετών γονικής κατηγορίας. |
| [setParentLabelLayout(int value)](#setParentLabelLayout-int-) | Αναπαριστά τη διάταξη των ετικετών γονικής κατηγορίας. |
| [hasUpDownBars()](#hasUpDownBars--) | Καθορίζει εάν το διάγραμμα Γραμμής ή Μετοχών έχει γραμμές πάνω/κάτω. |
| [getGapWidth()](#getGapWidth--) | Καθορίζει το κενό μεταξύ ομάδων ράβδων ή στηλών, ως ποσοστό του πλάτους της ράβδου ή της στήλης. |
| [getGapDepth()](#getGapDepth--) | Επιστρέφει ή ορίζει την απόσταση, ως ποσοστό του πλάτους του δείκτη, μεταξύ των σειρών δεδομένων σε διάγραμμα 3Δ. |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | Καθορίζει τη γωνία του πρώτου κομματιού πίτας ή δακτυλίου, σε μοίρες (δεξιόστροφα από την κορυφή, από 0 έως 360 μοίρες). |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | Καθορίζει το μέγεθος της τρύπας σε διάγραμμα δακτυλίου (μπορεί να είναι μεταξύ 10 και 90 τοις εκατό του μεγέθους της περιοχής σχεδίασης). |
| [getOverlap()](#getOverlap--) | Καθορίζει πόσο επικαλύπτονται οι ράβδοι και οι στήλες σε 2-Δ διαγράμματα, ως ποσοστό (από -100% έως 100%). |
| [getSecondPieSize()](#getSecondPieSize--) | Καθορίζει το μέγεθος της δεύτερης πίτας ή ράβδου σε διάγραμμα πίτας-εντός-πίτας ή ράβδου-εντός-πίτας, ως ποσοστό του μεγέθους της πρώτης πίτας (μπορεί να είναι μεταξύ 5 και 200 τοις εκατό). |
| [hasSeriesLines()](#hasSeriesLines--) | Καθορίζει εάν υπάρχουν γραμμές σειράς για αυτή τη σειρά και τις συναφείς σειρές. |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | Καθορίζει πώς αντιπροσωπεύονται οι τιμές μεγέθους φούσκας στο διάγραμμα φούσκας. |
| [getPieSplitPosition()](#getPieSplitPosition--) | Καθορίζει μια τιμή που θα χρησιμοποιηθεί για τον προσδιορισμό των σημείων δεδομένων που βρίσκονται στη δεύτερη πίτα ή ράβδο σε διάγραμμα πίτας-εντός-πίτας ή ράβδου-εντός-πίτας. |
| [getPieSplitBy()](#getPieSplitBy--) | Καθορίζει πώς να προσδιοριστούν τα σημεία δεδομένων που βρίσκονται στη δεύτερη πίτα ή ράβδο σε διάγραμμα πίτας-εντός-πίτας ή ράβδου-εντός-πίτας. |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | Οι προσαρμοσμένες πληροφορίες διαχωρισμού για ένα διάγραμμα πίτας-εντός-πίτας ή ράβδου-εντός-πίτας με προσαρμοσμένο διαχωρισμό. |
| [isColorVaried()](#isColorVaried--) | Καθορίζει ότι κάθε δείκτη δεδομένων στη σειρά έχει διαφορετικό χρώμα. |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | Καθορίζει τον συντελεστή κλίμακας για το διάγραμμα φούσκας (μπορεί να είναι μεταξύ 0 και 300 τοις εκατό του προεπιλεγμένου μεγέθους). |
| [getSlide()](#getSlide--) | Επιστρέφει τη γονική διαφάνεια ενός FillFormat. |
| [getPresentation()](#getPresentation--) | Επιστρέφει τη γονική παρουσίαση ενός FillFormat. |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Επιστρέφει το αντικείμενο Parent_Immediate. Μόνο για ανάγνωση IDOMObject.

**Επιστρέφει:**  
com.aspose.slides.IDOMObject

### getChart() {#getChart--}
```
public final IChart getChart()
```

Επιστρέφει το γονικό διάγραμμα. Μόνο για ανάγνωση [IChart](../../com.aspose.slides/ichart).

**Επιστρέφει:**  
[IChart](../../com.aspose.slides/ichart)

### getExplosion() {#getExplosion--}
```
public final int getExplosion()
```

Η απόσταση ενός ανοιχτού κομματιού πίτας από το κέντρο του διαγράμματος πίτας εκφράζεται ως ποσοστό της διαμέτρου της πίτας. Αναγνώ-εγγραφή int.

**Επιστρέφει:**  
int

### setExplosion(int value) {#setExplosion-int-}
```
public final void setExplosion(int value)
```

Η απόσταση ενός ανοιχτού κομματιού πίτας από το κέντρο του διαγράμματος πίτας εκφράζεται ως ποσοστό της διαμέτρου της πίτας. Αναγνώ-εγγραφή int.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getSmooth() {#getSmooth--}
```
public final boolean getSmooth()
```

Αναπαριστά εξομάλυνση καμπύλης. True αν η εξομάλυνση είναι ενεργή για διάγραμμα γραμμής ή διάγραμμα διασποράς συνδεδεμένο με γραμμές. Ισχύει μόνο για γραμμές και διασπορά συνδεδεμένα με γραμμές. Αναγνώ-εγγραφή boolean.

**Επιστρέφει:**  
boolean

### setSmooth(boolean value) {#setSmooth-boolean-}
```
public final void setSmooth(boolean value)
```

Αναπαριστά εξομάλυνση καμπύλης. True αν η εξομάλυνση είναι ενεργή για διάγραμμα γραμμής ή διάγραμμα διασποράς συνδεδεμένο με γραμμές. Ισχύει μόνο για γραμμές και διασπορά συνδεδεμένα με γραμμές. Αναγνώ-εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getName() {#getName--}
```
public final IStringChartValue getName()
```

Επιστρέφει το όνομα της σειράς. Μόνο για ανάγνωση [IStringChartValue](../../com.aspose.slides/istringchartvalue).

**Επιστρέφει:**  
[IStringChartValue](../../com.aspose.slides/istringchartvalue)

### getDataPoints() {#getDataPoints--}
```
public final IChartDataPointCollection getDataPoints()
```

Επιστρέφει τη συλλογή των σημείων δεδομένων αυτής της σειράς. Μόνο για ανάγνωση [IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection).

**Επιστρέφει:**  
[IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection)

### getType() {#getType--}
```
public final int getType()
```

Επιστρέφει έναν τύπο αυτής της σειράς. Αναγνώ-εγγραφή [ChartType](../../com.aspose.slides/charttype).

**Επιστρέφει:**  
int

### setType(int value) {#setType-int-}
```
public final void setType(int value)
```

Επιστρέφει έναν τύπο αυτής της σειράς. Αναγνώ-εγγραφή [ChartType](../../com.aspose.slides/charttype).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public final boolean getPlotOnSecondAxis()
```

Δείχνει αν αυτή η σειρά σχεδιάζεται στον δευτερογενή άξονα. Αναγνώ-εγγραφή boolean.

**Επιστρέφει:**  
boolean

### setPlotOnSecondAxis(boolean value) {#setPlotOnSecondAxis-boolean-}
```
public final void setPlotOnSecondAxis(boolean value)
```

Δείχνει αν αυτή η σειρά σχεδιάζεται στον δευτερογενή άξονα. Αναγνώ-εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getParentSeriesGroup() {#getParentSeriesGroup--}
```
public final IChartSeriesGroup getParentSeriesGroup()
```

ParentSeriesGroup. Μόνο για ανάγνωση [IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup).

**Επιστρέφει:**  
[IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup)

### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

Επιστρέφει τη μορφή μιας σειράς. Μόνο για ανάγνωση [IFormat](../../com.aspose.slides/iformat).

**Επιστρέφει:**  
[IFormat](../../com.aspose.slides/iformat)

### getOrder() {#getOrder--}
```
public final int getOrder()
```

Επιστρέφει τη σειρά μιας σειράς. Αναγνώ-εγγραφή int.

**Επιστρέφει:**  
int

### setOrder(int value) {#setOrder-int-}
```
public final void setOrder(int value)
```

Επιστρέφει τη σειρά μιας σειράς. Αναγνώ-εγγραφή int.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getLabels() {#getLabels--}
```
public final IDataLabelCollection getLabels()
```

Επιστρέφει τις ετικέτες μιας σειράς. Μόνο για ανάγνωση [IDataLabelCollection](../../com.aspose.slides/idatalabelcollection).

**Επιστρέφει:**  
[IDataLabelCollection](../../com.aspose.slides/idatalabelcollection)

### getTrendLines() {#getTrendLines--}
```
public final ITrendlineCollection getTrendLines()
```

Συλλογή γραμμών τάσης σειράς. Μόνο για ανάγνωση [ITrendlineCollection](../../com.aspose.slides/itrendlinecollection).

--------------------

Οι TrendLines είναι διαθέσιμες (μη-null) για σειρές δεδομένων σε μη-στοιβαγμένα 2-Δ area, bar, column, line, stock, xy (scatter) και bubble διαγράμματα. Μια TrendLine δεν είναι διαθέσιμη για σειρές δεδομένων σε οποιονδήποτε τύπο διαγράμματος που είναι στοιβαγμένος ή 3-Δ. Οι TrendLines δεν είναι επίσης διαθέσιμες για radar, pie, surface ή doughnut διαγράμματα.

**Επιστρέφει:**  
[ITrendlineCollection](../../com.aspose.slides/itrendlinecollection)

### getErrorBarsXFormat() {#getErrorBarsXFormat--}
```
public final IErrorBarsFormat getErrorBarsXFormat()
```

Αναπαριστά τις ErrorBars της σειράς με κατεύθυνση X. Μόνο για ανάγνωση [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat).

--------------------

Οι ErrorBars με διεύθυνση X είναι διαθέσιμες για σειρές τύπου area, bar, scatter και bubble. Για οποιονδήποτε άλλο τύπο διαγράμματος αυτή η ιδιότητα επιστρέφει null (συμπεριλαμβανομένων 3D διαγραμμάτων). Σε περίπτωση προσαρμοσμένων τιμών χρησιμοποιήστε τη συλλογή DataPoints για να καθορίσετε την τιμή (με την ιδιότητα ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues))).

**Επιστρέφει:**  
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)

### getErrorBarsYFormat() {#getErrorBarsYFormat--}
```
public final IErrorBarsFormat getErrorBarsYFormat()
```

Αναπαριστά τις ErrorBars της σειράς με κατεύθυνση Y. Μόνο για ανάγνωση [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat).

--------------------

Οι ErrorBars με διεύθυνση Y είναι διαθέσιμες για σειρές τύπου area, bar, line, scatter και bubble. Για οποιονδήποτε άλλο τύπο διαγράμματος αυτή η ιδιότητα επιστρέφει null (συμπεριλαμβανομένων 3D διαγραμμάτων). Σε περίπτωση προσαρμοσμένων τιμών χρησιμοποιήστε τη συλλογή DataPoints για να καθορίσετε την τιμή (με την ιδιότητα ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues))).

**Επιστρέφει:**  
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)

### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public final ILegendEntryProperties getRelatedLegendEntry()
```

Αναπαριστά την καταχώρηση υπομνήματος που σχετίζεται με αυτή τη σειρά Μόνο για ανάγνωση [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**Επιστρέφει:**  
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)

### getNumberFormatOfValues() {#getNumberFormatOfValues--}
```
public final String getNumberFormatOfValues()
```

NumberFormatOfValues. Αναγνώ-εγγραφή String.

**Επιστρέφει:**  
java.lang.String

### setNumberFormatOfValues(String value) {#setNumberFormatOfValues-java.lang.String-}
```
public final void setNumberFormatOfValues(String value)
```

NumberFormatOfValues. Αναγνώ-εγγραφή String.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |

### getNumberFormatOfXValues() {#getNumberFormatOfXValues--}
```
public final String getNumberFormatOfXValues()
```

NumberFormatOfXValues. Αναγνώ-εγγραφή String.

**Επιστρέφει:**  
java.lang.String

### setNumberFormatOfXValues(String value) {#setNumberFormatOfXValues-java.lang.String-}
```
public final void setNumberFormatOfXValues(String value)
```

NumberFormatOfXValues. Αναγνώ-εγγραφή String.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |

### getNumberFormatOfYValues() {#getNumberFormatOfYValues--}
```
public final String getNumberFormatOfYValues()
```

NumberFormatOfYValues. Αναγνώ-εγγραφή String.

**Επιστρέφει:**  
java.lang.String

### setNumberFormatOfYValues(String value) {#setNumberFormatOfYValues-java.lang.String-}
```
public final void setNumberFormatOfYValues(String value)
```

NumberFormatOfYValues. Αναγνώ-εγγραφή String.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |

### getNumberFormatOfBubbleSizes() {#getNumberFormatOfBubbleSizes--}
```
public final String getNumberFormatOfBubbleSizes()
```

NumberFormatOfBubbleSizes. Αναγνώ-εγγραφή String.

**Επιστρέφει:**  
java.lang.String

### setNumberFormatOfBubbleSizes(String value) {#setNumberFormatOfBubbleSizes-java.lang.String-}
```
public final void setNumberFormatOfBubbleSizes(String value)
```

NumberFormatOfBubbleSizes. Αναγνώ-εγγραφή String.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |

### getMarker() {#getMarker--}
```
public final IMarker getMarker()
```

Marker. Μόνο για ανάγνωση [IMarker](../../com.aspose.slides/imarker).

**Επιστρέφει:**  
[IMarker](../../com.aspose.slides/imarker)

### getBar3DShape() {#getBar3DShape--}
```
public final int getBar3DShape()
```

Καθορίζει το σχήμα μιας σειράς σε διάγραμμα 3-Δ ράβδων. Η αλλαγή της τιμής αυτής της ιδιότητας μπορεί να προκαλέσει αυτόματη αλλαγή του Type της σειράς. Αναγνώ-εγγραφή [ChartShapeType](../../com.aspose.slides/chartshapetype).

**Επιστρέφει:**  
int

### setBar3DShape(int value) {#setBar3DShape-int-}
```
public final void setBar3DShape(int value)
```

Καθορίζει το σχήμα μιας σειράς σε διάγραμμα 3-Δ ράβδων. Η αλλαγή της τιμής αυτής της ιδιότητας μπορεί να προκαλέσει αυτόματη αλλαγή του Type της σειράς. Αναγνώ-εγγραφή [ChartShapeType](../../com.aspose.slides/chartshapetype).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getInvertIfNegative() {#getInvertIfNegative--}
```
public final boolean getInvertIfNegative()
```

Καθορίζει ότι η σειρά ράβδου, στήλης ή φούσκας θα αντιστρέψει τα χρώματά της εάν η τιμή είναι αρνητική. Αναγνώ-εγγραφή boolean.

**Επιστρέφει:**  
boolean

### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public final void setInvertIfNegative(boolean value)
```

Καθορίζει ότι η σειρά ράβδου, στήλης ή φούσκας θα αντιστρέψει τα χρώματά της εάν η τιμή είναι αρνητική. Αναγνώ-εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getInvertedSolidFillColor() {#getInvertedSolidFillColor--}
```
public final IColorFormat getInvertedSolidFillColor()
```

Καθορίζει την αντιστροφή του συμπαγούς χρώματος για τη σειρά. Για να εφαρμοστεί η ρύθμιση του χρώματος ορίστε το FillType της σειράς σε FillType.Solid. Αναγνώ-εγγραφή [ColorFormat](../../com.aspose.slides/colorformat).

**Επιστρέφει:**  
[IColorFormat](../../com.aspose.slides/icolorformat)

### getAutomaticSeriesColor() {#getAutomaticSeriesColor--}
```
public final Integer getAutomaticSeriesColor()
```

Επιστρέφει αυτόματο χρώμα σειράς βάσει του δείκτη σειράς και του στυλ διαγράμματος. Αυτό το χρώμα χρησιμοποιείται εξ ορισμού αν το FillType είναι NotDefined.

**Επιστρέφει:**  
java.lang.Integer - The java.lang.Integer object.

### getShowInnerPoints() {#getShowInnerPoints--}
```
public final boolean getShowInnerPoints()
```

Αναπαριστά εσωτερικά σημεία. True αν τα εσωτερικά σημεία εμφανίζονται στο διάγραμμα BoxAndWhisker. Ισχύει μόνο για διαγράμματα BoxAndWhisker. Αναγνώ-εγγραφή boolean.

**Επιστρέφει:**  
boolean

### setShowInnerPoints(boolean value) {#setShowInnerPoints-boolean-}
```
public final void setShowInnerPoints(boolean value)
```

Αναπαριστά εσωτερικά σημεία. True αν τα εσωτερικά σημεία εμφανίζονται στο διάγραμμα BoxAndWhisker. Ισχύει μόνο για διαγράμματα BoxAndWhisker. Αναγνώ-εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getShowOutlierPoints() {#getShowOutlierPoints--}
```
public final boolean getShowOutlierPoints()
```

Αναπαριστά ακραία σημεία. True αν τα ακραία σημεία εμφανίζονται στο διάγραμμα BoxAndWhisker. Ισχύει μόνο για διαγράμματα BoxAndWhisker. Αναγνώ-εγγραφή boolean.

**Επιστρέφει:**  
boolean

### setShowOutlierPoints(boolean value) {#setShowOutlierPoints-boolean-}
```
public final void setShowOutlierPoints(boolean value)
```

Αναπαριστά ακραία σημεία. True αν τα ακραία σημεία εμφανίζονται στο διάγραμμα BoxAndWhisker. Ισχύει μόνο για διαγράμματα BoxAndWhisker. Αναγνώ-εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getShowMeanMarkers() {#getShowMeanMarkers--}
```
public final boolean getShowMeanMarkers()
```

Αναπαριστά δείκτες μέσου όρου. True αν οι δείκτες μέσου όρου εμφανίζονται στο διάγραμμα BoxAndWhisker. Ισχύει μόνο για διαγράμματα BoxAndWhisker. Αναγνώ-εγγραφή boolean.

**Επιστρέφει:**  
boolean

### setShowMeanMarkers(boolean value) {#setShowMeanMarkers-boolean-}
```
public final void setShowMeanMarkers(boolean value)
```

Αναπαριστά δείκτες μέσου όρου. True αν οι δείκτες μέσου όρου εμφανίζονται στο διάγραμμα BoxAndWhisker. Ισχύει μόνο για διαγράμματα BoxAndWhisker. Αναγνώ-εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getShowMeanLine() {#getShowMeanLine--}
```
public final boolean getShowMeanLine()
```

Αναπαριστά τη γραμμή μέσου. True αν η γραμμή μέσου εμφανίζεται στο διάγραμμα BoxAndWhisker. Ισχύει μόνο για διαγράμματα BoxAndWhisker. Αναγνώ-εγγραφή boolean.

**Επιστρέφει:**  
boolean

### setShowMeanLine(boolean value) {#setShowMeanLine-boolean-}
```
public final void setShowMeanLine(boolean value)
```

Αναπαριστά τη γραμμή μέσου. True αν η γραμμή μέσου εμφανίζεται στο διάγραμμα BoxAndWhisker. Ισχύει μόνο για διαγράμματα BoxAndWhisker. Αναγνώ-εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getQuartileMethod() {#getQuartileMethod--}
```
public final int getQuartileMethod()
```

Αναπαριστά τη μέθοδο τεταρτοδείκτη. Ισχύει μόνο για διαγράμματα BoxAndWhisker.

**Επιστρέφει:**  
int

### setQuartileMethod(int value) {#setQuartileMethod-int-}
```
public final void setQuartileMethod(int value)
```

Αναπαριστά τη μέθοδο τεταρτοδείκτη. Ισχύει μόνο για διαγράμματα BoxAndWhisker.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getShowConnectorLines() {#getShowConnectorLines--}
```
public final boolean getShowConnectorLines()
```

Αναπαριστά γραμμές σύνδεσης. Ισχύει μόνο για διαγράμματα Waterfall.

**Επιστρέφει:**  
boolean

### setShowConnectorLines(boolean value) {#setShowConnectorLines-boolean-}
```
public final void setShowConnectorLines(boolean value)
```

Αναπαριστά γραμμές σύνδεσης. Ισχύει μόνο για διαγράμματα Waterfall.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getParentLabelLayout() {#getParentLabelLayout--}
```
public final int getParentLabelLayout()
```

Αναπαριστά τη διάταξη των ετικετών γονικής κατηγορίας. Ισχύει μόνο για διαγράμματα Treemap.

**Επιστρέφει:**  
int

### setParentLabelLayout(int value) {#setParentLabelLayout-int-}
```
public final void setParentLabelLayout(int value)
```

Αναπαριστά τη διάταξη των ετικετών γονικής κατηγορίας. Ισχύει μόνο για διαγράμματα Treemap.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### hasUpDownBars() {#hasUpDownBars--}
```
public final boolean hasUpDownBars()
```

Καθορίζει εάν το διάγραμμα Γραμμής ή Μετοχών έχει γραμμές πάνω/κάτω. Αυτή η ιδιότητα είναι μόνο για ανάγνωση. Χρησιμοποιήστε την ιδιότητα ParentSeriesGroup για πρόσβαση στην ομάδα γονικών σειρών. Χρησιμοποιήστε την ιδιότητα ParentSeriesGroup.UpDownBars.HasUpDownBars για αλλαγή τιμής. Χρησιμοποιήστε την ιδιότητα ParentSeriesGroup.UpDownBars για μορφοποίηση των γραμμών πάνω/κάτω. Μόνο για ανάγνωση boolean.

--------------------

Αυτή είναι η προβολή της ιδιότητας ParentSeriesGroup.UpDownBars.HasUpDownBars.

**Επιστρέφει:**  
boolean

### getGapWidth() {#getGapWidth--}
```
public final int getGapWidth()
```

Καθορίζει το κενό μεταξύ ομάδων ράβδων ή στηλών, ως ποσοστό του πλάτους της ράβδου ή της στήλης. Αυτή η ιδιότητα είναι μόνο για ανάγνωση. Χρησιμοποιήστε την ιδιότητα ParentSeriesGroup για πρόσβαση στην ομάδα γονικών σειρών. Χρησιμοποιήστε την ιδιότητα ParentSeriesGroup.GapWidth για αλλαγή τιμής. Μόνο για ανάγνωση int.

--------------------

Αυτή είναι η προβολή της ιδιότητας ParentSeriesGroup.GapWidth.

**Επιστρέφει:**  
int

### getGapDepth() {#getGapDepth--}
```
public final int getGapDepth()
```

Επιστρέφει ή ορίζει την απόσταση, ως ποσοστό του πλάτους του δείκτη, μεταξύ των σειρών δεδομένων σε διάγραμμα 3Δ. Αυτή η ιδιότητα είναι μόνο για ανάγνωση. Χρησιμοποιήστε την ιδιότητα ParentSeriesGroup για πρόσβαση στην ομάδα γονικών σειρών. Χρησιμοποιήστε την ιδιότητα ParentSeriesGroup.GapDepth για αλλαγή τιμής. Μόνο για ανάγνωση int.

--------------------

Αυτή είναι η προβολή της ιδιότητας ParentSeriesGroup.GapDepth.

**Επιστρέφει:**  
int

### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public final int getFirstSliceAngle()
```

Καθορίζει τη γωνία του πρώτου κομματιού πίτας ή δακτυλίου, σε μοίρες (δεξιόστροφα από την κορυφή, από 0 έως 360 μοίρες). Αυτή η ιδιότητα είναι μόνο για ανάγνωση. Χρησιμοποιήστε την ιδιότητα ParentSeriesGroup για πρόσβαση στην ομάδα γονικών σειρών. Χρησιμοποιήστε την ιδιότητα ParentSeriesGroup.FirstSliceAngle για αλλαγή τιμής. Μόνο για ανάγνωση int.

--------------------

Αυτή είναι η προβολή της ιδιότητας ParentSeriesGroup.FirstSliceAngle.

**Επιστρέφει:**  
int

### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public final byte getDoughnutHoleSize()
```

Καθορίζει το μέγεθος της τρύπας σε διάγραμμα δακτυλίου (μπορεί να είναι μεταξύ 10 και 90 τοις εκατό του μεγέθους της περιοχής σχεδίασης). Αυτή η ιδιότητα είναι μόνο για ανάγνωση. Χρησιμοποιήστε την ιδιότητα ParentSeriesGroup για πρόσβαση στην ομάδα γονικών σειρών. Χρησιμοποιήστε την ιδιότητα ParentSeriesGroup.DoughnutHoleSize για αλλαγή τιμής. Μόνο για ανάγνωση byte.

--------------------

Αυτή είναι η προβολή της ιδιότητας ParentSeriesGroup.DoughnutHoleSize.

**Επιστρέφει:**  
byte

### getOverlap() {#getOverlap--}
```
public final byte getOverlap()
```

Καθορίζει πόσο επικαλύπτονται οι ράβδοι και οι στήλες σε 2-Δ διαγράμματα, ως ποσοστό (από -100% έως 100%). Αυτή η ιδιότητα είναι μόνο για ανάγνωση. Για αλλαγή τιμής, χρησιμοποιήστε την ιδιότητα ParentSeriesGroup.Overlap. Μόνο για ανάγνωση byte.

--------------------

Η επικάλυψη καθορίζει το βαθμό επικάλυψης ή απόστασης μεταξύ ράβδων και στηλών ως ποσοστό του πλάτους τους: -100%: Μέγιστο κενό (οι ράβδοι είναι εντελώς χωρισμένες). 0%: Οι ράβδοι τοποθετούνται δίπλα χωρίς επικάλυψη ή κενό. 100%: Μέγιστη επικάλυψη (οι ράβδοι επικαλύπτονται πλήρως). Αυτό είναι η προβολή της ιδιότητας ParentSeriesGroup.Overlap.

**Επιστρέφει:**  
byte

### getSecondPieSize() {#getSecondPieSize--}
```
public final int getSecondPieSize()
```

Καθορίζει το μέγεθος της δεύτερης πίτας ή ράβδου σε διάγραμμα πίτας-εντός-πίτας ή ράβδου-εντός-πίτας, ως ποσοστό του μεγέθους της πρώτης πίτας (μπορεί να είναι μεταξύ 5 και 200 τοις εκατό). Αυτή η ιδιότητα είναι μόνο για ανάγνωση. Χρησιμοποιήστε την ιδιότητα ParentSeriesGroup για πρόσβαση στην ομάδα γονικών σειρών. Χρησιμοποιήστε την ιδιότητα ParentSeriesGroup.SecondPieSize για αλλαγή τιμής. Μόνο για ανάγνωση int.

--------------------

Αυτή είναι η προβολή της ιδιότητας ParentSeriesGroup.SecondPieSize.

**Επιστρέφει:**  
int

### hasSeriesLines() {#hasSeriesLines--}
```
public final boolean hasSeriesLines()
```

Καθορίζει εάν υπάρχουν γραμμές σειράς για αυτή τη σειρά και τις συναφείς σειρές. Αυτή η ιδιότητα είναι μόνο για ανάγνωση. Χρησιμοποιήστε την ιδιότητα ParentSeriesGroup για πρόσβαση στην ομάδα γονικών σειρών. Χρησιμοποιήστε την ιδιότητα ParentSeriesGroup.HasSeriesLines για αλλαγή τιμής. Χρησιμοποιήστε την ιδιότητα ParentSeriesGroup.SeriesLinesFormat για μορφοποίηση των γραμμών σειράς. Μόνο για ανάγνωση boolean.

--------------------

Αυτή είναι η προβολή της ιδιότητας ParentSeriesGroup.HasSeriesLines.

**Επιστρέφει:**  
boolean

### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public final int getBubbleSizeRepresentation()
```

Καθορίζει πώς αντιπροσωπεύονται οι τιμές μεγέθους φούσκας στο διάγραμμα φούσκας. Αυτή η ιδιότητα είναι μόνο για ανάγνωση. Χρησιμοποιήστε την ιδιότητα ParentSeriesGroup για πρόσβαση στην ομάδα γονικών σειρών. Χρησιμοποιήστε την ιδιότητα ParentSeriesGroup.BubbleSizeRepresentation για αλλαγή τιμής.

--------------------

Αυτή είναι η προβολή της ιδιότητας ParentSeriesGroup.BubbleSizeRepresentation.

**Επιστρέφει:**  
int

### getPieSplitPosition() {#getPieSplitPosition--}
```
public final double getPieSplitPosition()
```

Καθορίζει μια τιμή που θα χρησιμοποιηθεί για τον προσδιορισμό των σημείων δεδομένων που βρίσκονται στη δεύτερη πίτα ή ράβδο σε διάγραμμα πίτας-εντός-πίτας ή ράβδου-εντός-πίτας. Είναι συνδυασμένη με την ιδιότητα PieSplitBy. Αυτή η ιδιότητα είναι μόνο για ανάγνωση. Χρησιμοποιήστε την ιδιότητα ParentSeriesGroup για πρόσβαση στην ομάδα γονικών σειρών. Χρησιμοποιήστε την ιδιότητα ParentSeriesGroup.PieSplitPosition για αλλαγή τιμής. Μόνο για ανάγνωση double.

--------------------

Αυτή είναι η προβολή της ιδιότητας ParentSeriesGroup.PieSplitPosition.

**Επιστρέφει:**  
double

### getPieSplitBy() {#getPieSplitBy--}
```
public final int getPieSplitBy()
```

Καθορίζει πώς να προσδιοριστούν τα σημεία δεδομένων που βρίσκονται στη δεύτερη πίτα ή ράβδο σε διάγραμμα πίτας-εντός-πίτας ή ράβδου-εντός-πίτας. Αυτή η ιδιότητα είναι μόνο για ανάγνωση. Χρησιμοποιήστε την ιδιότητα ParentSeriesGroup για πρόσβαση στην ομάδα γονικών σειρών. Χρησιμοποιήστε την ιδιότητα ParentSeriesGroup.PieSplitBy για αλλαγή τιμής. Μόνο για ανάγνωση [PieSplitType](../../com.aspose.slides/piesplittype).

--------------------

1) Αυτή είναι η προβολή της ιδιότητας ParentSeriesGroup.PieSplitBy. 2) Αν η τιμή της ιδιότητας είναι PieSplitType.Custom τότε μπορείτε να ορίσετε τις προσαρμοσμένες πληροφορίες διαχωρισμού με την ιδιότητα ParentSeriesGroup.PieSplitCustomPoints.

**Επιστρέφει:**  
int

### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public final IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

Οι προσαρμοσμένες πληροφορίες διαχωρισμού για ένα διάγραμμα πίτας-εντός-πίτας ή ράβδου-εντός-πίτας με προσαρμοσμένο διαχωρισμό. Περιέχει σημεία δεδομένων που θα σχεδιαστούν στη δεύτερη πίτα ή ράβδο. Αυτή η ιδιότητα είναι μόνο για ανάγνωση [PieSplitCustomPointCollection](../../com.aspose.slides/piesplitcustompointcollection).

--------------------

Αυτή είναι η προβολή της ιδιότητας ParentSeriesGroup.PieSplitCustomPoints.

**Επιστρέφει:**  
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)

### isColorVaried() {#isColorVaried--}
```
public final boolean isColorVaried()
```

Καθορίζει ότι κάθε δείκτη δεδομένων στη σειρά έχει διαφορετικό χρώμα. Αυτή η ιδιότητα είναι μόνο για ανάγνωση. Χρησιμοποιήστε την ιδιότητα ParentSeriesGroup για πρόσβαση στην ομάδα γονικών σειρών. Χρησιμοποιήστε την ιδιότητα ParentSeriesGroup.IsColorVaried για αλλαγή τιμής. Μόνο για ανάγνωση boolean.

--------------------

Αυτή είναι η προβολή της ιδιότητας ParentSeriesGroup.IsColorVaried.

**Επιστρέφει:**  
boolean

### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public final int getBubbleSizeScale()
```

Καθορίζει τον συντελεστή κλίμακας για το διάγραμμα φούσκας (μπορεί να είναι μεταξύ 0 και 300 τοις εκατό του προεπιλεγμένου μεγέθους). Αυτή η ιδιότητα είναι μόνο για ανάγνωση. Χρησιμοποιήστε την ιδιότητα ParentSeriesGroup για πρόσβαση στην ομάδα γονικών σειρών. Χρησιμοποιήστε την ιδιότητα ParentSeriesGroup.BubbleSizeScale για αλλαγή τιμής.

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

Επιστρέφει τη γονική παρουσίαση ενός FillFormat. Μόνο για ανάγνωση [IPresentation](../../com.aspose.slides/ipresentation).

**Επιστρέφει:**  
[IPresentation](../../com.aspose.slides/ipresentation)