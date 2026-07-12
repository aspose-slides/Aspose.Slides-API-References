---
title: IThreeDFormat
second_title: Aspose.Slides Androidhoz Java API hivatkozás
description: 3-D tulajdonságokat képvisel.
type: docs
url: /hu/com.aspose.slides/ithreedformat/
---
**Minden megvalósított interfész:**
[com.aspose.slides.IThreeDParamSource](../../com.aspose.slides/ithreedparamsource)
```
public interface IThreeDFormat extends IThreeDParamSource
```

3-D tulajdonságokat képvisel.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getContourWidth()](#getContourWidth--) | Visszaadja vagy beállítja egy 3D kontúr szélességét. |
| [setContourWidth(double value)](#setContourWidth-double-) | Visszaadja vagy beállítja egy 3D kontúr szélességét. |
| [getExtrusionHeight()](#getExtrusionHeight--) | Visszaadja vagy beállítja egy extrudálás hatás magasságát. |
| [setExtrusionHeight(double value)](#setExtrusionHeight-double-) | Visszaadja vagy beállítja egy extrudálás hatás magasságát. |
| [getDepth()](#getDepth--) | Visszaadja vagy beállítja egy 3D alak mélységét. |
| [setDepth(double value)](#setDepth-double-) | Visszaadja vagy beállítja egy 3D alak mélységét. |
| [getBevelTop()](#getBevelTop--) | Visszaadja vagy beállítja egy felső 3D bevel típusát. |
| [getBevelBottom()](#getBevelBottom--) | Visszaadja vagy beállítja egy alsó 3D bevel típusát. |
| [getContourColor()](#getContourColor--) | Visszaadja vagy beállítja egy kontúr színét. |
| [getExtrusionColor()](#getExtrusionColor--) | Visszaadja vagy beállítja egy extrudálás színét. |
| [getCamera()](#getCamera--) | Visszaadja vagy beállítja egy kamera beállításait. |
| [getLightRig()](#getLightRig--) | Visszaadja vagy beállítja egy fény típusát. |
| [getMaterial()](#getMaterial--) | Visszaadja vagy beállítja egy anyag típusát. |
| [setMaterial(int value)](#setMaterial-int-) | Visszaadja vagy beállítja egy anyag típusát. |
| [getEffective()](#getEffective--) | Hatékony 3-D formázási adatokat kap a leszármazás alkalmazásával. |
### getContourWidth() {#getContourWidth--}
```
public abstract double getContourWidth()
```

Visszaadja vagy beállítja egy 3D kontúr szélességét. Olvasás/írás double.

**Visszatérési érték:**
double
### setContourWidth(double value) {#setContourWidth-double-}
```
public abstract void setContourWidth(double value)
```

Visszaadja vagy beállítja egy 3D kontúr szélességét. Olvasás/írás double.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double |  |
### getExtrusionHeight() {#getExtrusionHeight--}
```
public abstract double getExtrusionHeight()
```

Visszaadja vagy beállítja egy extrudálás hatás magasságát. Olvasás/írás double.

**Visszatérési érték:**
double
### setExtrusionHeight(double value) {#setExtrusionHeight-double-}
```
public abstract void setExtrusionHeight(double value)
```

Visszaadja vagy beállítja egy extrudálás hatás magasságát. Olvasás/írás double.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double |  |
### getDepth() {#getDepth--}
```
public abstract double getDepth()
```

Visszaadja vagy beállítja egy 3D alak mélységét. Olvasás/írás double.

**Visszatérési érték:**
double
### setDepth(double value) {#setDepth-double-}
```
public abstract void setDepth(double value)
```

Visszaadja vagy beállítja egy 3D alak mélységét. Olvasás/írás double.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double |  |
### getBevelTop() {#getBevelTop--}
```
public abstract IShapeBevel getBevelTop()
```

Visszaadja vagy beállítja egy felső 3D bevel típusát. Csak olvasható [IShapeBevel](../../com.aspose.slides/ishapebevel).

**Visszatérési érték:**
[IShapeBevel](../../com.aspose.slides/ishapebevel)
### getBevelBottom() {#getBevelBottom--}
```
public abstract IShapeBevel getBevelBottom()
```

Visszaadja vagy beállítja egy alsó 3D bevel típusát. Csak olvasható [IShapeBevel](../../com.aspose.slides/ishapebevel).

**Visszatérési érték:**
[IShapeBevel](../../com.aspose.slides/ishapebevel)
### getContourColor() {#getContourColor--}
```
public abstract IColorFormat getContourColor()
```

Visszaadja vagy beállítja egy kontúr színét. Csak olvasható [IColorFormat](../../com.aspose.slides/icolorformat).

**Visszatérési érték:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getExtrusionColor() {#getExtrusionColor--}
```
public abstract IColorFormat getExtrusionColor()
```

Visszaadja vagy beállítja egy extrudálás színét. Csak olvasható [IColorFormat](../../com.aspose.slides/icolorformat).

**Visszatérési érték:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getCamera() {#getCamera--}
```
public abstract ICamera getCamera()
```

Visszaadja vagy beállítja egy kamera beállításait. Csak olvasható [ICamera](../../com.aspose.slides/icamera).

**Visszatérési érték:**
[ICamera](../../com.aspose.slides/icamera)
### getLightRig() {#getLightRig--}
```
public abstract ILightRig getLightRig()
```

Visszaadja vagy beállítja egy fény típusát. Csak olvasható [ILightRig](../../com.aspose.slides/ilightrig).

**Visszatérési érték:**
[ILightRig](../../com.aspose.slides/ilightrig)
### getMaterial() {#getMaterial--}
```
public abstract int getMaterial()
```

Visszaadja vagy beállítja egy anyag típusát. Olvasás/írás [MaterialPresetType](../../com.aspose.slides/materialpresettype).

**Visszatérési érték:**
int
### setMaterial(int value) {#setMaterial-int-}
```
public abstract void setMaterial(int value)
```

Visszaadja vagy beállítja egy anyag típusát. Olvasás/írás [MaterialPresetType](../../com.aspose.slides/materialpresettype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |
### getEffective() {#getEffective--}
```
public abstract IThreeDFormatEffectiveData getEffective()
```

Hatékony 3-D formázási adatokat kap a leszármazás alkalmazásával.

**Visszatérési érték:**
[IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata) - A [IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata).