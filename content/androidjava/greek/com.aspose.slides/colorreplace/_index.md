---
title: ColorReplace
second_title: Aspose.Slides για Android μέσω αναφοράς Java API
description: Αντιπροσωπεύει ένα εφέ Αντικατάστασης Χρώματος.
type: docs
url: /el/com.aspose.slides/colorreplace/
---
**Κληρονομικότητα:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IColorReplace](../../com.aspose.slides/icolorreplace), com.aspose.slides.IVisualEffect, java.lang.Cloneable
```
public final class ColorReplace extends ImageTransformOperation implements IColorReplace, IVisualEffect, Cloneable
```

Αντιπροσωπεύει ένα εφέ Αντικατάστασης Χρώματος. Όλα τα χρώματα του εφέ αλλάζουν σε ένα σταθερό χρώμα. Οι τιμές Alpha δεν επηρεάζονται.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getColor()](#getColor--) | Επιστρέφει τη μορφή χρώματος που θα αντικαταστήσει το χρώμα κάθε pixel. |
| [getEffective()](#getEffective--) | Λαμβάνει τα αποτελεσματικά δεδομένα του εφέ Αντικατάστασης Χρώματος με την κληρονομικότητα εφαρμοσμένη. |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Καθορίζει εάν το συγκεκριμένο [ColorReplace](../../com.aspose.slides/colorreplace) είναι ίσο με το τρέχον [ColorReplace](../../com.aspose.slides/colorreplace). |
| [hashCode()](#hashCode--) | Λειτουργεί ως συνάρτηση hash για έναν συγκεκριμένο τύπο. |
### getColor() {#getColor--}
```
public final IColorFormat getColor()
```


Επιστρέφει τη μορφή χρώματος που θα αντικαταστήσει το χρώμα κάθε pixel. Μόνο για ανάγνωση [IColorFormat](../../com.aspose.slides/icolorformat).

**Επιστρέφει:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffective() {#getEffective--}
```
public final IColorReplaceEffectiveData getEffective()
```


Λαμβάνει τα αποτελεσματικά δεδομένα του εφέ Αντικατάστασης Χρώματος με την κληρονομικότητα εφαρμοσμένη.

**Επιστρέφει:**
[IColorReplaceEffectiveData](../../com.aspose.slides/icolorreplaceeffectivedata) - Ένα [IColorReplaceEffectiveData](../../com.aspose.slides/icolorreplaceeffectivedata).
### getVersion() {#getVersion--}
```
public long getVersion()
```


Έκδοση. Μόνο για ανάγνωση long.

**Επιστρέφει:**
long
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Καθορίζει εάν το συγκεκριμένο [ColorReplace](../../com.aspose.slides/colorreplace) είναι ίσο με το τρέχον [ColorReplace](../../com.aspose.slides/colorreplace).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj | java.lang.Object | Το [ColorReplace](../../com.aspose.slides/colorreplace) για σύγκριση. |

**Επιστρέφει:**
boolean - true αν τα αντικείμενα είναι ίσα· διαφορετικά, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Λειτουργεί ως συνάρτηση hash για έναν συγκεκριμένο τύπο.

**Επιστρέφει:**
int - Ένας κώδικας hash για το τρέχον αντικείμενο.