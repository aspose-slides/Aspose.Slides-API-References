---
title: SizeF
second_title: Aspose.Slides για Android μέσω Java API Αναφορά
description: Κλάση για την περιγραφή διαστάσεων πλάτους και ύψους σε κάποια αυθαίρετη μονάδα με δεκαδικές τιμές.
type: docs
url: /el/com.aspose.slides.android/sizef/
---
**Κληρονόμηση:**
java.lang.Object
```
public class SizeF
```

Κλάση για την περιγραφή διαστάσεων πλάτους και ύψους σε κάποια αυθαίρετη μονάδα με δεκαδικές τιμές.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [SizeF(float width, float height)](#SizeF-float-float-) | Δημιουργεί μια νέα παρουσία SizeF. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getWidth()](#getWidth--) | Λαμβάνει το πλάτος του μεγέθους. |
| [getHeight()](#getHeight--) | Λαμβάνει το ύψος του μεγέθους. |
| [equals(Object obj)](#equals-java.lang.Object-) | Ελέγχει αν αυτό το μέγεθος είναι ίσο με άλλο μέγεθος. |
| [hashCode()](#hashCode--) | \{@inheritDoc\} |
| [toString()](#toString--) | Επιστρέφει το μέγεθος ως συμβολοσειρά με τη μορφή "WxH" |
### SizeF(float width, float height) {#SizeF-float-float-}
```
public SizeF(float width, float height)
```


Δημιουργεί μια νέα παρουσία SizeF.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| width | float | Το πλάτος του μεγέθους |
| height | float | Το ύψος του μεγέθους |

### getWidth() {#getWidth--}
```
public float getWidth()
```


Λαμβάνει το πλάτος του μεγέθους.

**Επιστρέφει:**
float - πλάτος
### getHeight() {#getHeight--}
```
public float getHeight()
```


Λαμβάνει το ύψος του μεγέθους.

**Επιστρέφει:**
float - ύψος
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Ελέγχει αν αυτό το μέγεθος είναι ίσο με άλλο μέγεθος.

Δύο μεγέθη είναι ίσα αν και μόνο αν και τα δύο πλάτη και ύψη είναι τα ίδια.

Για το σκοπό αυτό, οι τιμές float του πλάτους/ύψους θεωρούνται ίσες αν και μόνο αν η μέθοδος Float#floatToIntBits(float).floatToIntBits(float) επιστρέφει την ίδια τιμή int όταν εφαρμοστεί σε καθεμία.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Επιστρέφει:**
boolean -  true  αν τα αντικείμενα ήταν ίσα,  false  αλλιώς
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


Επιστρέφει το μέγεθος ως συμβολοσειρά με τη μορφή "WxH"

**Επιστρέφει:**
java.lang.String - αναπαράσταση συμβολοσειράς του μεγέθους