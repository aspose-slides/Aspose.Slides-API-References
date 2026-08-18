---
title: IThreeDFormatEffectiveData
second_title: Aspose.Slides for Java API hivatkozás
description: Változtathatatlan objektum, amely a tényleges 3-D formázási tulajdonságokat képviseli.
type: docs
url: /hu/com.aspose.slides/ithreedformateffectivedata/
---
**Az összes megvalósított interfész:**
[com.aspose.slides.IThreeDParamSource](../../com.aspose.slides/ithreedparamsource)
```
public interface IThreeDFormatEffectiveData extends IThreeDParamSource
```

Változtathatatlan objektum, amely a tényleges 3-D formázási tulajdonságokat képviseli.

--------------------

Ez az interfész a [IThreeDFormat](../../com.aspose.slides/ithreedformat) interfésszel együtt használható a tényleges formázási értékek visszaadására öröklődéssel alkalmazva.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getContourWidth()](#getContourWidth--) | Visszaadja a 3D kontúr szélességét. |
| [getExtrusionHeight()](#getExtrusionHeight--) | Visszaadja az extrúziós hatás magasságát. |
| [getDepth()](#getDepth--) | Visszaadja a 3D alakzat mélységét. |
| [getBevelTop()](#getBevelTop--) | Visszaadja a felső 3D levágás típusát. |
| [getBevelBottom()](#getBevelBottom--) | Visszaadja az alsó 3D levágás típusát. |
| [getContourColor()](#getContourColor--) | Visszaadja a kontúr színét. |
| [getExtrusionColor()](#getExtrusionColor--) | Visszaadja az extrúzió színét. |
| [getCamera()](#getCamera--) | Visszaadja a kamera beállításait. |
| [getLightRig()](#getLightRig--) | Visszaadja a fény típusát. |
| [getMaterial()](#getMaterial--) | Visszaadja az anyag típusát. |
### getContourWidth() {#getContourWidth--}
```
public abstract double getContourWidth()
```

Visszaadja a 3D kontúr szélességét. Csak olvasható double.

**Visszaad:**
double
### getExtrusionHeight() {#getExtrusionHeight--}
```
public abstract double getExtrusionHeight()
```

Visszaadja az extrúziós hatás magasságát. Csak olvasható double.

**Visszaad:**
double
### getDepth() {#getDepth--}
```
public abstract double getDepth()
```

Visszaadja a 3D alakzat mélységét. Csak olvasható double.

**Visszaad:**
double
### getBevelTop() {#getBevelTop--}
```
public abstract IShapeBevelEffectiveData getBevelTop()
```

Visszaadja a felső 3D levágás típusát. Csak olvasható [IShapeBevelEffectiveData](../../com.aspose.slides/ishapebeveleffectivedata).

**Visszaad:**
[IShapeBevelEffectiveData](../../com.aspose.slides/ishapebeveleffectivedata)
### getBevelBottom() {#getBevelBottom--}
```
public abstract IShapeBevelEffectiveData getBevelBottom()
```

Visszaadja az alsó 3D levágás típusát. Csak olvasható [IShapeBevelEffectiveData](../../com.aspose.slides/ishapebeveleffectivedata).

**Visszaad:**
[IShapeBevelEffectiveData](../../com.aspose.slides/ishapebeveleffectivedata)
### getContourColor() {#getContourColor--}
```
public abstract Color getContourColor()
```

Visszaadja a kontúr színét. Csak olvasható java.awt.Color.

**Visszaad:**
java.awt.Color
### getExtrusionColor() {#getExtrusionColor--}
```
public abstract Color getExtrusionColor()
```

Visszaadja az extrúzió színét. Csak olvasható java.awt.Color.

**Visszaad:**
java.awt.Color
### getCamera() {#getCamera--}
```
public abstract ICameraEffectiveData getCamera()
```

Visszaadja a kamera beállításait. Csak olvasható [ICameraEffectiveData](../../com.aspose.slides/icameraeffectivedata).

**Visszaad:**
[ICameraEffectiveData](../../com.aspose.slides/icameraeffectivedata)
### getLightRig() {#getLightRig--}
```
public abstract ILightRigEffectiveData getLightRig()
```

Visszaadja a fény típusát. Csak olvasható [ILightRigEffectiveData](../../com.aspose.slides/ilightrigeffectivedata).

**Visszaad:**
[ILightRigEffectiveData](../../com.aspose.slides/ilightrigeffectivedata)
### getMaterial() {#getMaterial--}
```
public abstract int getMaterial()
```

Visszaadja az anyag típusát. Csak olvasható [MaterialPresetType](../../com.aspose.slides/materialpresettype).

**Visszaad:**
int