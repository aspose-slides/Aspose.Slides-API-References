---
title: IThreeDFormatEffectiveData
second_title: Aspose.Slides för Java API-referens
description: Oföränderligt objekt som representerar effektiva 3-D formateringsegenskaper.
type: docs
url: /sv/com.aspose.slides/ithreedformateffectivedata/
---
**Alla implementerade gränssnitt:**
[com.aspose.slides.IThreeDParamSource](../../com.aspose.slides/ithreedparamsource)
```
public interface IThreeDFormatEffectiveData extends IThreeDParamSource
```

Oföränderligt objekt som representerar effektiva 3-D formateringsegenskaper.

--------------------

Det här gränssnittet används tillsammans med [IThreeDFormat](../../com.aspose.slides/ithreedformat) gränssnitt för att returnera effektiva formateringsvärden med ärftlighet tillämpad.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getContourWidth()](#getContourWidth--) | Returnerar bredden på en 3D-kontur. |
| [getExtrusionHeight()](#getExtrusionHeight--) | Returnerar höjden på en extruderings effekt. |
| [getDepth()](#getDepth--) | Returnerar djupet på en 3D-form. |
| [getBevelTop()](#getBevelTop--) | Returnerar typen av en topp 3D-avfasning. |
| [getBevelBottom()](#getBevelBottom--) | Returnerar typen av en botten 3D-avfasning. |
| [getContourColor()](#getContourColor--) | Returnerar färgen på en kontur. |
| [getExtrusionColor()](#getExtrusionColor--) | Returnerar färgen på en extrudering. |
| [getCamera()](#getCamera--) | Returnerar inställningarna för en kamera. |
| [getLightRig()](#getLightRig--) | Returnerar typen av ett ljus. |
| [getMaterial()](#getMaterial--) | Returnerar typen av ett material. |
### getContourWidth() {#getContourWidth--}
```
public abstract double getContourWidth()
```


Returnerar bredden på en 3D-kontur. Skrivskyddad double.

**Returnerar:**
double
### getExtrusionHeight() {#getExtrusionHeight--}
```
public abstract double getExtrusionHeight()
```


Returnerar höjden på en extruderings effekt. Skrivskyddad double.

**Returnerar:**
double
### getDepth() {#getDepth--}
```
public abstract double getDepth()
```


Returnerar djupet på en 3D-form. Skrivskyddad double.

**Returnerar:**
double
### getBevelTop() {#getBevelTop--}
```
public abstract IShapeBevelEffectiveData getBevelTop()
```


Returnerar typen av en topp 3D-avfasning. Skrivskyddad [IShapeBevelEffectiveData](../../com.aspose.slides/ishapebeveleffectivedata).

**Returnerar:**
[IShapeBevelEffectiveData](../../com.aspose.slides/ishapebeveleffectivedata)
### getBevelBottom() {#getBevelBottom--}
```
public abstract IShapeBevelEffectiveData getBevelBottom()
```


Returnerar typen av en botten 3D-avfasning. Skrivskyddad [IShapeBevelEffectiveData](../../com.aspose.slides/ishapebeveleffectivedata).

**Returnerar:**
[IShapeBevelEffectiveData](../../com.aspose.slides/ishapebeveleffectivedata)
### getContourColor() {#getContourColor--}
```
public abstract Color getContourColor()
```


Returnerar färgen på en kontur. Skrivskyddad java.awt.Color.

**Returnerar:**
java.awt.Color
### getExtrusionColor() {#getExtrusionColor--}
```
public abstract Color getExtrusionColor()
```


Returnerar färgen på en extrudering. Skrivskyddad java.awt.Color.

**Returnerar:**
java.awt.Color
### getCamera() {#getCamera--}
```
public abstract ICameraEffectiveData getCamera()
```


Returnerar inställningarna för en kamera. Skrivskyddad [ICameraEffectiveData](../../com.aspose.slides/icameraeffectivedata).

**Returnerar:**
[ICameraEffectiveData](../../com.aspose.slides/icameraeffectivedata)
### getLightRig() {#getLightRig--}
```
public abstract ILightRigEffectiveData getLightRig()
```


Returnerar typen av ett ljus. Skrivskyddad [ILightRigEffectiveData](../../com.aspose.slides/ilightrigeffectivedata).

**Returnerar:**
[ILightRigEffectiveData](../../com.aspose.slides/ilightrigeffectivedata)
### getMaterial() {#getMaterial--}
```
public abstract int getMaterial()
```


Returnerar typen av ett material. Skrivskyddad [MaterialPresetType](../../com.aspose.slides/materialpresettype).

**Returnerar:**
int