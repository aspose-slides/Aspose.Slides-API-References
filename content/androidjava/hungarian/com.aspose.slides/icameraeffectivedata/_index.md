---
title: ICameraEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: Megváltoztathatatlan objektum, amely a hatékony kamera tulajdonságokat tartalmazza.
type: docs
url: /hu/com.aspose.slides/icameraeffectivedata/
---```
public interface ICameraEffectiveData
```

Megváltoztathatatlan objektum, amely a hatékony kamera tulajdonságokat tartalmazza.

--------------------

Ez az interfész a [IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata) részeként használható.
## Módszerek

| Method | Description |
| --- | --- |
| [getCameraType()](#getCameraType--) | Kamera típusa. |
| [getFieldOfViewAngle()](#getFieldOfViewAngle--) | Kamera látószöge (0-180 deg, látótér). |
| [getZoom()](#getZoom--) | Kamera zoom (pozitív érték százalékban). |
| [getRotation()](#getRotation--) | A forgatás egy szélességi koordináta, egy hosszúsági koordináta és a tengely körüli forogás használatával definiálható. Az első elem a visszatérő tömbben – szélességi fok, a második – hosszúsági fok, a harmadik – forogás. Null értéket ad vissza, ha nincs definiált forgatás. |

### getCameraType() {#getCameraType--}
```
public abstract int getCameraType()
```

Kamera típusa. Csak olvasható [CameraPresetType](../../com.aspose.slides/camerapresettype).

**Visszatér:**
int

### getFieldOfViewAngle() {#getFieldOfViewAngle--}
```
public abstract float getFieldOfViewAngle()
```

Kamera látószöge (0-180 deg, látótér). Csak olvasható float.

**Visszatér:**
float

### getZoom() {#getZoom--}
```
public abstract float getZoom()
```

Kamera zoom (pozitív érték százalékban). Csak olvasható float.

**Visszatér:**
float

### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```

A forgatás egy szélességi koordináta, egy hosszúsági koordináta és a tengely körüli forogás használatával definiálható. Az első elem a visszatérő tömbben – szélességi fok, a második – hosszúsági fok, a harmadik – forogás. Null értéket ad vissza, ha nincs definiált forgatás.

**Visszatér:**
float[] – A forgatási értékek tömbje, float[] típusú.