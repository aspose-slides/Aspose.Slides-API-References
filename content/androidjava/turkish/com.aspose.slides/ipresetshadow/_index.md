---
title: IPresetShadow
second_title: Java API Referansı aracılığıyla Android için Aspose.Slides
description: Bir Ön Ayar Gölge etkisini temsil eder.
type: docs
url: /tr/com.aspose.slides/ipresetshadow/
---
**Tüm Uygulanan Arabirimler:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IPresetShadow extends IImageTransformOperation, IAccessiblePVIObject<IPresetShadowEffectiveData>
```

Bir Ön Ayar Gölge efekti temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getDirection()](#getDirection--) | Gölgenin yönü. |
| [setDirection(float value)](#setDirection-float-) | Gölgenin yönü. |
| [getDistance()](#getDistance--) | Gölgenin mesafesi. |
| [setDistance(double value)](#setDistance-double-) | Gölgenin mesafesi. |
| [getShadowColor()](#getShadowColor--) | Gölgenin rengi. |
| [getPreset()](#getPreset--) | Ön ayar. |
| [setPreset(int value)](#setPreset-int-) | Ön ayar. |
### getDirection() {#getDirection--}
```
public abstract float getDirection()
```

Gölgenin yönü. Okunur/Yazılabilir float.

**Döndürür:**  
float
### setDirection(float value) {#setDirection-float-}
```
public abstract void setDirection(float value)
```

Gölgenin yönü. Okunur/Yazılabilir float.

**Parametreler:**  
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |
### getDistance() {#getDistance--}
```
public abstract double getDistance()
```

Gölgenin mesafesi. Okunur/Yazılabilir double.

**Döndürür:**  
double
### setDistance(double value) {#setDistance-double-}
```
public abstract void setDistance(double value)
```

Gölgenin mesafesi. Okunur/Yazılabilir double.

**Parametreler:**  
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | double |  |
### getShadowColor() {#getShadowColor--}
```
public abstract IColorFormat getShadowColor()
```

Gölgenin rengi. Sadece-okunur [IColorFormat](../../com.aspose.slides/icolorformat).

**Döndürür:**  
[IColorFormat](../../com.aspose.slides/icolorformat)
### getPreset() {#getPreset--}
```
public abstract int getPreset()
```

Ön ayar. Okunur/Yazılabilir [PresetShadowType](../../com.aspose.slides/presetshadowtype).

**Döndürür:**  
int
### setPreset(int value) {#setPreset-int-}
```
public abstract void setPreset(int value)
```

Ön ayar. Okunur/Yazılabilir [PresetShadowType](../../com.aspose.slides/presetshadowtype).

**Parametreler:**  
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |