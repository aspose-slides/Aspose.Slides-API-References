---
title: ISensitivityLabelCollection
second_title: Aspose.Slides για την Αναφορά API Java
description: Αντιπροσωπεύει μια συλλογή από ετικέτες ευαισθησίας που εφαρμόζονται στο έγγραφο.
type: docs
url: /el/com.aspose.slides/isensitivitylabelcollection/
---
**Όλες οι υλοποιημένες διεπαφές:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface ISensitivityLabelCollection extends System.Collections.Generic.IGenericEnumerable<ISensitivityLabel>
```

Αντιπροσωπεύει μια συλλογή από ετικέτες ευαισθησίας που εφαρμόζονται στο έγγραφο.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Επιστρέφει την ετικέτα ευαισθησίας με βάση το δείκτη. |
| [add(String id, UUID siteId, boolean isEnabled, int methodType)](#add-java.lang.String-java.util.UUID-boolean-int-) | Προσθέτει την ετικέτα ευαισθησίας στο τέλος της συλλογής. |
| [add(ISensitivityLabel label)](#add-com.aspose.slides.ISensitivityLabel-) | Προσθέτει ένα SensitivityLabel στη συλλογή. |
| [removeAt(int index)](#removeAt-int-) | Αφαιρεί την ετικέτα ευαισθησίας στο συγκεκριμένο δείκτη. |
| [clear()](#clear--) | Αφαιρεί όλα τα στοιχεία από τη συλλογή. |
| [getCount()](#getCount--) | Λαμβάνει τον αριθμό όλων των στοιχείων στη συλλογή. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ISensitivityLabel get_Item(int index)
```

Επιστρέφει την ετικέτα ευαισθησίας με βάση το δείκτη. Μόνο για ανάγνωση [ISensitivityLabel](../../com.aspose.slides/isensitivitylabel).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int |  |

**Επιστρέφει:**
[ISensitivityLabel](../../com.aspose.slides/isensitivitylabel)
### add(String id, UUID siteId, boolean isEnabled, int methodType) {#add-java.lang.String-java.util.UUID-boolean-int-}
```
public abstract ISensitivityLabel add(String id, UUID siteId, boolean isEnabled, int methodType)
```

Προσθέτει την ετικέτα ευαισθησίας στο τέλος της συλλογής.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| id | java.lang.String | Το αναγνωριστικό της ετικέτας ευαισθησίας. |
| siteId | java.util.UUID | Το αναγνωριστικό του ιστότοπου Azure Active Directory (Azure AD). |
| isEnabled | boolean | Σημαία που υποδεικνύει αν η ετικέτα ευαισθησίας είναι ενεργή. |
| methodType | int | Η μέθοδος ανάθεσης για την ετικέτα ευαισθησίας. |

**Επιστρέφει:**
[ISensitivityLabel](../../com.aspose.slides/isensitivitylabel)
### add(ISensitivityLabel label) {#add-com.aspose.slides.ISensitivityLabel-}
```
public abstract int add(ISensitivityLabel label)
```

Προσθέτει ένα SensitivityLabel στη συλλογή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| label | [ISensitivityLabel](../../com.aspose.slides/isensitivitylabel) | Το αντικείμενο SensitivityLabel που θα προστεθεί στο τέλος της συλλογής. |

**Επιστρέφει:**
int - Ο δείκτης στο οποίο προστέθηκε το SensitivityLabel.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Αφαιρεί την ετικέτα ευαισθησίας στο συγκεκριμένο δείκτη.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Δείκτης της ετικέτας ευαισθησίας που πρέπει να διαγραφεί. |

### clear() {#clear--}
```
public abstract void clear()
```

Αφαιρεί όλα τα στοιχεία από τη συλλογή.

### getCount() {#getCount--}
```
public abstract int getCount()
```

Λαμβάνει τον αριθμό όλων των στοιχείων στη συλλογή. Μόνο για ανάγνωση int .

**Επιστρέφει:**
int