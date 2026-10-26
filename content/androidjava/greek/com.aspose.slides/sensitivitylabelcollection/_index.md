---
title: SensitivityLabelCollection
second_title: Aspose.Slides για Android μέσω Αναφοράς API Java
description: Αντιπροσωπεύει μια συλλογή από ετικέτες ευαισθησίας που εφαρμόζονται στο έγγραφο.
type: docs
url: /el/com.aspose.slides/sensitivitylabelcollection/
---
**Κληρονομικότητα:**
java.lang.Object, com.aspose.slides.DomObject

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.ISensitivityLabelCollection](../../com.aspose.slides/isensitivitylabelcollection)
```
public final class SensitivityLabelCollection extends DomObject<Presentation> implements ISensitivityLabelCollection
```

Αντιπροσωπεύει μια συλλογή από ετικέτες ευαισθησίας που εφαρμόζονται στο έγγραφο.
## Μεθόδοι

| Μεθοδος | Περιγραφή |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Επιστρέφει την ετικέτα ευαισθησίας με βάση τον δείκτη. |
| [add(String id, UUID siteId, boolean isEnabled, int methodType)](#add-java.lang.String-java.util.UUID-boolean-int-) | Προσθέτει την ετικέτα ευαισθησίας στο τέλος της συλλογής. |
| [add(ISensitivityLabel label)](#add-com.aspose.slides.ISensitivityLabel-) | Προσθέτει ένα SensitivityLabel στη συλλογή. |
| [removeAt(int index)](#removeAt-int-) | Αφαιρεί την ετικέτα ευαισθησίας στο συγκεκριμένο δείκτη. |
| [clear()](#clear--) | Αφαιρεί όλα τα στοιχεία από τη συλλογή. |
| [iterator()](#iterator--) | Επιστρέφει έναν enumerator που διασχίζει τη συλλογή. |
| [getCount()](#getCount--) | Επιστρέφει τον αριθμό των στοιχείων στη συλλογή. |
| [copyTo(ISensitivityLabel[] array, int index)](#copyTo-com.aspose.slides.ISensitivityLabel---int-) | Αντιγράφει όλα τα στοιχεία από τη συλλογή στον καθορισμένο πίνακα. |
### get_Item(int index) {#get-Item-int-}
```
public final ISensitivityLabel get_Item(int index)
```


Επιστρέφει την ετικέτα ευαίσθησης με βάση τον δείκτη.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int |  |

**Επιστρέφει:**
[ISensitivityLabel](../../com.aspose.slides/isensitivitylabel)
### add(String id, UUID siteId, boolean isEnabled, int methodType) {#add-java.lang.String-java.util.UUID-boolean-int-}
```
public final ISensitivityLabel add(String id, UUID siteId, boolean isEnabled, int methodType)
```


Προσθέτει την ετικέτα ευαισθησίας στο τέλος της συλλογής.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| id | java.lang.String | Το αναγνωριστικό (id) της ετικέτας ευαισθησίας. |
| siteId | java.util.UUID | Το αναγνωριστικό του site Azure Active Directory (Azure AD). |
| isEnabled | boolean | Σημαία που υποδεικνύει εάν η ετικέτα ευαισθησίας είναι ενεργή. |
| methodType | int | Η μέθοδος εκχώρησης για την ετικέτα ευαισθησίας. |

**Επιστρέφει:**
[ISensitivityLabel](../../com.aspose.slides/isensitivitylabel)
### add(ISensitivityLabel label) {#add-com.aspose.slides.ISensitivityLabel-}
```
public final int add(ISensitivityLabel label)
```


Προσθέτει ένα SensitivityLabel στη συλλογή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| label | [ISensitivityLabel](../../com.aspose.slides/isensitivitylabel) | Το αντικείμενο SensitivityLabel που θα προστεθεί στο τέλος της συλλογής. |

**Επιστρέφει:**
int - Ο δείκτης στον οποίο προστέθηκε το SensitivityLabel.
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Αφαιρεί την ετικέτα ευαισθησίας στο συγκεκριμένο δείκτη.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Δείκτης της ετικέτας ευαισθησίας που πρέπει να διαγραφεί. |

### clear() {#clear--}
```
public final void clear()
```


Αφαιρεί όλα τα στοιχεία από τη συλλογή.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISensitivityLabel> iterator()
```


Επιστρέφει έναν enumerator που διασχίζει τη συλλογή.

**Επιστρέφει:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISensitivityLabel> - Ένα System.Collections.Generic.IEnumerator1 που μπορεί να χρησιμοποιηθεί για την διέλευση της συλλογής.
### getCount() {#getCount--}
```
public final int getCount()
```


Επιστρέφει τον αριθμό των στοιχείων στη συλλογή. Μόνο για ανάγνωση  int .

**Επιστρέφει:**
int
### copyTo(ISensitivityLabel[] array, int index) {#copyTo-com.aspose.slides.ISensitivityLabel---int-}
```
public final void copyTo(ISensitivityLabel[] array, int index)
```


Αντιγράφει όλα τα στοιχεία από τη συλλογή στον καθορισμένο πίνακα.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| array | [ISensitivityLabel\[\]](../../com.aspose.slides/isensitivitylabel) | Πίνακας προορισμού. |
| index | int | Αρχικός δείκτης στον πίνακα προορισμού. |