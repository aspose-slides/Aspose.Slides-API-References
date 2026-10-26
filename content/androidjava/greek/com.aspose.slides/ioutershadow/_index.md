---
title: IOuterShadow
second_title: Aspose.Slides για Android μέσω Αναφοράς Java API
description: Αντιπροσωπεύει ένα εφέ Εξωτερικής Σκιάς.
type: docs
url: /el/com.aspose.slides/ioutershadow/
---
**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IOuterShadow extends IImageTransformOperation, IAccessiblePVIObject<IOuterShadowEffectiveData>
```

Αντιπροσωπεύει ένα εφέ Εξωτερικής Σκιάς.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getBlurRadius()](#getBlurRadius--) | Ακτίνα θολώματος, σε σημεία. |
| [setBlurRadius(double value)](#setBlurRadius-double-) | Ακτίνα θολώματος, σε σημεία. |
| [getDirection()](#getDirection--) | Κατεύθυνση της σκιάς, σε μοίρες. |
| [setDirection(float value)](#setDirection-float-) | Κατεύθυνση της σκιάς, σε μοίρες. |
| [getDistance()](#getDistance--) | Απόσταση της σκιάς από το αντικείμενο, σε σημεία. |
| [setDistance(double value)](#setDistance-double-) | Απόσταση της σκιάς από το αντικείμενο, σε σημεία. |
| [getShadowColor()](#getShadowColor--) | Χρώμα της σκιάς. |
| [getRectangleAlign()](#getRectangleAlign--) | Στοίχιση του ορθογωνίου. |
| [setRectangleAlign(byte value)](#setRectangleAlign-byte-) | Στοίχιση του ορθογωνίου. |
| [getSkewHorizontal()](#getSkewHorizontal--) | Οριζόντια γωνία παραμόρφωσης, σε μοίρες. |
| [setSkewHorizontal(double value)](#setSkewHorizontal-double-) | Οριζόντια γωνία παραμόρφωσης, σε μοίρες. |
| [getSkewVertical()](#getSkewVertical--) | Κάθετη γωνία παραμόρφωσης, σε μοίρες. |
| [setSkewVertical(double value)](#setSkewVertical-double-) | Κάθετη γωνία παραμόρφωσης, σε μοίρες. |
| [getRotateShadowWithShape()](#getRotateShadowWithShape--) | Δείχνει αν η σκιά περιστρέφεται μαζί με το σχήμα. |
| [setRotateShadowWithShape(boolean value)](#setRotateShadowWithShape-boolean-) | Δείχνει αν η σκιά περιστρέφεται μαζί με το σχήμα. |
| [getScaleHorizontal()](#getScaleHorizontal--) | Οριζόντιος παράγοντας κλίμακας, σε ποσοστό του αρχικού μεγέθους. |
| [setScaleHorizontal(double value)](#setScaleHorizontal-double-) | Οριζόντιος παράγοντας κλίμακας, σε ποσοστό του αρχικού μεγέθους. |
| [getScaleVertical()](#getScaleVertical--) | Κάθετος παράγοντας κλίμακας, σε ποσοστό του αρχικού μεγέθους. |
| [setScaleVertical(double value)](#setScaleVertical-double-) | Κάθετος παράγοντας κλίμακας, σε ποσοστό του αρχικού μεγέθους. |
### getBlurRadius() {#getBlurRadius--}
```
public abstract double getBlurRadius()
```


Ακτίνα θολώματος, σε σημεία. Προεπιλεγμένη τιμή - 0 pt. Ανάγνωση/εγγραφή double.

**Επιστρέφει:**
double
### setBlurRadius(double value) {#setBlurRadius-double-}
```
public abstract void setBlurRadius(double value)
```


Ακτίνα θολώματος, σε σημεία. Προεπιλεγμένη τιμή - 0 pt. Ανάγνωση/εγγραφή double.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | double |  |

### getDirection() {#getDirection--}
```
public abstract float getDirection()
```


Κατεύθυνση της σκιάς, σε μοίρες. Προεπιλεγμένη τιμή - 0 � (αριστερό προς δεξί). Ανάγνωση/εγγραφή float.

**Επιστρέφει:**
float
### setDirection(float value) {#setDirection-float-}
```
public abstract void setDirection(float value)
```


Κατεύθυνση της σκιάς, σε μοίρες. Προεπιλεγμένη τιμή - 0 � (αριστερό προς δεξί). Ανάγνωση/εγγραφή float.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |

### getDistance() {#getDistance--}
```
public abstract double getDistance()
```


Απόσταση της σκιάς από το αντικείμενο, σε σημεία. Προεπιλεγμένη τιμή - 0 pt. Ανάγνωση/εγγραφή double.

**Επιστρέφει:**
double
### setDistance(double value) {#setDistance-double-}
```
public abstract void setDistance(double value)
```


Απόσταση της σκιάς από το αντικείμενο, σε σημεία. Προεπιλεγμένη τιμή - 0 pt. Ανάγνωση/εγγραφή double.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | double |  |

### getShadowColor() {#getShadowColor--}
```
public abstract IColorFormat getShadowColor()
```


Χρώμα της σκιάς. Προεπιλεγμένη τιμή - αυτόματο μαύρο (εξαρτάται από το θέμα). Μόνο ανάγνωση [IColorFormat](../../com.aspose.slides/icolorformat).

**Επιστρέφει:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getRectangleAlign() {#getRectangleAlign--}
```
public abstract byte getRectangleAlign()
```


Στοίχιση του ορθογωνίου. Προεπιλεγμένη τιμή - [RectangleAlignment.Bottom](../../com.aspose.slides/rectanglealignment\#Bottom). Ανάγνωση/εγγραφή [RectangleAlignment](../../com.aspose.slides/rectanglealignment).

**Επιστρέφει:**
byte
### setRectangleAlign(byte value) {#setRectangleAlign-byte-}
```
public abstract void setRectangleAlign(byte value)
```


Στοίχιση του ορθογωνίου. Προεπιλεγμένη τιμή - [RectangleAlignment.Bottom](../../com.aspose.slides/rectanglealignment\#Bottom). Ανάγνωση/εγγραφή [RectangleAlignment](../../com.aspose.slides/rectanglealignment).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte |  |

### getSkewHorizontal() {#getSkewHorizontal--}
```
public abstract double getSkewHorizontal()
```


Οριζόντια γωνία παραμόρφωσης, σε μοίρες. Προεπιλεγμένη τιμή - 0 �. Ανάγνωση/εγγραφή double.

**Επιστρέφει:**
double
### setSkewHorizontal(double value) {#setSkewHorizontal-double-}
```
public abstract void setSkewHorizontal(double value)
```


Οριζόντια γωνία παραμόρφωσης, σε μοίρες. Προεπιλεγμένη τιμή - 0 �. Ανάγνωση/εγγραφή double.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | double |  |

### getSkewVertical() {#getSkewVertical--}
```
public abstract double getSkewVertical()
```


Κάθετη γωνία παραμόρφωσης, σε μοίρες. Προεπιλεγμένη τιμή - 0 �. Ανάγνωση/εγγραφή double.

**Επιστρέφει:**
double
### setSkewVertical(double value) {#setSkewVertical-double-}
```
public abstract void setSkewVertical(double value)
```


Κάθετη γωνία παραμόρφωσης, σε μοίρες. Προεπιλεγμένη τιμή - 0 �. Ανάγνωση/εγγραφή double.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | double |  |

### getRotateShadowWithShape() {#getRotateShadowWithShape--}
```
public abstract boolean getRotateShadowWithShape()
```


Δείχνει αν η σκιά περιστρέφεται μαζί με το σχήμα. Προεπιλεγμένη τιμή - true. Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**
boolean
### setRotateShadowWithShape(boolean value) {#setRotateShadowWithShape-boolean-}
```
public abstract void setRotateShadowWithShape(boolean value)
```


Δείχνει αν η σκιά περιστρέφεται μαζί με το σχήμα. Προεπιλεγμένη τιμή - true. Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getScaleHorizontal() {#getScaleHorizontal--}
```
public abstract double getScaleHorizontal()
```


Οριζόντιος παράγοντας κλίμακας, σε ποσοστό του αρχικού μεγέθους. Αρνητική κλίμακα προκαλεί αναστροφή. Προεπιλεγμένη τιμή - 100 %. Ανάγνωση/εγγραφή double.

**Επιστρέφει:**
double
### setScaleHorizontal(double value) {#setScaleHorizontal-double-}
```
public abstract void setScaleHorizontal(double value)
```


Οριζόντιος παράγοντας κλίμακας, σε ποσοστό του αρχικού μεγέθους. Αρνητική κλίμακα προκαλεί αναστροφή. Προεπιλεγμένη τιμή - 100 %. Ανάγνωση/εγγραφή double.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | double |  |

### getScaleVertical() {#getScaleVertical--}
```
public abstract double getScaleVertical()
```


Κάθετος παράγοντας κλίμακας, σε ποσοστό του αρχικού μεγέθους. Αρνητική κλίμακα προκαλεί αναστροφή. Προεπιλεγμένη τιμή - 100 %. Ανάγνωση/εγγραφή double.

**Επιστρέφει:**
double
### setScaleVertical(double value) {#setScaleVertical-double-}
```
public abstract void setScaleVertical(double value)
```


Κάθετος παράγοντας κλίμακας, σε ποσοστό του αρχικού μεγέθους. Αρνητική κλίμακα προκαλεί αναστροφή. Προεπιλεγμένη τιμή - 100 %. Ανάγνωση/εγγραφή double.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | double |  |