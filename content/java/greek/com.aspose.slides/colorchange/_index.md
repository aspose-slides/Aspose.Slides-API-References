---
title: ColorChange
second_title: Αναφορά API Aspose.Slides για Java
description: Αντιπροσωπεύει ένα εφέ Αλλαγής Χρώματος.
type: docs
url: /el/com.aspose.slides/colorchange/
---
**Κληρονομικότητα:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Όλες οι υλοποιημένες διεπαφές:**
[com.aspose.slides.IColorChange](../../com.aspose.slides/icolorchange), com.aspose.slides.IVisualEffect
```
public final class ColorChange extends ImageTransformOperation implements IColorChange, IVisualEffect
```

Αντιπροσωπεύει ένα εφέ Αλλαγής Χρώματος. Οι παρουσίες του FromColor αντικαθίστανται με παρουσίες του ToColor.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getFromColor()](#getFromColor--) | Χρώμα που θα αντικατασταθεί. |
| [getToColor()](#getToColor--) | Χρώμα που θα αντικαταστήσει. |
| [getEffective()](#getEffective--) | Λαμβάνει τα αποτελεσματικά δεδομένα εφέ Αλλαγής Χρώματος με την κληρονομική εφαρμογή. |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Καθορίζει αν το καθορισμένο [ColorChange](../../com.aspose.slides/colorchange) είναι ίσο με το τρέχον [ColorChange](../../com.aspose.slides/colorchange). |
| [hashCode()](#hashCode--) | Λειτουργεί ως συνάρτηση κατακερματισμού για έναν συγκεκριμένο τύπο. |
### getFromColor() {#getFromColor--}
```
public final IColorFormat getFromColor()
```

Χρώμα που θα αντικατασταθεί. Μόνο για ανάγνωση [IColorFormat](../../com.aspose.slides/icolorformat).

**Επιστρέφει:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getToColor() {#getToColor--}
```
public final IColorFormat getToColor()
```

Χρώμα που θα αντικαταστήσει. Μόνο για ανάγνωση [IColorFormat](../../com.aspose.slides/icolorformat).

**Επιστρέφει:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffective() {#getEffective--}
```
public final IColorChangeEffectiveData getEffective()
```

Λαμβάνει τα αποτελεσματικά δεδομένα εφέ Αλλαγής Χρώματος με την κληρονομική εφαρμογή.

**Επιστρέφει:**
[IColorChangeEffectiveData](../../com.aspose.slides/icolorchangeeffectivedata) - Ένα [IColorChangeEffectiveData](../../com.aspose.slides/icolorchangeeffectivedata).
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

Καθορίζει αν το καθορισμένο [ColorChange](../../com.aspose.slides/colorchange) είναι ίσο με το τρέχον [ColorChange](../../com.aspose.slides/colorchange).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj | java.lang.Object | Το [ColorChange](../../com.aspose.slides/colorchange) για σύγκριση. |

**Επιστρέφει:**
boolean - true εάν τα αντικείμενα είναι ίσα· διαφορετικά, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Λειτουργεί ως συνάρτηση κατακερματισμού για έναν συγκεκριμένο τύπο.

**Επιστρέφει:**
int - Ένας κωδικός κατακερματισμού για το τρέχον αντικείμενο.