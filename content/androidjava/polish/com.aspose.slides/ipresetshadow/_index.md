---
title: IPresetShadow
second_title: Aspose.Slides dla Androida przez odwołanie do API Java
description: Reprezentuje efekt cienia predefiniowanego.
type: docs
url: /pl/com.aspose.slides/ipresetshadow/
---
**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IPresetShadow extends IImageTransformOperation, IAccessiblePVIObject<IPresetShadowEffectiveData>
```

Reprezentuje efekt cienia predefiniowanego.
## Metody

| Metoda | Opis |
| --- | --- |
| [getDirection()](#getDirection--) | Kierunek cienia. |
| [setDirection(float value)](#setDirection-float-) | Kierunek cienia. |
| [getDistance()](#getDistance--) | Odległość cienia. |
| [setDistance(double value)](#setDistance-double-) | Odległość cienia. |
| [getShadowColor()](#getShadowColor--) | Kolor cienia. |
| [getPreset()](#getPreset--) | Predefiniowany. |
| [setPreset(int value)](#setPreset-int-) | Predefiniowany. |
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


Predefiniowany. Odczyt/zapis [PresetShadowType](../../com.aspose.slides/presetshadowtype).

**Zwraca:**
int
### setPreset(int value) {#setPreset-int-}
```
public abstract void setPreset(int value)
```


Predefiniowany. Odczyt/zapis [PresetShadowType](../../com.aspose.slides/presetshadowtype).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |