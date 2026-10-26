---
title: Size
second_title: Aspose.Slides για Android μέσω Java API Αναφορά
description: Κλάση για την περιγραφή διαστάσεων πλάτους και ύψους σε κάποια αυθαίρετη μονάδα.
type: docs
url: /el/com.aspose.slides.android/size/
---
**Κληρονομικότητα:**
java.lang.Object
```
public class Size
```

Κλάση για την περιγραφή των διαστάσεων πλάτους και ύψους σε κάποια αυθαίρετη μονάδα.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [Size(int width, int height)](#Size-int-int-) | Δημιουργία μιας νέας παρουσίας του Size. |
## Μεθόδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getWidth()](#getWidth--) | Λήψη του πλάτους του size. |
| [getHeight()](#getHeight--) | Λήψη του ύψους του size. |
| [equals(Object obj)](#equals-java.lang.Object-) | Έλεγχος εάν αυτό το size είναι ίσο με άλλο size. |
| [hashCode()](#hashCode--) | \{@inheritDoc\} |
| [toString()](#toString--) | Επιστρέφει το size ως συμβολοσειρά με τη μορφή "WxH" |
### Size(int width, int height) {#Size-int-int-}
```
public Size(int width, int height)
```


Δημιουργία μιας νέας παρουσίας του Size.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| width | int | Το πλάτος του size |
| height | int | Το ύψος του size |

### getWidth() {#getWidth--}
```
public int getWidth()
```


Λήψη του πλάτους του size.

**Επιστρέφει:**
int - πλάτος
### getHeight() {#getHeight--}
```
public int getHeight()
```


Λήψη του ύψους του size.

**Επιστρέφει:**
int - ύψος
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Έλεγχος εάν αυτό το size είναι ίσο με άλλο size.

Δύο size είναι ίσα εάν και μόνο εάν και τα δύο πλάτη και ύψη τους είναι ίσα.

Ένα αντικείμενο size δεν είναι ποτέ ίσο με κάποιον άλλο τύπο αντικειμένου.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Επιστρέφει:**
boolean -  true  αν τα αντικείμενα ήταν ίσα,  false  διαφορετικά
### hashCode() {#hashCode--}
```
public int hashCode()
```




**Επιστρέφει:**
int
### toString() {#toString--}
```
public String toString()
```


Επιστρέφει το size ως συμβολοσειρά με τη μορφή "WxH"

**Επιστρέφει:**
java.lang.String - αναπαράσταση συμβολοσειράς του size