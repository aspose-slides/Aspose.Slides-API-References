---
title: LightRig
second_title: Aspose.Slides for Java API Referansı
description: LightRig'i temsil eder.
type: docs
url: /tr/com.aspose.slides/lightrig/
---
**Kalıtım:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Uygulanan Tüm Arabirimler:**
[com.aspose.slides.ILightRig](../../com.aspose.slides/ilightrig)
```
public final class LightRig extends PVIObject implements ILightRig
```

LightRig'i temsil eder.
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getDirection()](#getDirection--) | Işık yönü. |
| [setDirection(int value)](#setDirection-int-) | Işık yönü. |
| [getLightType()](#getLightType--) | Bir şekle uygulanabilecek önceden ayarlanmış bir ışık profili temsil eder. |
| [setLightType(int value)](#setLightType-int-) | Bir şekle uygulanabilecek önceden ayarlanmış bir ışık profili temsil eder. |
| [setRotation(float latitude, float longitude, float revolution)](#setRotation-float-float-float-) | Bir dönüş, enlem koordinatı, boylam koordinatı ve eksen etrafında enlem ve boylam koordinatları olarak bir devrim kullanılarak tanımlanır. |
| [getRotation()](#getRotation--) | Bir dönüş, enlem koordinatı, boylam koordinatı ve eksen etrafında enlem ve boylam koordinatları olarak bir devrim kullanılarak tanımlanır. |
### getVersion() {#getVersion--}
```
public long getVersion()
```


Sürüm. Salt okunur long.

**Döndürür:**
long
### getDirection() {#getDirection--}
```
public final int getDirection()
```


Işık yönü. Okunabilir/Yazılabilir [LightingDirection](../../com.aspose.slides/lightingdirection).

**Döndürür:**
int
### setDirection(int value) {#setDirection-int-}
```
public final void setDirection(int value)
```


Işık yönü. Okunabilir/Yazılabilir [LightingDirection](../../com.aspose.slides/lightingdirection).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |
### getLightType() {#getLightType--}
```
public final int getLightType()
```


Bir şekle uygulanabilecek önceden ayarlanmış bir ışık profili temsil eder. Light rig, 3D sahneye göre belirli bir şekilde yönlendirilmiş bir ışık grubunu temsil eder. Okunabilir/Yazılabilir [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**Döndürür:**
int
### setLightType(int value) {#setLightType-int-}
```
public final void setLightType(int value)
```


Bir şekle uygulanabilecek önceden ayarlanmış bir ışık profili temsil eder. Light rig, 3D sahneye göre belirli bir şekilde yönlendirilmiş bir ışık grubunu temsil eder. Okunabilir/Yazılabilir [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |
### setRotation(float latitude, float longitude, float revolution) {#setRotation-float-float-float-}
```
public final void setRotation(float latitude, float longitude, float revolution)
```


Bir dönüş, enlem koordinatı, boylam koordinatı ve eksen etrafında enlem ve boylam koordinatları olarak bir devrim kullanılarak tanımlanır. Eğer herhangi bir koordinat değeri Float.NaN ise, tüm dönüş tanımsızdır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| latitude | float |  |
| longitude | float |  |
| revolution | float |  |
### getRotation() {#getRotation--}
```
public final float[] getRotation()
```


Bir dönüş, enlem koordinatı, boylam koordinatı ve eksen etrafında enlem ve boylam koordinatları olarak bir devrim kullanılarak tanımlanır. Geri dönüş dizisindeki ilk eleman - enlem, ikinci - boylam, üçüncü - devrim. Tanımlı bir dönüş yoksa null döner.

**Döndürür:**
float[]