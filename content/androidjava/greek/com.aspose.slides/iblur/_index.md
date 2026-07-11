---
title: IBlur
second_title: Aspose.Slides για Android μέσω Java API Αναφορά
description: Αναπαριστά ένα εφέ θολώματος που εφαρμόζεται σε ολόκληρο το σχήμα, συμπεριλαμβανομένου του γεμίσματος του.
type: docs
url: /el/com.aspose.slides/iblur/
---
**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IBlur extends IImageTransformOperation, IAccessiblePVIObject<IBlurEffectiveData>
```

Αναπαριστά ένα εφέ θολώματος που εφαρμόζεται σε ολόκληρο το σχήμα, συμπεριλαμβανομένου του γεμίσματος του. Όλα τα χρωματικά κανάλια, συμπεριλαμβανομένου του άλφα, επηρεάζονται.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getRadius()](#getRadius--) | Επιστρέφει ή ορίζει την ακτίνα θολώματος. |
| [setRadius(double value)](#setRadius-double-) | Επιστρέφει ή ορίζει την ακτίνα θολώματος. |
| [getGrow()](#getGrow--) | Καθορίζει εάν τα όρια του αντικειμένου πρέπει να επεκταθούν ως αποτέλεσμα του θολώματος. |
| [setGrow(boolean value)](#setGrow-boolean-) | Καθορίζει εάν τα όρια του αντικειμένου πρέπει να επεκταθούν ως αποτέλεσμα του θολώματος. |
### getRadius() {#getRadius--}
```
public abstract double getRadius()
```


Επιστρέφει ή ορίζει την ακτίνα θολώματος. Ανάγνωση/εγγραφή double.

**Επιστροφή:**
double
### setRadius(double value) {#setRadius-double-}
```
public abstract void setRadius(double value)
```


Επιστρέφει ή ορίζει την ακτίνα θολώματος. Ανάγνωση/εγγραφή double.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | double |  |

### getGrow() {#getGrow--}
```
public abstract boolean getGrow()
```


Καθορίζει εάν τα όρια του αντικειμένου πρέπει να επεκταθούν ως αποτέλεσμα του θολώματος. Η τιμή true υποδεικνύει ότι τα όρια επεκτείνονται, ενώ false ότι δεν επεκτείνονται. Ανάγνωση/εγγραφή boolean.

**Επιστροφή:**
boolean
### setGrow(boolean value) {#setGrow-boolean-}
```
public abstract void setGrow(boolean value)
```


Καθορίζει εάν τα όρια του αντικειμένου πρέπει να επεκταθούν ως αποτέλεσμα του θολώματος. Η τιμή true υποδεικνύει ότι τα όρια επεκτείνονται, ενώ false ότι δεν επεκτείνονται. Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |