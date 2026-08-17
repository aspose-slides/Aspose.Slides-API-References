---
title: IChartSeries
second_title: Αναφορά API του Aspose.Slides για Java
description: Αντιπροσωπεύει μια σειρά διαγράμματος.
type: docs
url: /el/com.aspose.slides/ichartseries/
---
**All Implemented Interfaces:**  
[com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IChartSeries extends IChartComponent
```

Represents a chart series.  
## Methods

| Method | Description |
| --- | --- |
| [getExplosion()](#getExplosion--) | Η απόσταση ενός ανοικτού κομματιού πίτας από το κέντρο του διαγράμματος πίτας εκφράζεται ως ποσοστό της διαμέτρου της πίτας. |
| [setExplosion(int value)](#setExplosion-int-) | Η απόσταση ενός ανοικτού κομματιού πίτας από το κέντρο του διαγράμματος πίτας εκφράζεται ως ποσοστό της διαμέτρου της πίτας. |
| [getSmooth()](#getSmooth--) | Αναπαριστά την εξομάλυνση καμπυλών. |
| [setSmooth(boolean value)](#setSmooth-boolean-) | Αναπαριστά την εξομάλυνση καμπυλών. |
| [getMarker()](#getMarker--) | Επιστρέφει το δείκτη σειράς. |
| [getBar3DShape()](#getBar3DShape--) | Καθορίζει το σχήμα μιας σειράς σε διάγραμμα 3Δ μπάρας. |
| [setBar3DShape(int value)](#setBar3DShape-int-) | Καθορίζει το σχήμα μιας σειράς σε διάγραμμα 3Δ μπάρας. |
| [getName()](#getName--) | Επιστρέφει το όνομα της σειράς. |
| [getDataPoints()](#getDataPoints--) | Επιστρέφει τη συλλογή των σημείων δεδομένων αυτής της σειράς. |
| [getType()](#getType--) | Επιστρέφει έναν τύπο αυτής της σειράς. |
| [setType(int value)](#setType-int-) | Επιστρέφει έναν τύπο αυτής της σειράς. |
| [getParentSeriesGroup()](#getParentSeriesGroup--) | Επιστρέφει την γονική ομάδα σειρών. |
| [getFormat()](#getFormat--) | Επιστρέφει τη μορφοποίηση μιας σειράς. |
| [getOrder()](#getOrder--) | Επιστρέφει τη σειρά μιας σειράς. |
| [setOrder(int value)](#setOrder-int-) | Επιστρέφει τη σειρά μιας σειράς. |
| [getLabels()](#getLabels--) | Επιστρέφει τις Labels μιας σειράς. |
| [getTrendLines()](#getTrendLines--) | Συλλογή των γραμμών τάσης σειράς Μόνο για ανάγνωση [ITrendlineCollection](../../com.aspose.slides/itrendlinecollection). |
| [getErrorBarsXFormat()](#getErrorBarsXFormat--) | Αναπαριστά τις ErrorBars της σειράς με κατεύθυνση X. |
| [getErrorBarsYFormat()](#getErrorBarsYFormat--) | Αναπαριστά τις ErrorBars της σειράς με κατεύθυνση Y. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | Δείχνει αν αυτή η σειρά είναι σχεδιασμένη σε δευτερεύον άξονα τιμών. |
| [setPlotOnSecondAxis(boolean value)](#setPlotOnSecondAxis-boolean-) | Δείχνει αν αυτή η σειρά είναι σχεδιασμένη σε δευτερεύον άξονα τιμών. |
| [getNumberFormatOfValues()](#getNumberFormatOfValues--) | Επιστρέφει ή ορίζει τη μορφή αριθμού για τις τιμές της σειράς. |
| [setNumberFormatOfValues(String value)](#setNumberFormatOfValues-java.lang.String-) | Επιστρέφει ή ορίζει τη μορφή αριθμού για τις τιμές της σειράς. |
| [getNumberFormatOfXValues()](#getNumberFormatOfXValues--) | Επιστρέφει ή ορίζει τη μορφή αριθμού για τις τιμές x της σειράς. |
| [setNumberFormatOfXValues(String value)](#setNumberFormatOfXValues-java.lang.String-) | Επιστρέφει ή ορίζει τη μορφή αριθμού για τις τιμές x της σειράς. |
| [getNumberFormatOfYValues()](#getNumberFormatOfYValues--) | Επιστρέφει ή ορίζει τη μορφή αριθμού για τις τιμές y της σειράς. |
| [setNumberFormatOfYValues(String value)](#setNumberFormatOfYValues-java.lang.String-) | Επιστρέφει ή ορίζει τη μορφή αριθμού για τις τιμές y της σειράς. |
| [getNumberFormatOfBubbleSizes()](#getNumberFormatOfBubbleSizes--) | Επιστρέφει ή ορίζει τη μορφή αριθμού για τα μεγέθη φυσαλίδων της σειράς. |
| [setNumberFormatOfBubbleSizes(String value)](#setNumberFormatOfBubbleSizes-java.lang.String-) | Επιστρέφει ή ορίζει τη μορφή αριθμού για τα μεγέθη φυσαλίδων της σειράς. |
| [getInvertIfNegative()](#getInvertIfNegative--) | Καθορίζει ότι η σειρά τύπου μπάρα, στήλη ή φούσκα θα αντιστρέψει τα χρώματά της εάν η τιμή είναι αρνητική. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | Καθορίζει ότι η σειρά τύπου μπάρα, στήλη ή φούσκα θα αντιστρέψει τα χρώματά της εάν η τιμή είναι αρνητική. |
| [getInvertedSolidFillColor()](#getInvertedSolidFillColor--) | Καθορίζει την αντιστροφή του συμπαγούς χρώματος για τη σειρά. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Αναπαριστά την καταχώρηση υπομνήματος σχετική με αυτή τη σειρά Μόνο για ανάγνωση [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties). |
| [getAutomaticSeriesColor()](#getAutomaticSeriesColor--) | Επιστρέφει αυτόματο χρώμα σειράς βάσει του δείκτη σειράς και του στυλ γραφήματος. |
| [getShowInnerPoints()](#getShowInnerPoints--) | Αναπαριστά εσωτερικά σημεία. |
| [setShowInnerPoints(boolean value)](#setShowInnerPoints-boolean-) | Αναπαριστά εσωτερικά σημεία. |
| [getShowOutlierPoints()](#getShowOutlierPoints--) | Αναπαριστά ακραίες τιμές. |
| [setShowOutlierPoints(boolean value)](#setShowOutlierPoints-boolean-) | Αναπαριστά ακραίες τιμές. |
| [getShowMeanMarkers()](#getShowMeanMarkers--) | Αναπαριστά δείκτες μέσου όρου. |
| [setShowMeanMarkers(boolean value)](#setShowMeanMarkers-boolean-) | Αναπαριστά δείκτες μέσου όρου. |
| [getShowMeanLine()](#getShowMeanLine--) | Αναπαριστά δείκτες μέσου όρου. |
| [setShowMeanLine(boolean value)](#setShowMeanLine-boolean-) | Αναπαριστά δείκτες μέσου όρου. |
| [getQuartileMethod()](#getQuartileMethod--) | Αναπαριστά τη μέθοδο τεταρτημόριου. |
| [setQuartileMethod(int value)](#setQuartileMethod-int-) | Αναπαριστά τη μέθοδο τεταρτημόριου. |
| [getShowConnectorLines()](#getShowConnectorLines--) | Αναπαριστά γραμμές σύνδεσης. |
| [setShowConnectorLines(boolean value)](#setShowConnectorLines-boolean-) | Αναπαριστά γραμμές σύνδεσης. |
| [getParentLabelLayout()](#getParentLabelLayout--) | Αναπαριστά τη διάταξη των ετικετών γονικής κατηγορίας. |
| [setParentLabelLayout(int value)](#setParentLabelLayout-int-) | Αναπαριστά τη διάταξη των ετικετών γονικής κατηγορίας. |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | Καθορίζει τον συντελεστή κλίμακας για το διάγραμμα φυσαλίδων (μπορεί να είναι μεταξύ 0 και 300 τοις εκατό του προεπιλεγμένου μεγέθους). |
| [hasUpDownBars()](#hasUpDownBars--) | Καθορίζει εάν το γράφημα Γραμμής ή Απόθεσης έχει μπάρες άνω/κάτω. |
| [getGapWidth()](#getGapWidth--) | Καθορίζει το κενό μεταξύ ομάδων μπαρά ή στήλης, ως ποσοστό του πλάτους της μπαρά ή στήλης. |
| [getGapDepth()](#getGapDepth--) | Επιστρέφει ή ορίζει την απόσταση, ως ποσοστό του πλάτους του δείκτη, μεταξύ των σειρών δεδομένων σε διάγραμμα 3Δ. |
| [isColorVaried()](#isColorVaried--) | Καθορίζει ότι κάθε σημείο δεδομένων στη σειρά έχει διαφορετικό χρώμα. |
| [hasSeriesLines()](#hasSeriesLines--) | Καθορίζει εάν υπάρχουν γραμμές σειράς για αυτή τη σειρά και τις σχετικές σειρές. |
| [getOverlap()](#getOverlap--) | Καθορίζει πόσο επικάνονται οι μπάρες και στήλες σε 2Δ διαγράμματα, ως ποσοστό (από -100% έως 100%). |
| [getSecondPieSize()](#getSecondPieSize--) | Καθορίζει το μέγεθος του δεύτερου κομματιού πίτας ή μπάρας σε διάγραμμα πίτα-επί-πίτα ή μπάρα-επί-πίτα, ως ποσοστό του μεγέθους της πρώτης πίτας (μπορεί να είναι μεταξύ 5 και 200 τοις εκατό). |
| [getPieSplitPosition()](#getPieSplitPosition--) | Καθορίζει μια τιμή που θα χρησιμοποιηθεί για τον καθορισμό των σημείων δεδομένων που βρίσκονται στο δεύτερο κομμάτι πίτας ή μπάρας σε διάγραμμα πίτα-επί-πίτα ή μπάρα-επί-πίτα. |
| [getPieSplitBy()](#getPieSplitBy--) | Καθορίζει πώς να καθοριστούν τα σημεία δεδομένων που βρίσκονται στο δεύτερο κομμάτι πίτας ή μπάρας σε διάγραμμα πίτα-επί-πίτα ή μπάρα-επί-πίτα. |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | Καθορίζει το μέγεθος της τρύπας σε διάγραμμα δακτυλίου (μπορεί να είναι μεταξύ 10 και 90 τοις εκατό του μεγέθους της περιοχής σχεδίασης). |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | Καθορίζει τη γωνία του πρώτου κομματιού πίτας ή δακτυλίου, σε μοίρες (δεξιόστροφα από την κορυφή, από 0 έως 360 μοίρες). |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | Οι προσαρμοσμένες πληροφορίες διαχωρισμού για διάγραμμα πίτα-επί-πίτα ή μπάρα-επί-πίτα με προσαρμοσμένο διαχωρισμό. |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | Καθορίζει πώς αντιπροσωπεύονται οι τιμές μεγέθους φυσαλίδων στο διάγραμμα φυσαλίδων. |
### getExplosion() {#getExplosion--}
```
public abstract int getExplosion()
```

Η απόσταση ενός ανοικτού κομματιού πίτας από το κέντρο του διαγράμματος πίτας εκφράζεται ως ποσοστό της διαμέτρου της πίτας. Ανάγνωση/εγγραφή int.

**Returns:**  
int
### setExplosion(int value) {#setExplosion-int-}
```
public abstract void setExplosion(int value)
```

Η απόσταση ενός ανοικτού κομματιού πίτας από το κέντρο του διαγράμματος πίτας εκφράζεται ως ποσοστό της διαμέτρου της πίτας. Ανάγνωση/εγγραφή int.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getSmooth() {#getSmooth--}
```
public abstract boolean getSmooth()
```

Αναπαριστά την εξομάλυνση καμπυλών. True if curve smoothing is turned on for the line chart or scatter chart. Applies only to line and scatter connected by lines charts. Ανάγνωση/εγγραφή boolean.

**Returns:**  
boolean
### setSmooth(boolean value) {#setSmooth-boolean-}
```
public abstract void setSmooth(boolean value)
```

Αναπαριστά την εξομάλυνση καμπυλών. True if curve smoothing is turned on for the line chart or scatter chart. Applies only to line and scatter connected by lines charts. Ανάγνωση/εγγραφή boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getMarker() {#getMarker--}
```
public abstract IMarker getMarker()
```

Επιστρέφει το δείκτη σειράς. Μόνο για ανάγνωση [IMarker](../../com.aspose.slides/imarker).

**Returns:**  
[IMarker](../../com.aspose.slides/imarker)
### getBar3DShape() {#getBar3DShape--}
```
public abstract int getBar3DShape()
```

Καθορίζει το σχήμα μιας σειράς σε διάγραμμα 3Δ μπάρας. Changing of value of this property can cause to automatically changing Type of series. Ανάγνωση/εγγραφή [ChartShapeType](../../com.aspose.slides/chartshapetype).

**Returns:**  
int
### setBar3DShape(int value) {#setBar3DShape-int-}
```
public abstract void setBar3DShape(int value)
```

Καθορίζει το σχήμα μιας σειράς σε διάγραμμα 3Δ μπάρας. Changing of value of this property can cause to automatically changing Type of series. Ανάγνωση/εγγραφή [ChartShapeType](../../com.aspose.slides/chartshapetype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getName() {#getName--}
```
public abstract IStringChartValue getName()
```

Επιστρέφει το όνομα της σειράς. Μόνο για ανάγνωση [IStringChartValue](../../com.aspose.slides/istringchartvalue).

**Returns:**  
[IStringChartValue](../../com.aspose.slides/istringchartvalue)
### getDataPoints() {#getDataPoints--}
```
public abstract IChartDataPointCollection getDataPoints()
```

Επιστρέφει τη συλλογή των σημείων δεδομένων αυτής της σειράς. Μόνο για ανάγνωση [IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection).

**Returns:**  
[IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection)
### getType() {#getType--}
```
public abstract int getType()
```

Επιστρέφει έναν τύπο αυτής της σειράς. Ανάγνωση/εγγραφή [ChartType](../../com.aspose.slides/charttype).

**Returns:**  
int
### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```

Επιστρέφει έναν τύπο αυτής της σειράς. Ανάγνωση/εγγραφή [ChartType](../../com.aspose.slides/charttype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getParentSeriesGroup() {#getParentSeriesGroup--}
```
public abstract IChartSeriesGroup getParentSeriesGroup()
```

Επιστρέφει την γονική ομάδα σειρών. Μόνο για ανάγνωση [IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup).

**Returns:**  
[IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup)
### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Επιστρέφει τη μορφοποίηση μιας σειράς. Μόνο για ανάγνωση [IFormat](../../com.aspose.slides/iformat).

**Returns:**  
[IFormat](../../com.aspose.slides/iformat)
### getOrder() {#getOrder--}
```
public abstract int getOrder()
```

Επιστρέφει τη σειρά μιας σειράς. Ανάγνωση/εγγραφή int.

**Returns:**  
int
### setOrder(int value) {#setOrder-int-}
```
public abstract void setOrder(int value)
```

Επιστρέφει τη σειρά μιας σειράς. Ανάγνωση/εγγραφή int.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getLabels() {#getLabels--}
```
public abstract IDataLabelCollection getLabels()
```

Επιστρέφει τις Labels μιας σειράς. Μόνο για ανάγνωση [IDataLabelCollection](../../com.aspose.slides/idatalabelcollection).

**Returns:**  
[IDataLabelCollection](../../com.aspose.slides/idatalabelcollection)
### getTrendLines() {#getTrendLines--}
```
public abstract ITrendlineCollection getTrendLines()
```

Συλλογή των γραμμών τάσης σειράς Μόνο για ανάγνωση [ITrendlineCollection](../../com.aspose.slides/itrendlinecollection).

**Returns:**  
[ITrendlineCollection](../../com.aspose.slides/itrendlinecollection)
### getErrorBarsXFormat() {#getErrorBarsXFormat--}
```
public abstract IErrorBarsFormat getErrorBarsXFormat()
```

Αναπαριστά τις ErrorBars της σειράς με κατεύθυνση X. Μόνο για ανάγνωση [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat).

--------------------

ErrorBars with X direction are avalible for series of type area, bar, scatter and bubble. For any other types of chart this property returns null (including 3D charts). In case of custom values use DataPoints collection to specify value (with ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)) property).

**Returns:**  
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)
### getErrorBarsYFormat() {#getErrorBarsYFormat--}
```
public abstract IErrorBarsFormat getErrorBarsYFormat()
```

Αναπαριστά τις ErrorBars της σειράς με κατεύθυνση Y. Μόνο για ανάγνωση [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat).

--------------------

ErrorBars with Y direction are avalible for series of type area, bar, line, scatter and bubble. For any other types of chart this property returns null (including 3D charts). In case of custom values use DataPoints collection to specify value (with ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)) property).

**Returns:**  
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)
### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public abstract boolean getPlotOnSecondAxis()
```

Δείχνει αν αυτή η σειρά είναι σχεδιασμένη σε δευτερεύον άξονα τιμών. Ανάγνωση/εγγραφή boolean.

**Returns:**  
boolean
### setPlotOnSecondAxis(boolean value) {#setPlotOnSecondAxis-boolean-}
```
public abstract void setPlotOnSecondAxis(boolean value)
```

Δείχνει αν αυτή η σειρά είναι σχεδιασμένη σε δευτερεύον άξονα τιμών. Ανάγνωση/εγγραφή boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getNumberFormatOfValues() {#getNumberFormatOfValues--}
```
public abstract String getNumberFormatOfValues()
```

Επιστρέφει ή ορίζει τη μορφή αριθμού για τις τιμές της σειράς. Ανάγνωση/εγγραφή String.

**Returns:**  
java.lang.String
### setNumberFormatOfValues(String value) {#setNumberFormatOfValues-java.lang.String-}
```
public abstract void setNumberFormatOfValues(String value)
```

Επιστρέφει ή ορίζει τη μορφή αριθμού για τις τιμές της σειράς. Ανάγνωση/εγγραφή String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |
### getNumberFormatOfXValues() {#getNumberFormatOfXValues--}
```
public abstract String getNumberFormatOfXValues()
```

Επιστρέφει ή ορίζει τη μορφή αριθμού για τις τιμές x της σειράς. Ανάγνωση/εγγραφή String.

**Returns:**  
java.lang.String
### setNumberFormatOfXValues(String value) {#setNumberFormatOfXValues-java.lang.String-}
```
public abstract void setNumberFormatOfXValues(String value)
```

Επιστρέφει ή ορίζει τη μορφή αριθμού για τις τιμές x της σειράς. Ανάγνωση/εγγραφή String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |
### getNumberFormatOfYValues() {#getNumberFormatOfYValues--}
```
public abstract String getNumberFormatOfYValues()
```

Επιστρέφει ή ορίζει τη μορφή αριθμού για τις τιμές y της σειράς. Ανάγνωση/εγγραφή String.

**Returns:**  
java.lang.String
### setNumberFormatOfYValues(String value) {#setNumberFormatOfYValues-java.lang.String-}
```
public abstract void setNumberFormatOfYValues(String value)
```

Επιστρέφει ή ορίζει τη μορφή αριθμού για τις τιμές y της σειράς. Ανάγνωση/εγγραφή String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |
### getNumberFormatOfBubbleSizes() {#getNumberFormatOfBubbleSizes--}
```
public abstract String getNumberFormatOfBubbleSizes()
```

Επιστρέφει ή ορίζει τη μορφή αριθμού για τα μεγέθη φυσαλίδων της σειράς. Ανάγνωση/εγγραφή String.

**Returns:**  
java.lang.String
### setNumberFormatOfBubbleSizes(String value) {#setNumberFormatOfBubbleSizes-java.lang.String-}
```
public abstract void setNumberFormatOfBubbleSizes(String value)
```

Επιστρέφει ή ορίζει τη μορφή αριθμού για τα μεγέθη φυσαλίδων της σειράς. Ανάγνωση/εγγραφή String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |
### getInvertIfNegative() {#getInvertIfNegative--}
```
public abstract boolean getInvertIfNegative()
```

Καθορίζει ότι η σειρά τύπου μπάρα, στήλη ή φούσκα θα αντιστρέψει τα χρώματά της εάν η τιμή είναι αρνητική. Ανάγνωση/εγγραφή boolean.

**Returns:**  
boolean
### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public abstract void setInvertIfNegative(boolean value)
```

Καθορίζει ότι η σειρά τύπου μπάρα, στήλη ή φούσκα θα αντιστρέψει τα χρώματά της εάν η τιμή είναι αρνητική. Ανάγνωση/εγγραφή boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getInvertedSolidFillColor() {#getInvertedSolidFillColor--}
```
public abstract IColorFormat getInvertedSolidFillColor()
```

Καθορίζει την αντιστροφή του συμπαγούς χρώματος για τη σειρά. To apply color setting set series format FillType to FillType.Solid. Ανάγνωση/εγγραφή [IColorFormat](../../com.aspose.slides/icolorformat).

**Returns:**  
[IColorFormat](../../com.aspose.slides/icolorformat)
### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public abstract ILegendEntryProperties getRelatedLegendEntry()
```

Αναπαριστά την καταχώρηση υπομνήματος σχετική με αυτή τη σειρά Μόνο για ανάγνωση [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**Returns:**  
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)
### getAutomaticSeriesColor() {#getAutomaticSeriesColor--}
```
public abstract Color getAutomaticSeriesColor()
```
Επιστρέφει ένα αυτόματο χρώμα σειράς βασισμένο στον δείκτη σειράς και στο στυλ διαγράμματος. Αυτό το χρώμα χρησιμοποιείται από προεπιλογή εάν FillType είναι ίσο με NotDefined.

**Επιστρέφει:**
java.awt.Color - Αυτόματο χρώμα σειράς java.awt.Color
### getShowInnerPoints() {#getShowInnerPoints--}
```
public abstract boolean getShowInnerPoints()
```

Αντιπροσωπεύει εσωτερικά σημεία. Αληθές εάν τα εσωτερικά σημεία εμφανίζονται στο διάγραμμα BoxAndWhisker. Ισχύει μόνο για διαγράμματα BoxAndWhisker. Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**
boolean
### setShowInnerPoints(boolean value) {#setShowInnerPoints-boolean-}
```
public abstract void setShowInnerPoints(boolean value)
```

Αντιπροσωπεύει εσωτερικά σημεία. Αληθές εάν τα εσωτερικά σημεία εμφανίζονται στο διάγραμμα BoxAndWhisker. Ισχύει μόνο για διαγράμματα BoxAndWhisker. Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getShowOutlierPoints() {#getShowOutlierPoints--}
```
public abstract boolean getShowOutlierPoints()
```

Αντιπροσωπεύει σημεία εκτός τάσης. Αληθές εάν τα σημεία εκτός τάσης εμφανίζονται στο διάγραμμα BoxAndWhisker. Ισχύει μόνο για διαγράμματα BoxAndWhisker. Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**
boolean
### setShowOutlierPoints(boolean value) {#setShowOutlierPoints-boolean-}
```
public abstract void setShowOutlierPoints(boolean value)
```

Αντιπροσωπεύει σημεία εκτός τάσης. Αληθές εάν τα σημεία εκτός τάσης εμφανίζονται στο διάγραμμα BoxAndWhisker. Ισχύει μόνο για διαγράμματα BoxAndWhisker. Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getShowMeanMarkers() {#getShowMeanMarkers--}
```
public abstract boolean getShowMeanMarkers()
```

Αντιπροσωπεύει δείκτες μέσου όρου. Αληθές εάν οι δείκτες μέσου όρου εμφανίζονται στο διάγραμμα BoxAndWhisker. Ισχύει μόνο για διαγράμματα BoxAndWhisker. Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**
boolean
### setShowMeanMarkers(boolean value) {#setShowMeanMarkers-boolean-}
```
public abstract void setShowMeanMarkers(boolean value)
```

Αντιπροσωπεύει δείκτες μέσου όρου. Αληθές εάν οι δείκτες μέσου όρου εμφανίζονται στο διάγραμμα BoxAndWhisker. Ισχύει μόνο για διαγράμματα BoxAndWhisker. Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getShowMeanLine() {#getShowMeanLine--}
```
public abstract boolean getShowMeanLine()
```

Αντιπροσωπεύει δείκτες μέσου όρου. Αληθές εάν η γραμμή μέσου είναι εμφανής στο διάγραμμα BoxAndWhisker. Ισχύει μόνο για διαγράμματα BoxAndWhisker. Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**
boolean
### setShowMeanLine(boolean value) {#setShowMeanLine-boolean-}
```
public abstract void setShowMeanLine(boolean value)
```

Αντιπροσωπεύει δείκτες μέσου όρου. Αληθές εάν η γραμμή μέσου είναι εμφανής στο διάγραμμα BoxAndWhisker. Ισχύει μόνο για διαγράμματα BoxAndWhisker. Ανάγνωση/εγγραφή boolean.

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

Καθορίζει το συντελεστή κλίμακας για το διάγραμμα φυσαλίδων (μπορεί να είναι μεταξύ 0 και 300 τοις εκατό του προεπιλεγμένου μεγέθους). Αυτό δεν είναι μόνο ιδιότητα αυτής της σειράς αλλά και όλων των σειρών της γονικής ομάδας σειρών – είναι προβολή της αντίστοιχης ιδιότητας ομάδας. Αυτή η ιδιότητα είναι μόνο για ανάγνωση. Χρησιμοποιήστε την ιδιότητα ParentSeriesGroup για πρόσβαση στη γονική ομάδα σειρών. Χρησιμοποιήστε την ιδιότητα ParentSeriesGroup.BubbleSizeScale για ανάγνωση/εγγραφή προκειμένου να αλλάξετε την τιμή.

--------------------

Αυτή είναι η προβολή της ιδιότητας ParentSeriesGroup.BubbleSizeScale.

**Επιστρέφει:**
int
### hasUpDownBars() {#hasUpDownBars--}
```
public abstract boolean hasUpDownBars()
```

Καθορίζει εάν το διάγραμμα Line ή Stock έχει μπαρ πάνω/κάτω. Αυτό δεν είναι μόνο ιδιότητα αυτής της σειράς αλλά και όλων των σειρών της γονικής ομάδας σειρών – είναι προβολή της αντίστοιχης ιδιότητας ομάδας. Αυτή η ιδιότητα είναι μόνο για ανάγνωση. Χρησιμοποιήστε την ιδιότητα ParentSeriesGroup για πρόσβαση στη γονική ομάδα σειρών. Χρησιμοποιήστε την ιδιότητα ParentSeriesGroup.UpDownBars.HasUpDownBars για ανάγνωση/εγγραφή προκειμένου να αλλάξετε την τιμή. Χρησιμοποιήστε την ιδιότητα ParentSeriesGroup.UpDownBars για μορφοποίηση των μπαρ πάνω/κάτω. Μόνο για ανάγνωση boolean.

--------------------

Αυτή είναι η προβολή της ιδιότητας ParentSeriesGroup.UpDownBars.HasUpDownBars.

**Επιστρέφει:**
boolean
### getGapWidth() {#getGapWidth--}
```
public abstract int getGapWidth()
```

Καθορίζει το κενό μεταξύ ομάδων μπαρ ή στηλών, ως ποσοστό του πλάτους του μπαρ ή της στήλης. Αυτό δεν είναι μόνο ιδιότητα αυτής της σειράς αλλά και όλων των σειρών της γονικής ομάδας σειρών – είναι προβολή της αντίστοιχης ιδιότητας ομάδας. Αυτή η ιδιότητα είναι μόνο για ανάγνωση. Χρησιμοποιήστε την ιδιότητα ParentSeriesGroup για πρόσβαση στη γονική ομάδα σειρών. Χρησιμοποιήστε την ιδιότητα ParentSeriesGroup.GapWidth για ανάγνωση/εγγραφή προκειμένου να αλλάξετε την τιμή. Μόνο για ανάγνωση int.

--------------------

Αυτή είναι η προβολή της ιδιότητας ParentSeriesGroup.GapWidth.

**Επιστρέφει:**
int
### getGapDepth() {#getGapDepth--}
```
public abstract int getGapDepth()
```

Επιστρέφει ή ορίζει την απόσταση, ως ποσοστό του πλάτους του δείκτη, μεταξύ των σειρών δεδομένων σε 3D διάγραμμα. Αυτό δεν είναι μόνο ιδιότητα αυτής της σειράς αλλά και όλων των σειρών της γονικής ομάδας σειρών – είναι προβολή της αντίστοιχης ιδιότητας ομάδας. Αυτή η ιδιότητα είναι μόνο για ανάγνωση. Χρησιμοποιήστε την ιδιότητα ParentSeriesGroup για πρόσβαση στη γονική ομάδα σειρών. Χρησιμοποιήστε την ιδιότητα ParentSeriesGroup.GapDepth για ανάγνωση/εγγραφή προκειμένου να αλλάξετε την τιμή. Μόνο για ανάγνωση int.

--------------------

Αυτή είναι η προβολή της ιδιότητας ParentSeriesGroup.GapDepth.

**Επιστρέφει:**
int
### isColorVaried() {#isColorVaried--}
```
public abstract boolean isColorVaried()
```

Καθορίζει ότι κάθε δείκτη δεδομένων στη σειρά έχει διαφορετικό χρώμα. Αυτό δεν είναι μόνο ιδιότητα αυτής της σειράς αλλά και όλων των σειρών της γονικής ομάδας σειρών – είναι προβολή της αντίστοιχης ιδιότητας ομάδας. Αυτή η ιδιότητα είναι μόνο για ανάγνωση. Χρησιμοποιήστε την ιδιότητα ParentSeriesGroup για πρόσβαση στη γονική ομάδα σειρών. Χρησιμοποιήστε την ιδιότητα ParentSeriesGroup.IsColorVaried για ανάγνωση/εγγραφή προκειμένου να αλλάξετε την τιμή. Μόνο για ανάγνωση boolean.

--------------------

Αυτή είναι η προβολή της ιδιότητας ParentSeriesGroup.IsColorVaried.

**Επιστρέφει:**
boolean
### hasSeriesLines() {#hasSeriesLines--}
```
public abstract boolean hasSeriesLines()
```

Καθορίζει εάν υπάρχουν γραμμές σειράς για αυτή τη σειρά και τις συγγενείς σειρές. Αυτό δεν είναι μόνο ιδιότητα αυτής της σειράς αλλά και όλων των σειρών της γονικής ομάδας σειρών – είναι προβολή της αντίστοιχης ιδιότητας ομάδας. Αυτή η ιδιότητα είναι μόνο για ανάγνωση. Χρησιμοποιήστε την ιδιότητα ParentSeriesGroup για πρόσβαση στη γονική ομάδα σειρών. Χρησιμοποιήστε την ιδιότητα ParentSeriesGroup.HasSeriesLines για ανάγνωση/εγγραφή προκειμένου να αλλάξετε την τιμή. Χρησιμοποιήστε την ιδιότητα ParentSeriesGroup.SeriesLinesFormat για μορφοποίηση των γραμμών σειράς. Μόνο για ανάγνωση boolean.

--------------------

Αυτή είναι η προβολή της ιδιότητας ParentSeriesGroup.HasSeriesLines.

**Επιστρέφει:**
boolean
### getOverlap() {#getOverlap--}
```
public abstract byte getOverlap()
```

Καθορίζει πόσο τα μπαρ και οι στήλες επικαλύπτονται σε 2-Δ διαγράμματα, ως ποσοστό (από -100% έως 100%). Αυτό δεν είναι μόνο ιδιότητα αυτής της σειράς αλλά και όλων των σειρών της γονικής ομάδας σειρών. Είναι προβολή της αντίστοιχης ιδιότητας στη γονική ομάδα σειρών, και έτσι αυτή η ιδιότητα είναι μόνο για ανάγνωση. Για αλλαγή της τιμής, χρησιμοποιήστε την ιδιότητα ParentSeriesGroup.Overlap για ανάγνωση/εγγραφή. Μόνο για ανάγνωση byte.

--------------------

Το Overlap καθορίζει το βαθμό επικαλύψεως ή απόστασης μεταξύ μπαρ και στηλών ως ποσοστό του πλάτους τους:
- -100%: Μέγιστη απόσταση (τα μπαρ είναι εντελώς ξεχωριστά).
- 0%: Τα μπαρ τοποθετούνται δίπλα-δίπλα χωρίς επικαλύψεις ή αποστάσεις.
- 100%: Μέγιστη επικάλυψη (τα μπαρ επικαλύπτουν πλήρως το ένα το άλλο). Αυτή είναι η προβολή της ιδιότητας ParentSeriesGroup.Overlap.

**Επιστρέφει:**
byte
### getSecondPieSize() {#getSecondPieSize--}
```
public abstract int getSecondPieSize()
```

Καθορίζει το μέγεθος του δεύτερου κύκλου ή μπαρ ενός διαγράμματος pie-of-pie ή bar-of-pie, ως ποσοστό του μεγέθους του πρώτου κύκλου (μπορεί να είναι μεταξύ 5 και 200 τοις εκατό). Αυτό δεν είναι μόνο ιδιότητα αυτής της σειράς αλλά και όλων των σειρών της γονικής ομάδας σειρών – είναι προβολή της αντίστοιχης ιδιότητας ομάδας. Αυτή η ιδιότητα είναι μόνο για ανάγνωση. Χρησιμοποιήστε την ιδιότητα ParentSeriesGroup για πρόσβαση στη γονική ομάδα σειρών. Χρησιμοποιήστε την ιδιότητα ParentSeriesGroup.SecondPieSize για ανάγνωση/εγγραφή προκειμένου να αλλάξετε την τιμή. Μόνο για ανάγνωση int.

--------------------

Αυτή είναι η προβολή της ιδιότητας ParentSeriesGroup.SecondPieSize.

**Επιστρέφει:**
int
### getPieSplitPosition() {#getPieSplitPosition--}
```
public abstract double getPieSplitPosition()
```

Καθορίζει μια τιμή που θα χρησιμοποιηθεί για τον προσδιορισμό του ποιου σημείου δεδομένων ανήκει στο δεύτερο κύκλο ή μπαρ σε διάγραμμα pie-of-pie ή bar-of-pie. Χρησιμοποιείται μαζί με την ιδιότητα PieSplitBy. Αυτό δεν είναι μόνο ιδιότητα αυτής της σειράς αλλά και όλων των σειρών της γονικής ομάδας σειρών – είναι προβολή της αντίστοιχης ιδιότητας ομάδας. Αυτή η ιδιότητα είναι μόνο για ανάγνωση. Χρησιμοποιήστε την ιδιότητα ParentSeriesGroup για πρόσβαση στη γονική ομάδα σειρών. Χρησιμοποιήστε την ιδιότητα ParentSeriesGroup.PieSplitPosition για ανάγνωση/εγγραφή προκειμένου να αλλάξετε την τιμή. Μόνο για ανάγνωση double.

--------------------

Αυτή είναι η προβολή της ιδιότητας ParentSeriesGroup.PieSplitPosition.

**Επιστρέφει:**
double
### getPieSplitBy() {#getPieSplitBy--}
```
public abstract int getPieSplitBy()
```

Καθορίζει πώς θα προσδιοριστεί ποια σημεία δεδομένων ανήκουν στο δεύτερο κύκλο ή μπαρ σε διάγραμμα pie-of-pie ή bar-of-pie. Αυτό δεν είναι μόνο ιδιότητα αυτής της σειράς αλλά και όλων των σειρών της γονικής ομάδας σειρών – είναι προβολή της αντίστοιχης ιδιότητας ομάδας. Αυτή η ιδιότητα είναι μόνο για ανάγνωση. Χρησιμοποιήστε την ιδιότητα ParentSeriesGroup για πρόσβαση στη γονική ομάδα σειρών. Χρησιμοποιήστε την ιδιότητα ParentSeriesGroup.PieSplitBy για ανάγνωση/εγγραφή προκειμένου να αλλάξετε την τιμή. Μόνο για ανάγνωση [PieSplitType](../../com.aspose.slides/piesplittype).

--------------------

1) Αυτή είναι η προβολή της ιδιότητας ParentSeriesGroup.PieSplitBy. 2) Εάν η τιμή της ιδιότητας είναι PieSplitType.Custom, μπορείτε να ορίσετε προσαρμοσμένες πληροφορίες διαχωρισμού με την ιδιότητα ParentSeriesGroup.PieSplitCustomPoints.

**Επιστρέφει:**
int
### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public abstract byte getDoughnutHoleSize()
```

Καθορίζει το μέγεθος της τρύπας σε διάγραμμα doughnut (μπορεί να είναι μεταξύ 10 και 90 τοις εκατό του μεγέθους της περιοχής σχεδίασης). Αυτό δεν είναι μόνο ιδιότητα αυτής της σειράς αλλά και όλων των σειρών της γονικής ομάδας σειρών – είναι προβολή της αντίστοιχης ιδιότητας ομάδας. Αυτή η ιδιότητα είναι μόνο για ανάγνωση. Χρησιμοποιήστε την ιδιότητα ParentSeriesGroup για πρόσβαση στη γονική ομάδα σειρών. Χρησιμοποιήστε την ιδιότητα ParentSeriesGroup.DoughnutHoleSize για ανάγνωση/εγγραφή προκειμένου να αλλάξετε την τιμή. Μόνο για ανάγνωση byte.

--------------------

Αυτή είναι η προβολή της ιδιότητας ParentSeriesGroup.DoughnutHoleSize.

**Επιστρέφει:**
byte
### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public abstract int getFirstSliceAngle()
```

Καθορίζει τη γωνία της πρώτης φέτας σε διάγραμμα pie ή doughnut, σε μοίρες (δεξιόστροφα από την κορυφή, από 0 έως 360 μοίρες). Αυτό δεν είναι μόνο ιδιότητα αυτής της σειράς αλλά και όλων των σειρών της γονικής ομάδας σειρών – είναι προβολή της αντίστοιχης ιδιότητας ομάδας. Αυτή η ιδιότητα είναι μόνο για ανάγνωση. Χρησιμοποιήστε την ιδιότητα ParentSeriesGroup για πρόσβαση στη γονική ομάδα σειρών. Χρησιμοποιήστε την ιδιότητα ParentSeriesGroup.FirstSliceAngle για ανάγνωση/εγγραφή προκειμένου να αλλάξετε την τιμή. Μόνο για ανάγνωση int.

--------------------

Αυτή είναι η προβολή της ιδιότητας ParentSeriesGroup.FirstSliceAngle.

**Επιστρέφει:**
int
### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public abstract IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

Οι προσαρμοσμένες πληροφορίες διαχωρισμού για ένα διάγραμμα pie-of-pie ή bar-of-pie με προσαρμοσμένο διαχωρισμό. Περιλαμβάνει τα σημεία δεδομένων που θα σχεδιαστούν στο δεύτερο κύκλο ή μπαρ. Αυτό δεν είναι μόνο ιδιότητα αυτής της σειράς αλλά και όλων των σειρών της γονικής ομάδας σειρών – είναι προβολή της αντίστοιχης ιδιότητας ομάδας Μόνο για ανάγνωση [IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection).

--------------------

Αυτή είναι η προβολή της ιδιότητας ParentSeriesGroup.PieSplitCustomPoints.

**Επιστρέφει:**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)
### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public abstract int getBubbleSizeRepresentation()
```
Καθορίζει πώς αντιπροσωπεύονται οι τιμές μεγέθους φυσαλίδας στη γραφική παράσταση φυσαλίδων. Αυτή είναι η ιδιότητα όχι μόνο αυτής της σειράς αλλά και όλων των σειρών της ομάδας γονικών σειρών - αυτή είναι η προβολή της κατάλληλης ιδιότητας της ομάδας. Κατά συνέπεια, αυτή η ιδιότητα είναι μόνο για ανάγνωση. Χρησιμοποιήστε την ιδιότητα ParentSeriesGroup για πρόσβαση στην ομάδα γονικών σειρών. Χρησιμοποιήστε την ιδιότητα ανάγνωση/εγγραφή ParentSeriesGroup.BubbleSizeRepresentation για την αλλαγή της τιμής.

--------------------

Αυτή είναι η προβολή της ιδιότητας ParentSeriesGroup.BubbleSizeRepresentation.

**Επιστρέφει:**  
int