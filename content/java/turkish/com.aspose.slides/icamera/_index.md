---
title: ICamera
second_title: Aspose.Slides for Java API Reference
description: Represents Camera.
type: docs
url: /tr/com.aspose.slides/icamera/
---```
public interface ICamera
```

Kamerayı temsil eder.
## Yöntemler

| Metod | Açıklama |
| --- | --- |
| [getCameraType()](#getCameraType--) | Kamera türü Okuma/Yazma [CameraPresetType](../../com.aspose.slides/camerapresettype). |
| [setCameraType(int value)](#setCameraType-int-) | Kamera türü Okuma/Yazma [CameraPresetType](../../com.aspose.slides/camerapresettype). |
| [getFieldOfViewAngle()](#getFieldOfViewAngle--) | Kamera FOV (0-180 derece, görüş alanı) Okuma/Yazma float. |
| [setFieldOfViewAngle(float value)](#setFieldOfViewAngle-float-) | Kamera FOV (0-180 derece, görüş alanı) Okuma/Yazma float. |
| [getZoom()](#getZoom--) | Kamera yakınlaştırması (yüzde olarak pozitif değer) Okuma/Yazma float. |
| [setZoom(float value)](#setZoom-float-) | Kamera yakınlaştırması (yüzde olarak pozitif değer) Okuma/Yazma float. |
| [setRotation(float latitude, float longitude, float revolution)](#setRotation-float-float-float-) | Bir dönüş, enlem koordinatı, boylam koordinatı ve eksen etrafında bir devrim kullanılarak, enlem ve boylam koordinatları olarak tanımlanır. |
| [getRotation()](#getRotation--) | Bir dönüş, enlem koordinatı, boylam koordinatı ve eksen etrafında bir devrim kullanılarak, enlem ve boylam koordinatları olarak tanımlanır. |

### getCameraType() {#getCameraType--}
```
public abstract int getCameraType()
```

Kamera türü Okuma/Yazma [CameraPresetType](../../com.aspose.slides/camerapresettype).

**Döndürür:**
int

### setCameraType(int value) {#setCameraType-int-}
```
public abstract void setCameraType(int value)
```

Kamera türü Okuma/Yazma [CameraPresetType](../../com.aspose.slides/camerapresettype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getFieldOfViewAngle() {#getFieldOfViewAngle--}
```
public abstract float getFieldOfViewAngle()
```

Kamera FOV (0-180 derece, görüş alanı) Okuma/Yazma float.

**Döndürür:**
float

### setFieldOfViewAngle(float value) {#setFieldOfViewAngle-float-}
```
public abstract void setFieldOfViewAngle(float value)
```

Kamera FOV (0-180 derece, görüş alanı) Okuma/Yazma float.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |

### getZoom() {#getZoom--}
```
public abstract float getZoom()
```

Kamera yakınlaştırması (yüzde olarak pozitif değer) Okuma/Yazma float.

**Döndürür:**
float

### setZoom(float value) {#setZoom-float-}
```
public abstract void setZoom(float value)
```

Kamera yakınlaştırması (yüzde olarak pozitif değer) Okuma/Yazma float.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |

### setRotation(float latitude, float longitude, float revolution) {#setRotation-float-float-float-}
```
public abstract void setRotation(float latitude, float longitude, float revolution)
```

Bir dönüş, enlem koordinatı, boylam koordinatı ve eksen etrafında bir devrim kullanılarak, enlem ve boylam koordinatları olarak tanımlanır. Eğer herhangi bir koordinat değeri Float.NaN ise, tüm dönüş tanımsızdır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| latitude | float | Enlem değeri float |
| longitude | float |  |
| revolution | float |  |

### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```

Bir dönüş, enlem koordinatı, boylam koordinatı ve eksen etrafında bir devrim kullanılarak, enlem ve boylam koordinatları olarak tanımlanır. Dönüş dizisindeki ilk öğe - enlem, ikincisi - boylam, üçüncüsü - devrim. Dönüş tanımlı değilse null döner.

**Döndürür:**
float[] - Dönüş değerlerinin dizisi, float[] olarak.