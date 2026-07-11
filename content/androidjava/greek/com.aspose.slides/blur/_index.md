---
title: Blur
second_title: Aspose.Slides για Android μέσω Java API Αναφορά
description: Αναπαριστά ένα εφέ θολώματος που εφαρμόζεται σε ολόκληρο το σχήμα, συμπεριλαμβανομένου του γεμίσματος.
type: docs
url: /el/com.aspose.slides/blur/
---
**Κληρονομικότητα:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Όλες οι υλοποιημένες διεπαφές:**
[com.aspose.slides.IBlur](../../com.aspose.slides/iblur), com.aspose.slides.IVisualEffect
```
public final class Blur extends ImageTransformOperation implements IBlur, IVisualEffect
```

Αναπαριστά ένα εφέ θολώματος που εφαρμόζεται σε ολόκληρο το σχήμα, συμπεριλαμβανομένου του γεμίσματος του. Όλα τα κανάλια χρώματος, συμπεριλαμβανομένου του άλφα, επηρεάζονται.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getRadius()](#getRadius--) | Επιστρέφει ή ορίζει την ακτίνα θολώματος. |
| [setRadius(double value)](#setRadius-double-) | Επιστρέφει ή ορίζει την ακτίνα θολώματος. |
| [getGrow()](#getGrow--) | Καθορίζει εάν τα όρια του αντικειμένου πρέπει να αυξηθούν ως αποτέλεσμα του θολώματος. |
| [setGrow(boolean value)](#setGrow-boolean-) | Καθορίζει εάν τα όρια του αντικειμένου πρέπει να αυξηθούν ως αποτέλεσμα του θολώματος. |
| [getEffective()](#getEffective--) | Λαμβάνει τα αποτελεσματικά δεδομένα εφέ θολώματος με την κληρονόμηση εφαρμοσμένη. |
| [equals(Object obj)](#equals-java.lang.Object-) | Καθορίζει εάν το καθορισμένο [Blur](../../com.aspose.slides/blur) είναι ίσο με το τρέχον [Blur](../../com.aspose.slides/blur). |
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

Καθορίζει εάν τα όρια του αντικειμένου πρέπει να αυξηθούν ως αποτέλεσμα του θολώματος. Η τιμή true υποδεικνύει ότι τα όρια αυξάνονται, ενώ η τιμή false υποδεικνύει ότι δεν αυξάνονται. Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**
boolean
### setGrow(boolean value) {#setGrow-boolean-}
```
public final void setGrow(boolean value)
```

Καθορίζει εάν τα όρια του αντικειμένου πρέπει να αυξηθούν ως αποτέλεσμα του θολώματος. Η τιμή true υποδεικνύει ότι τα όρια αυξάνονται, ενώ η τιμή false υποδεικνύει ότι δεν αυξάνονται. Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getEffective() {#getEffective--}
```
public final IBlurEffectiveData getEffective()
```

Λαμβάνει τα αποτελεσματικά δεδομένα εφέ θολώματος με την κληρονόμηση εφαρμοσμένη.

**Επιστρέφει:**
[IBlurEffectiveData](../../com.aspose.slides/iblureffectivedata) - A [IBlurEffectiveData](../../com.aspose.slides/iblureffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Καθορίζει εάν το καθορισμένο [Blur](../../com.aspose.slides/blur) είναι ίσο με το τρέχον [Blur](../../com.aspose.slides/blur).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj | java.lang.Object | Το [Blur](../../com.aspose.slides/blur) προς σύγκριση. |

**Επιστρέφει:**
boolean - true εάν τα αντικείμενα είναι ίσα· διαφορετικά, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Λειτουργεί ως συνάρτηση κατακερματισμού για έναν συγκεκριμένο τύπο.

**Επιστρέφει:**
int - Ένας κωδικός κατακερματισμού για το τρέχον αντικείμενο.