---
title: ErrorBarsFormat
second_title: Aspose.Slides για την Αναφορά API της Java
description: Αναπαριστά τις γραμμές σφάλματος των σειρών διαγράμματος.
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

Αναπαριστά τις γραμμές σφάλματος της σειράς διαγράμματος. Οι προσαρμοσμένες τιμές των ErrorBars βρίσκονται στο IChartDataPointCollection (στην ιδιότητα ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues))).

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getType()](#getType--) | Λαμβάνει ή ορίζει τον τύπο των γραμμών σφάλματος. |
| [setType(int value)](#setType-int-) | Λαμβάνει ή ορίζει τον τύπο των γραμμών σφάλματος. |
| [getValueType()](#getValueType--) | Αναπαριστά πιθανούς τρόπους για τον καθορισμό του μήκους των γραμμών σφάλματος. |
| [setValueType(int value)](#setValueType-int-) | Αναπαριστά πιθανούς τρόπους για τον καθορισμό του μήκους των γραμμών σφάλματος. |
| [hasEndCap()](#hasEndCap--) | Καθορίζει ότι το άκρο δεν σχεδιάζεται στις γραμμές σφάλματος. |
| [setEndCap(boolean value)](#setEndCap-boolean-) | Καθορίζει ότι το άκρο δεν σχεδιάζεται στις γραμμές σφάλματος. |
| [getValue()](#getValue--) | Λαμβάνει ή ορίζει την τιμή που χρησιμοποιείται με Fixed, Percentage και StandardDeviation για τον καθορισμό του μήκους των γραμμών σφάλματος. |
| [setValue(float value)](#setValue-float-) | Λαμβάνει ή ορίζει την τιμή που χρησιμοποιείται με Fixed, Percentage και StandardDeviation για τον καθορισμό του μήκους των γραμμών σφάλματος. |
| [getFormat()](#getFormat--) | Αναπαριστά τη μορφή των γραμμών σφάλματος. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | Αναπαριστά τη μορφή των γραμμών σφάλματος. |
| [getChart()](#getChart--) | Επιστρέφει το γονικό διάγραμμα. |
| [isVisible()](#isVisible--) | Λαμβάνει ή ορίζει την ορατότητα των Error Bars. |
| [setVisible(boolean value)](#setVisible-boolean-) | Λαμβάνει ή ορίζει την ορατότητα των Error Bars. |
| [getSlide()](#getSlide--) | Επιστρέφει τη γονική διαφάνεια ενός FillFormat. |
| [getPresentation()](#getPresentation--) | Επιστρέφει την γονική παρουσίαση ενός FillFormat. |

### getType() {#getType--}
```
public final int getType()
```

Λαμβάνει ή ορίζει τον τύπο των γραμμών σφάλματος. Ανάγνωση/εγγραφή [ErrorBarType](../../com.aspose.slides/errorbartype).

**Επιστρέφει:**
int

### setType(int value) {#setType-int-}
```
public final void setType(int value)
```

Λαμβάνει ή ορίζει τον τύπο των γραμμών σφάλματος. Ανάγνωση/εγγραφή [ErrorBarType](../../com.aspose.slides/errorbartype).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getValueType() {#getValueType--}
```
public final int getValueType()
```

Αναπαριστά πιθανούς τρόπους για τον καθορισμό του μήκους των γραμμών σφάλματος. Σε περίπτωση προσαρμοσμένου τύπου τιμής για τον καθορισμό τιμής, χρησιμοποιήστε την ιδιότητα ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)) του συγκεκριμένου σημείου δεδομένων στη συλλογή DataPoints της σειράς. Σε περίπτωση τύπων Fixed, Percentage ή StandardDeviation, χρησιμοποιήστε την ιδιότητα Value για τον καθορισμό της τιμής. Ανάγνωση/εγγραφή [ErrorBarValueType](../../com.aspose.slides/errorbarvaluetype).

**Επιστρέφει:**
int

### setValueType(int value) {#setValueType-int-}
```
public final void setValueType(int value)
```

Αναπαριστά πιθανούς τρόπους για τον καθορισμό του μήκους των γραμμών σφάλματος. Σε περίπτωση προσαρμοσμένου τύπου τιμής για τον καθορισμό τιμής, χρησιμοποιήστε την ιδιότητα ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)) του συγκεκριμένου σημείου δεδομένων στη συλλογή DataPoints της σειράς. Σε περίπτωση τύπων Fixed, Percentage ή StandardDeviation, χρησιμοποιήστε την ιδιότητα Value για τον καθορισμό της τιμής. Ανάγνωση/εγγραφή [ErrorBarValueType](../../com.aspose.slides/errorbarvaluetype).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### hasEndCap() {#hasEndCap--}
```
public final boolean hasEndCap()
```

Καθορίζει ότι το άκρο δεν σχεδιάζεται στις γραμμές σφάλματος. Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**
boolean

### setEndCap(boolean value) {#setEndCap-boolean-}
```
public final void setEndCap(boolean value)
```

Καθορίζει ότι το άκρο δεν σχεδιάζεται στις γραμμές σφάλματος. Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getValue() {#getValue--}
```
public final float getValue()
```

Λαμβάνει ή ορίζει την τιμή που χρησιμοποιείται με Fixed, Percentage και StandardDeviation για τον καθορισμό του μήκους των γραμμών σφάλματος. Σε οποιαδήποτε άλλη περίπτωση επιστρέφει NaN. Ανάγνωση/εγγραφή float.

**Επιστρέφει:**
float

### setValue(float value) {#setValue-float-}
```
public final void setValue(float value)
```

Λαμβάνει ή ορίζει την τιμή που χρησιμοποιείται με Fixed, Percentage και StandardDeviation για τον καθορισμό του μήκους των γραμμών σφάλματος. Σε οποιαδήποτε άλλη περίπτωση επιστρέφει NaN. Ανάγνωση/εγγραφή float.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |

### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

Αναπαριστά τη μορφή των γραμμών σφάλματος. Ανάγνωση/εγγραφή [IFormat](../../com.aspose.slides/iformat).

**Επιστρέφει:**
[IFormat](../../com.aspose.slides/iformat)

### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public final void setFormat(IFormat value)
```

Αναπαριστά τη μορφή των γραμμών σφάλματος. Ανάγνωση/εγγραφή [IFormat](../../com.aspose.slides/iformat).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |

### getChart() {#getChart--}
```
public final IChart getChart()
```

Επιστρέφει το γονικό διάγραμμα. Μόνο για ανάγνωση [IChart](../../com.aspose.slides/ichart).

**Επιστρέφει:**
[IChart](../../com.aspose.slides/ichart)

### isVisible() {#isVisible--}
```
public final boolean isVisible()
```

Λαμβάνει ή ορίζει την ορατότητα των Error Bars. Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**
boolean

### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```

Λαμβάνει ή ορίζει την ορατότητα των Error Bars. Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

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