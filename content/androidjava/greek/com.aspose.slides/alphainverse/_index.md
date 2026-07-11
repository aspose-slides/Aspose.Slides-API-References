---
title: AlphaInverse
second_title: Aspose.Slides για Android μέσω Αναφοράς Java API
description: Αντιπροσωπεύει ένα εφέ Alpha Inverse.
type: docs
url: /el/com.aspose.slides/alphainverse/
---
**Κληρονομικότητα:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IAlphaInverse](../../com.aspose.slides/ialphainverse), com.aspose.slides.IVisualEffect
```
public final class AlphaInverse extends ImageTransformOperation implements IAlphaInverse, IVisualEffect
```

Αντιπροσωπεύει ένα εφέ Αντίστροφης Άλφα. Οι τιμές Alpha (διαφάνειας) αντιστρέφονται αφαιρώντας από το 100%.
## Methods

| Method | Description |
| --- | --- |
| [getEffective()](#getEffective--) | Λαμβάνει τα αποτελεσματικά δεδομένα εφέ Αντίστροφης Άλφα με την κληρονομικότητα εφαρμοσμένη. |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Καθορίζει εάν το καθορισμένο [AlphaInverse](../../com.aspose.slides/alphainverse) είναι ίσο με το τρέχον [AlphaInverse](../../com.aspose.slides/alphainverse). |
| [hashCode()](#hashCode--) | Λειτουργεί ως συνάρτηση κατακερματισμού για έναν συγκεκριμένο τύπο. |
### getEffective() {#getEffective--}
```
public final IAlphaInverseEffectiveData getEffective()
```

Λαμβάνει τα αποτελεσματικά δεδομένα εφέ Αντίστροφης Άλφα με την κληρονομικότητα εφαρμοσμένη.

**Επιστρέφει:**
[IAlphaInverseEffectiveData](../../com.aspose.slides/ialphainverseeffectivedata) - Ένα [IAlphaInverseEffectiveData](../../com.aspose.slides/ialphainverseeffectivedata).
### getVersion() {#getVersion--}
```
public long getVersion()
```

Έκδοση. Μόνο για ανάγνωση τύπου long.

**Επιστρέφει:**
long
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Καθορίζει εάν το καθορισμένο [AlphaInverse](../../com.aspose.slides/alphainverse) είναι ίσο με το τρέχον [AlphaInverse](../../com.aspose.slides/alphainverse).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | Το [AlphaInverse](../../com.aspose.slides/alphainverse) προς σύγκριση. |

**Επιστρέφει:**
boolean - αληθές εάν τα αντικείμενα είναι ίσα· διαφορετικά, ψευδές.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Λειτουργεί ως συνάρτηση κατακερματισμού για έναν συγκεκριμένο τύπο.

**Επιστρέφει:**
int - Ένας κώδικας κατακερματισμού για το τρέχον αντικείμενο.