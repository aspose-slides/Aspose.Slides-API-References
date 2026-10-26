---
title: IGlow
second_title: Aspose.Slides για την Αναφορά API Java
description: Αναπαριστά ένα εφέ Glow, στο οποίο ένα θολό περίγραμμα χρώματος προστίθεται έξω από τις άκρες του αντικειμένου.
type: docs
url: /el/com.aspose.slides/iglow/
---
**Όλες οι υλοποιημένες διεπαφές:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IGlow extends IImageTransformOperation, IAccessiblePVIObject<IGlowEffectiveData>
```

Αναπαριστά ένα εφέ Glow, στο οποίο ένα θολό περίγραμμα χρώματος προστίθεται έξω από τις άκρες του αντικειμένου.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getRadius()](#getRadius--) | Ακτίνα. |
| [setRadius(double value)](#setRadius-double-) | Ακτίνα. |
| [getColor()](#getColor--) | Μορφή χρώματος. |
### getRadius() {#getRadius--}
```
public abstract double getRadius()
```


Ακτίνα. Ανάγνωση/εγγραφή double.

**Επιστρέφει:**
double
### setRadius(double value) {#setRadius-double-}
```
public abstract void setRadius(double value)
```


Ακτίνα. Ανάγνωση/εγγραφή double.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | double |  |

### getColor() {#getColor--}
```
public abstract IColorFormat getColor()
```


Μορφή χρώματος. Μόνο για ανάγνωση [IColorFormat](../../com.aspose.slides/icolorformat).

**Επιστρέφει:**
[IColorFormat](../../com.aspose.slides/icolorformat)