---
title: IGlow
second_title: Aspose.Slides για Android μέσω Αναφοράς API Java
description: Αντιπροσωπεύει ένα εφέ λάμψης, στο οποίο προστίθεται μια θολή περίγραμμα χρώματος γύρω από τις άκρες του αντικειμένου.
type: docs
url: /el/com.aspose.slides/iglow/
---
**Όλες οι Υλοποιημένες Διασυνδέσεις:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IGlow extends IImageTransformOperation, IAccessiblePVIObject<IGlowEffectiveData>
```

Αντιπροσωπεύει ένα εφέ λάμψης, στο οποίο προστίθεται μια θολή περίγραμμα χρώματος γύρω από τις άκρες του αντικειμένου.
## Μεθόδοι

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

Μορφή χρώματος. Μόνο ανάγνωση [IColorFormat](../../com.aspose.slides/icolorformat).

**Επιστρέφει:**
[IColorFormat](../../com.aspose.slides/icolorformat)