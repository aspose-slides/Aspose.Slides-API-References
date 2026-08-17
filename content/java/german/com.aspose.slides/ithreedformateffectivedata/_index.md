---
title: IThreeDFormatEffectiveData
second_title: Aspose.Slides für Java API Referenz
description: Unveränderliches Objekt, das die effektiven 3-D-Formatierungseigenschaften repräsentiert.
type: docs
url: /de/com.aspose.slides/ithreedformateffectivedata/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.IThreeDParamSource](../../com.aspose.slides/ithreedparamsource)
```
public interface IThreeDFormatEffectiveData extends IThreeDParamSource
```

Unveränderliches Objekt, das die effektiven 3-D-Formatierungseigenschaften repräsentiert.

--------------------

Dieses Interface wird zusammen mit dem [IThreeDFormat](../../com.aspose.slides/ithreedformat) Interface verwendet, um effektive Formatierungswerte mit angewandter Vererbung zurückzugeben.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getContourWidth()](#getContourWidth--) | Gibt die Breite eines 3D-Konturs zurück. |
| [getExtrusionHeight()](#getExtrusionHeight--) | Gibt die Höhe eines Extrusions-Effekts zurück. |
| [getDepth()](#getDepth--) | Gibt die Tiefe einer 3D-Form zurück. |
| [getBevelTop()](#getBevelTop--) | Gibt den Typ einer oberen 3D-Fase zurück. |
| [getBevelBottom()](#getBevelBottom--) | Gibt den Typ einer unteren 3D-Fase zurück. |
| [getContourColor()](#getContourColor--) | Gibt die Farbe eines Konturs zurück. |
| [getExtrusionColor()](#getExtrusionColor--) | Gibt die Farbe einer Extrusion zurück. |
| [getCamera()](#getCamera--) | Gibt die Einstellungen einer Kamera zurück. |
| [getLightRig()](#getLightRig--) | Gibt den Typ eines Lichts zurück. |
| [getMaterial()](#getMaterial--) | Gibt den Typ eines Materials zurück. |
### getContourWidth() {#getContourWidth--}
```
public abstract double getContourWidth()
```


Gibt die Breite eines 3D-Konturs zurück. Nur-lesbarer double.

**Rückgabe:**
double
### getExtrusionHeight() {#getExtrusionHeight--}
```
public abstract double getExtrusionHeight()
```


Gibt die Höhe eines Extrusions-Effekts zurück. Nur-lesbarer double.

**Rückgabe:**
double
### getDepth() {#getDepth--}
```
public abstract double getDepth()
```


Gibt die Tiefe einer 3D-Form zurück. Nur-lesbarer double.

**Rückgabe:**
double
### getBevelTop() {#getBevelTop--}
```
public abstract IShapeBevelEffectiveData getBevelTop()
```


Gibt den Typ einer oberen 3D-Fase zurück. Nur-lesbarer [IShapeBevelEffectiveData](../../com.aspose.slides/ishapebeveleffectivedata).

**Rückgabe:**
[IShapeBevelEffectiveData](../../com.aspose.slides/ishapebeveleffectivedata)
### getBevelBottom() {#getBevelBottom--}
```
public abstract IShapeBevelEffectiveData getBevelBottom()
```


Gibt den Typ einer unteren 3D-Fase zurück. Nur-lesbarer [IShapeBevelEffectiveData](../../com.aspose.slides/ishapebeveleffectivedata).

**Rückgabe:**
[IShapeBevelEffectiveData](../../com.aspose.slides/ishapebeveleffectivedata)
### getContourColor() {#getContourColor--}
```
public abstract Color getContourColor()
```


Gibt die Farbe eines Konturs zurück. Nur-lesbarer java.awt.Color.

**Rückgabe:**
java.awt.Color
### getExtrusionColor() {#getExtrusionColor--}
```
public abstract Color getExtrusionColor()
```


Gibt die Farbe einer Extrusion zurück. Nur-lesbarer java.awt.Color.

**Rückgabe:**
java.awt.Color
### getCamera() {#getCamera--}
```
public abstract ICameraEffectiveData getCamera()
```


Gibt die Einstellungen einer Kamera zurück. Nur-lesbarer [ICameraEffectiveData](../../com.aspose.slides/icameraeffectivedata).

**Rückgabe:**
[ICameraEffectiveData](../../com.aspose.slides/icameraeffectivedata)
### getLightRig() {#getLightRig--}
```
public abstract ILightRigEffectiveData getLightRig()
```


Gibt den Typ eines Lichts zurück. Nur-lesbarer [ILightRigEffectiveData](../../com.aspose.slides/ilightrigeffectivedata).

**Rückgabe:**
[ILightRigEffectiveData](../../com.aspose.slides/ilightrigeffectivedata)
### getMaterial() {#getMaterial--}
```
public abstract int getMaterial()
```


Gibt den Typ eines Materials zurück. Nur-lesbarer [MaterialPresetType](../../com.aspose.slides/materialpresettype).

**Rückgabe:**
int