---
title: ICachedChartValue
second_title: Aspose.Slides για την Αναφορά API Java
description: Αντιπροσωπεύει μια αποθηκευμένη τιμή διαγράμματος π.χ. X Y μέγεθος φυσαλίδας ή την κύρια τιμή.
type: docs
url: /el/com.aspose.slides/icachedchartvalue/
---```
public interface ICachedChartValue
```

Αντιπροσωπεύει μια αποθηκευμένη τιμή διαγράμματος (π.χ., X, Y, μέγεθος φυσαλίδας ή την κύρια τιμή).
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getData()](#getData--) | Ανακτά το αντικείμενο δεδομένων. |
| [toDouble()](#toDouble--) | Μετατρέπει την αποθηκευμένη τιμή σε double. |
### getData() {#getData--}
```
public abstract Object getData()
```


Ανακτά το αντικείμενο δεδομένων. Μόνο για ανάγνωση Object .

**Επιστρέφει:**
java.lang.Object
### toDouble() {#toDouble--}
```
public abstract double toDouble()
```


Μετατρέπει την αποθηκευμένη τιμή σε double.

**Επιστρέφει:**
double - Η αριθμητική αναπαράσταση, ή Double.NaN εάν το Data (\#getData.getData) είναι null ή δεν μπορεί να μετατραπεί σε double.