---
title: ILightRig
second_title: Aspose.Slides for Java API Referansı
description: LightRig'i temsil eder.
type: docs
url: /tr/com.aspose.slides/ilightrig/
---```
public interface ILightRig
```

LightRig'i temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getDirection()](#getDirection--) | Işık yönü. |
| [setDirection(int value)](#setDirection-int-) | Işık yönü. |
| [getLightType()](#getLightType--) | Bir şekle uygulanabilen ön ayar bir sağ ışığı temsil eder. |
| [setLightType(int value)](#setLightType-int-) | Bir şekle uygulanabilen ön ayar bir sağ ışığı temsil eder. |
| [setRotation(float latitude, float longitude, float revolution)](#setRotation-float-float-float-) | Bir dönüş, enlem koordinatı, boylam koordinatı ve eksen etrafında enlem ve boylam koordinatları olarak bir devrim kullanılarak tanımlanır. |
| [getRotation()](#getRotation--) | Bir dönüş, enlem koordinatı, boylam koordinatı ve eksen etrafında enlem ve boylam koordinatları olarak bir devrim kullanılarak tanımlanır. |
### getDirection() {#getDirection--}
```
public abstract int getDirection()
```

Işık yönü. Okunabilir/Yazılabilir [LightingDirection](../../com.aspose.slides/lightingdirection).

**Returns:**
int
### setDirection(int value) {#setDirection-int-}
```
public abstract void setDirection(int value)
```

Işık yönü. Okunabilir/Yazılabilir [LightingDirection](../../com.aspose.slides/lightingdirection).

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getLightType() {#getLightType--}
```
public abstract int getLightType()
```

Bir şekle uygulanabilen ön ayar bir sağ ışığı temsil eder. Light rig, 3D sahneye göre belirli bir şekilde yönlendirilmiş bir ışık grubunu temsil eder. Okunabilir/Yazılabilir [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**Returns:**
int
### setLightType(int value) {#setLightType-int-}
```
public abstract void setLightType(int value)
```

Bir şekle uygulanabilen ön ayar bir sağ ışığı temsil eder. Light rig, 3D sahneye göre belirli bir şekilde yönlendirilmiş bir ışık grubunu temsil eder. Okunabilir/Yazılabilir [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### setRotation(float latitude, float longitude, float revolution) {#setRotation-float-float-float-}
```
public abstract void setRotation(float latitude, float longitude, float revolution)
```

Bir dönüş, enlem koordinatı, boylam koordinatı ve eksen etrafında enlem ve boylam koordinatları olarak bir devrim kullanılarak tanımlanır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| latitude | float | Enlem koordinatı float |
| longitude | float | Boylam koordinatı float |
| revolution | float | Devrim koordinatı float |

### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```

Bir dönüş, enlem koordinatı, boylam koordinatı ve eksen etrafında enlem ve boylam koordinatları olarak bir devrim kullanılarak tanımlanır. Döndürme dizisinin ilk öğesi - enlem, ikinci - boylam, üçüncü - devrim.

**Returns:**
float[] - Döndürme koordinatları float[] olarak