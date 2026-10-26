---
title: Camera
second_title: Aspose.Slides für Android über Java API-Referenz
description: Stellt die Kamera dar.
type: docs
url: /de/com.aspose.slides/camera/
---
**Vererbung:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Alle implementierten Schnittstellen:**
[com.aspose.slides.ICamera](../../com.aspose.slides/icamera)
```
public final class Camera extends PVIObject implements ICamera
```

Stellt Kamera dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getCameraType()](#getCameraType--) | Kameratyp. |
| [setCameraType(int value)](#setCameraType-int-) | Kameratyp. |
| [getFieldOfViewAngle()](#getFieldOfViewAngle--) | Kamera-FOV (0-180 Grad, Sichtfeld). |
| [setFieldOfViewAngle(float value)](#setFieldOfViewAngle-float-) | Kamera-FOV (0-180 Grad, Sichtfeld). |
| [getZoom()](#getZoom--) | Kamera-Zoom (positiver Wert in Prozent). |
| [setZoom(float value)](#setZoom-float-) | Kamera-Zoom (positiver Wert in Prozent). |
| [setRotation(float latitude, float longitude, float revolution)](#setRotation-float-float-float-) | Eine Drehung wird definiert durch die Verwendung einer Breitengradkoordinate, einer Längengradkoordinate und einer Umdrehung um die Achse als Breitengrad- und Längengradkoordinaten. |
| [getRotation()](#getRotation--) | Eine Drehung wird definiert durch die Verwendung einer Breitengradkoordinate, einer Längengradkoordinate und einer Umdrehung um die Achse als Breitengrad- und Längengradkoordinaten. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

Version. Nur lesbar long.

**Rückgabe:**
long

### getCameraType() {#getCameraType--}
```
public final int getCameraType()
```

Kameratyp. Lesen/Schreiben [CameraPresetType](../../com.aspose.slides/camerapresettype).

**Rückgabe:**
int

### setCameraType(int value) {#setCameraType-int-}
```
public final void setCameraType(int value)
```

Kameratyp. Lesen/Schreiben [CameraPresetType](../../com.aspose.slides/camerapresettype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getFieldOfViewAngle() {#getFieldOfViewAngle--}
```
public final float getFieldOfViewAngle()
```

Kamera-FOV (0-180 Grad, Sichtfeld). Lesen/Schreiben float.

**Rückgabe:**
float

### setFieldOfViewAngle(float value) {#setFieldOfViewAngle-float-}
```
public final void setFieldOfViewAngle(float value)
```

Kamera-FOV (0-180 Grad, Sichtfeld). Lesen/Schreiben float.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |

### getZoom() {#getZoom--}
```
public final float getZoom()
```

Kamera-Zoom (positiver Wert in Prozent). Lesen/Schreiben float.

**Rückgabe:**
float

### setZoom(float value) {#setZoom-float-}
```
public final void setZoom(float value)
```

Kamera-Zoom (positiver Wert in Prozent). Lesen/Schreiben float.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |

### setRotation(float latitude, float longitude, float revolution) {#setRotation-float-float-float-}
```
public final void setRotation(float latitude, float longitude, float revolution)
```

Eine Drehung wird definiert durch die Verwendung einer Breitengradkoordinate, einer Längengradkoordinate und einer Umdrehung um die Achse als Breitengrad- und Längengradkoordinaten. Wenn ein beliebiger Koordinatenwert Float.NaN ist, ist die gesamte Drehung undefiniert.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| latitude | float |  |
| longitude | float |  |
| revolution | float |  |

### getRotation() {#getRotation--}
```
public final float[] getRotation()
```

Eine Drehung wird definiert durch die Verwendung einer Breitengradkoordinate, einer Längengradkoordinate und einer Umdrehung um die Achse als Breitengrad- und Längengradkoordinaten. Erstes Element im Rückgabe-Array – Breitengrad, zweites – Längengrad, drittes – Umdrehung. Gibt null zurück, wenn keine Drehung definiert ist.

**Rückgabe:**
float[]