---
title: HSL
second_title: Aspose.Slides για την Java API Αναφορά
description: Αναπαριστά ένα εφέ Hue/Saturation/Luminance.
type: docs
url: /el/com.aspose.slides/hsl/
---
**Κληρονομικότητα:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IHSL](../../com.aspose.slides/ihsl), com.aspose.slides.IVisualEffect
```
public final class HSL extends ImageTransformOperation implements IHSL, IVisualEffect
```

Αναπαριστά ένα εφέ Hue/Saturation/Luminance. Η απόχρωση, ο κορεσμός και η φωτεινότητα μπορούν να ρυθμιστούν ανεξάρτητα ως προς την τρέχουσα τιμή τους.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getEffective()](#getEffective--) | Λαμβάνει τα αποτελεσματικά δεδομένα εφέ Hue/Saturation/Luminance με την κληρονομικότητα εφαρμοσμένη. |
| [equals(Object obj)](#equals-java.lang.Object-) | Καθορίζει εάν το συγκεκριμένο [HSL](../../com.aspose.slides/hsl) είναι ίσο με το τρέχον [HSL](../../com.aspose.slides/hsl). |
| [hashCode()](#hashCode--) | Λειτουργεί ως συνάρτηση κατακερματισμού για έναν συγκεκριμένο τύπο. |
### getEffective() {#getEffective--}
```
public final IHSLEffectiveData getEffective()
```

Λαμβάνει τα αποτελεσματικά δεδομένα εφέ Hue/Saturation/Luminance με την κληρονομικότητα εφαρμοσμένη.

**Επιστρέφει:**
[IHSLEffectiveData](../../com.aspose.slides/ihsleffectivedata) - Ένα [IHSLEffectiveData](../../com.aspose.slides/ihsleffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Καθορίζει εάν το συγκεκριμένο [HSL](../../com.aspose.slides/hsl) είναι ίσο με το τρέχον [HSL](../../com.aspose.slides/hsl).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj | java.lang.Object | Το [HSL](../../com.aspose.slides/hsl) προς σύγκριση. |

**Επιστρέφει:**
boolean - αληθές εάν τα αντικείμενα είναι ίσα· διαφορετικά, ψευδές.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Λειτουργεί ως συνάρτηση κατακερματισμού για έναν συγκεκριμένο τύπο.

**Επιστρέφει:**
int - Ένας κώδικας κατακερματισμού για το τρέχον αντικείμενο.