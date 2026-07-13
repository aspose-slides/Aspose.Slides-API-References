---
title: Camera
second_title: Aspose.Slides pro Android pomocí Java API reference
description: Reprezentuje kameru.
type: docs
url: /cs/com.aspose.slides/camera/
---
**Dědičnost:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Všechny implementované rozhraní:**
[com.aspose.slides.ICamera](../../com.aspose.slides/icamera)
```
public final class Camera extends PVIObject implements ICamera
```

Reprezentuje kameru.
## Metody

| Metoda | Popis |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getCameraType()](#getCameraType--) | Typ kamery. |
| [setCameraType(int value)](#setCameraType-int-) | Typ kamery. |
| [getFieldOfViewAngle()](#getFieldOfViewAngle--) | FOV kamery (0-180 deg, field of View). |
| [setFieldOfViewAngle(float value)](#setFieldOfViewAngle-float-) | FOV kamery (0-180 deg, field of View). |
| [getZoom()](#getZoom--) | Zoom kamery (kladná hodnota v procentech). |
| [setZoom(float value)](#setZoom-float-) | Zoom kamery (kladná hodnota v procentech). |
| [setRotation(float latitude, float longitude, float revolution)](#setRotation-float-float-float-) | Rotace je definována pomocí souřadnice zeměpisné šířky, souřadnice zeměpisné délky a otáčení kolem osy podle souřadnic zeměpisné šířky a délky. |
| [getRotation()](#getRotation--) | Rotace je definována pomocí souřadnice zeměpisné šířky, souřadnice zeměpisné délky a otáčení kolem osy podle souřadnic zeměpisné šířky a délky. |
### getVersion() {#getVersion--}
```
public long getVersion()
```

Verze. Pouze pro čtení long.

**Vrací:**
long
### getCameraType() {#getCameraType--}
```
public final int getCameraType()
```

Typ kamery. Čtení/Zápis [CameraPresetType](../../com.aspose.slides/camerapresettype).

**Vrací:**
int
### setCameraType(int value) {#setCameraType-int-}
```
public final void setCameraType(int value)
```

Typ kamery. Čtení/Zápis [CameraPresetType](../../com.aspose.slides/camerapresettype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |
### getFieldOfViewAngle() {#getFieldOfViewAngle--}
```
public final float getFieldOfViewAngle()
```

FOV kamery (0-180 deg, field of View). Čtení/Zápis float.

**Vrací:**
float
### setFieldOfViewAngle(float value) {#setFieldOfViewAngle-float-}
```
public final void setFieldOfViewAngle(float value)
```

FOV kamery (0-180 deg, field of View). Čtení/Zápis float.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |
### getZoom() {#getZoom--}
```
public final float getZoom()
```

Zoom kamery (kladná hodnota v procentech). Čtení/Zápis float.

**Vrací:**
float
### setZoom(float value) {#setZoom-float-}
```
public final void setZoom(float value)
```

Zoom kamery (kladná hodnota v procentech). Čtení/Zápis float.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |
### setRotation(float latitude, float longitude, float revolution) {#setRotation-float-float-float-}
```
public final void setRotation(float latitude, float longitude, float revolution)
```

Rotace je definována pomocí souřadnice zeměpisné šířky, souřadnice zeměpisné délky a otáčení kolem osy podle souřadnic zeměpisné šířky a délky. Pokud je některá hodnota souřadnice Float.NaN, je celá rotace nedefinovaná.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| latitude | float |  |
| longitude | float |  |
| revolution | float |  |
### getRotation() {#getRotation--}
```
public final float[] getRotation()
```

Rotace je definována pomocí souřadnice zeměpisné šířky, souřadnice zeměpisné délky a otáčení kolem osy podle souřadnic zeměpisné šířky a délky. první prvek v návratovém poli – zeměpisná šířka, druhý – zeměpisná délka, třetí – otáčení. Vrací null, pokud není definována žádná rotace.

**Vrací:**
float[]