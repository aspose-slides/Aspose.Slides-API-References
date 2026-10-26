---
title: IErrorBarsFormat
second_title: Aspose.Slides για Android μέσω Java API Αναφορά
description: Αναπαριστά τις γραμμές σφάλματος της σειράς διαγράμματος.
type: docs
url: /el/com.aspose.slides/ierrorbarsformat/
---
**All Implemented Interfaces:**
[com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IErrorBarsFormat extends IChartComponent
```

Αναπαριστά τις γραμμές σφάλματος της σειράς διαγράμματος. Οι προσαρμοσμένες τιμές ErrorBars βρίσκονται στο IChartDataPointCollection (στην ιδιότητα [IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)).

## Μέθοδοι

| Method | Description |
| --- | --- |
| [getType()](#getType--) | Λαμβάνει ή ορίζει τον τύπο των γραμμών σφάλματος. |
| [setType(int value)](#setType-int-) | Λαμβάνει ή ορίζει τον τύπο των γραμμών σφάλματος. |
| [getValueType()](#getValueType--) | Αναπαριστά τους πιθανούς τρόπους καθορισμού του μήκους των γραμμών σφάλματος. |
| [setValueType(int value)](#setValueType-int-) | Αναπαριστά τους πιθανούς τρόπους καθορισμού του μήκους των γραμμών σφάλματος. |
| [hasEndCap()](#hasEndCap--) | Καθορίζει ότι δεν σχεδιάζεται άκρο στις γραμμές σφάλματος. |
| [setEndCap(boolean value)](#setEndCap-boolean-) | Καθορίζει ότι δεν σχεδιάζεται άκρο στις γραμμές σφάλματος. |
| [getValue()](#getValue--) | Λαμβάνει ή ορίζει την τιμή που χρησιμοποιείται με τους τύπους τιμών Fixed, Percentage και StandardDeviation για τον καθορισμό του μήκους των γραμμών σφάλματος. |
| [setValue(float value)](#setValue-float-) | Λαμβάνει ή ορίζει την τιμή που χρησιμοποιείται με τους τύπους τιμών Fixed, Percentage και StandardDeviation για τον καθορισμό του μήκους των γραμμών σφάλματος. |
| [getFormat()](#getFormat--) | Αναπαριστά τη μορφή των γραμμών σφάλματος. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | Αναπαριστά τη μορφή των γραμμών σφάλματος. |
| [isVisible()](#isVisible--) | Λαμβάνει ή ορίζει την ορατότητα των γραμμών σφάλματος. |
| [setVisible(boolean value)](#setVisible-boolean-) | Λαμβάνει ή ορίζει την ορατότητα των γραμμών σφάλματος. |

### getType() {#getType--}
```
public abstract int getType()
```

Λαμβάνει ή ορίζει τον τύπο των γραμμών σφάλματος. Ανάγνωση/εγγραφή [ErrorBarType](../../com.aspose.slides/errorbartype).

**Επιστρέφει:**
int

### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```

Λαμβάνει ή ορίζει τον τύπο των γραμμών σφάλματος. Ανάγνωση/εγγραφή [ErrorBarType](../../com.aspose.slides/errorbartype).

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getValueType() {#getValueType--}
```
public abstract int getValueType()
```

Αναπαριστά τους πιθανούς τρόπους καθορισμού του μήκους των γραμμών σφάλματος. Σε περίπτωση προσαρμοσμένου τύπου τιμής για τον καθορισμό της τιμής χρησιμοποιήστε την ιδιότητα [IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues) του συγκεκριμένου σημείου δεδομένων στη συλλογή DataPoints της σειράς. Ανάγνωση/εγγραφή [ErrorBarValueType](../../com.aspose.slides/errorbarvaluetype).

**Επιστρέφει:**
int

### setValueType(int value) {#setValueType-int-}
```
public abstract void setValueType(int value)
```

Αναπαριστά τους πιθανούς τρόπους καθορισμού του μήκους των γραμμών σφάλματος. Σε περίπτωση προσαρμοσμένου τύπου τιμής για τον καθορισμό της τιμής χρησιμοποιήστε την ιδιότητα [IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues) του συγκεκριμένου σημείου δεδομένων στη συλλογή DataPoints της σειράς. Ανάγνωση/εγγραφή [ErrorBarValueType](../../com.aspose.slides/errorbarvaluetype).

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### hasEndCap() {#hasEndCap--}
```
public abstract boolean hasEndCap()
```

Καθορίζει ότι δεν σχεδιάζεται άκρο στις γραμμές σφάλματος. Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**
boolean

### setEndCap(boolean value) {#setEndCap-boolean-}
```
public abstract void setEndCap(boolean value)
```

Καθορίζει ότι δεν σχεδιάζεται άκρο στις γραμμές σφάλματος. Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getValue() {#getValue--}
```
public abstract float getValue()
```

Λαμβάνει ή ορίζει την τιμή που χρησιμοποιείται με τους τύπους τιμών Fixed, Percentage και StandardDeviation για τον καθορισμό του μήκους των γραμμών σφάλματος. Ανάγνωση/εγγραφή float.

**Επιστρέφει:**
float

### setValue(float value) {#setValue-float-}
```
public abstract void setValue(float value)
```

Λαμβάνει ή ορίζει την τιμή που χρησιμοποιείται με τους τύπους τιμών Fixed, Percentage και StandardDeviation για τον καθορισμό του μήκους των γραμμών σφάλματος. Ανάγνωση/εγγραφή float.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Αναπαριστά τη μορφή των γραμμών σφάλματος. Ανάγνωση/εγγραφή [IFormat](../../com.aspose.slides/iformat).

**Επιστρέφει:**
[IFormat](../../com.aspose.slides/iformat)

### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public abstract void setFormat(IFormat value)
```

Αναπαριστά τη μορφή των γραμμών σφάλματος. Ανάγνωση/εγγραφή [IFormat](../../com.aspose.slides/iformat).

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |

### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```

Λαμβάνει ή ορίζει την ορατότητα των γραμμών σφάλματος. Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**
boolean

### setVisible(boolean value) {#setVisible-boolean-}
```
public abstract void setVisible(boolean value)
```

Λαμβάνει ή ορίζει την ορατότητα των γραμμών σφάλματος. Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |