---
title: ICameraEffectiveData
second_title: Aspose.Slides for Java API Reference
description: Neměnný objekt, který obsahuje efektivní vlastnosti kamery.
type: docs
url: /cs/com.aspose.slides/icameraeffectivedata/
---```
public interface ICameraEffectiveData
```

Neměnný objekt, který obsahuje efektivní vlastnosti kamery.

--------------------

Toto rozhraní se používá jako součást [IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata).
## Metody

| Metoda | Popis |
| --- | --- |
| [getCameraType()](#getCameraType--) | Typ kamery. |
| [getFieldOfViewAngle()](#getFieldOfViewAngle--) | FOV kamery (0-180 °, field of View). |
| [getZoom()](#getZoom--) | Zoom kamery (kladná hodnota v procentech). |
| [getRotation()](#getRotation--) | Rotace je definována pomocí souřadnice latitude, souřadnice longitude a otáčení kolem osy jako latitude a longitude. |

### getCameraType() {#getCameraType--}
```
public abstract int getCameraType()
```

Typ kamery. Pouze ke čtení [CameraPresetType](../../com.aspose.slides/camerapresettype).

**Vrací:**
int

### getFieldOfViewAngle() {#getFieldOfViewAngle--}
```
public abstract float getFieldOfViewAngle()
```

FOV kamery (0-180 °, field of View). Pouze ke čtení float.

**Vrací:**
float

### getZoom() {#getZoom--}
```
public abstract float getZoom()
```

Zoom kamery (kladná hodnota v procentech). Pouze ke čtení float.

**Vrací:**
float

### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```

Rotace je definována pomocí souřadnice latitude, souřadnice longitude a otáčení kolem osy jako latitude a longitude. první prvek v návratovém poli – latitude, druhý – longitude, třetí – revolution. Vrátí null, pokud není definována žádná rotace.

**Vrací:**
float[] - Pole hodnot rotace jako float[].