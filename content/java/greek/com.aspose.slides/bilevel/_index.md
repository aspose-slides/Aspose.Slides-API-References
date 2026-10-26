---
title: BiLevel
second_title: Aspose.Slides για αναφορά API Java
description: Αντιπροσωπεύει ένα εφέ Bi-Level μαύρου/λευκού.
type: docs
url: /el/com.aspose.slides/bilevel/
---
**Κληρονομικότητα:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IBiLevel](../../com.aspose.slides/ibilevel), com.aspose.slides.IVisualEffect
```
public final class BiLevel extends ImageTransformOperation implements IBiLevel, IVisualEffect
```

Αντιπροσωπεύει ένα εφέ Bi-Level (μαύρο/λευκό). Τα χρώματα εισόδου των οποίων η φωτεινότητα είναι μικρότερη από τη συγκεκριμένη τιμή κατωφλίου μετατρέπονται σε μαύρο. Τα χρώματα εισόδου των οποίων η φωτεινότητα είναι μεγαλύτερη ή ίση με τη συγκεκριμένη τιμή ορίζονται σε λευκό. Οι τιμές του εφέ άλφα δεν επηρεάζονται από αυτό το εφέ.
## Methods

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getEffective()](#getEffective--) | Λαμβάνει τα αποτελεσματικά δεδομένα εφέ Bi-Level με την κληρονομικότητα εφαρμοσμένη. |
| [equals(Object obj)](#equals-java.lang.Object-) | Καθορίζει αν το συγκεκριμένο [BiLevel](../../com.aspose.slides/bilevel) είναι ίσο με το τρέχον [BiLevel](../../com.aspose.slides/bilevel). |
| [hashCode()](#hashCode--) | Λειτουργεί ως συνάρτηση κατακερματισμού για έναν συγκεκριμένο τύπο. |
### getEffective() {#getEffective--}
```
public final IBiLevelEffectiveData getEffective()
```

Λαμβάνει τα αποτελεσματικά δεδομένα εφέ Bi-Level με την κληρονομικότητα εφαρμοσμένη.

**Επιστρέφει:**
[IBiLevelEffectiveData](../../com.aspose.slides/ibileveleffectivedata) - A [IBiLevelEffectiveData](../../com.aspose.slides/ibileveleffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Καθορίζει αν το συγκεκριμένο [BiLevel](../../com.aspose.slides/bilevel) είναι ίσο με το τρέχον [BiLevel](../../com.aspose.slides/bilevel).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj | java.lang.Object | Το [BiLevel](../../com.aspose.slides/bilevel) προς σύγκριση. |

**Επιστρέφει:**
boolean - true αν τα αντικείμενα είναι ίσα· διαφορετικά, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Λειτουργεί ως συνάρτηση κατακερματισμού για έναν συγκεκριμένο τύπο.

**Επιστρέφει:**
int - Ένας κωδικός κατακερματισμού για το τρέχον αντικείμενο.