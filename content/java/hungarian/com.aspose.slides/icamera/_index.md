---
title: ICamera
second_title: Aspose.Slides for Java API Reference
description: Kamerát reprezentálja.
type: docs
url: /hu/com.aspose.slides/icamera/
---```
public interface ICamera
```

Kamerát reprezentálja.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getCameraType()](#getCameraType--) | Camera type Olvasás/írás [CameraPresetType](../../com.aspose.slides/camerapresettype). |
| [setCameraType(int value)](#setCameraType-int-) | Camera type Olvasás/írás [CameraPresetType](../../com.aspose.slides/camerapresettype). |
| [getFieldOfViewAngle()](#getFieldOfViewAngle--) | Camera FOV (0-180 deg, field of View) Olvasás/írás float. |
| [setFieldOfViewAngle(float value)](#setFieldOfViewAngle-float-) | Camera FOV (0-180 deg, field of View) Olvasás/írás float. |
| [getZoom()](#getZoom--) | Camera zoom (positive value in percentage) Olvasás/írás float. |
| [setZoom(float value)](#setZoom-float-) | Camera zoom (positive value in percentage) Olvasás/írás float. |
| [setRotation(float latitude, float longitude, float revolution)](#setRotation-float-float-float-) | A forgást a szélességi koordináta, a hosszúsági koordináta és az tengely körüli forgatás segítségével definiálják, mint a szélességi és hosszúsági koordinátákat. |
| [getRotation()](#getRotation--) | A forgást a szélességi koordináta, a hosszúsági koordináta és az tengely körüli forgatás segítségével definiálják, mint a szélességi és hosszúsági koordinátákat. |

### getCameraType() {#getCameraType--}
```
public abstract int getCameraType()
```

Camera type Olvasás/írás [CameraPresetType](../../com.aspose.slides/camerapresettype).

**Visszatérési érték:**
int

### setCameraType(int value) {#setCameraType-int-}
```
public abstract void setCameraType(int value)
```

Camera type Olvasás/írás [CameraPresetType](../../com.aspose.slides/camerapresettype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getFieldOfViewAngle() {#getFieldOfViewAngle--}
```
public abstract float getFieldOfViewAngle()
```

Camera FOV (0-180 deg, field of View) Olvasás/írás float.

**Visszatérési érték:**
float

### setFieldOfViewAngle(float value) {#setFieldOfViewAngle-float-}
```
public abstract void setFieldOfViewAngle(float value)
```

Camera FOV (0-180 deg, field of View) Olvasás/írás float.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getZoom() {#getZoom--}
```
public abstract float getZoom()
```

Camera zoom (positive value in percentage) Olvasás/írás float.

**Visszatérési érték:**
float

### setZoom(float value) {#setZoom-float-}
```
public abstract void setZoom(float value)
```

Camera zoom (positive value in percentage) Olvasás/írás float.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### setRotation(float latitude, float longitude, float revolution) {#setRotation-float-float-float-}
```
public abstract void setRotation(float latitude, float longitude, float revolution)
```

A forgást a szélességi koordináta, a hosszúsági koordináta és az tengely körüli forgatás segítségével definiálják, mint a szélességi és hosszúsági koordinátákat. Ha bármely koordináták értéke Float.NaN, a forgás nem definiált.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| latitude | float | Latitude value float |
| longitude | float |  |
| revolution | float |  |

### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```

A forgást a szélességi koordináta, a hosszúsági koordináta és az tengely körüli forgatás segítségével definiálják, mint a szélességi és hosszúsági koordinátákat. Az első elem a visszatérő tömbben – szélesség, a második – hosszúság, a harmadik – forgatás. Null értéket ad vissza, ha nincs definiált forgás.

**Visszatérési érték:**
float[] - A forgási értékek tömbje float[] típusban.