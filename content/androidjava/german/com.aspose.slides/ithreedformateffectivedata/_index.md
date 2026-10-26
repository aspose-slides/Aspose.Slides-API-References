---
title: IThreeDFormatEffectiveData
second_title: Aspose.Slides für Android über die Java-API Referenz
description: Unveränderliches Objekt, das die wirksamen 3-D-Formatierungseigenschaften darstellt.
type: docs
url: /de/com.aspose.slides/ithreedformateffectivedata/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.IThreeDParamSource](../../com.aspose.slides/ithreedparamsource)
```
public interface IThreeDFormatEffectiveData extends IThreeDParamSource
```

Unveränderliches Objekt, das die wirksamen 3D-Formatierungseigenschaften darstellt.

--------------------

Dieses Interface wird zusammen mit dem [IThreeDFormat](../../com.aspose.slides/ithreedformat) Interface verwendet, um wirksame Formatierungswerte mit angewandter Vererbung zurückzugeben.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getContourWidth()](#getContourWidth--) | Gibt die Breite einer 3D-Kontur zurück. |
| [getExtrusionHeight()](#getExtrusionHeight--) | Gibt die Höhe eines Extrusionseffekts zurück. |
| [getDepth()](#getDepth--) | Gibt die Tiefe einer 3D-Form zurück. |
| [getBevelTop()](#getBevelTop--) | Gibt den Typ einer oberen 3D-Abrundung zurück. |
| [getBevelBottom()](#getBevelBottom--) | Gibt den Typ einer unteren 3D-Abrundung zurück. |
| [getContourColor()](#getContourColor--) | Gibt die Farbe einer Kontur zurück. |
| [getExtrusionColor()](#getExtrusionColor--) | Gibt die Farbe einer Extrusion zurück. |
| [getCamera()](#getCamera--) | Gibt die Einstellungen einer Kamera zurück. |
| [getLightRig()](#getLightRig--) | Gibt den Typ eines Lichts zurück. |
| [getMaterial()](#getMaterial--) | Gibt den Typ eines Materials zurück. |
### getContourWidth() {#getContourWidth--}
```
public abstract double getContourWidth()
```

Gibt die Breite einer 3D-Kontur zurück. Nur lesbarer double.

**Rückgabewert:**
double
### getExtrusionHeight() {#getExtrusionHeight--}
```
public abstract double getExtrusionHeight()
```

Gibt die Höhe eines Extrusionseffekts zurück. Nur lesbarer double.

**Rückgabewert:**
double
### getDepth() {#getDepth--}
```
public abstract double getDepth()
```

Gibt die Tiefe einer 3D-Form zurück. Nur lesbarer double.

**Rückgabewert:**
double
### getBevelTop() {#getBevelTop--}
```
public abstract IShapeBevelEffectiveData getBevelTop()
```

Gibt den Typ einer oberen 3D-Abrundung zurück. Nur lesbar [IShapeBevelEffectiveData](../../com.aspose.slides/ishapebeveleffectivedata).

**Rückgabewert:**
[IShapeBevelEffectiveData](../../com.aspose.slides/ishapebeveleffectivedata)
### getBevelBottom() {#getBevelBottom--}
```
public abstract IShapeBevelEffectiveData getBevelBottom()
```

Gibt den Typ einer unteren 3D-Abrundung zurück. Nur lesbar [IShapeBevelEffectiveData](../../com.aspose.slides/ishapebeveleffectivedata).

**Rückgabewert:**
[IShapeBevelEffectiveData](../../com.aspose.slides/ishapebeveleffectivedata)
### getContourColor() {#getContourColor--}
```
public abstract Integer getContourColor()
```

Gibt die Farbe einer Kontur zurück. Nur lesbar java.lang.Integer.

**Rückgabewert:**
java.lang.Integer
### getExtrusionColor() {#getExtrusionColor--}
```
public abstract Integer getExtrusionColor()
```

Gibt die Farbe einer Extrusion zurück. Nur lesbar java.lang.Integer.

**Rückgabewert:**
java.lang.Integer
### getCamera() {#getCamera--}
```
public abstract ICameraEffectiveData getCamera()
```

Gibt die Einstellungen einer Kamera zurück. Nur lesbar [ICameraEffectiveData](../../com.aspose.slides/icameraeffectivedata).

**Rückgabewert:**
[ICameraEffectiveData](../../com.aspose.slides/icameraeffectivedata)
### getLightRig() {#getLightRig--}
```
public abstract ILightRigEffectiveData getLightRig()
```

Gibt den Typ eines Lichts zurück. Nur lesbar [ILightRigEffectiveData](../../com.aspose.slides/ilightrigeffectivedata).

**Rückgabewert:**
[ILightRigEffectiveData](../../com.aspose.slides/ilightrigeffectivedata)
### getMaterial() {#getMaterial--}
```
public abstract int getMaterial()
```

Gibt den Typ eines Materials zurück. Nur lesbar [MaterialPresetType](../../com.aspose.slides/materialpresettype).

**Rückgabewert:**
int