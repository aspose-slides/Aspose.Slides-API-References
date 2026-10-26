---
title: AlphaBiLevel
second_title: Aspose.Slides για Android μέσω αναφοράς Java API
description: Αναπαριστά ένα εφέ Alpha Bi-Level.
type: docs
url: /el/com.aspose.slides/alphabilevel/
---
**Κληρονόμηση:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IAlphaBiLevel](../../com.aspose.slides/ialphabilevel), com.aspose.slides.IVisualEffect
```
public final class AlphaBiLevel extends ImageTransformOperation implements IAlphaBiLevel, IVisualEffect
```

Αναπαριστά ένα εφέ Alpha Bi-Level. Οι τιμές Alpha (Opacity) μικρότερες από το κατώφλι μετατρέπονται σε 0 (πλήρως διαφανές) και οι τιμές αλφα μεγαλύτερες ή ίσες με το κατώφλι μετατρέπονται σε 100% (πλήρως αδιαπέραστο).
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getThreshold()](#getThreshold--) | Επιστρέφει το όριο του εφέ. |
| [setThreshold(float value)](#setThreshold-float-) | Επιστρέφει το όριο του εφέ. |
| [getEffective()](#getEffective--) | Αποκτά τα αποτελεσματικά δεδομένα του εφέ Alpha Bi-Level με την κληρονόμηση εφαρμοσμένη. |
| [equals(Object obj)](#equals-java.lang.Object-) | Καθορίζει εάν το συγκεκριμένο [AlphaBiLevel](../../com.aspose.slides/alphabilevel) είναι ίσο με το τρέχον [AlphaBiLevel](../../com.aspose.slides/alphabilevel). |
| [hashCode()](#hashCode--) | Λειτουργεί ως συνάρτηση κατακερματισμού για έναν συγκεκριμένο τύπο. |
### getThreshold() {#getThreshold--}
```
public final float getThreshold()
```


Επιστρέφει το όριο του εφέ. Ανάγνωση/εγγραφή float.

**Επιστρέφει:**
float
### setThreshold(float value) {#setThreshold-float-}
```
public final void setThreshold(float value)
```


Επιστρέφει το όριο του εφέ. Ανάγνωση/εγγραφή float.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |

### getEffective() {#getEffective--}
```
public final IAlphaBiLevelEffectiveData getEffective()
```


Αποκτά τα αποτελεσματικά δεδομένα του εφέ Alpha Bi-Level με την κληρονόμηση εφαρμοσμένη.

**Επιστρέφει:**
[IAlphaBiLevelEffectiveData](../../com.aspose.slides/ialphabileveleffectivedata) - Ένα [IAlphaBiLevelEffectiveData](../../com.aspose.slides/ialphabileveleffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Καθορίζει εάν το συγκεκριμένο [AlphaBiLevel](../../com.aspose.slides/alphabilevel) είναι ίσο με το τρέχον [AlphaBiLevel](../../com.aspose.slides/alphabilevel).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj | java.lang.Object | Το [AlphaBiLevel](../../com.aspose.slides/alphabilevel) για σύγκριση. |

**Επιστρέφει:**
boolean - true εάν τα αντικείμενα είναι ίσα· διαφορετικά, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Λειτουργεί ως συνάρτηση κατακερματισμού για έναν συγκεκριμένο τύπο.

**Επιστρέφει:**
int - Ένας κώδικας κατακερματισμού για το τρέχον αντικείμενο.