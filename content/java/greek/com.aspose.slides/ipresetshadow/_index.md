---
title: IPresetShadow
second_title: Aspose.Slides - Αναφορά API για Java
description: Αντιπροσωπεύει ένα προεπιλεγμένο εφέ σκιάς.
type: docs
url: /el/com.aspose.slides/ipresetshadow/
---
**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IPresetShadow extends IImageTransformOperation, IAccessiblePVIObject<IPresetShadowEffectiveData>
```

Αντιπροσωπεύει ένα προεπιλεγμένο εφέ σκιάς.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getDirection()](#getDirection--) | Κατεύθυνση της σκιάς. |
| [setDirection(float value)](#setDirection-float-) | Κατεύθυνση της σκιάς. |
| [getDistance()](#getDistance--) | Απόσταση της σκιάς. |
| [setDistance(double value)](#setDistance-double-) | Απόσταση της σκιάς. |
| [getShadowColor()](#getShadowColor--) | Χρώμα της σκιάς. |
| [getPreset()](#getPreset--) | Προεπιλογή. |
| [setPreset(int value)](#setPreset-int-) | Προεπιλογή. |
### getDirection() {#getDirection--}
```
public abstract float getDirection()
```

Κατεύθυνση της σκιάς. Ανάγνωση/εγγραφή float.

**Επιστρέφει:**
float
### setDirection(float value) {#setDirection-float-}
```
public abstract void setDirection(float value)
```

Κατεύθυνση της σκιάς. Ανάγνωση/εγγραφή float.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |
### getDistance() {#getDistance--}
```
public abstract double getDistance()
```

Απόσταση της σκιάς. Ανάγνωση/εγγραφή double.

**Επιστρέφει:**
double
### setDistance(double value) {#setDistance-double-}
```
public abstract void setDistance(double value)
```

Απόσταση της σκιάς. Ανάγνωση/εγγραφή double.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | double |  |
### getShadowColor() {#getShadowColor--}
```
public abstract IColorFormat getShadowColor()
```

Χρώμα της σκιάς. Μόνο για ανάγνωση [IColorFormat](../../com.aspose.slides/icolorformat).

**Επιστρέφει:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getPreset() {#getPreset--}
```
public abstract int getPreset()
```

Προεπιλογή. Ανάγνωση/εγγραφή [PresetShadowType](../../com.aspose.slides/presetshadowtype).

**Επιστρέφει:**
int
### setPreset(int value) {#setPreset-int-}
```
public abstract void setPreset(int value)
```

Προεπιλογή. Ανάγνωση/εγγραφή [PresetShadowType](../../com.aspose.slides/presetshadowtype).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |