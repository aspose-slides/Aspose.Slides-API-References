---
title: ILightRig
second_title: Aspose.Slides for Android için Java API Referansı
description: LightRig'i temsil eder.
type: docs
url: /tr/com.aspose.slides/ilightrig/
---```
public interface ILightRig
```

LightRig'i temsil eder.
## Yöntemler

| Metot | Açıklama |
| --- | --- |
| [getDirection()](#getDirection--) | Işık yönü. |
| [setDirection(int value)](#setDirection-int-) | Işık yönü. |
| [getLightType()](#getLightType--) | Şekle uygulanabilen önceden ayarlanmış bir ışık yönünü temsil eder. |
| [setLightType(int value)](#setLightType-int-) | Şekle uygulanabilen önceden ayarlanmış bir ışık yönünü temsil eder. |
| [setRotation(float latitude, float longitude, float revolution)](#setRotation-float-float-float-) | Dönüş, enlem koordinatı, boylam koordinatı ve eksen etrafındaki bir devrim kullanılarak tanımlanır; enlem ve boylam koordinatları olarak. |
| [getRotation()](#getRotation--) | Dönüş, enlem koordinatı, boylam koordinatı ve eksen etrafındaki bir devrim kullanılarak tanımlanır; enlem ve boylam koordinatları olarak. |
### getDirection() {#getDirection--}
```
public abstract int getDirection()
```

Işık yönü. Okunur/yazılır [LightingDirection](../../com.aspose.slides/lightingdirection).

**Döndürür:**
int
### setDirection(int value) {#setDirection-int-}
```
public abstract void setDirection(int value)
```

Işık yönü. Okunur/yazılır [LightingDirection](../../com.aspose.slides/lightingdirection).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |
### getLightType() {#getLightType--}
```
public abstract int getLightType()
```

Şekle uygulanabilen önceden ayarlanmış bir ışık yönünü temsil eder. Işık seti, 3D sahneye göre belirli bir şekilde konumlandırılmış bir ışık grubunu temsil eder. Okunur/yazılır [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**Döndürür:**
int
### setLightType(int value) {#setLightType-int-}
```
public abstract void setLightType(int value)
```

Şekle uygulanabilen önceden ayarlanmış bir ışık yönünü temsil eder. Işık seti, 3D sahneye göre belirli bir şekilde konumlandırılmış bir ışık grubunu temsil eder. Okunur/yazılır [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |
### setRotation(float latitude, float longitude, float revolution) {#setRotation-float-float-float-}
```
public abstract void setRotation(float latitude, float longitude, float revolution)
```

Dönüş, enlem koordinatı, boylam koordinatı ve eksen etrafındaki bir devrim kullanılarak tanımlanır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| latitude | float | Enlem koordinatı float |
| longitude | float | Boylam koordinatı float |
| revolution | float | Devrim koordinatı float |
### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```

Dönüş, enlem koordinatı, boylam koordinatı ve eksen etrafındaki bir devrim kullanılarak tanımlanır; ilk öğe - enlem, ikinci - boylam, üçüncü - devrim.

**Döndürür:**
float[] - Dönüş koordinatları float[] olarak