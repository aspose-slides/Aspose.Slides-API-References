---
title: LightRig
second_title: Java API Referansı aracılığıyla Android için Aspose.Slides
description: LightRig'i temsil eder.
type: docs
url: /tr/com.aspose.slides/lightrig/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**All Implemented Interfaces:**
[com.aspose.slides.ILightRig](../../com.aspose.slides/ilightrig)
```
public final class LightRig extends PVIObject implements ILightRig
```

LightRig'i temsil eder.

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getDirection()](#getDirection--) | Işık yönü. |
| [setDirection(int value)](#setDirection-int-) | Işık yönü. |
| [getLightType()](#getLightType--) | Bir şekle uygulanabilecek ön ayarlı bir sağ ışığı temsil eder. |
| [setLightType(int value)](#setLightType-int-) | Bir şekle uygulanabilecek ön ayarlı bir sağ ışığı temsil eder. |
| [setRotation(float latitude, float longitude, float revolution)](#setRotation-float-float-float-) | Bir dönüş, enlem koordinatı, boylam koordinatı ve eksen etrafındaki devrim kullanılarak tanımlanır. |
| [getRotation()](#getRotation--) | Bir dönüş, enlem koordinatı, boylam koordinatı ve eksen etrafındaki devrim kullanılarak tanımlanır. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

Sürüm. Salt-okunur long.

**Döndürür:**
long

### getDirection() {#getDirection--}
```
public final int getDirection()
```

Işık yönü. Okunur/Yazılır [LightingDirection](../../com.aspose.slides/lightingdirection).

**Döndürür:**
int

### setDirection(int value) {#setDirection-int-}
```
public final void setDirection(int value)
```

Işık yönü. Okunur/Yazılır [LightingDirection](../../com.aspose.slides/lightingdirection).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getLightType() {#getLightType--}
```
public final int getLightType()
```

Bir şekle uygulanabilecek ön ayarlı bir sağ ışığı temsil eder. Light rig, 3D sahneye göre belirli bir şekilde yönlendirilmiş bir ışık grubunu temsil eder. Okunur/Yazılır [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**Döndürür:**
int

### setLightType(int value) {#setLightType-int-}
```java
public final void setLightType(int value)
```

Bir şekle uygulanabilecek ön ayarlı bir sağ ışığı temsil eder. Light rig, 3D sahneye göre belirli bir şekilde yönlendirilmiş bir ışık grubunu temsil eder. Okunur/Yazılır [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### setRotation(float latitude, float longitude, float revolution) {#setRotation-float-float-float-}
```
public final void setRotation(float latitude, float longitude, float revolution)
```

Bir dönüş, enlem koordinatı, boylam koordinatı ve eksen etrafındaki devrim kullanılarak tanımlanır. Eğer herhangi bir koordinat değeri Float.NaN ise, tüm dönüş tanımsızdır.

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

Bir dönüş, enlem koordinatı, boylam koordinatı ve eksen etrafındaki devrim kullanılarak tanımlanır. Döndürme dizisinin ilk öğesi - enlem, ikincisi - boylam, üçüncüsü - devrim. Rotasyon tanımlı değilse null döndürür.

**Döndürür:**
float[]