---
title: Duotone
second_title: Aspose.Slides για Android μέσω αναφοράς του Java API
description: Αντιπροσωπεύει ένα εφέ Duotone.
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

Αντιπροσωπεύει ένα εφέ Duotone. Για κάθε pixel, συνδυάζει τα Color1 και Color2 μέσω γραμμικής παρεμβολής για να προσδιορίσει το νέο χρώμα για εκείνο το pixel.

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getColor1()](#getColor1--) | Επιστρέφει τη μορφή χρώματος-στόχο για σκοτεινά pixel. |
| [getColor2()](#getColor2--) | Επιστρέφει τη μορφή χρώματος-στόχο για φωτεινά pixel. |
| [getEffective()](#getEffective--) | Λαμβάνει τα αποτελεσματικά δεδομένα του εφέ Duotone με την κληρονομικότητα εφαρμοσμένη. |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Καθορίζει αν το συγκεκριμένο [Duotone](../../com.aspose.slides/duotone) είναι ίσο με το τρέχον [Duotone](../../com.aspose.slides/duotone). |
| [hashCode()](#hashCode--) | Λειτουργεί ως συνάρτηση κατακερματισμού για έναν συγκεκριμένο τύπο. |

### getColor1() {#getColor1--}
```
public final IColorFormat getColor1()
```

Επιστρέφει τη μορφή χρώματος-στόχο για σκοτεινά pixel. Μόνο για ανάγνωση [IColorFormat](../../com.aspose.slides/icolorformat).

**Επιστρέφει:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getColor2() {#getColor2--}
```
public final IColorFormat getColor2()
```

Επιστρέφει τη μορφή χρώματος-στόχο για φωτεινά pixel. Μόνο για ανάγνωση [IColorFormat](../../com.aspose.slides/icolorformat).

**Επιστρέφει:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getEffective() {#getEffective--}
```
public final IDuotoneEffectiveData getEffective()
```

Λαμβάνει τα αποτελεσματικά δεδομένα του εφέ Duotone με την κληρονομικότητα εφαρμοσμένη.

**Επιστρέφει:**
[IDuotoneEffectiveData](../../com.aspose.slides/iduotoneeffectivedata) - A [IDuotoneEffectiveData](../../com.aspose.slides/iduotoneeffectivedata).

### getVersion() {#getVersion--}
```
public long getVersion()
```

Έκδοση. Μόνο για ανάγνωση long.

**Επιστρέφει:**
long

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Καθορίζει αν το συγκεκριμένο [Duotone](../../com.aspose.slides/duotone) είναι ίσο με το τρέχον [Duotone](../../com.aspose.slides/duotone).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj | java.lang.Object | Το [Duotone](../../com.aspose.slides/duotone) προς σύγκριση. |

**Επιστρέφει:**
boolean - αληθές εάν τα αντικείμενα είναι ίσα· διαφορετικά, ψευδές.

### hashCode() {#hashCode--}
```
public int hashCode()
```

Λειτουργεί ως συνάρτηση κατακερματισμού για έναν συγκεκριμένο τύπο.

**Επιστρέφει:**
int - Ένας κωδικός κατακερματισμού για το τρέχον αντικείμενο.