---
title: Camera
second_title: Aspose.Slides für Java API Referenz
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

Stellt die Kamera dar.
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
| [setRotation(float latitude, float longitude, float revolution)](#setRotation-float-float-float-) | Eine Rotation wird durch die Verwendung einer Breitengradkoordinate, einer Längengradkoordinate und einer Umdrehung um die Achse definiert, wobei die Breitengrad- und Längengradkoordinaten verwendet werden. |
| [getRotation()](#getRotation--) | Eine Rotation wird durch die Verwendung einer Breitengradkoordinate, einer Längengradkoordinate und einer Umdrehung um die Achse definiert, wobei die Breitengrad- und Längengradkoordinaten verwendet werden. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

Version. Nur-Lesen long.

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

Eine Rotation wird durch die Verwendung einer Breitengradkoordinate, einer Längengradkoordinate und einer Umdrehung um die Achse definiert, wobei die Breitengrad- und Längengradkoordinaten verwendet werden. Wenn ein Koordinatenwert Float.NaN ist, ist die gesamte Rotation undefiniert.

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

Eine Rotation wird durch die Verwendung einer Breitengradkoordinate, einer Längengradkoordinate und einer Umdrehung um die Achse definiert, wobei die Breitengrad- und Längengradkoordinaten verwendet werden. Das erste Element im Rückgabe-Array – Breitengrad, das zweite – Längengrad, das dritte – Umdrehung. Gibt null zurück, wenn keine Rotation definiert ist.

**Rückgabe:**
float[]