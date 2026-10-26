---
title: GrayScale
second_title: Aspose.Slides για Android μέσω αναφοράς Java API
description: Αναπαριστά ένα εφέ κλίμακας του γκρι.
type: docs
url: /el/com.aspose.slides/grayscale/
---
**Κληρονομικότητα:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IGrayScale](../../com.aspose.slides/igrayscale), com.aspose.slides.IVisualEffect
```
public final class GrayScale extends ImageTransformOperation implements IGrayScale, IVisualEffect
```

Αναπαριστά ένα εφέ κλίμακας του γκρι. Μετατρέπει όλες τις τιμές χρώματος του εφέ σε μια απόχρωση του γκρι, που αντιστοιχεί στη φωτεινότητά τους. Οι τιμές άλφα (διαφάνειας) του εφέ δεν επηρεάζονται.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getEffective()](#getEffective--) | Gets effective Gray Scale effect data with the inheritance applied. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determines whether the specified [GrayScale](../../com.aspose.slides/grayscale) is equal to the current [GrayScale](../../com.aspose.slides/grayscale). |
| [hashCode()](#hashCode--) | Serves as a hash function for a particular type. |
### getEffective() {#getEffective--}
```
public final IGrayScaleEffectiveData getEffective()
```

Λαμβάνει τα αποτελεσματικά δεδομένα εφέ κλίμακας του γκρι με την κληρονομικότητα να έχει εφαρμοστεί.

**Επιστρέφει:**
[IGrayScaleEffectiveData](../../com.aspose.slides/igrayscaleeffectivedata) - Ένα [IGrayScaleEffectiveData](../../com.aspose.slides/igrayscaleeffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Καθορίζει αν το καθορισμένο [GrayScale](../../com.aspose.slides/grayscale) είναι ίσο με το τρέχον [GrayScale](../../com.aspose.slides/grayscale).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj | java.lang.Object | Το [GrayScale](../../com.aspose.slides/grayscale) προς σύγκριση. |

**Επιστρέφει:**
boolean - true if objects are equal; otherwise, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Λειτουργεί ως συνάρτηση κατακερματισμού για έναν συγκεκριμένο τύπο.

**Επιστρέφει:**
int - Ένας κωδικός κατακερματισμού για το τρέχον αντικείμενο.