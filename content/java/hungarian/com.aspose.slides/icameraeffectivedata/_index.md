---
title: ICameraEffectiveData
second_title: Aspose.Slides for Java API Referencia
description: Megváltoztathatatlan objektum, amely hatékony kamera tulajdonságokat tartalmaz.
type: docs
url: /hu/com.aspose.slides/icameraeffectivedata/
---```
public interface ICameraEffectiveData
```

Megváltoztathatatlan objektum, amely hatékony kamera tulajdonságokat tartalmaz.

--------------------

Ez a felület a [IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata) részeként használatos.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getCameraType()](#getCameraType--) | Kamera típusa. |
| [getFieldOfViewAngle()](#getFieldOfViewAngle--) | Kamera FOV (0-180 fok, látótér). |
| [getZoom()](#getZoom--) | Kamera zoom (pozitív érték százalékban). |
| [getRotation()](#getRotation--) | A forgatás egy szélességi koordináta, egy hosszúsági koordináta és az tengely körüli revolúció használatával definiálható a szélességi és hosszúsági koordináták alapján. |
### getCameraType() {#getCameraType--}
```
public abstract int getCameraType()
```


Kamera típusa. Csak olvasható [CameraPresetType](../../com.aspose.slides/camerapresettype).

**Visszatérési érték:**
int
### getFieldOfViewAngle() {#getFieldOfViewAngle--}
```
public abstract float getFieldOfViewAngle()
```


Kamera FOV (0-180 fok, látótér). Csak olvasható float.

**Visszatérési érték:**
float
### getZoom() {#getZoom--}
```
public abstract float getZoom()
```


Kamera zoom (pozitív érték százalékban). Csak olvasható float.

**Visszatérési érték:**
float
### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```


A forgatás egy szélességi koordináta, egy hosszúsági koordináta és az tengely körüli revolúció használatával definiálható a szélességi és hosszúsági koordináták alapján. az első elem a visszatérő tömbben – szélesség, a második – hosszúság, a harmadik – revolúció. Null értéket ad vissza, ha nincs definiált forgatás.

**Visszatérési érték:**
float[] – A forgatási értékek tömbje float[] típusként.