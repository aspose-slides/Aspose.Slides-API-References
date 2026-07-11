---
title: ErrorBarsFormat
second_title: Aspose.Slides για Android μέσω αναφοράς API Java
description: Αντιπροσωπεύει τις γραμμές σφάλματος της σειράς διαγράμματος.
type: docs
url: /el/com.aspose.slides/errorbarsformat/
---
**Κληρονομικότητα:**  
java.lang.Object, com.aspose.slides.DomObject

**Όλες οι Υλοποιημένες Διεπαφές:**  
[com.aspose.slides.IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)  
```
public class ErrorBarsFormat extends DomObject<ChartSeries> implements IErrorBarsFormat
```

Αντιπροσωπεύει τις γραμμές σφάλματος της σειράς διαγράμματος. Οι προσαρμοσμένες τιμές ErrorBars βρίσκονται στο IChartDataPointCollection (στην ιδιότητα ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)) property).

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getType()](#getType--) | Λαμβάνει ή ορίζει τον τύπο των γραμμών σφάλματος. |
| [setType(int value)](#setType-int-) | Λαμβάνει ή ορίζει τον τύπο των γραμμών σφάλματος. |
| [getValueType()](#getValueType--) | Αντιπροσωπεύει πιθανές μεθόδους για τον καθορισμό του μήκους των γραμμών σφάλματος. |
| [setValueType(int value)](#setValueType-int-) | Αντιπροσωπεύει πιθανές μεθόδους για τον καθορισμό του μήκους των γραμμών σφάλματος. |
| [hasEndCap()](#hasEndCap--) | Καθορίζει ότι δεν σχεδιάζεται άκρο στις γραμμές σφάλματος. |
| [setEndCap(boolean value)](#setEndCap-boolean-) | Καθορίζει ότι δεν σχεδιάζεται άκρο στις γραμμές σφάλματος. |
| [getValue()](#getValue--) | Λαμβάνει ή ορίζει την τιμή που χρησιμοποιείται με Fixed, Percentage και StandardDeviation value types για τον καθορισμό του μήκους των γραμμών σφάλματος. |
| [setValue(float value)](#setValue-float-) | Λαμβάνει ή ορίζει την τιμή που χρησιμοποιείται με Fixed, Percentage και StandardDeviation value types για τον καθορισμό του μήκους των γραμμών σφάλματος. |
| [getFormat()](#getFormat--) | Αντιπροσωπεύει τη μορφή των γραμμών σφάλματος. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | Αντιπροσωπεύει τη μορφή των γραμμών σφάλματος. |
| [getChart()](#getChart--) | Επιστρέφει το γονικό γράφημα. |
| [isVisible()](#isVisible--) | Λαμβάνει ή ορίζει την ορατότητα των γραμμών σφάλματος. |
| [setVisible(boolean value)](#setVisible-boolean-) | Λαμβάνει ή ορίζει την ορατότητα των γραμμών σφάλματος. |
| [getSlide()](#getSlide--) | Επιστρέφει τη γονική διαφάνεια ενός FillFormat. |
| [getPresentation()](#getPresentation--) | Επιστρέφει την γονική παρουσίαση ενός FillFormat. |

### getType() {#getType--}
```
public final int getType()
```

Λαμβάνει ή ορίζει τον τύπο των γραμμών σφάλματος. Ανάγνωση/εγγραφή [ErrorBarType](../../com.aspose.slides/errorbartype).

**Returns:**  
int

### setType(int value) {#setType-int-}
```
public final void setType(int value)
```

Λαμβάνει ή ορίζει τον τύπο των γραμμών σφάλματος. Ανάγνωση/εγγραφή [ErrorBarType](../../com.aspose.slides/errorbartype).

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getValueType() {#getValueType--}
```
public final int getValueType()
```

Αντιπροσωπεύει πιθανές μεθόδους για τον καθορισμό του μήκους των γραμμών σφάλματος. Σε περίπτωση προσαρμοσμένου τύπου τιμής, χρησιμοποιήστε την ιδιότητα ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)) του συγκεκριμένου σημείου δεδομένων στη συλλογή DataPoints της σειράς. Σε περίπτωση Fixed, Percentage ή StandardDeviation, χρησιμοποιήστε την ιδιότητα Value για να ορίσετε την τιμή. Ανάγνωση/εγγραφή [ErrorBarValueType](../../com.aspose.slides/errorbarvaluetype).

**Returns:**  
int

### setValueType(int value) {#setValueType-int-}
```
public final void setValueType(int value)
```

Αντιπροσωπεύει πιθανές μεθόδους για τον καθορισμό του μήκους των γραμμών σφάλματος. Σε περίπτωση προσαρμοσμένου τύπου τιμής, χρησιμοποιήστε την ιδιότητα ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)) του συγκεκριμένου σημείου δεδομένων στη συλλογή DataPoints της σειράς. Σε περίπτωση Fixed, Percentage ή StandardDeviation, χρησιμοποιήστε την ιδιότητα Value για να ορίσετε την τιμή. Ανάγνωση/εγγραφή [ErrorBarValueType](../../com.aspose.slides/errorbarvaluetype).

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### hasEndCap() {#hasEndCap--}
```
public final boolean hasEndCap()
```

Καθορίζει ότι δεν σχεδιάζεται άκρο στις γραμμές σφάλματος. Ανάγνωση/εγγραφή boolean.

**Returns:**  
boolean

### setEndCap(boolean value) {#setEndCap-boolean-}
```
public final void setEndCap(boolean value)
```

Καθορίζει ότι δεν σχεδιάζεται άκρο στις γραμμές σφάλματος. Ανάγνωση/εγγραφή boolean.

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getValue() {#getValue--}
```
public final float getValue()
```

Λαμβάνει ή ορίζει την τιμή που χρησιμοποιείται με Fixed, Percentage και StandardDeviation value types για τον καθορισμό του μήκους των γραμμών σφάλματος. Σε οποιαδήποτε άλλη περίπτωση θα επιστρέψει NaN. Ανάγνωση/εγγραφή float.

**Returns:**  
float

### setValue(float value) {#setValue-float-}
```
public final void setValue(float value)
```

Λαμβάνει ή ορίζει την τιμή που χρησιμοποιείται με Fixed, Percentage και StandardDeviation value types για τον καθορισμό του μήκους των γραμμών σφάλματος. Σε οποιαδήποτε άλλη περίπτωση θα επιστρέψει NaN. Ανάγνωση/εγγραφή float.

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

Αντιπροσωπεύει τη μορφή των γραμμών σφάλματος. Ανάγνωση/εγγραφή [IFormat](../../com.aspose.slides/iformat).

**Returns:**  
[IFormat](../../com.aspose.slides/iformat)

### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public final void setFormat(IFormat value)
```

Αντιπροσωπεύει τη μορφή των γραμμών σφάλματος. Ανάγνωση/εγγραφή [IFormat](../../com.aspose.slides/iformat).

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |

### getChart() {#getChart--}
```
public final IChart getChart()
```

Επιστρέφει το γονικό γράφημα. Μόνο για ανάγνωση [IChart](../../com.aspose.slides/ichart).

**Returns:**  
[IChart](../../com.aspose.slides/ichart)

### isVisible() {#isVisible--}
```
public final boolean isVisible()
```

Λαμβάνει ή ορίζει την ορατότητα των γραμμών σφάλματος. Ανάγνωση/εγγραφή boolean.

**Returns:**  
boolean

### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```

Λαμβάνει ή ορίζει την ορατότητα των γραμμών σφάλματος. Ανάγνωση/εγγραφή boolean.

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Επιστρέφει τη γονική διαφάνεια ενός FillFormat. Μόνο για ανάγνωση [BaseSlide](../../com.aspose.slides/baseslide).

**Returns:**  
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Επιστρέφει την γονική παρουσίαση ενός FillFormat. Μόνο για ανάγνωση [IPresentation](../../com.aspose.slides/ipresentation).

**Returns:**  
[IPresentation](../../com.aspose.slides/ipresentation)