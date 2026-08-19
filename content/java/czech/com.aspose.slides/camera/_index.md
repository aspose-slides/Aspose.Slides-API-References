---
title: Camera
second_title: Aspose.Slides pro Java – referenční příručka API
description: Reprezentuje kameru.
type: docs
url: /cs/com.aspose.slides/camera/
---
**Dědičnost:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Všechna implementovaná rozhraní:**
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
| [getFieldOfViewAngle()](#getFieldOfViewAngle--) | Zorné pole kamery (0-180°). |
| [setFieldOfViewAngle(float value)](#setFieldOfViewAngle-float-) | Zorné pole kamery (0-180°). |
| [getZoom()](#getZoom--) | Zoom kamery (kladná hodnota v procentech). |
| [setZoom(float value)](#setZoom-float-) | Zoom kamery (kladná hodnota v procentech). |
| [setRotation(float latitude, float longitude, float revolution)](#setRotation-float-float-float-) | Rotace je definována pomocí souřadnice zeměpisné šířky, souřadnice zeměpisné délky a otáčení kolem osy jako souřadnice šířky a délky. |
| [getRotation()](#getRotation--) | Rotace je definována pomocí souřadnice zeměpisné šířky, souřadnice zeměpisné délky a otáčení kolem osy jako souřadnice šířky a délky. |
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

Typ kamery. Čtení/zápis [CameraPresetType](../../com.aspose.slides/camerapresettype).

**Vrací:**
int
### setCameraType(int value) {#setCameraType-int-}
```
public final void setCameraType(int value)
```

Typ kamery. Čtení/zápis [CameraPresetType](../../com.aspose.slides/camerapresettype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |
### getFieldOfViewAngle() {#getFieldOfViewAngle--}
```
public final float getFieldOfViewAngle()
```

Zorné pole kamery (0-180°). Čtení/zápis float.

**Vrací:**
float
### setFieldOfViewAngle(float value) {#setFieldOfViewAngle-float-}
```
public final void setFieldOfViewAngle(float value)
```

Zorné pole kamery (0-180°). Čtení/zápis float.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |
### getZoom() {#getZoom--}
```
public final float getZoom()
```

Zoom kamery (kladná hodnota v procentech). Čtení/zápis float.

**Vrací:**
float
### setZoom(float value) {#setZoom-float-}
```
public final void setZoom(float value)
```

Zoom kamery (kladná hodnota v procentech). Čtení/zápis float.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |
### setRotation(float latitude, float longitude, float revolution) {#setRotation-float-float-float-}
```
public final void setRotation(float latitude, float longitude, float revolution)
```

Rotace je definována pomocí souřadnice zeměpisné šířky, souřadnice zeměpisné délky a otáčení kolem osy jako souřadnice šířky a délky. Pokud je některá hodnota souřadnice Float.NaN, je rotace nedefinovaná.

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

Rotace je definována pomocí souřadnice zeměpisné šířky, souřadnice zeměpisné délky a otáčení kolem osy jako souřadnice šířky a délky. první prvek v návratovém poli – latitude, druhý – longitude, třetí – revolution. Vrací null, pokud není definována žádná rotace.

**Vrací:**
float[]