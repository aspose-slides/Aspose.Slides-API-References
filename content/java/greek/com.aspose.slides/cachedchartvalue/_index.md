---
title: CachedChartValue
second_title: Aspose.Slides για την Java API Αναφορά
description: Αντιπροσωπεύει μια αποθηκευμένη τιμή διαγράμματος π.χ. X Y μέγεθος φούσκας ή η κύρια τιμή.
type: docs
url: /el/com.aspose.slides/cachedchartvalue/
---
**Κληρονομικότητα:**
java.lang.Object

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.ICachedChartValue](../../com.aspose.slides/icachedchartvalue)
```
public class CachedChartValue implements ICachedChartValue
```

Αντιπροσωπεύει μια αποθηκευμένη τιμή διαγράμματος (π.χ., X, Y, μέγεθος φούσκας ή η κύρια τιμή).
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [CachedChartValue()](#CachedChartValue--) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [toString()](#toString--) | Επιστρέφει μια αναπαράσταση συμβολοσειράς της αποθηκευμένης τιμής. |
| [toDouble()](#toDouble--) | Μετατρέπει την αποθηκευμένη τιμή σε double. |
| [getData()](#getData--) | Λαμβάνει το αποθηκευμένο αντικείμενο δεδομένων. |
### CachedChartValue() {#CachedChartValue--}
```
public CachedChartValue()
```


### toString() {#toString--}
```
public String toString()
```


Επιστρέφει μια αναπαράσταση συμβολοσειράς της αποθηκευμένης τιμής.

**Επιστρέφει:**
java.lang.String
### toDouble() {#toDouble--}
```
public final double toDouble()
```


Μετατρέπει την αποθηκευμένη τιμή σε double.

**Επιστρέφει:**
double - Η αριθμητική αναπαράσταση, ή Double.NaN εάν το Data (\#getData.getData/\#setData(Object).setData(Object)) είναι null ή δεν μπορεί να μετατραπεί σε double.
### getData() {#getData--}
```
public final Object getData()
```


Λαμβάνει το αποθηκευμένο αντικείμενο δεδομένων. Μόνο-ανάγνωση  Object .

**Επιστρέφει:**
java.lang.Object