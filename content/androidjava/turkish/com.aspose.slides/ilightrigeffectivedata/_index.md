---
title: ILightRigEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: Immutable object which contains effective light rig properties.
type: docs
url: /tr/com.aspose.slides/ilightrigeffectivedata/
---```
public interface ILightRigEffectiveData
```

Etkili ışık çerçevesi özelliklerini içeren değiştirilemez bir nesne.

--------------------

Bu arayüz [IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata) parçası olarak kullanılır.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getDirection()](#getDirection--) | Işık yönü. |
| [getLightType()](#getLightType--) | Bir şekle uygulanabilen önceden ayarlanmış bir ışık sağını temsil eder. |
| [getRotation()](#getRotation--) | Bir dönüş, enlem koordinatı, boylam koordinatı ve eksen etrafında enlem ve boylam koordinatları olarak bir devrim kullanılarak tanımlanır. |

### getDirection() {#getDirection--}
```
public abstract int getDirection()
```

Işık yönü. Salt okunur [LightingDirection](../../com.aspose.slides/lightingdirection).

**Döndürür:**
int

### getLightType() {#getLightType--}
```
public abstract int getLightType()
```

Bir şekle uygulanabilen önceden ayarlanmış bir ışık sağını temsil eder. Light rig, bir 3D sahneye göre belirli bir şekilde yönlendirilmiş ışık grubunu temsil eder. Salt okunur [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**Döndürür:**
int

### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```

Bir dönüş, enlem koordinatı, boylam koordinatı ve eksen etrafında enlem ve boylam koordinatları olarak bir devrim kullanılarak tanımlanır. Dönen dizideki ilk öğe - enlem, ikinci - boylam, üçüncü - devrim.

**Döndürür:**
float[] - Dönüş koordinatları float[] olarak