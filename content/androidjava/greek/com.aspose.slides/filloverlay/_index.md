---
title: FillOverlay
second_title: Aspose.Slides για Android μέσω αναφοράς API Java
description: Αναπαριστά ένα εφέ Fill Overlay.
type: docs
url: /el/com.aspose.slides/filloverlay/
---
**Κληρονομικότητα:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IFillOverlay](../../com.aspose.slides/ifilloverlay), com.aspose.slides.IVisualEffect
```
public final class FillOverlay extends ImageTransformOperation implements IFillOverlay, IVisualEffect
```

Παραθέτει ένα εφέ Fill Overlay. Ένα fill overlay μπορεί να χρησιμοποιηθεί για να καθορίσει ένα επιπλέον γέμισμα για ένα αντικείμενο και να αναμείξει τα δύο γέμισματα μαζί.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | Μορφή γεμίσματος. |
| [getBlend()](#getBlend--) | FillBlendMode. |
| [setBlend(int value)](#setBlend-int-) | FillBlendMode. |
| [getEffective()](#getEffective--) | Λαμβάνει τα αποτελεσματικά δεδομένα του εφέ Fill Overlay με την κληρονόμηση εφαρμόσμένη. |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Καθορίζει εάν το συγκεκριμένο [FillOverlay](../../com.aspose.slides/filloverlay) είναι ίσο με το τρέχον [FillOverlay](../../com.aspose.slides/filloverlay). |
| [hashCode()](#hashCode--) | Λειτουργεί ως συνάρτηση κατακερματισμού για έναν συγκεκριμένο τύπο. |
### getFillFormat() {#getFillFormat--}
```
public final IFillFormat getFillFormat()
```


Μορφή γεμίσματος. Μόνο ανάγνωση [IFillFormat](../../com.aspose.slides/ifillformat).

**Επιστρέφει:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getBlend() {#getBlend--}
```
public final int getBlend()
```


FillBlendMode. Ανάγνωση/εγγραφή [FillBlendMode](../../com.aspose.slides/fillblendmode).

**Επιστρέφει:**
int
### setBlend(int value) {#setBlend-int-}
```
public final void setBlend(int value)
```


FillBlendMode. Ανάγνωση/εγγραφή [FillBlendMode](../../com.aspose.slides/fillblendmode).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getEffective() {#getEffective--}
```
public final IFillOverlayEffectiveData getEffective()
```


Λαμβάνει τα αποτελεσματικά δεδομένα του εφέ Fill Overlay με την κληρονόμηση εφαρμόσμένη.

**Επιστρέφει:**
[IFillOverlayEffectiveData](../../com.aspose.slides/ifilloverlayeffectivedata) - Ένα [IFillOverlayEffectiveData](../../com.aspose.slides/ifilloverlayeffectivedata).
### getVersion() {#getVersion--}
```
public long getVersion()
```


Έκδοση. Μόνο ανάγνωση long.

**Επιστρέφει:**
long
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Καθορίζει εάν το συγκεκριμένο [FillOverlay](../../com.aspose.slides/filloverlay) είναι ίσο με το τρέχον [FillOverlay](../../com.aspose.slides/filloverlay).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj | java.lang.Object | Το [FillOverlay](../../com.aspose.slides/filloverlay) για σύγκριση. |

**Επιστρέφει:**
boolean - true εάν τα αντικείμενα είναι ίσα· διαφορετικά, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Λειτουργεί ως συνάρτηση κατακερματισμού για έναν συγκεκριμένο τύπο.

**Επιστρέφει:**
int - Ένας κωδικός κατακερματισμού για το τρέχον αντικείμενο.