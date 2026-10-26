---
title: AlphaFloor
second_title: Aspose.Slides για Android μέσω Java API Reference
description: Αντιπροσωπεύει ένα εφέ Alpha Floor.
type: docs
url: /el/com.aspose.slides/alphafloor/
---
**Κληρονομικότητα:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IAlphaFloor](../../com.aspose.slides/ialphafloor), com.aspose.slides.IVisualEffect
```
public final class AlphaFloor extends ImageTransformOperation implements IAlphaFloor, IVisualEffect
```

Αναπαριστά ένα εφέ Alpha Floor. Οι τιμές Alpha (αδιαφάνειας) μικρότερες από 100% μετατρέπονται σε μηδέν. Με άλλα λόγια, ό,τι είναι εν μέρει διαφανούς γίνεται πλήρως διαφανές.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getEffective()](#getEffective--) | Λαμβάνει τα δεδομένα του εφέ Alpha Floor με την εφαρμοσμένη κληρονομικότητα. |
| [equals(Object obj)](#equals-java.lang.Object-) | Καθορίζει αν το καθορισμένο [AlphaFloor](../../com.aspose.slides/alphafloor) είναι ίσο με το τρέχον [AlphaFloor](../../com.aspose.slides/alphafloor). |
| [hashCode()](#hashCode--) | Λειτουργεί ως συνάρτηση κατατεματισμού (hash) για έναν συγκεκριμένο τύπο. |
### getEffective() {#getEffective--}
```
public final IAlphaFloorEffectiveData getEffective()
```


Λαμβάνει τα δεδομένα του εφέ Alpha Floor με την εφαρμοσμένη κληρονομικότητα.

**Επιστρέφει:**
[IAlphaFloorEffectiveData](../../com.aspose.slides/ialphaflooreffectivedata) - Ένα [IAlphaFloorEffectiveData](../../com.aspose.slides/ialphaflooreffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Καθορίζει αν το καθορισμένο [AlphaFloor](../../com.aspose.slides/alphafloor) είναι ίσο με το τρέχον [AlphaFloor](../../com.aspose.slides/alphafloor).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj | java.lang.Object | Το [AlphaFloor](../../com.aspose.slides/alphafloor) για σύγκριση. |

**Επιστρέφει:**
boolean - true εάν τα αντικείμενα είναι ίσα· διαφορετικά, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Λειτουργεί ως συνάρτηση κατατεματισμού (hash) για έναν συγκεκριμένο τύπο.

**Επιστρέφει:**
int - Ένας κωδικός hash για το τρέχον αντικείμενο.