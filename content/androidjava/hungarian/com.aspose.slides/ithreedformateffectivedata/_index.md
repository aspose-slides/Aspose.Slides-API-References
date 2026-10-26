---
title: IThreeDFormatEffectiveData
second_title: Aspose.Slides Androidhoz Java API-referencia
description: Változtathatatlan objektum, amely a tényleges 3-D formázási tulajdonságokat képviseli.
type: docs
url: /hu/com.aspose.slides/ithreedformateffectivedata/
---
**Minden megvalósított interfész:**
[com.aspose.slides.IThreeDParamSource](../../com.aspose.slides/ithreedparamsource)
```
public interface IThreeDFormatEffectiveData extends IThreeDParamSource
```

Változtathatatlan objektum, amely a tényleges 3-D formázási tulajdonságokat képviseli.

--------------------

Ez az interfész a [IThreeDFormat](../../com.aspose.slides/ithreedformat) interfésszel együtt használható a tényleges formázási értékek visszaadására, öröklődéssel alkalmazva.
## Módszerek

| Method | Description |
| --- | --- |
| [getContourWidth()](#getContourWidth--) | Visszaadja egy 3D kontúr szélességét. |
| [getExtrusionHeight()](#getExtrusionHeight--) | Visszaadja egy kiállítási effektus magasságát. |
| [getDepth()](#getDepth--) | Visszaadja egy 3D alak mélységét. |
| [getBevelTop()](#getBevelTop--) | Visszaadja egy felső 3D élesítés típusát. |
| [getBevelBottom()](#getBevelBottom--) | Visszaadja egy alsó 3D élesítés típusát. |
| [getContourColor()](#getContourColor--) | Visszaadja egy kontúr színét. |
| [getExtrusionColor()](#getExtrusionColor--) | Visszaadja egy kiállítás színét. |
| [getCamera()](#getCamera--) | Visszaadja a kamera beállításait. |
| [getLightRig()](#getLightRig--) | Visszaadja egy fény típusát. |
| [getMaterial()](#getMaterial--) | Visszaadja egy anyag típusát. |
### getContourWidth() {#getContourWidth--}
```
public abstract double getContourWidth()
```

Visszaadja egy 3D kontúr szélességét. Csak olvasható double.

**Visszatér:**
double
### getExtrusionHeight() {#getExtrusionHeight--}
```
public abstract double getExtrusionHeight()
```

Visszaadja egy kiállítási effektus magasságát. Csak olvasható double.

**Visszatér:**
double
### getDepth() {#getDepth--}
```
public abstract double getDepth()
```

Visszaadja egy 3D alak mélységét. Csak olvasható double.

**Visszatér:**
double
### getBevelTop() {#getBevelTop--}
```
public abstract IShapeBevelEffectiveData getBevelTop()
```

Visszaadja egy felső 3D élesítés típusát. Csak olvasható [IShapeBevelEffectiveData](../../com.aspose.slides/ishapebeveleffectivedata).

**Visszatér:**
[IShapeBevelEffectiveData](../../com.aspose.slides/ishapebeveleffectivedata)
### getBevelBottom() {#getBevelBottom--}
```
public abstract IShapeBevelEffectiveData getBevelBottom()
```

Visszaadja egy alsó 3D élesítés típusát. Csak olvasható [IShapeBevelEffectiveData](../../com.aspose.slides/ishapebeveleffectivedata).

**Visszatér:**
[IShapeBevelEffectiveData](../../com.aspose.slides/ishapebeveleffectivedata)
### getContourColor() {#getContourColor--}
```
public abstract Integer getContourColor()
```

Visszaadja egy kontúr színét. Csak olvasható java.lang.Integer.

**Visszatér:**
java.lang.Integer
### getExtrusionColor() {#getExtrusionColor--}
```
public abstract Integer getExtrusionColor()
```

Visszaadja egy kiállítás színét. Csak olvasható java.lang.Integer.

**Visszatér:**
java.lang.Integer
### getCamera() {#getCamera--}
```
public abstract ICameraEffectiveData getCamera()
```

Visszaadja a kamera beállításait. Csak olvasható [ICameraEffectiveData](../../com.aspose.slides/icameraeffectivedata).

**Visszatér:**
[ICameraEffectiveData](../../com.aspose.slides/icameraeffectivedata)
### getLightRig() {#getLightRig--}
```
public abstract ILightRigEffectiveData getLightRig()
```

Visszaadja egy fény típusát. Csak olvasható [ILightRigEffectiveData](../../com.aspose.slides/ilightrigeffectivedata).

**Visszatér:**
[ILightRigEffectiveData](../../com.aspose.slides/ilightrigeffectivedata)
### getMaterial() {#getMaterial--}
```
public abstract int getMaterial()
```

Visszaadja egy anyag típusát. Csak olvasható [MaterialPresetType](../../com.aspose.slides/materialpresettype).

**Visszatér:**
int