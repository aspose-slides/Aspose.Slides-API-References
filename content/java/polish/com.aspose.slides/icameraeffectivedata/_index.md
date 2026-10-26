---
title: ICameraEffectiveData
second_title: Aspose.Slides for Java API Reference
description: Immutable object which contains effective camera properties.
type: docs
url: /pl/com.aspose.slides/icameraeffectivedata/
---```
public interface ICameraEffectiveData
```

Niezmienny obiekt zawierający efektywne właściwości kamery.

--------------------

Ten interfejs jest używany jako część [IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata).
## Metody

| Metoda | Opis |
| --- | --- |
| [getCameraType()](#getCameraType--) | Typ kamery. |
| [getFieldOfViewAngle()](#getFieldOfViewAngle--) | Pole widzenia kamery (0-180 deg, field of View). |
| [getZoom()](#getZoom--) | Powiększenie kamery (wartość dodatnia w procentach). |
| [getRotation()](#getRotation--) | Rotacja jest definiowana przy użyciu współrzędnej szerokości, współrzędnej długości oraz obrotu wokół osi jako współrzędnych szerokości i długości. |

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

Pole widzenia kamery (0-180 deg, field of View). Tylko do odczytu float.

**Zwraca:**
float
### getZoom() {#getZoom--}
```
public abstract float getZoom()
```

Powiększenie kamery (wartość dodatnia w procentach). Tylko do odczytu float.

**Zwraca:**
float
### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```

Rotacja jest definiowana przy użyciu współrzędnej szerokości, współrzędnej długości oraz obrotu wokół osi jako współrzędnych szerokości i długości. pierwszy element w zwracanej tablicy - szerokość geograficzna, drugi - długość geograficzna, trzeci - obrót. Zwraca null, jeśli nie zdefiniowano rotacji.

**Zwraca:**
float[] - Tablica wartości rotacji jako float[].