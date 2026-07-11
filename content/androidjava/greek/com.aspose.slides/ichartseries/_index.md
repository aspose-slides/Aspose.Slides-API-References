---
title: IChartSeries
second_title: Aspose.Slides για Android μέσω αναφοράς Java API
description: Αντιπροσωπεύει μια σειρά διαγράμματος.
type: docs
url: /el/com.aspose.slides/ichartseries/
---
**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IChartSeries extends IChartComponent
```

Αντιπροσωπεύει μια σειρά διαγράμματος.
## Μεθόδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getExplosion()](#getExplosion--) | Η απόσταση ενός ανοιγμένου κομματιού πίτας από το κέντρο του διαγράμματος πίτας εκφράζεται ως ποσοστό της διαμέτρου της πίτας. |
| [setExplosion(int value)](#setExplosion-int-) | Η απόσταση ενός ανοιγμένου κομματιού πίτας από το κέντρο του διαγράμματος πίτας εκφράζεται ως ποσοστό της διαμέτρου της πίτας. |
| [getSmooth()](#getSmooth--) | Αντιπροσωπεύει την εξομάλυνση καμπύλης. |
| [setSmooth(boolean value)](#setSmooth-boolean-) | Αντιπροσωπεύει την εξομάλυνση καμπύλης. |
| [getMarker()](#getMarker--) | Επιστρέφει τον δείκτη σειράς. |
| [getBar3DShape()](#getBar3DShape--) | Καθορίζει το σχήμα μιας σειράς ενός 3-Δ διαγράμματος μπάρας. |
| [setBar3DShape(int value)](#setBar3DShape-int-) | Καθορίζει το σχήμα μιας σειράς ενός 3-Δ διαγράμματος μπάρας. |
| [getName()](#getName--) | Επιστρέφει το όνομα της σειράς. |
| [getDataPoints()](#getDataPoints--) | Επιστρέφει τη συλλογή σημείων δεδομένων αυτής της σειράς. |
| [getType()](#getType--) | Επιστρέφει έναν τύπο αυτής της σειράς. |
| [setType(int value)](#setType-int-) | Επιστρέφει έναν τύπο αυτής της σειράς. |
| [getParentSeriesGroup()](#getParentSeriesGroup--) | Επιστρέφει την ομάδα γονικής σειράς. |
| [getFormat()](#getFormat--) | Επιστρέφει τη μορφή μιας σειράς. |
| [getOrder()](#getOrder--) | Επιστρέφει τη σειρά της σειράς. |
| [setOrder(int value)](#setOrder-int-) | Επιστρέφει τη σειρά της σειράς. |
| [getLabels()](#getLabels--) | Επιστρέφει τις Ετικέτες μιας σειράς. |
| [getTrendLines()](#getTrendLines--) | Συλλογή γραμμών τάσης σειράς Μόνο ανάγνωση [ITrendlineCollection](../../com.aspose.slides/itrendlinecollection). |
| [getErrorBarsXFormat()](#getErrorBarsXFormat--) | Αντιπροσωπεύει τις ErrorBars της σειράς με κατεύθυνση X. |
| [getErrorBarsYFormat()](#getErrorBarsYFormat--) | Αντιπροσωπεύει τις ErrorBars της σειράς με κατεύθυνση Y. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | Δείχνει αν αυτή η σειρά σχεδιάζεται στον δεύτερο άξονα τιμών. |
| [setPlotOnSecondAxis(boolean value)](#setPlotOnSecondAxis-boolean-) | Δείχνει αν αυτή η σειρά σχεδιάζεται στον δεύτερο άξονα τιμών. |
| [getNumberFormatOfValues()](#getNumberFormatOfValues--) | Επιστρέφει ή ορίζει τη μορφή αριθμού για τις τιμές της σειράς. |
| [setNumberFormatOfValues(String value)](#setNumberFormatOfValues-java.lang.String-) | Επιστρέφει ή ορίζει τη μορφή αριθμού για τις τιμές της σειράς. |
| [getNumberFormatOfXValues()](#getNumberFormatOfXValues--) | Επιστρέφει ή ορίζει τη μορφή αριθμού για τις τιμές x της σειράς. |
| [setNumberFormatOfXValues(String value)](#setNumberFormatOfXValues-java.lang.String-) | Επιστρέφει ή ορίζει τη μορφή αριθμού για τις τιμές x της σειράς. |
| [getNumberFormatOfYValues()](#getNumberFormatOfYValues--) | Επιστρέφει ή ορίζει τη μορφή αριθμού για τις τιμές y της σειράς. |
| [setNumberFormatOfYValues(String value)](#setNumberFormatOfYValues-java.lang.String-) | Επιστρέφει ή ορίζει τη μορφή αριθμού για τις τιμές y της σειράς. |
| [getNumberFormatOfBubbleSizes()](#getNumberFormatOfBubbleSizes--) | Επιστρέφει ή ορίζει τη μορφή αριθμού για τα μεγέθη φυσαλίδων της σειράς. |
| [setNumberFormatOfBubbleSizes(String value)](#setNumberFormatOfBubbleSizes-java.lang.String-) | Επιστρέφει ή ορίζει τη μορφή αριθμού για τα μεγέθη φυσαλίδων της σειράς. |
| [getInvertIfNegative()](#getInvertIfNegative--) | Καθορίζει ότι η σειρά τύπου μπάρας, στήλης ή φυσαλίδας θα αντιστρέψει τα χρώματά της εάν η τιμή είναι αρνητική. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | Καθορίζει ότι η σειρά τύπου μπάρας, στήλης ή φυσαλίδας θα αντιστρέψει τα χρώματά της εάν η τιμή είναι αρνητική. |
| [getInvertedSolidFillColor()](#getInvertedSolidFillColor--) | Καθορίζει την αντιστροφή του συμπαγούς χρώματος για τη σειρά. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Αντιπροσωπεύει την καταχώριση υπομνήματος σχετική με αυτήν τη σειρά Μόνο ανάγνωση [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties). |
| [getAutomaticSeriesColor()](#getAutomaticSeriesColor--) | Επιστρέφει αυτόματο χρώμα σειράς βάσει του δείκτη σειράς και του στυλ διαγράμματος. |
| [getShowInnerPoints()](#getShowInnerPoints--) | Αντιπροσωπεύει εσωτερικά σημεία. |
| [setShowInnerPoints(boolean value)](#setShowInnerPoints-boolean-) | Αντιπροσωπεύει εσωτερικά σημεία. |
| [getShowOutlierPoints()](#getShowOutlierPoints--) | Αντιπροσωπεύει εξαιρετικά σημεία. |
| [setShowOutlierPoints(boolean value)](#setShowOutlierPoints-boolean-) | Αντιπροσωπεύει εξαιρετικά σημεία. |
| [getShowMeanMarkers()](#getShowMeanMarkers--) | Αντιπροσωπεύει δείκτες μέσου όρου. |
| [setShowMeanMarkers(boolean value)](#setShowMeanMarkers-boolean-) | Αντιπροσωπεύει δείκτες μέσου όρου. |
| [getShowMeanLine()](#getShowMeanLine--) | Αντιπροσωπεύει δείκτες μέσου όρου. |
| [setShowMeanLine(boolean value)](#setShowMeanLine-boolean-) | Αντιπροσωπεύει δείκτες μέσου όρου. |
| [getQuartileMethod()](#getQuartileMethod--) | Αντιπροσωπεύει τη μέθοδο τεταρτημόριου. |
| [setQuartileMethod(int value)](#setQuartileMethod-int-) | Αντιπροσωπεύει τη μέθοδο τεταρτημόριου. |
| [getShowConnectorLines()](#getShowConnectorLines--) | Αντιπροσωπεύει γραμμές σύνδεσης. |
| [setShowConnectorLines(boolean value)](#setShowConnectorLines-boolean-) | Αντιπροσωπεύει γραμμές σύνδεσης. |
| [getParentLabelLayout()](#getParentLabelLayout--) | Αντιπροσωπεύει τη διάταξη των ετικετών γονικής κατηγορίας. |
| [setParentLabelLayout(int value)](#setParentLabelLayout-int-) | Αντιπροσωπεύει τη διάταξη των ετικετών γονικής κατηγορίας. |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | Καθορίζει τον συντελεστή κλίμακας για το διάγραμμα φυσαλίδων (μπορεί να είναι μεταξύ 0 και 300 τοις εκατό του προεπιλεγμένου μεγέθους). |
| [hasUpDownBars()](#hasUpDownBars--) | Καθορίζει εάν το διάγραμμα γραμμής ή κερδών έχει γραμμές ανοδικής/καθοδικής κίνησης. |
| [getGapWidth()](#getGapWidth--) | Καθορίζει το κενό μεταξύ ομάδων μπάρας ή στήλης, ως ποσοστό του πλάτους της μπάρας ή στήλης. |
| [getGapDepth()](#getGapDepth--) | Επιστρέφει ή ορίζει την απόσταση, ως ποσοστό του πλάτους του δείκτη, μεταξύ των σειρών δεδομένων σε 3Δ διάγραμμα. |
| [isColorVaried()](#isColorVaried--) | Καθορίζει ότι κάθε δείκτης δεδομένων στη σειρά έχει διαφορετικό χρώμα. |
| [hasSeriesLines()](#hasSeriesLines--) | Καθορίζει εάν υπάρχουν γραμμές σειράς για αυτή τη σειρά και συναφείς σειρές. |
| [getOverlap()](#getOverlap--) | Καθορίζει το πόσο οι μπάρες και στήλες επικαλύπτονται σε 2-Δ διαγράμματα, ως ποσοστό (από -100% έως 100%). |
| [getSecondPieSize()](#getSecondPieSize--) | Καθορίζει το μέγεθος της δεύτερης πίτας ή μπάρας σε διάγραμμα πίτα-στη-πίτα ή μπάρα-στη-πίτα, ως ποσοστό του μεγέθους της πρώτης πίτας (μπορεί να είναι μεταξύ 5 και 200 τοις εκατό). |
| [getPieSplitPosition()](#getPieSplitPosition--) | Καθορίζει μια τιμή που θα χρησιμοποιηθεί για τον καθορισμό των σημείων δεδομένων που βρίσκονται στη δεύτερη πίτα ή μπάρα σε διάγραμμα πίτα-στη-πίτα ή μπάρα-στη-πίτα. |
| [getPieSplitBy()](#getPieSplitBy--) | Καθορίζει πώς να προσδιοριστούν τα σημεία δεδομένων που βρίσκονται στη δεύτερη πίτα ή μπάρα σε διάγραμμα πίτα-στη-πίτα ή μπάρα-στη-πίτα. |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | Καθορίζει το μέγεθος της τρύπας σε διάγραμμα δαχτυλιδιού (μπορεί να είναι μεταξύ 10 και 90 τοις εκατό του μεγέθους της περιοχής σχεδίασης). |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | Καθορίζει τη γωνία του πρώτου κομματιού πίτας ή δαχτυλιδιού, σε μοίρες (δεξιόστροφα από το πάνω, από 0 έως 360 μοίρες). |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | Οι προσαρμοσμένες πληροφορίες διαχωρισμού για διάγραμμα πίτα-στη-πίτα ή μπάρα-στη-πίτα με προσαρμοσμένο διαχωρισμό. |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | Καθορίζει πώς οι τιμές μεγέθους φυσαλίδας παρουσιάζονται στο διάγραμμα φυσαλίδων. |

### getExplosion() {#getExplosion--}
```
public abstract int getExplosion()
```

Η απόσταση ενός ανοιγμένου κομματιού πίτας από το κέντρο του διαγράμματος πίτας εκφράζεται ως ποσοστό της διαμέτρου της πίτας. Απάντηση/εγγραφή int.

**Επιστρέφει:**
int

### setExplosion(int value) {#setExplosion-int-}
```
public abstract void setExplosion(int value)
```

Η απόσταση ενός ανοιγμένου κομματιού πίτας από το κέντρο του διαγράμματος πίτας εκφράζεται ως ποσοστό της διαμέτρου της πίτας. Απάντηση/εγγραφή int.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getSmooth() {#getSmooth--}
```
public abstract boolean getSmooth()
```

Αντιπροσωπεύει την εξομάλυνση καμπύλης. Αληθές εάν η εξομάλυνση καμπύλης είναι ενεργοποιημένη για το διάγραμμα γραμμής ή διασποράς. Ισχύει μόνο για διαγράμματα γραμμής και διασποράς συνδεδεμένα με γραμμές. Απάντηση/εγγραφή boolean.

**Επιστρέφει:**
boolean

### setSmooth(boolean value) {#setSmooth-boolean-}
```
public abstract void setSmooth(boolean value)
```

Αντιπροσωπεύει την εξομάλυνση καμπύλης. Αληθές εάν η εξομάλυνση καμπύλης είναι ενεργοποιημένη για το διάγραμμα γραμμής ή διασποράς. Ισχύει μόνο για διαγράμματα γραμμής και διασποράς συνδεδεμένα με γραμμές. Απάντηση/εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getMarker() {#getMarker--}
```
public abstract IMarker getMarker()
```

Επιστρέφει τον δείκτη σειράς. Μόνο ανάγνωση [IMarker](../../com.aspose.slides/imarker).

**Επιστρέφει:**
[IMarker](../../com.aspose.slides/imarker)

### getBar3DShape() {#getBar3DShape--}
```
public abstract int getBar3DShape()
```

Καθορίζει το σχήμα μιας σειράς ενός 3-Δ διαγράμματος μπάρας. Η αλλαγή της τιμής αυτής της ιδιότητας μπορεί να προκαλέσει αυτόματη αλλαγή του Τύπου της σειράς. Απάντηση/εγγραφή [ChartShapeType](../../com.aspose.slides/chartshapetype).

**Επιστρέφει:**
int

### setBar3DShape(int value) {#setBar3DShape-int-}
```
public abstract void setBar3DShape(int value)
```

Καθορίζει το σχήμα μιας σειράς ενός 3-Δ διαγράμματος μπάρας. Η αλλαγή της τιμής αυτής της ιδιότητας μπορεί να προκαλέσει αυτόματη αλλαγή του Τύπου της σειράς. Απάντηση/εγγραφή [ChartShapeType](../../com.aspose.slides/chartshapetype).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getName() {#getName--}
```
public abstract IStringChartValue getName()
```

Επιστρέφει το όνομα της σειράς. Μόνο ανάγνωση [IStringChartValue](../../com.aspose.slides/istringchartvalue).

**Επιστρέφει:**
[IStringChartValue](../../com.aspose.slides/istringchartvalue)

### getDataPoints() {#getDataPoints--}
```
public abstract IChartDataPointCollection getDataPoints()
```

Επιστρέφει τη συλλογή σημείων δεδομένων αυτής της σειράς. Μόνο ανάγνωση [IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection).

**Επιστρέφει:**
[IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection)

### getType() {#getType--}
```
public abstract int getType()
```

Επιστρέφει έναν τύπο αυτής της σειράς. Απάντηση/εγγραφή [ChartType](../../com.aspose.slides/charttype).

**Επιστρέφει:**
int

### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```

Επιστρέφει έναν τύπο αυτής της σειράς. Απάντηση/εγγραφή [ChartType](../../com.aspose.slides/charttype).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getParentSeriesGroup() {#getParentSeriesGroup--}
```
public abstract IChartSeriesGroup getParentSeriesGroup()
```

Επιστρέφει την ομάδα γονικής σειράς. Μόνο ανάγνωση [IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup).

**Επιστρέφει:**
[IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup)

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Επιστρέφει τη μορφή μιας σειράς. Μόνο ανάγνωση [IFormat](../../com.aspose.slides/iformat).

**Επιστρέφει:**
[IFormat](../../com.aspose.slides/iformat)

### getOrder() {#getOrder--}
```
public abstract int getOrder()
```

Επιστρέφει τη σειρά της σειράς. Απάντηση/εγγραφή int.

**Επιστρέφει:**
int

### setOrder(int value) {#setOrder-int-}
```
public abstract void setOrder(int value)
```

Επιστρέφει τη σειρά της σειράς. Απάντηση/εγγραφή int.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getLabels() {#getLabels--}
```
public abstract IDataLabelCollection getLabels()
```

Επιστρέφει τις Ετικέτες μιας σειράς. Μόνο ανάγνωση [IDataLabelCollection](../../com.aspose.slides/idatalabelcollection).

**Επιστρέφει:**
[IDataLabelCollection](../../com.aspose.slides/idatalabelcollection)

### getTrendLines() {#getTrendLines--}
```
public abstract ITrendlineCollection getTrendLines()
```

Συλλογή γραμμών τάσης σειράς Μόνο ανάγνωση [ITrendlineCollection](../../com.aspose.slides/itrendlinecollection).

**Επιστρέφει:**
[ITrendlineCollection](../../com.aspose.slides/itrendlinecollection)

### getErrorBarsXFormat() {#getErrorBarsXFormat--}
```
public abstract IErrorBarsFormat getErrorBarsXFormat()
```

Αντιπροσωπεύει τις ErrorBars της σειράς με κατεύθυνση X. Μόνο ανάγνωση [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat).

--------------------

Οι ErrorBars με κατεύθυνση X είναι διαθέσιμες για σειρές τύπου area, bar, scatter και bubble. Για άλλους τύπους διαγράμματος αυτή η ιδιότητα επιστρέφει null (συμπεριλαμβανομένων 3D διαγραμμάτων). Σε περίπτωση προσαρμοσμένων τιμών, χρησιμοποιήστε τη συλλογή DataPoints για να ορίσετε την τιμή (με την ιδιότητα ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues))).

**Επιστρέφει:**
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)

### getErrorBarsYFormat() {#getErrorBarsYFormat--}
```
public abstract IErrorBarsFormat getErrorBarsYFormat()
```

Αντιπροσωπεύει τις ErrorBars της σειράς με κατεύθυνση Y. Μόνο ανάγνωση [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat).

--------------------

Οι ErrorBars με κατεύθυνση Y είναι διαθέσιμες για σειρές τύπου area, bar, line, scatter και bubble. Για άλλους τύπους διαγράμματος αυτή η ιδιότητα επιστρέφει null (συμπεριλαμβανομένων 3D διαγραμμάτων). Σε περίπτωση προσαρμοσμένων τιμών, χρησιμοποιήστε τη συλλογή DataPoints για να ορίσετε την τιμή (με την ιδιότητα ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues))).

**Επιστρέφει:**
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)

### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public abstract boolean getPlotOnSecondAxis()
```

Δείχνει αν αυτή η σειρά σχεδιάζεται στον δεύτερο άξονα τιμών. Απάντηση/εγγραφή boolean.

**Επιστρέφει:**
boolean

### setPlotOnSecondAxis(boolean value) {#setPlotOnSecondAxis-boolean-}
```
public abstract void setPlotOnSecondAxis(boolean value)
```

Δείχνει αν αυτή η σειρά σχεδιάζεται στον δεύτερο άξονα τιμών. Απάντηση/εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormatOfValues() {#getNumberFormatOfValues--}
```
public abstract String getNumberFormatOfValues()
```

Επιστρέφει ή ορίζει τη μορφή αριθμού για τις τιμές της σειράς. Απάντηση/εγγραφή String.

**Επιστρέφει:**
java.lang.String

### setNumberFormatOfValues(String value) {#setNumberFormatOfValues-java.lang.String-}
```
public abstract void setNumberFormatOfValues(String value)
```

Επιστρέφει ή ορίζει τη μορφή αριθμού για τις τιμές της σειράς. Απάντηση/εγγραφή String.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |

### getNumberFormatOfXValues() {#getNumberFormatOfXValues--}
```
public abstract String getNumberFormatOfXValues()
```

Επιστρέφει ή ορίζει τη μορφή αριθμού για τις τιμές x της σειράς. Απάντηση/εγγραφή String.

**Επιστρέφει:**
java.lang.String

### setNumberFormatOfXValues(String value) {#setNumberFormatOfXValues-java.lang.String-}
```
public abstract void setNumberFormatOfXValues(String value)
```

Επιστρέφει ή ορίζει τη μορφή αριθμού για τις τιμές x της σειράς. Απάντηση/εγγραφή String.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |

### getNumberFormatOfYValues() {#getNumberFormatOfYValues--}
```
public abstract String getNumberFormatOfYValues()
```

Επιστρέφει ή ορίζει τη μορφή αριθμού για τις τιμές y της σειράς. Απάντηση/εγγραφή String.

**Επιστρέφει:**
java.lang.String

### setNumberFormatOfYValues(String value) {#setNumberFormatOfYValues-java.lang.String-}
```
public abstract void setNumberFormatOfYValues(String value)
```

Επιστρέφει ή ορίζει τη μορφή αριθμού για τις τιμές y της σειράς. Απάντηση/εγγραφή String.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |

### getNumberFormatOfBubbleSizes() {#getNumberFormatOfBubbleSizes--}
```
public abstract String getNumberFormatOfBubbleSizes()
```

Επιστρέφει ή ορίζει τη μορφή αριθμού για τα μεγέθη φυσαλίδων της σειράς. Απάντηση/εγγραφή String.

**Επιστρέφει:**
java.lang.String

### setNumberFormatOfBubbleSizes(String value) {#setNumberFormatOfBubbleSizes-java.lang.String-}
```
public abstract void setNumberFormatOfBubbleSizes(String value)
```

Επιστρέφει ή ορίζει τη μορφή αριθμού για τα μεγέθη φυσαλίδων της σειράς. Απάντηση/εγγραφή String.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |

### getInvertIfNegative() {#getInvertIfNegative--}
```
public abstract boolean getInvertIfNegative()
```

Καθορίζει ότι η σειρά τύπου μπάρας, στήλης ή φυσαλίδας θα αντιστρέψει τα χρώματά της εάν η τιμή είναι αρνητική. Απάντηση/εγγραφή boolean.

**Επιστρέφει:**
boolean

### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public abstract void setInvertIfNegative(boolean value)
```

Καθορίζει ότι η σειρά τύπου μπάρας, στήλης ή φυσαλίδας θα αντιστρέψει τα χρώματά της εάν η τιμή είναι αρνητική. Απάντηση/εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getInvertedSolidFillColor() {#getInvertedSolidFillColor--}
```
public abstract IColorFormat getInvertedSolidFillColor()
```

Καθορίζει την αντιστροφή του συμπαγούς χρώματος για τη σειρά. Για εφαρμογή χρώματος, ορίστε το FillType της σειράς σε FillType.Solid. Απάντηση/εγγραφή [IColorFormat](../../com.aspose.slides/icolorformat).

**Επιστρέφει:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public abstract ILegendEntryProperties getRelatedLegendEntry()
```

Αντιπροσωπεύει την καταχώριση υπομνήματος σχετική με αυτήν τη σειρά Μόνο ανάγνωση [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**Επιστρέφει:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)

### getAutomaticSeriesColor() {#getAutomaticSeriesColor--}
```
public abstract Integer getAutomaticSeriesColor()
```

Επιστρέφει αυτόματο χρώμα σειράς βάσει του δείκτη σειράς και του στυλ διαγράμματος. Αυτό το χρώμα χρησιμοποιείται εξ ορισμού εάν FillType = NotDefined.

**Επιστρέφει:**
java.lang.Integer - Automatic color of series java.lang.Integer

### getShowInnerPoints() {#getShowInnerPoints--}
```
public abstract boolean getShowInnerPoints()
```

Αντιπροσωπεύει εσωτερικά σημεία. Αληθές εάν τα εσωτερικά σημεία εμφανίζονται στο διάγραμμα BoxAndWhisker. Ισχύει μόνο για διαγράμματα BoxAndWhisker. Απάντηση/εγγραφή boolean.

**Επιστρέφει:**
boolean

### setShowInnerPoints(boolean value) {#setShowInnerPoints-boolean-}
```
public abstract void setShowInnerPoints(boolean value)
```

Αντιπροσωπεύει εσωτερικά σημεία. Αληθές εάν τα εσωτερικά σημεία εμφανίζονται στο διάγραμμα BoxAndWhisker. Ισχύει μόνο για διαγράμματα BoxAndWhisker. Απάντηση/εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getShowOutlierPoints() {#getShowOutlierPoints--}
```
public abstract boolean getShowOutlierPoints()
```

Αντιπροσωπεύει εξαιρετικά σημεία. Αληθές εάν τα εξαιρετικά σημεία εμφανίζονται στο διάγραμμα BoxAndWhisker. Ισχύει μόνο για διαγράμματα BoxAndWhisker. Απάντηση/εγγραφή boolean.

**Επιστρέφει:**
boolean

### setShowOutlierPoints(boolean value) {#setShowOutlierPoints-boolean-}
```
public abstract void setShowOutlierPoints(boolean value)
```

Αντιπροσωπεύει εξαιρετικά σημεία. Αληθές εάν τα εξαιρετικά σημεία εμφανίζονται στο διάγραμμα BoxAndWhisker. Ισχύει μόνο για διαγράμματα BoxAndWhisker. Απάντηση/εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getShowMeanMarkers() {#getShowMeanMarkers--}
```
public abstract boolean getShowMeanMarkers()
```

Αντιπροσωπεύει δείκτες μέσου όρου. Αληθές εάν οι δείκτες μέσου όρου εμφανίζονται στο διάγραμμα BoxAndWhisker. Ισχύει μόνο για διαγράμματα BoxAndWhisker. Απάντηση/εγγραφή boolean.

**Επιστρέφει:**
boolean

### setShowMeanMarkers(boolean value) {#setShowMeanMarkers-boolean-}
```
public abstract void setShowMeanMarkers(boolean value)
```

Αντιπροσωπεύει δείκτες μέσου όρου. Αληθές εάν οι δείκτες μέσου όρου εμφανίζονται στο διάγραμμα BoxAndWhisker. Ισχύει μόνο για διαγράμματα BoxAndWhisker. Απάντηση/εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getShowMeanLine() {#getShowMeanLine--}
```
public abstract boolean getShowMeanLine()
```

Αντιπροσωπεύει τη γραμμή μέσου όρου. Αληθές εάν η γραμμή μέσου όρου εμφανίζεται στο διάγραμμα BoxAndWhisker. Ισχύει μόνο για διαγράμματα BoxAndWhisker. Απάντηση/εγγραφή boolean.

**Επιστρέφει:**
boolean

### setShowMeanLine(boolean value) {#setShowMeanLine-boolean-}
```
public abstract void setShowMeanLine(boolean value)
```

Αντιπροσωπεύει τη γραμμή μέσου όρου. Αληθές εάν η γραμμή μέσου όρου εμφανίζεται στο διάγραμμα BoxAndWhisker. Ισχύει μόνο για διαγράμματα BoxAndWhisker. Απάντηση/εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getQuartileMethod() {#getQuartileMethod--}
```
public abstract int getQuartileMethod()
```

Αντιπροσωπεύει τη μέθοδο τεταρτημόριου. Ισχύει μόνο για διαγράμματα BoxAndWhisker.

**Επιστρέφει:**
int

### setQuartileMethod(int value) {#setQuartileMethod-int-}
```
public abstract void setQuartileMethod(int value)
```

Αντιπροσωπεύει τη μέθοδο τεταρτημόριου. Ισχύει μόνο για διαγράμματα BoxAndWhisker.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getShowConnectorLines() {#getShowConnectorLines--}
```
public abstract boolean getShowConnectorLines()
```

Αντιπροσωπεύει γραμμές σύνδεσης. Ισχύει μόνο για διαγράμματα Waterfall.

**Επιστρέφει:**
boolean

### setShowConnectorLines(boolean value) {#setShowConnectorLines-boolean-}
```
public abstract void setShowConnectorLines(boolean value)
```

Αντιπροσωπεύει γραμμές σύνδεσης. Ισχύει μόνο για διαγράμματα Waterfall.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getParentLabelLayout() {#getParentLabelLayout--}
```
public abstract int getParentLabelLayout()
```

Αντιπροσωπεύει τη διάταξη των ετικετών γονικής κατηγορίας. Ισχύει μόνο για διαγράμματα Treemap.

**Επιστρέφει:**
int

### setParentLabelLayout(int value) {#setParentLabelLayout-int-}
```
public abstract void setParentLabelLayout(int value)
```

Αντιπροσωπεύει τη διάταξη των ετικετών γονικής κατηγορίας. Ισχύει μόνο για διαγράμματα Treemap.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public abstract int getBubbleSizeScale()
```

Καθορίζει τον συντελεστή κλίμακας για το διάγραμμα φυσαλίδων (μπορεί να είναι μεταξύ 0 και 300 τοις εκατό του προεπιλεγμένου μεγέθους). Αυτή η ιδιότητα είναι μόνο για αυτή τη σειρά αλλά και για όλες τις σειρές της ομάδας γονικής σειράς – είναι προβολή της αντίστοιχης ιδιότητας ομάδας. Συνεπώς η ιδιότητα είναι μόνο ανάγνωση. Χρησιμοποιήστε την ιδιότητα ParentSeriesGroup για πρόσβαση στην ομάδα γονικής σειράς. Χρησιμοποιήστε την ιδιότητα ParentSeriesGroup.BubbleSizeScale για ανάγνωση/εγγραφή για αλλαγή τιμής.

--------------------

Αυτή είναι η προβολή της ιδιότητας ParentSeriesGroup.BubbleSizeScale.

**Επιστρέφει:**
int

### hasUpDownBars() {#hasUpDownBars--}
```
public abstract boolean hasUpDownBars()
```

Καθορίζει εάν το διάγραμμα γραμμής ή κερδών (Stock) έχει γραμμές ανοδικής/καθοδικής κίνησης. Αυτή η ιδιότητα είναι μόνο για αυτή τη σειρά αλλά και για όλες τις σειρές της ομάδας γονικής σειράς – είναι προβολή της αντίστοιχης ιδιότητας ομάδας. Συνεπώς η ιδιότητα είναι μόνο ανάγνωση. Χρησιμοποιήστε την ιδιότητα ParentSeriesGroup για πρόσβαση στην ομάδα γονικής σειράς. Χρησιμοποιήστε την ιδιότητα ParentSeriesGroup.UpDownBars.HasUpDownBars για ανάγνωση/εγγραφή αλλαγή τιμής. Χρησιμοποιήστε την ιδιότητα ParentSeriesGroup.UpDownBars για μορφοποίηση γραμμών ανοδικής/καθοδικής. Μόνο ανάγνωση boolean.

--------------------

Αυτή είναι η προβολή της ιδιότητας ParentSeriesGroup.UpDownBars.HasUpDownBars.

**Επιστρέφει:**
boolean

### getGapWidth() {#getGapWidth--}
```
public abstract int getGapWidth()
```

Καθορίζει το κενό μεταξύ ομάδων μπάρας ή στήλης, ως ποσοστό του πλάτους της μπάρας ή στήλης. Αυτή η ιδιότητα είναι μόνο για αυτή τη σειρά αλλά και για όλες τις σειρές της ομάδας γονικής σειράς – είναι προβολή της αντίστοιχης ιδιότητας ομάδας. Συνεπώς η ιδιότητα είναι μόνο ανάγνωση. Χρησιμοποιήστε την ιδιότητα ParentSeriesGroup για πρόσβαση στην ομάδα γονικής σειράς. Χρησιμοποιήστε την ιδιότητα ParentSeriesGroup.GapWidth για ανάγνωση/εγγραφή αλλαγή τιμής. Μόνο ανάγνωση int.

--------------------

Αυτή είναι η προβολή της ιδιότητας ParentSeriesGroup.GapWidth.

**Επιστρέφει:**
int

### getGapDepth() {#getGapDepth--}
```
public abstract int getGapDepth()
```

Επιστρέφει ή ορίζει την απόσταση, ως ποσοστό του πλάτους του δείκτη, μεταξύ των σειρών δεδομένων σε 3Δ διάγραμμα. Αυτή η ιδιότητα είναι μόνο για αυτή τη σειρά αλλά και για όλες τις σειρές της ομάδας γονικής σειράς – είναι προβολή της αντίστοιχης ιδιότητας ομάδας. Συνεπώς η ιδιότητα είναι μόνο ανάγνωση. Χρησιμοποιήστε την ιδιότητα ParentSeriesGroup για πρόσβαση στην ομάδα γονικής σειράς. Χρησιμοποιήστε την ιδιότητα ParentSeriesGroup.GapDepth για ανάγνωση/εγγραφή αλλαγή τιμής. Μόνο ανάγνωση int.

--------------------

Αυτή είναι η προβολή της ιδιότητας ParentSeriesGroup.GapDepth.

**Επιστρέφει:**
int

### isColorVaried() {#isColorVaried--}
```
public abstract boolean isColorVaried()
```

Καθορίζει ότι κάθε δείκτης δεδομένων στη σειρά έχει διαφορετικό χρώμα. Αυτή η ιδιότητα είναι μόνο για αυτή τη σειρά αλλά και για όλες τις σειρές της ομάδας γονικής σειράς – είναι προβολή της αντίστοιχης ιδιότητας ομάδας. Συνεπώς η ιδιότητα είναι μόνο ανάγνωση. Χρησιμοποιήστε την ιδιότητα ParentSeriesGroup για πρόσβαση στην ομάδα γονικής σειράς. Χρησιμοποιήστε την ιδιότητα ParentSeriesGroup.IsColorVaried για ανάγνωση/εγγραφή αλλαγή τιμής. Μόνο ανάγνωση boolean.

--------------------

Αυτή είναι η προβολή της ιδιότητας ParentSeriesGroup.IsColorVaried.

**Επιστρέφει:**
boolean

### hasSeriesLines() {#hasSeriesLines--}
```
public abstract boolean hasSeriesLines()
```

Καθορίζει εάν υπάρχουν γραμμές σειράς για αυτή τη σειρά και συναφείς σειρές. Αυτή η ιδιότητα είναι μόνο για αυτή τη σειρά αλλά και για όλες τις σειρές της ομάδας γονικής σειράς – είναι προβολή της αντίστοιχης ιδιότητας ομάδας. Συνεπώς η ιδιότητα είναι μόνο ανάγνωση. Χρησιμοποιήστε την ιδιότητα ParentSeriesGroup για πρόσβαση στην ομάδα γονικής σειράς. Χρησιμοποιήστε την ιδιότητα ParentSeriesGroup.HasSeriesLines για ανάγνωση/εγγραφή αλλαγή τιμής. Χρησιμοποιήστε την ιδιότητα ParentSeriesGroup.SeriesLinesFormat για μορφοποίηση γραμμών σειράς. Μόνο ανάγνωση boolean.

--------------------

Αυτή είναι η προβολή της ιδιότητας ParentSeriesGroup.HasSeriesLines.

**Επιστρέφει:**
boolean

### getOverlap() {#getOverlap--}
```
public abstract byte getOverlap()
```

Καθορίζει το πόσο οι μπάρες και στήλες επικαλύπτονται σε 2-Δ διαγράμματα, ως ποσοστό (από -100% έως 100%). Αυτή η ιδιότητα είναι μόνο για αυτή τη σειρά αλλά και για όλες τις σειρές της ομάδας γονικής σειράς. Είναι προβολή της αντίστοιχης ιδιότητας στην ομάδα γονικής σειράς, επομένως η ιδιότητα είναι μόνο ανάγνωση. Για αλλαγή τιμής, χρησιμοποιήστε την ιδιότητα ParentSeriesGroup.Overlap για ανάγνωση/εγγραφή. Μόνο ανάγνωση byte.

--------------------

Η Overlap καθορίζει το βαθμό επικαλύψεως ή απόστασης μεταξύ μπαρ και στηλών ως ποσοστό του πλάτους τους:
- -100%: Μέγιστο κενό (τα μπάρες είναι πλήρως χωρισμένα).
- 0%: Τα μπάρες τοποθετούνται δίπλα δίπλα χωρίς επικαλυψή ή κενό.
- 100%: Μέγιστη επικαλύψή (τα μπάρες αλληλοεπικαλύπτονται πλήρως). Αυτή είναι η προβολή της ιδιότητας ParentSeriesGroup.Overlap.

**Επιστρέφει:**
byte

### getSecondPieSize() {#getSecondPieSize--}
```
public abstract int getSecondPieSize()
```

Καθορίζει το μέγεθος της δεύτερης πίτας ή μπάρας σε διάγραμμα πίτα-στη-πίτα ή μπάρα-στη-πίτα, ως ποσοστό του μεγέθους της πρώτης πίτας (μπορεί να είναι μεταξύ 5 και 200 τοις εκατό). Αυτή η ιδιότητα είναι μόνο για αυτή τη σειρά αλλά και για όλες τις σειρές της ομάδας γονικής σειράς – είναι προβολή της αντίστοιχης ιδιότητας ομάδας. Συνεπώς η ιδιότητα είναι μόνο ανάγνωση. Χρησιμοποιήστε την ιδιότητα ParentSeriesGroup για πρόσβαση στην ομάδα γονικής σειράς. Χρησιμοποιήστε την ιδιότητα ParentSeriesGroup.SecondPieSize για ανάγνωση/εγγραφή αλλαγή τιμής. Μόνο ανάγνωση int.

--------------------

Αυτή είναι η προβολή της ιδιότητας ParentSeriesGroup.SecondPieSize.

**Επιστρέφει:**
int

### getPieSplitPosition() {#getPieSplitPosition--}
```
public abstract double getPieSplitPosition()
```

Καθορίζει μια τιμή που θα χρησιμοποιηθεί για τον καθορισμό των σημείων δεδομένων που βρίσκονται στη δεύτερη πίτα ή μπάρα σε διάγραμμα πίτα-στη-πίτα ή μπάρα-στη-πίτα. Χρησιμοποιείται μαζί με την ιδιότητα PieSplitBy. Αυτή η ιδιότητα είναι μόνο για αυτή τη σειρά αλλά και για όλες τις σειρές της ομάδας γονικής σειράς – είναι προβολή της αντίστοιχης ιδιότητας ομάδας. Συνεπώς η ιδιότητα είναι μόνο ανάγνωση. Χρησιμοποιήστε την ιδιότητα ParentSeriesGroup για πρόσβαση στην ομάδα γονικής σειράς. Χρησιμοποιήστε την ιδιότητα ParentSeriesGroup.PieSplitPosition για ανάγνωση/εγγραφή αλλαγή τιμής. Μόνο ανάγνωση double.

--------------------

Αυτή είναι η προβολή της ιδιότητας ParentSeriesGroup.PieSplitPosition.

**Επιστρέφει:**
double

### getPieSplitBy() {#getPieSplitBy--}
```
public abstract int getPieSplitBy()
```

Καθορίζει πώς να προσδιοριστούν τα σημεία δεδομένων που βρίσκονται στη δεύτερη πίτα ή μπάρα σε διάγραμμα πίτα-στη-πίτα ή μπάρα-στη-πίτα. Αυτή η ιδιότητα είναι μόνο για αυτή τη σειρά αλλά και για όλες τις σειρές της ομάδας γονικής σειράς – είναι προβολή της αντίστοιχης ιδιότητας ομάδας. Συνεπώς η ιδιότητα είναι μόνο ανάγνωση. Χρησιμοποιήστε την ιδιότητα ParentSeriesGroup για πρόσβαση στην ομάδα γονικής σειράς. Χρησιμοποιήστε την ιδιότητα ParentSeriesGroup.PieSplitBy για ανάγνωση/εγγραφή αλλαγή τιμής. Μόνο ανάγνωση [PieSplitType](../../com.aspose.slides/piesplittype).

--------------------

1) Αυτή είναι η προβολή της ιδιότητας ParentSeriesGroup.PieSplitBy. 2) Εάν η τιμή της ιδιότητας είναι PieSplitType.Custom, μπορείτε να ορίσετε προσαρμοσμένες πληροφορίες διαχωρισμού με την ιδιότητα ParentSeriesGroup.PieSplitCustomPoints.

**Επιστρέφει:**
int

### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public abstract byte getDoughnutHoleSize()
```

Καθορίζει το μέγεθος της τρύπας σε διάγραμμα δαχτυλιδιού (μπορεί να είναι μεταξύ 10 και 90 τοις εκατό του μεγέθους της περιοχής σχεδίασης). Αυτή η ιδιότητα δεν αφορά μόνο αυτή τη σειρά αλλά και όλες τις σειρές της ομάδας γονικής σειράς – είναι προβολή της αντίστοιχης ιδιότητας ομάδας. Συνεπώς η ιδιότητα είναι μόνο ανάγνωση. Χρησιμοποιήστε την ιδιότητα ParentSeriesGroup για πρόσβαση στην ομάδα γονικής σειράς. Χρησιμοποιήστε την ιδιότητα ParentSeriesGroup.DoughnutHoleSize για ανάγνωση/εγγραφή αλλαγή τιμής. Μόνο ανάγνωση byte.

--------------------

Αυτή είναι η προβολή της ιδιότητας ParentSeriesGroup.DoughnutHoleSize.

**Επιστρέφει:**
byte

### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public abstract int getFirstSliceAngle()
```

Καθορίζει τη γωνία του πρώτου κομματιού πίτας ή δαχτυλιδιού, σε μοίρες (δεξιόστροφα από το πάνω, από 0 έως 360 μοίρες). Αυτή η ιδιότητα δεν αφορά μόνο αυτή τη σειρά αλλά και όλες τις σειρές της ομάδας γονικής σειράς – είναι προβολή της αντίστοιχης ιδιότητας ομάδας. Συνεπώς η ιδιότητα είναι μόνο ανάγνωση. Χρησιμοποιήστε την ιδιότητα ParentSeriesGroup για πρόσβαση στην ομάδα γονικής σειράς. Χρησιμοποιήστε την ιδιότητα ParentSeriesGroup.FirstSliceAngle για ανάγνωση/εγγραφή αλλαγή τιμής. Μόνο ανάγνωση int.

--------------------

Αυτή είναι η προβολή της ιδιότητας ParentSeriesGroup.FirstSliceAngle.

**Επιστρέφει:**
int

### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public abstract IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

Οι προσαρμοσμένες πληροφορίες διαχωρισμού για διάγραμμα πίτα-στη-πίτα ή μπάρα-στη-πίτα με προσαρμοσμένο διαχωρισμό. Περιέχει σημεία δεδομένων που θα σχεδιαστούν στη δεύτερη πίτα ή μπάρα. Αυτή η ιδιότητα δεν αφορά μόνο αυτή τη σειρά αλλά και όλες τις σειρές της ομάδας γονικής σειράς – είναι προβολή της αντίστοιχης ιδιότητας Μόνο ανάγνωση [IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection).

--------------------

Αυτή είναι η προβολή της ιδιότητας ParentSeriesGroup.PieSplitCustomPoints.

**Επιστρέφει:**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)

### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public abstract int getBubbleSizeRepresentation()
```

Καθορίζει πώς οι τιμές μεγέθους φυσαλίδας παρουσιάζονται στο διάγραμμα φυσαλίδων. Αυτή η ιδιότητα δεν αφορά μόνο αυτή τη σειρά αλλά και όλες τις σειρές της ομάδας γονικής σειράς – είναι προβολή της αντίστοιχης ιδιότητας. Συνεπώς η ιδιότητα είναι μόνο ανάγνωση. Χρησιμοποιήστε την ιδιότητα ParentSeriesGroup για πρόσβαση στην ομάδα γονικής σειράς. Χρησιμοποιήτε την ιδιότητα ParentSeriesGroup.BubbleSizeRepresentation για ανάγνωση/εγγραφή αλλαγή τιμής.

--------------------

Αυτή είναι η προβολή της ιδιότητας ParentSeriesGroup.BubbleSizeRepresentation.

**Επιστρέφει:**
int