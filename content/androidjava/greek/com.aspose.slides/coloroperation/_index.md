---
title: ColorOperation
second_title: Aspose.Slides για Android μέσω αναφοράς API Java
description: Αντιπροσωπεύει διαφορετικές λειτουργίες χρώματος που χρησιμοποιούνται για μετασχηματισμούς χρώματος.
type: docs
url: /el/com.aspose.slides/coloroperation/
---
**Κληρονομία:**
java.lang.Object

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IColorOperation](../../com.aspose.slides/icoloroperation)
```
public class ColorOperation implements IColorOperation
```

Αντιπροσωπεύει διαφορετικές λειτουργίες χρώματος που χρησιμοποιούνται για μετασχηματισμούς χρώματος. Αμετάβλητο αντικείμενο.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [ColorOperation(int op)](#ColorOperation-int-) | Creates new color transform operation. |
| [ColorOperation(int op, float parameter)](#ColorOperation-int-float-) | Creates new color transform operation. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getOperationType()](#getOperationType--) | Returns or sets the type of an operation. |
| [getParameter()](#getParameter--) | Returns a parameter of an operation. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determines whether the two ColorOperation instances are equal. |
| [hashCode()](#hashCode--) | Serves as a hash function for a particular type, suitable for use in hashing algorithms and data structures like a hash table. |
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

Καθορίζει εάν τα δύο αντικείμενα ColorOperation είναι ίσα.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj | java.lang.Object | Το ColorOperation για σύγκριση με το τρέχον ColorOperation. |

**Επιστρέφει:**
boolean - **true** εάν το συγκεκριμένο ColorOperation είναι ίσο με το τρέχον ColorOperation· διαφορετικά, **false**.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Λειτουργεί ως συνάρτηση κατακερματισμού για έναν συγκεκριμένο τύπο, κατάλληλη για χρήση σε αλγορίθμους κατακερματισμού και δομές δεδομένων όπως ένας πίνακας κατακερματισμού.

**Επιστρέφει:**
int