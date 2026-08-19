---
title: IThreeDFormat
second_title: Aspose.Slides för Java API-referens
description: Representerar 3-D egenskaper.
type: docs
url: /sv/com.aspose.slides/ithreedformat/
---
**Alla implementerade gränssnitt:**
[com.aspose.slides.IThreeDParamSource](../../com.aspose.slides/ithreedparamsource)
```
public interface IThreeDFormat extends IThreeDParamSource
```

Representerar 3-D egenskaper.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getContourWidth()](#getContourWidth--) | Returnerar eller sätter bredden på en 3D-kontur. |
| [setContourWidth(double value)](#setContourWidth-double-) | Returnerar eller sätter bredden på en 3D-kontur. |
| [getExtrusionHeight()](#getExtrusionHeight--) | Returnerar eller sätter höjden på en extruderingseffekt. |
| [setExtrusionHeight(double value)](#setExtrusionHeight-double-) | Returnerar eller sätter höjden på en extruderingseffekt. |
| [getDepth()](#getDepth--) | Returnerar eller sätter djupet på en 3D-form. |
| [setDepth(double value)](#setDepth-double-) | Returnerar eller sätter djupet på en 3D-form. |
| [getBevelTop()](#getBevelTop--) | Returnerar eller sätter typen av en topp 3D-fasning. |
| [getBevelBottom()](#getBevelBottom--) | Returnerar eller sätter typen av en botten 3D-fasning. |
| [getContourColor()](#getContourColor--) | Returnerar eller sätter färgen på en kontur. |
| [getExtrusionColor()](#getExtrusionColor--) | Returnerar eller sätter färgen på en extrudering. |
| [getCamera()](#getCamera--) | Returnerar eller sätter inställningarna för en kamera. |
| [getLightRig()](#getLightRig--) | Returnerar eller sätter typen av ett ljus. |
| [getMaterial()](#getMaterial--) | Returnerar eller sätter typen av ett material. |
| [setMaterial(int value)](#setMaterial-int-) | Returnerar eller sätter typen av ett material. |
| [getEffective()](#getEffective--) | Hämtar effektiv 3-D formateringsdata med arv tillämpat. |
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


Returnerar eller sätter höjden på en extruderingseffekt. Läs/skriv double.

**Returnerar:**
double
### setExtrusionHeight(double value) {#setExtrusionHeight-double-}
```
public abstract void setExtrusionHeight(double value)
```


Returnerar eller sätter höjden på en extruderingseffekt. Läs/skriv double.

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


Returnerar eller sätter typen av en topp 3D-fasning. Skrivskyddad [IShapeBevel](../../com.aspose.slides/ishapebevel).

**Returnerar:**
[IShapeBevel](../../com.aspose.slides/ishapebevel)
### getBevelBottom() {#getBevelBottom--}
```
public abstract IShapeBevel getBevelBottom()
```


Returnerar eller sätter typen av en botten 3D-fasning. Skrivskyddad [IShapeBevel](../../com.aspose.slides/ishapebevel).

**Returnerar:**
[IShapeBevel](../../com.aspose.slides/ishapebevel)
### getContourColor() {#getContourColor--}
```
public abstract IColorFormat getContourColor()
```


Returnerar eller sätter färgen på en kontur. Skrivskyddad [IColorFormat](../../com.aspose.slides/icolorformat).

**Returnerar:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getExtrusionColor() {#getExtrusionColor--}
```
public abstract IColorFormat getExtrusionColor()
```


Returnerar eller sätter färgen på en extrudering. Skrivskyddad [IColorFormat](../../com.aspose.slides/icolorformat).

**Returnerar:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getCamera() {#getCamera--}
```
public abstract ICamera getCamera()
```


Returnerar eller sätter inställningarna för en kamera. Skrivskyddad [ICamera](../../com.aspose.slides/icamera).

**Returnerar:**
[ICamera](../../com.aspose.slides/icamera)
### getLightRig() {#getLightRig--}
```
public abstract ILightRig getLightRig()
```


Returnerar eller sätter typen av ett ljus. Skrivskyddad [ILightRig](../../com.aspose.slides/ilightrig).

**Returnerar:**
[ILightRig](../../com.aspose.slides/ilightrig)
### getMaterial() {#getMaterial--}
```
public abstract int getMaterial()
```


Returnerar eller sätter typen av ett material. Läs/skriv [MaterialPresetType](../../com.aspose.slides/materialpresettype).

**Returnerar:**
int
### setMaterial(int value) {#setMaterial-int-}
```
public abstract void setMaterial(int value)
```


Returnerar eller sätter typen av ett material. Läs/skriv [MaterialPresetType](../../com.aspose.slides/materialpresettype).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getEffective() {#getEffective--}
```
public abstract IThreeDFormatEffectiveData getEffective()
```


Hämtar effektiv 3-D formateringsdata med arv tillämpat.

**Returnerar:**
[IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata) - A [IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata).