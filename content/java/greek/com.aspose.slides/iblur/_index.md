---
title: IBlur
second_title: Αναφορά API του Aspose.Slides για Java
description: Αναπαριστά ένα εφέ θολώματος που εφαρμόζεται σε ολόκληρο το σχήμα, συμπεριλαμβανομένου του γεμίσματος.
type: docs
url: /el/com.aspose.slides/iblur/
---
**All Implemented Interfaces:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IBlur extends IImageTransformOperation, IAccessiblePVIObject<IBlurEffectiveData>
```

Αντιπροσωπεύει ένα εφέ θολώματος που εφαρμόζεται σε ολόκληρο το σχήμα, συμπεριλαμβανομένου του γεμίσματος. Όλα τα κανάλια χρώματος, συμπεριλαμβανομένου του άλφα, επηρεάζονται.
## Methods

| Method | Description |
| --- | --- |
| [getRadius()](#getRadius--) | Επιστρέφει ή ορίζει την ακτίνα θολώματος. |
| [setRadius(double value)](#setRadius-double-) | Επιστρέφει ή ορίζει την ακτίνα θολώματος. |
| [getGrow()](#getGrow--) | Καθορίζει αν τα όρια του αντικειμένου πρέπει να αυξηθούν ως αποτέλεσμα του θολώματος. |
| [setGrow(boolean value)](#setGrow-boolean-) | Καθορίζει αν τα όρια του αντικειμένου πρέπει να αυξηθούν ως αποτέλεσμα του θολώματος. |
### getRadius() {#getRadius--}
```
public abstract double getRadius()
```


Επιστρέφει ή ορίζει την ακτίνα θολώματος. Ανάγνωση/εγγραφή double.

**Returns:**
double
### setRadius(double value) {#setRadius-double-}
```
public abstract void setRadius(double value)
```


Επιστρέφει ή ορίζει την ακτίνα θολώματος. Ανάγνωση/εγγραφή double.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getGrow() {#getGrow--}
```
public abstract boolean getGrow()
```


Καθορίζει αν τα όρια του αντικειμένου πρέπει να αυξηθούν ως αποτέλεσμα του θολώματος. Το true υποδηλώνει ότι τα όρια αυξάνονται, ενώ το false υποδηλώνει ότι δεν αυξάνονται. Ανάγνωση/εγγραφή boolean.

**Returns:**
boolean
### setGrow(boolean value) {#setGrow-boolean-}
```
public abstract void setGrow(boolean value)
```


Καθορίζει αν τα όρια του αντικειμένου πρέπει να αυξηθούν ως αποτέλεσμα του θολώματος. Το true υποδηλώνει ότι τα όρια αυξάνονται, ενώ το false υποδηλώνει ότι δεν αυξάνονται. Ανάγνωση/εγγραφή boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |