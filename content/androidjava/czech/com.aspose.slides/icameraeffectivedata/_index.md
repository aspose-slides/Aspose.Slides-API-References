---
title: ICameraEffectiveData
second_title: Aspose.Slides pro Android přes Java API Reference
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

| Method | Description |
| --- | --- |
| [getCameraType()](#getCameraType--) | Typ kamery. |
| [getFieldOfViewAngle()](#getFieldOfViewAngle--) | FOV kamery (0-180 deg, field of View). |
| [getZoom()](#getZoom--) | Přiblížení kamery (kladná hodnota v procentech). |
| [getRotation()](#getRotation--) | Rotace je definována pomocí souřadnice zeměpisné šířky, souřadnice zeměpisné délky a otáčením kolem osy jako zeměpisné šířky a délky. |

### getCameraType() {#getCameraType--}
```
public abstract int getCameraType()
```

Typ kamery. Pouze pro čtení [CameraPresetType](../../com.aspose.slides/camerapresettype).

**Vrací:**
int

### getFieldOfViewAngle() {#getFieldOfViewAngle--}
```
public abstract float getFieldOfViewAngle()
```

FOV kamery (0-180 deg, field of View). Pouze pro čtení float.

**Vrací:**
float

### getZoom() {#getZoom--}
```
public abstract float getZoom()
```

Přiblížení kamery (kladná hodnota v procentech). Pouze pro čtení float.

**Vrací:**
float

### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```

Rotace je definována pomocí souřadnice zeměpisné šířky, souřadnice zeměpisné délky a otáčením kolem osy jako zeměpisné šířky a délky. první prvek v návratovém poli – latitude, druhý – longitude, třetí – revolution. Vrací null, pokud není rotace definována.

**Vrací:**
float[] - Pole rotačních hodnot jako float[].