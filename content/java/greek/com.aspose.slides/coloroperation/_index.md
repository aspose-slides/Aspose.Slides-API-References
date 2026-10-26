---
title: ColorOperation
second_title: Aspose.Slides για την Αναφορά API Java
description: Αντιπροσωπεύει διάφορες λειτουργίες χρώματος που χρησιμοποιούνται για μετασχηματισμούς χρώματος.
type: docs
url: /el/com.aspose.slides/coloroperation/
---
**Κληρονομικότητα:**
java.lang.Object

**Όλες οι υλοποιημένες διεπαφές:**
[com.aspose.slides.IColorOperation](../../com.aspose.slides/icoloroperation)
```
public class ColorOperation implements IColorOperation
```

Αντιπροσωπεύει διάφορες λειτουργίες χρώματος που χρησιμοποιούνται για μετασχηματισμούς χρώματος. Αμετάβλητο αντικείμενο.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [ColorOperation(int op)](#ColorOperation-int-) | Δημιουργεί νέα λειτουργία μετασχηματισμού χρώματος. |
| [ColorOperation(int op, float parameter)](#ColorOperation-int-float-) | Δημιουργεί νέα λειτουργία μετασχηματισμού χρώματος. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getOperationType()](#getOperationType--) | Επιστρέφει ή ορίζει τον τύπο μιας λειτουργίας. |
| [getParameter()](#getParameter--) | Επιστρέφει μια παράμετρο μιας λειτουργίας. |
| [equals(Object obj)](#equals-java.lang.Object-) | Καθορίζει εάν οι δύο ColorOperation είναι ίσες. |
| [hashCode()](#hashCode--) | Λειτουργεί ως συνάρτηση κατακερματισμού για έναν συγκεκριμένο τύπο, κατάλληλη για χρήση σε αλγορίθμους κατακερματισμού και δομές δεδομένων όπως πίνακας κατακερματισμού. |
### ColorOperation(int op) {#ColorOperation-int-}
```
public ColorOperation(int op)
```

Δημιουργεί νέα λειτουργία μετασχηματισμού χρώματος.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| op | int | Τύπος λειτουργίας. |

### ColorOperation(int op, float parameter) {#ColorOperation-int-float-}
```
public ColorOperation(int op, float parameter)
```

Δημιουργεί νέα λειτουργία μετασχηματισμού χρώματος.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| op | int | Τύπος λειτουργίας. |
| parameter | float | Παράμετρος λειτουργίας. |

### getOperationType() {#getOperationType--}
```
public final int getOperationType()
```

Επιστρέφει ή ορίζει τον τύπο μιας λειτουργίας. Μόνο για ανάγνωση [ColorTransformOperation](../../com.aspose.slides/colortransformoperation).

**Επιστρέφει:**
int
### getParameter() {#getParameter--}
```
public final float getParameter()
```

Επιστρέφει μια παράμετρο μιας λειτουργίας. Μόνο για ανάγνωση float.

**Επιστρέφει:**
float
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Καθορίζει εάν οι δύο ColorOperation είναι ίσες.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj | java.lang.Object | Η ColorOperation για σύγκριση με την τρέχουσα ColorOperation. |

**Επιστρέφει:**
boolean - **true** εάν η καθορισμένη ColorOperation είναι ίση με την τρέχουσα ColorOperation· διαφορετικά, **false**.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Λειτουργεί ως συνάρτηση κατακερματισμού για έναν συγκεκριμένο τύπο, κατάλληλη για χρήση σε αλγορίθμους κατακερματισμού και δομές δεδομένων όπως πίνακας κατακερματισμού.

**Επιστρέφει:**
int