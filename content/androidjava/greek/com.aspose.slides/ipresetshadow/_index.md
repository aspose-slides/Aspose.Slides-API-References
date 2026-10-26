---
title: IPresetShadow
second_title: Aspose.Slides για Android μέσω Αναφοράς Java API
description: Αντιπροσωπεύει ένα προκαθορισμένο εφέ σκιάς.
type: docs
url: /el/com.aspose.slides/ippresetshadow/
---
**All Implemented Interfaces:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IPresetShadow extends IImageTransformOperation, IAccessiblePVIObject<IPresetShadowEffectiveData>
```

Represents a Preset Shadow effect.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getDirection()](#getDirection--) | Κατεύθυνση της σκιάς. |
| [setDirection(float value)](#setDirection-float-) | Κατεύθυνση της σκιάς. |
| [getDistance()](#getDistance--) | Απόσταση της σκιάς. |
| [setDistance(double value)](#setDistance-double-) | Απόσταση της σκιάς. |
| [getShadowColor()](#getShadowColor--) | Χρώμα της σκιάς. |
| [getPreset()](#getPreset--) | Preset. |
| [setPreset(int value)](#setPreset-int-) | Preset. |
### getDirection() {#getDirection--}
```
public abstract float getDirection()
```


Κατεύθυνση της σκιάς. Ανάγνωση/Εγγραφή float.

**Επιστρέφει:**
float
### setDirection(float value) {#setDirection-float-}
```
public abstract void setDirection(float value)
```


Κατεύθυνση της σκιάς. Ανάγνωση/Εγγραφή float.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |

### getDistance() {#getDistance--}
```
public abstract double getDistance()
```


Απόσταση της σκιάς. Ανάγνωση/Εγγραφή double.

**Επιστρέφει:**
double
### setDistance(double value) {#setDistance-double-}
```
public abstract void setDistance(double value)
```


Απόσταση της σκιάς. Ανάγνωση/Εγγραφή double.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | double |  |

### getShadowColor() {#getShadowColor--}
```
public abstract IColorFormat getShadowColor()
```


Χρώμα της σκιάς. Μόνο ανάγνωση [IColorFormat](../../com.aspose.slides/icolorformat).

**Επιστρέφει:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getPreset() {#getPreset--}
```
public abstract int getPreset()
```


Preset. Ανάγνωση/Εγγραφή [PresetShadowType](../../com.aspose.slides/presetshadowtype).

**Επιστρέφει:**
int
### setPreset(int value) {#setPreset-int-}
```
public abstract void setPreset(int value)
```


Preset. Ανάγνωση/Εγγραφή [PresetShadowType](../../com.aspose.slides/presetshadowtype).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |