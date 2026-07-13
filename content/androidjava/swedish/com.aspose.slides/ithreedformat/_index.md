---
title: IThreeDFormat
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar 3-D egenskaper.
type: docs
url: /sv/com.aspose.slides/ithreedformat/
---
**Alla implementerade gränssnitt:**
[com.aspose.slides.IThreeDParamSource](../../com.aspose.slides/ithreedparamsource)
```
public interface IThreeDFormat extends IThreeDParamSource
```

Representerar 3D-egenskaper.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getContourWidth()](#getContourWidth--) | Returnerar eller sätter bredden på en 3D-kontur. |
| [setContourWidth(double value)](#setContourWidth-double-) | Returnerar eller sätter bredden på en 3D-kontur. |
| [getExtrusionHeight()](#getExtrusionHeight--) | Returnerar eller sätter höjden på en extrusion-effekt. |
| [setExtrusionHeight(double value)](#setExtrusionHeight-double-) | Returnerar eller sätter höjden på en extrusion-effekt. |
| [getDepth()](#getDepth--) | Returnerar eller sätter djupet på en 3D-form. |
| [setDepth(double value)](#setDepth-double-) | Returnerar eller sätter djupet på en 3D-form. |
| [getBevelTop()](#getBevelTop--) | Returnerar eller sätter typen på en topp-3D-förslutning. |
| [getBevelBottom()](#getBevelBottom--) | Returnerar eller sätter typen på en botten-3D-förslutning. |
| [getContourColor()](#getContourColor--) | Returnerar eller sätter färgen på en kontur. |
| [getExtrusionColor()](#getExtrusionColor--) | Returnerar eller sätter färgen på en extrusion. |
| [getCamera()](#getCamera--) | Returnerar eller sätter inställningarna för en kamera. |
| [getLightRig()](#getLightRig--) | Returnerar eller sätter typen på ett ljus. |
| [getMaterial()](#getMaterial--) | Returnerar eller sätter typen på ett material. |
| [setMaterial(int value)](#setMaterial-int-) | Returnerar eller sätter typen på ett material. |
| [getEffective()](#getEffective--) | Hämtar effektiv 3D-formateringsdata med arv tillämpat. |
### getContourWidth() {#getContourWidth--}
```
public abstract double getContourWidth()
```


Returnerar eller sätter bredden på en 3D-kontur. Läs/skriv double.

**Returnerar:**
double
### setContourWidth(double value) {#setContourWidth-double-}
```
public abstract void setContourWidth(double value)
```


Returnerar eller sätter bredden på en 3D-kontur. Läs/skriv double.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | double |  |

### getExtrusionHeight() {#getExtrusionHeight--}
```
public abstract double getExtrusionHeight()
```


Returnerar eller sätter höjden på en extrusion-effekt. Läs/skriv double.

**Returnerar:**
double
### setExtrusionHeight(double value) {#setExtrusionHeight-double-}
```
public abstract void setExtrusionHeight(double value)
```


Returnerar eller sätter höjden på en extrusion-effekt. Läs/skriv double.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | double |  |

### getDepth() {#getDepth--}
```
public abstract double getDepth()
```


Returnerar eller sätter djupet på en 3D-form. Läs/skriv double.

**Returnerar:**
double
### setDepth(double value) {#setDepth-double-}
```
public abstract void setDepth(double value)
```


Returnerar eller sätter djupet på en 3D-form. Läs/skriv double.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | double |  |

### getBevelTop() {#getBevelTop--}
```
public abstract IShapeBevel getBevelTop()
```


Returnerar eller sätter typen på en topp-3D-förslutning. Endast läs [IShapeBevel](../../com.aspose.slides/ishapebevel).

**Returnerar:**
[IShapeBevel](../../com.aspose.slides/ishapebevel)
### getBevelBottom() {#getBevelBottom--}
```
public abstract IShapeBevel getBevelBottom()
```


Returnerar eller sätter typen på en botten-3D-förslutning. Endast läs [IShapeBevel](../../com.aspose.slides/ishapebevel).

**Returnerar:**
[IShapeBevel](../../com.aspose.slides/ishapebevel)
### getContourColor() {#getContourColor--}
```
public abstract IColorFormat getContourColor()
```


Returnerar eller sätter färgen på en kontur. Endast läs [IColorFormat](../../com.aspose.slides/icolorformat).

**Returnerar:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getExtrusionColor() {#getExtrusionColor--}
```
public abstract IColorFormat getExtrusionColor()
```


Returnerar eller sätter färgen på en extrusion. Endast läs [IColorFormat](../../com.aspose.slides/icolorformat).

**Returnerar:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getCamera() {#getCamera--}
```
public abstract ICamera getCamera()
```


Returnerar eller sätter inställningarna för en kamera. Endast läs [ICamera](../../com.aspose.slides/icamera).

**Returnerar:**
[ICamera](../../com.aspose.slides/icamera)
### getLightRig() {#getLightRig--}
```
public abstract ILightRig getLightRig()
```


Returnerar eller sätter typen på ett ljus. Endast läs [ILightRig](../../com.aspose.slides/ilightrig).

**Returnerar:**
[ILightRig](../../com.aspose.slides/ilightrig)
### getMaterial() {#getMaterial--}
```
public abstract int getMaterial()
```


Returnerar eller sätter typen på ett material. Läs/skriv [MaterialPresetType](../../com.aspose.slides/materialpresettype).

**Returnerar:**
int
### setMaterial(int value) {#setMaterial-int-}
```
public abstract void setMaterial(int value)
```


Returnerar eller sätter typen på ett material. Läs/skriv [MaterialPresetType](../../com.aspose.slides/materialpresettype).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getEffective() {#getEffective--}
```
public abstract IThreeDFormatEffectiveData getEffective()
```


Hämtar effektiv 3D-formateringsdata med arv tillämpat.

**Returnerar:**
[IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata) - En [IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata).