---
title: IThreeDFormat
second_title: Aspose.Slides für Android über die Java-API-Referenz
description: Stellt 3-D-Eigenschaften dar.
type: docs
url: /de/com.aspose.slides/ithreedformat/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.IThreeDParamSource](../../com.aspose.slides/ithreedparamsource)
```
public interface IThreeDFormat extends IThreeDParamSource
```

Stellt 3D-Eigenschaften dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getContourWidth()](#getContourWidth--) | Liefert oder setzt die Breite eines 3D-Konturs. |
| [setContourWidth(double value)](#setContourWidth-double-) | Liefert oder setzt die Breite eines 3D-Konturs. |
| [getExtrusionHeight()](#getExtrusionHeight--) | Liefert oder setzt die Höhe eines Extrusions-Effekts. |
| [setExtrusionHeight(double value)](#setExtrusionHeight-double-) | Liefert oder setzt die Höhe eines Extrusions-Effekts. |
| [getDepth()](#getDepth--) | Liefert oder setzt die Tiefe einer 3D-Form. |
| [setDepth(double value)](#setDepth-double-) | Liefert oder setzt die Tiefe einer 3D-Form. |
| [getBevelTop()](#getBevelTop--) | Liefert oder setzt den Typ einer oberen 3D-Fase. |
| [getBevelBottom()](#getBevelBottom--) | Liefert oder setzt den Typ einer unteren 3D-Fase. |
| [getContourColor()](#getContourColor--) | Liefert oder setzt die Farbe eines Konturs. |
| [getExtrusionColor()](#getExtrusionColor--) | Liefert oder setzt die Farbe einer Extrusion. |
| [getCamera()](#getCamera--) | Liefert oder setzt die Einstellungen einer Kamera. |
| [getLightRig()](#getLightRig--) | Liefert oder setzt den Typ eines Lichts. |
| [getMaterial()](#getMaterial--) | Liefert oder setzt den Typ eines Materials. |
| [setMaterial(int value)](#setMaterial-int-) | Liefert oder setzt den Typ eines Materials. |
| [getEffective()](#getEffective--) | Ermittelt effektive 3D-Formatierungsdaten mit angewandter Vererbung. |
### getContourWidth() {#getContourWidth--}
```
public abstract double getContourWidth()
```

Liefert oder setzt die Breite eines 3D-Konturs. Lesen/Schreiben double.

**Rückgabe:**
double
### setContourWidth(double value) {#setContourWidth-double-}
```
public abstract void setContourWidth(double value)
```

Liefert oder setzt die Breite eines 3D-Konturs. Lesen/Schreiben double.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | double |  |

### getExtrusionHeight() {#getExtrusionHeight--}
```
public abstract double getExtrusionHeight()
```

Liefert oder setzt die Höhe eines Extrusions-Effekts. Lesen/Schreiben double.

**Rückgabe:**
double
### setExtrusionHeight(double value) {#setExtrusionHeight-double-}
```
public abstract void setExtrusionHeight(double value)
```

Liefert oder setzt die Höhe eines Extrusions-Effekts. Lesen/Schreiben double.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | double |  |

### getDepth() {#getDepth--}
```
public abstract double getDepth()
```

Liefert oder setzt die Tiefe einer 3D-Form. Lesen/Schreiben double.

**Rückgabe:**
double
### setDepth(double value) {#setDepth-double-}
```
public abstract void setDepth(double value)
```

Liefert oder setzt die Tiefe einer 3D-Form. Lesen/Schreiben double.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | double |  |

### getBevelTop() {#getBevelTop--}
```
public abstract IShapeBevel getBevelTop()
```

Liefert oder setzt den Typ einer oberen 3D-Fase. Nur-Lesen [IShapeBevel](../../com.aspose.slides/ishapebevel).

**Rückgabe:**
[IShapeBevel](../../com.aspose.slides/ishapebevel)
### getBevelBottom() {#getBevelBottom--}
```
public abstract IShapeBevel getBevelBottom()
```

Liefert oder setzt den Typ einer unteren 3D-Fase. Nur-Lesen [IShapeBevel](../../com.aspose.slides/ishapebevel).

**Rückgabe:**
[IShapeBevel](../../com.aspose.slides/ishapebevel)
### getContourColor() {#getContourColor--}
```
public abstract IColorFormat getContourColor()
```

Liefert oder setzt die Farbe eines Konturs. Nur-Lesen [IColorFormat](../../com.aspose.slides/icolorformat).

**Rückgabe:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getExtrusionColor() {#getExtrusionColor--}
```
public abstract IColorFormat getExtrusionColor()
```

Liefert oder setzt die Farbe einer Extrusion. Nur-Lesen [IColorFormat](../../com.aspose.slides/icolorformat).

**Rückgabe:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getCamera() {#getCamera--}
```
public abstract ICamera getCamera()
```

Liefert oder setzt die Einstellungen einer Kamera. Nur-Lesen [ICamera](../../com.aspose.slides/icamera).

**Rückgabe:**
[ICamera](../../com.aspose.slides/icamera)
### getLightRig() {#getLightRig--}
```
public abstract ILightRig getLightRig()
```

Liefert oder setzt den Typ eines Lichts. Nur-Lesen [ILightRig](../../com.aspose.slides/ilightrig).

**Rückgabe:**
[ILightRig](../../com.aspose.slides/ilightrig)
### getMaterial() {#getMaterial--}
```
public abstract int getMaterial()
```

Liefert oder setzt den Typ eines Materials. Lesen/Schreiben [MaterialPresetType](../../com.aspose.slides/materialpresettype).

**Rückgabe:**
int
### setMaterial(int value) {#setMaterial-int-}
```
public abstract void setMaterial(int value)
```

Liefert oder setzt den Typ eines Materials. Lesen/Schreiben [MaterialPresetType](../../com.aspose.slides/materialpresettype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getEffective() {#getEffective--}
```
public abstract IThreeDFormatEffectiveData getEffective()
```

Ermittelt effektive 3D-Formatierungsdaten mit angewandter Vererbung.

**Rückgabe:**
[IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata) - A [IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata).