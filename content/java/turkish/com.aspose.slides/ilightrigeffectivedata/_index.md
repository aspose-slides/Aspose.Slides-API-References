---
title: ILightRigEffectiveData
second_title: Aspose.Slides for Java API Reference
description: Etkin ışık donanımı özelliklerini içeren değiştirilemez nesne.
type: docs
url: /tr/com.aspose.slides/ilightrigeffectivedata/
---```
public interface ILightRigEffectiveData
```

Değiştirilemez nesne etkin ışık donanımı özelliklerini içerir.

--------------------

Bu arabirim [IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata)'nin bir parçası olarak kullanılır.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getDirection()](#getDirection--) | Işık yönü. |
| [getLightType()](#getLightType--) | Bir şekle uygulanabilen önceden ayarlanmış bir ışık yönünü temsil eder. |
| [getRotation()](#getRotation--) | Bir döndürme, enlem koordinatı, boylam koordinatı ve eksen etrafındaki devrim kullanılarak, enlem ve boylam koordinatları olarak tanımlanır. |

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

Bir şekle uygulanabilen önceden ayarlanmış bir ışık yönünü temsil eder. Işık donanımı, bir 3D sahneye göre belirli bir şekilde yönlendirilmiş ışıklar grubunu temsil eder. Salt okunur [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**Döndürür:**
int

### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```

Bir döndürme, enlem koordinatı, boylam koordinatı ve eksen etrafındaki devrim kullanılarak, enlem ve boylam koordinatları olarak tanımlanır. Döndürme dizisindeki ilk eleman - enlem, ikinci - boylam, üçüncü - devrim.

**Döndürür:**
float[] - Dönüş koordinatları float[] olarak