---
title: ICameraEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: Niezmienny obiekt zawierający skuteczne właściwości kamery.
type: docs
url: /pl/com.aspose.slides/icameraeffectivedata/
---```
public interface ICameraEffectiveData
```

Niezmienny obiekt zawierający skuteczne właściwości kamery.

--------------------

Ten interfejs jest używany jako część [IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata).
## Metody

| Metoda | Opis |
| --- | --- |
| [getCameraType()](#getCameraType--) | Typ kamery. |
| [getFieldOfViewAngle()](#getFieldOfViewAngle--) | Kąt widzenia kamery (0-180°, pole widzenia). |
| [getZoom()](#getZoom--) | Zoom kamery (wartość dodatnia w procentach). |
| [getRotation()](#getRotation--) | Obrót jest definiowany przy użyciu współrzędnej szerokości, współrzędnej długości oraz obrotu wokół osi jako współrzędne szerokości i długości. |

### getCameraType() {#getCameraType--}
```
public abstract int getCameraType()
```

Typ kamery. Tylko do odczytu [CameraPresetType](../../com.aspose.slides/camerapresettype).

**Zwraca:**
int

### getFieldOfViewAngle() {#getFieldOfViewAngle--}
```
public abstract float getFieldOfViewAngle()
```

Kąt widzenia kamery (0-180°, pole widzenia). Tylko do odczytu float.

**Zwraca:**
float

### getZoom() {#getZoom--}
```
public abstract float getZoom()
```

Zoom kamery (wartość dodatnia w procentach). Tylko do odczytu float.

**Zwraca:**
float

### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```

Obrót jest definiowany przy użyciu współrzędnej szerokości, współrzędnej długości oraz obrotu wokół osi jako współrzędne szerokości i długości. pierwszy element w zwracanej tablicy - szerokość, drugi - długość, trzeci - obrót. Zwraca null, jeśli obrót nie jest określony.

**Zwraca:**
float[] - Tablica wartości obrotu jako float[].