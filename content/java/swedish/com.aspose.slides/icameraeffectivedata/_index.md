---
title: ICameraEffectiveData
second_title: Aspose.Slides for Java API Reference
description: Immutable object which contains effective camera properties.
type: docs
url: /sv/com.aspose.slides/icameraeffectivedata/
---```
public interface ICameraEffectiveData
```

Immutabelt objekt som innehåller effektiva kamerainställningar.

--------------------

Detta gränssnitt används som en del av [IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata).
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getCameraType()](#getCameraType--) | Kameratyp. |
| [getFieldOfViewAngle()](#getFieldOfViewAngle--) | Kamera FOV (0-180 grad, synfält). |
| [getZoom()](#getZoom--) | Kamerazoom (positivt värde i procent). |
| [getRotation()](#getRotation--) | En rotation definieras genom användning av en latitud-koordinat, en longitud-koordinat och en revolution kring axeln som latitud- och longitud-koordinater. |
### getCameraType() {#getCameraType--}
```
public abstract int getCameraType()
```


Kameratyp. Skrivskyddad [CameraPresetType](../../com.aspose.slides/camerapresettype).

**Returnerar:**
int
### getFieldOfViewAngle() {#getFieldOfViewAngle--}
```
public abstract float getFieldOfViewAngle()
```


Kamera FOV (0-180 grad, synfält). Skrivskyddad float.

**Returnerar:**
float
### getZoom() {#getZoom--}
```
public abstract float getZoom()
```


Kamerazoom (positivt värde i procent). Skrivskyddad float.

**Returnerar:**
float
### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```


En rotation definieras genom användning av en latitud-koordinat, en longitud-koordinat och en revolution kring axeln som latitud- och longitud-koordinater. första elementet i retur-arrayen – latitud, andra – longitud, tredje – revolution. Returnerar null om ingen rotation är definierad.

**Returnerar:**
float[] – Array av rotationsvärden som float[].