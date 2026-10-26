---
title: Camera
second_title: Aspose.Slides dla Androida poprzez odwołanie do Java API
description: Reprezentuje kamerę.
type: docs
url: /pl/com.aspose.slides/camera/
---
**Dziedziczenie:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.ICamera](../../com.aspose.slides/icamera)
```
public final class Camera extends PVIObject implements ICamera
```

Reprezentuje kamerę.
## Metody

| Method | Description |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getCameraType()](#getCameraType--) | Typ kamery. |
| [setCameraType(int value)](#setCameraType-int-) | Typ kamery. |
| [getFieldOfViewAngle()](#getFieldOfViewAngle--) | Kąt widzenia kamery (0-180 stopni, pole widzenia). |
| [setFieldOfViewAngle(float value)](#setFieldOfViewAngle-float-) | Kąt widzenia kamery (0-180 stopni, pole widzenia). |
| [getZoom()](#getZoom--) | Powiększenie kamery (wartość dodatnia w procentach). |
| [setZoom(float value)](#setZoom-float-) | Powiększenie kamery (wartość dodatnia w procentach). |
| [setRotation(float latitude, float longitude, float revolution)](#setRotation-float-float-float-) | Obrót jest określony za pomocą współrzędnej szerokości geograficznej, współrzędnej długości geograficznej oraz obrotu wokół osi jako współrzędnych szerokości i długości. |
| [getRotation()](#getRotation--) | Obrót jest określony za pomocą współrzędnej szerokości geograficznej, współrzędnej długości geograficznej oraz obrotu wokół osi jako współrzędnych szerokości i długości. |
### getVersion() {#getVersion--}
```
public long getVersion()
```

Wersja. Long tylko do odczytu.

**Zwraca:**
long
### getCameraType() {#getCameraType--}
```
public final int getCameraType()
```

Typ kamery. Odczyt/zapis [CameraPresetType](../../com.aspose.slides/camerapresettype).

**Zwraca:**
int
### setCameraType(int value) {#setCameraType-int-}
```
public final void setCameraType(int value)
```

Typ kamery. Odczyt/zapis [CameraPresetType](../../com.aspose.slides/camerapresettype).

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getFieldOfViewAngle() {#getFieldOfViewAngle--}
```
public final float getFieldOfViewAngle()
```

Kąt widzenia kamery (0-180 stopni, pole widzenia). Odczyt/zapis float.

**Zwraca:**
float
### setFieldOfViewAngle(float value) {#setFieldOfViewAngle-float-}
```
public final void setFieldOfViewAngle(float value)
```

Kąt widzenia kamery (0-180 stopni, pole widzenia). Odczyt/zapis float.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |
### getZoom() {#getZoom--}
```
public final float getZoom()
```

Powiększenie kamery (wartość dodatnia w procentach). Odczyt/zapis float.

**Zwraca:**
float
### setZoom(float value) {#setZoom-float-}
```
public final void setZoom(float value)
```

Powiększenie kamery (wartość dodatnia w procentach). Odczyt/zapis float.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |
### setRotation(float latitude, float longitude, float revolution) {#setRotation-float-float-float-}
```
public final void setRotation(float latitude, float longitude, float revolution)
```

Obrót jest określony za pomocą współrzędnej szerokości geograficznej, współrzędnej długości geograficznej oraz obrotu wokół osi jako współrzędnych szerokości i długości. Jeśli którakolwiek wartość współrzędnej jest Float.NaN, cały obrót jest niezdefiniowany.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| latitude | float |  |
| longitude | float |  |
| revolution | float |  |
### getRotation() {#getRotation--}
```
public final float[] getRotation()
```

Obrót jest określony za pomocą współrzędnej szerokości geograficznej, współrzędnej długości geograficznej oraz obrotu wokół osi jako współrzędnych szerokości i długości. pierwszy element w zwracanej tablicy – szerokość, drugi – długość, trzeci – obrót. Zwraca null, jeśli obrót nie jest zdefiniowany.

**Zwraca:**
float[]