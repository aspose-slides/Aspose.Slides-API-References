---
title: IPresetShadow
second_title: Aspose.Slides dla Java – odniesienie API
description: Reprezentuje predefiniowany efekt cienia.
type: docs
url: /pl/com.aspose.slides/ippresetshadow/
---
**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IPresetShadow extends IImageTransformOperation, IAccessiblePVIObject<IPresetShadowEffectiveData>
```

Reprezentuje predefiniowany efekt cienia.
## Metody

| Metoda | Opis |
| --- | --- |
| [getDirection()](#getDirection--) | Kierunek cienia. |
| [setDirection(float value)](#setDirection-float-) | Kierunek cienia. |
| [getDistance()](#getDistance--) | Odległość cienia. |
| [setDistance(double value)](#setDistance-double-) | Odległość cienia. |
| [getShadowColor()](#getShadowColor--) | Kolor cienia. |
| [getPreset()](#getPreset--) | Ustawienie wstępne. |
| [setPreset(int value)](#setPreset-int-) | Ustawienie wstępne. |
### getDirection() {#getDirection--}
```
public abstract float getDirection()
```

Kierunek cienia. Odczyt/zapis float.

**Zwraca:**
float
### setDirection(float value) {#setDirection-float-}
```
public abstract void setDirection(float value)
```

Kierunek cienia. Odczyt/zapis float.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | float |  |
### getDistance() {#getDistance--}
```
public abstract double getDistance()
```

Odległość cienia. Odczyt/zapis double.

**Zwraca:**
double
### setDistance(double value) {#setDistance-double-}
```
public abstract void setDistance(double value)
```

Odległość cienia. Odczyt/zapis double.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | double |  |
### getShadowColor() {#getShadowColor--}
```
public abstract IColorFormat getShadowColor()
```

Kolor cienia. Tylko do odczytu [IColorFormat](../../com.aspose.slides/icolorformat).

**Zwraca:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getPreset() {#getPreset--}
```
public abstract int getPreset()
```

Ustawienie wstępne. Odczyt/zapis [PresetShadowType](../../com.aspose.slides/presetshadowtype).

**Zwraca:**
int
### setPreset(int value) {#setPreset-int-}
```
public abstract void setPreset(int value)
```

Ustawienie wstępne. Odczyt/zapis [PresetShadowType](../../com.aspose.slides/presetshadowtype).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |