---
title: Duotone
second_title: Αναφορά API Aspose.Slides για Java
description: Αναπαριστά ένα εφέ Duotone.
type: docs
url: /el/com.aspose.slides/duotone/
---
**Κληρονομικότητα:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IDuotone](../../com.aspose.slides/iduotone), com.aspose.slides.IVisualEffect
```
public final class Duotone extends ImageTransformOperation implements IDuotone, IVisualEffect
```

Αναπαριστά ένα εφέ Duotone. Για κάθε pixel, συνδυάζει το Color1 και το Color2 μέσω γραμμικής παρεμβολής για να προσδιορίσει το νέο χρώμα για εκείνο το pixel.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getColor1()](#getColor1--) | Επιστρέφει τη μορφή του χρώματος-στόχου για σκούρα pixels. |
| [getColor2()](#getColor2--) | Επιστρέφει τη μορφή του χρώματος-στόχου για φωτεινά pixels. |
| [getEffective()](#getEffective--) | Λαμβάνει τα δεδομένα του αποτελεσματικού εφέ Duotone με την κληρονομικότητα εφαρμοσμένη. |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Καθορίζει αν το καθορισμένο [Duotone](../../com.aspose.slides/duotone) είναι ίσο με το τρέχον [Duotone](../../com.aspose.slides/duotone). |
| [hashCode()](#hashCode--) | Λειτουργεί ως συνάρτηση κατακερματισμού για έναν συγκεκριμένο τύπο. |
### getColor1() {#getColor1--}
```
public final IColorFormat getColor1()
```


Επιστρέφει τη μορφή του χρώματος-στόχου για σκούρα pixels. Μόνο ανάγνωση [IColorFormat](../../com.aspose.slides/icolorformat).

**Επιστρέφει:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getColor2() {#getColor2--}
```
public final IColorFormat getColor2()
```


Επιστρέφει τη μορφή του χρώματος-στόχου για φωτεινά pixels. Μόνο ανάγνωση [IColorFormat](../../com.aspose.slides/icolorformat).

**Επιστρέφει:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffective() {#getEffective--}
```
public final IDuotoneEffectiveData getEffective()
```


Λαμβάνει τα δεδομένα του αποτελεσματικού εφέ Duotone με την κληρονομικότητα εφαρμοσμένη.

**Επιστρέφει:**
[IDuotoneEffectiveData](../../com.aspose.slides/iduotoneeffectivedata) - Ένα [IDuotoneEffectiveData](../../com.aspose.slides/iduotoneeffectivedata).
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


Καθορίζει αν το καθορισμένο [Duotone](../../com.aspose.slides/duotone) είναι ίσο με το τρέχον [Duotone](../../com.aspose.slides/duotone).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj | java.lang.Object | Το [Duotone](../../com.aspose.slides/duotone) προς σύγκριση. |

**Επιστρέφει:**
boolean - true εάν τα αντικείμενα είναι ίσα· διαφορετικά, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Λειτουργεί ως συνάρτηση κατακερματισμού για έναν συγκεκριμένο τύπο.

**Επιστρέφει:**
int - Ένας κώδικας κατακερματισμού για το τρέχον αντικείμενο.