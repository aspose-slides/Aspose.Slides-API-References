---
title: BiLevel
second_title: Aspose.Slides για Android μέσω Αναφοράς API Java
description: Αντιπροσωπεύει ένα Δι-Επίπεδο εφέ μαύρο/λευκό.
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

Αντιπροσωπεύει ένα Δι-Επίπεδο (μαύρο/λευκό) εφέ. Τα χρώματα εισόδου των οποίων η φωτεινότητα είναι μικρότερη από την καθορισμένη τιμή κατωφλίου μετατρέπονται σε μαύρο. Τα χρώματα εισόδου των οποίων η φωτεινότητα είναι μεγαλύτερη ή ίση με την καθορισμένη τιμή ορίζονται σε λευκό. Οι τιμές του αλφα εφέ δεν επηρεάζονται από αυτό το εφέ.

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getEffective()](#getEffective--) | Λαμβάνει τα αποτελεσματικά δεδομένα του Δι-Επίπεδου εφέ με την κληρονομικότητα εφαρμοσμένη. |
| [equals(Object obj)](#equals-java.lang.Object-) | Καθορίζει εάν το καθορισμένο [BiLevel](../../com.aspose.slides/bilevel) είναι ίσο με το τρέχον [BiLevel](../../com.aspose.slides/bilevel). |
| [hashCode()](#hashCode--) | Λειτουργεί ως συνάρτηση κατακερματισμού για έναν συγκεκριμένο τύπο. |

### getEffective() {#getEffective--}
```
public final IBiLevelEffectiveData getEffective()
```

Λαμβάνει τα αποτελεσματικά δεδομένα του Δι-Επίπεδου εφέ με την κληρονομικότητα εφαρμοσμένη.

**Επιστρέφει:**
[IBiLevelEffectiveData](../../com.aspose.slides/ibileveleffectivedata) - Ένα [IBiLevelEffectiveData](../../com.aspose.slides/ibileveleffectivedata).

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Καθορίζει εάν το καθορισμένο [BiLevel](../../com.aspose.slides/bilevel) είναι ίσο με το τρέχον [BiLevel](../../com.aspose.slides/bilevel).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj | java.lang.Object | Το [BiLevel](../../com.aspose.slides/bilevel) για σύγκριση. |

**Επιστρέφει:**
boolean - true εάν τα αντικείμενα είναι ίσα· διαφορετικά, false.

### hashCode() {#hashCode--}
```
public int hashCode()
```

Λειτουργεί ως συνάρτηση κατακερματισμού για έναν συγκεκριμένο τύπο.

**Επιστρέφει:**
int - Ένας κωδικός κατακερματισμού για το τρέχον αντικείμενο.