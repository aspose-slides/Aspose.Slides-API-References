---
title: Blur
second_title: Αναφορά API του Aspose.Slides για Java
description: Αναπαριστά ένα εφέ Blur που εφαρμόζεται σε ολόκληρο το σχήμα, συμπεριλαμβανομένου του γεμίσματος.
type: docs
url: /el/com.aspose.slides/blur/
---
**Κληρονομικότητα:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IBlur](../../com.aspose.slides/iblur), com.aspose.slides.IVisualEffect
```
public final class Blur extends ImageTransformOperation implements IBlur, IVisualEffect
```

Αναπαριστά ένα εφέ Blur που εφαρμόζεται σε ολόκληρο το σχήμα, συμπεριλαμβανομένου του γεμίσματος. Όλα τα κανάλια χρώματος, συμπεριλαμβανομένου του alpha, επηρεάζονται.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getRadius()](#getRadius--) | Επιστρέφει ή ορίζει την ακτίνα θολώματος. |
| [setRadius(double value)](#setRadius-double-) | Επιστρέφει ή ορίζει την ακτίνα θολώματος. |
| [getGrow()](#getGrow--) | Καθορίζει αν τα όρια του αντικειμένου πρέπει να αυξηθούν ως αποτέλεσμα της θόλωσης. |
| [setGrow(boolean value)](#setGrow-boolean-) | Καθορίζει αν τα όρια του αντικειμένου πρέπει να αυξηθούν ως αποτέλεσμα της θόλωσης. |
| [getEffective()](#getEffective--) | Λαμβάνει τα δεδομένα του εφέ Blur με την κληρονομικότητα εφαρμοσμένη. |
| [equals(Object obj)](#equals-java.lang.Object-) | Καθορίζει αν το καθορισμένο [Blur](../../com.aspose.slides/blur) είναι ισότιμο με το τρέχον [Blur](../../com.aspose.slides/blur). |
| [hashCode()](#hashCode--) | Λειτουργεί ως συνάρτηση κατακερματισμού για έναν συγκεκριμένο τύπο. |
### getRadius() {#getRadius--}
```
public final double getRadius()
```


Επιστρέφει ή ορίζει την ακτίνα θολώματος. Ανάγνωση/εγγραφή double.

**Επιστρέφει:**
double
### setRadius(double value) {#setRadius-double-}
```
public final void setRadius(double value)
```


Επιστρέφει ή ορίζει την ακτίνα θολώματος. Ανάγνωση/εγγραφή double.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | double |  |

### getGrow() {#getGrow--}
```
public final boolean getGrow()
```


Καθορίζει αν τα όρια του αντικειμένου πρέπει να αυξηθούν ως αποτέλεσμα της θόλωσης. Η τιμή true υποδεικνύει ότι τα όρια αυξάνονται, ενώ false υποδεικνύει ότι δεν αυξάνονται. Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**
boolean
### setGrow(boolean value) {#setGrow-boolean-}
```
public final void setGrow(boolean value)
```


Καθορίζει αν τα όρια του αντικειμένου πρέπει να αυξηθούν ως αποτέλεσμα της θόλωσης. Η τιμή true υποδεικνύει ότι τα όρια αυξάνονται, ενώ false υποδεικνύει ότι δεν αυξάνονται. Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getEffective() {#getEffective--}
```
public final IBlurEffectiveData getEffective()
```


Λαμβάνει τα δεδομένα του εφέ Blur με την κληρονομικότητα εφαρμοσμένη.

**Επιστρέφει:**
[IBlurEffectiveData](../../com.aspose.slides/iblureffectivedata) - A [IBlurEffectiveData](../../com.aspose.slides/iblureffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Καθορίζει αν το καθορισμένο [Blur](../../com.aspose.slides/blur) είναι ισότιμο με το τρέχον [Blur](../../com.aspose.slides/blur).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj | java.lang.Object | The [Blur](../../com.aspose.slides/blur) to compare. |

**Επιστρέφει:**
boolean - true if objects are equal; otherwise, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Λειτουργεί ως συνάρτηση κατακερματισμού για έναν συγκεκριμένο τύπο.

**Επιστρέφει:**
int - A hash code for the current object.