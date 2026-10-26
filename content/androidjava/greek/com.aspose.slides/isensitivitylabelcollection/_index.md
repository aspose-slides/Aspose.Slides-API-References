---
title: ISensitivityLabelCollection
second_title: Aspose.Slides για Android μέσω αναφοράς API Java
description: Αναπαριστά μια συλλογή από ετικέτες ευαισθησίας που εφαρμόζονται στο έγγραφο.
type: docs
url: /el/com.aspose.slides/isensitivitylabelcollection/
---
**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface ISensitivityLabelCollection extends System.Collections.Generic.IGenericEnumerable<ISensitivityLabel>
```

Represents a collection of sensitivity labels applied to the document.
## Methods

| Μέθοδος | Περιγραφή |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Επιστρέφει την ετικέτα ευαισθησίας κατά δείκτη. |
| [add(String id, UUID siteId, boolean isEnabled, int methodType)](#add-java.lang.String-java.util.UUID-boolean-int-) | Προσθέτει την ετικέτα ευαισθησίας στο τέλος της συλλογής. |
| [add(ISensitivityLabel label)](#add-com.aspose.slides.ISensitivityLabel-) | Προσθέτει ένα SensitivityLabel στη συλλογή. |
| [removeAt(int index)](#removeAt-int-) | Αφαιρεί την ετικέτα ευαισθησίας στον καθορισμένο δείκτη. |
| [clear()](#clear--) | Αφαιρεί όλα τα στοιχεία από τη συλλογή. |
| [getCount()](#getCount--) | Λαμβάνει τον αριθμό όλων των στοιχείων στη συλλογή. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ISensitivityLabel get_Item(int index)
```

Επιστρέφει την ετικέτα ευαισθησίας κατά δείκτη. Μόνο για ανάγνωση [ISensitivityLabel](../../com.aspose.slides/isensitivitylabel).

**Παράμετροι:**
| Parameter | Type | Description |
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
| Parameter | Type | Description |
| --- | --- | --- |
| id | java.lang.String | Το αναγνωριστικό της ετικέτας ευαισθησίας. |
| siteId | java.util.UUID | Το Azure Active Directory (Azure AD) site identifier. |
| isEnabled | boolean | Σημαία που υποδεικνύει αν η ετικέτα ευαισθησίας είναι ενεργοποιημένη. |
| methodType | int | Η μέθοδος ανάθεσης για την ετικέτα ευαισθησίας. |

**Επιστρέφει:**
[ISensitivityLabel](../../com.aspose.slides/isensitivitylabel)
### add(ISensitivityLabel label) {#add-com.aspose.slides.ISensitivityLabel-}
```
public abstract int add(ISensitivityLabel label)
```

Προσθέτει ένα SensitivityLabel στη συλλογή.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| label | [ISensitivityLabel](../../com.aspose.slides/isensitivitylabel) | Το αντικείμενο SensitivityLabel που θα προταθεί στο τέλος της συλλογής. |

**Επιστρέφει:**
int - Ο δείκτης στον οποίο προστέθηκε το SensitivityLabel.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Αφαιρεί την ετικέτα ευαισθησίας στον καθορισμένο δείκτη.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of the sensitivity label that should be deleted. |

### clear() {#clear--}
```
public abstract void clear()
```

Αφαιρεί όλα τα στοιχεία από τη συλλογή.

### getCount() {#getCount--}
```
public abstract int getCount()
```

Λαμβάνει τον αριθμό όλων των στοιχείων στη συλλογή. Μόνο για ανάγνωση  int .

**Επιστρέφει:**
int