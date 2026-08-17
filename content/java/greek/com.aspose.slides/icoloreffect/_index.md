---
title: IColorEffect
second_title: Aspose.Slides για την Αναφορά API Java
description: Αντιπροσωπεύει ένα χρωματικό εφέ για μια συμπεριφορά κίνησης.
type: docs
url: /el/com.aspose.slides/icoloreffect/
---
**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IBehavior](../../com.aspose.slides/ibehavior)
```
public interface IColorEffect extends IBehavior
```

Αντιπροσωπεύει ένα χρωματικό εφέ για μια συμπεριφορά κίνησης.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getFrom()](#getFrom--) | This value is used to specify the starting color of behavior. |
| [setFrom(IColorFormat value)](#setFrom-com.aspose.slides.IColorFormat-) | This value is used to specify the starting color of behavior. |
| [getTo()](#getTo--) | Describes resulting color for the animation color change. |
| [setTo(IColorFormat value)](#setTo-com.aspose.slides.IColorFormat-) | Describes resulting color for the animation color change. |
| [getBy()](#getBy--) | Describes the relative offset value for the color animation. |
| [setBy(IColorOffset value)](#setBy-com.aspose.slides.IColorOffset-) | Describes the relative offset value for the color animation. |
| [getColorSpace()](#getColorSpace--) | Represent color space of behavior. |
| [setColorSpace(int value)](#setColorSpace-int-) | Represent color space of behavior. |
| [getDirection()](#getDirection--) | Specifies which direction to cycle the hue around the color wheel. |
| [setDirection(int value)](#setDirection-int-) | Specifies which direction to cycle the hue around the color wheel. |
### getFrom() {#getFrom--}
```
public abstract IColorFormat getFrom()
```

Αυτή η τιμή χρησιμοποιείται για τον καθορισμό του αρχικού χρώματος της συμπεριφοράς. Ανάγνωση/εγγραφή [IColorFormat](../../com.aspose.slides/icolorformat).

**Επιστρέφει:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### setFrom(IColorFormat value) {#setFrom-com.aspose.slides.IColorFormat-}
```
public abstract void setFrom(IColorFormat value)
```

Αυτή η τιμή χρησιμοποιείται για τον καθορισμό του αρχικού χρώματος της συμπεριφοράς. Ανάγνωση/εγγραφή [IColorFormat](../../com.aspose.slides/icolorformat).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IColorFormat](../../com.aspose.slides/icolorformat) |  |
### getTo() {#getTo--}
```
public abstract IColorFormat getTo()
```

Περιγράφει το τελικό χρώμα για την αλλαγή χρώματος της κίνησης. Ανάγνωση/εγγραφή [IColorFormat](../../com.aspose.slides/icolorformat).

**Επιστρέφει:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### setTo(IColorFormat value) {#setTo-com.aspose.slides.IColorFormat-}
```
public abstract void setTo(IColorFormat value)
```

Περιγράφει το τελικό χρώμα για την αλλαγή χρώματος της κίνησης. Ανάγνωση/εγγραφή [IColorFormat](../../com.aspose.slides/icolorformat).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IColorFormat](../../com.aspose.slides/icolorformat) |  |
### getBy() {#getBy--}
```
public abstract IColorOffset getBy()
```

Περιγράφει τη σχετική τιμή μετατόπισης για την κίνηση χρώματος. Ανάγνωση/εγγραφή [IColorOffset](../../com.aspose.slides/icoloroffset).

**Επιστρέφει:**
[IColorOffset](../../com.aspose.slides/icoloroffset)
### setBy(IColorOffset value) {#setBy-com.aspose.slides.IColorOffset-}
```
public abstract void setBy(IColorOffset value)
```

Περιγράφει τη σχετική τιμή μετατόπισης για την κίνηση χρώματος. Ανάγνωση/εγγραφή [IColorOffset](../../com.aspose.slides/icoloroffset).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IColorOffset](../../com.aspose.slides/icoloroffset) |  |
### getColorSpace() {#getColorSpace--}
```
public abstract int getColorSpace()
```

Αναπαριστά το χρωματικό χώρο της συμπεριφοράς. Ανάγνωση/εγγραφή [ColorSpace](../../com.aspose.slides/colorspace)(\#getColorSpace.getColorSpace/\#setColorSpace(int).setColorSpace(int)).

**Επιστρέφει:**
int
### setColorSpace(int value) {#setColorSpace-int-}
```
public abstract void setColorSpace(int value)
```

Αναπαριστά το χρωματικό χώρο της συμπεριφοράς. Ανάγνωση/εγγραφή [ColorSpace](../../com.aspose.slides/colorspace)(\#getColorSpace.getColorSpace/\#setColorSpace(int).setColorSpace(int)).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |
### getDirection() {#getDirection--}
```
public abstract int getDirection()
```

Καθορίζει την κατεύθυνση κυκλικής αλλαγής του τόνου γύρω από τον χρωματικό κύκλο. Ανάγνωση/εγγραφή [ColorDirection](../../com.aspose.slides/colordirection).

**Επιστρέφει:**
int
### setDirection(int value) {#setDirection-int-}
```
public abstract void setDirection(int value)
```

Καθορίζει την κατεύθυνση κυκλικής αλλαγή του τόνου γύρω από τον χρωματικό κύκλο. Ανάγνωση/εγγραφή [ColorDirection](../../com.aspose.slides/colordirection).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |