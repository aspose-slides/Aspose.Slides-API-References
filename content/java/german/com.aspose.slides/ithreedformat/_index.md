---
title: IThreeDFormat
second_title: Aspose.Slides für Java API-Referenz
description: Stellt 3-D Eigenschaften dar.
type: docs
url: /de/com.aspose.slides/ithreedformat/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.IThreeDParamSource](../../com.aspose.slides/ithreedparamsource)
```
public interface IThreeDFormat extends IThreeDParamSource
```

Stellt 3-D-Eigenschaften dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getContourWidth()](#getContourWidth--) | Gibt die Breite einer 3D-Kontur zurück oder setzt sie. |
| [setContourWidth(double value)](#setContourWidth-double-) | Gibt die Breite einer 3D-Kontur zurück oder setzt sie. |
| [getExtrusionHeight()](#getExtrusionHeight--) | Gibt die Höhe eines Extrusionseffekts zurück oder setzt sie. |
| [setExtrusionHeight(double value)](#setExtrusionHeight-double-) | Gibt die Höhe eines Extrusionseffekts zurück oder setzt sie. |
| [getDepth()](#getDepth--) | Gibt die Tiefe einer 3D-Form zurück oder setzt sie. |
| [setDepth(double value)](#setDepth-double-) | Gibt die Tiefe einer 3D-Form zurück oder setzt sie. |
| [getBevelTop()](#getBevelTop--) | Gibt den Typ einer oberen 3D-Fase zurück oder setzt ihn. |
| [getBevelBottom()](#getBevelBottom--) | Gibt den Typ einer unteren 3D-Fase zurück oder setzt ihn. |
| [getContourColor()](#getContourColor--) | Gibt die Farbe einer Kontur zurück oder setzt sie. |
| [getExtrusionColor()](#getExtrusionColor--) | Gibt die Farbe einer Extrusion zurück oder setzt sie. |
| [getCamera()](#getCamera--) | Gibt die Einstellungen einer Kamera zurück oder setzt sie. |
| [getLightRig()](#getLightRig--) | Gibt den Typ eines Lichts zurück oder setzt ihn. |
| [getMaterial()](#getMaterial--) | Gibt den Typ eines Materials zurück oder setzt ihn. |
| [setMaterial(int value)](#setMaterial-int-) | Gibt den Typ eines Materials zurück oder setzt ihn. |
| [getEffective()](#getEffective--) | Ermittelt wirksame 3-D-Formatierungsdaten mit angewandter Vererbung. |
### getContourWidth() {#getContourWidth--}
```
public abstract double getContourWidth()
```

Gibt die Breite einer 3D-Kontur zurück oder setzt sie. Lese/Schreib double.

**Rückgabe:**
double
### setContourWidth(double value) {#setContourWidth-double-}
```
public abstract void setContourWidth(double value)
```

Gibt die Breite einer 3D-Kontur zurück oder setzt sie. Lese/Schreib double.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | double |  |
### getExtrusionHeight() {#getExtrusionHeight--}
```
public abstract double getExtrusionHeight()
```

Gibt die Höhe eines Extrusionseffekts zurück oder setzt sie. Lese/Schreib double.

**Rückgabe:**
double
### setExtrusionHeight(double value) {#setExtrusionHeight-double-}
```
public abstract void setExtrusionHeight(double value)
```

Gibt die Höhe eines Extrusionseffekts zurück oder setzt sie. Lese/Schreib double.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | double |  |
### getDepth() {#getDepth--}
```
public abstract double getDepth()
```

Gibt die Tiefe einer 3D-Form zurück oder setzt sie. Lese/Schreib double.

**Rückgabe:**
double
### setDepth(double value) {#setDepth-double-}
```
public abstract void setDepth(double value)
```

Gibt die Tiefe einer 3D-Form zurück oder setzt sie. Lese/Schreib double.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | double |  |
### getBevelTop() {#getBevelTop--}
```
public abstract IShapeBevel getBevelTop()
```

Gibt den Typ einer oberen 3D-Fase zurück oder setzt ihn. Nur-Lesen [IShapeBevel](../../com.aspose.slides/ishapebevel).

**Rückgabe:**
[IShapeBevel](../../com.aspose.slides/ishapebevel)
### getBevelBottom() {#getBevelBottom--}
```
public abstract IShapeBevel getBevelBottom()
```

Gibt den Typ einer unteren 3D-Fase zurück oder setzt ihn. Nur-Lesen [IShapeBevel](../../com.aspose.slides/ishapebevel).

**Rückgabe:**
[IShapeBevel](../../com.aspose.slides/ishapebevel)
### getContourColor() {#getContourColor--}
```
public abstract IColorFormat getContourColor()
```

Gibt die Farbe einer Kontur zurück oder setzt sie. Nur-Lesen [IColorFormat](../../com.aspose.slides/icolorformat).

**Rückgabe:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getExtrusionColor() {#getExtrusionColor--}
```
public abstract IColorFormat getExtrusionColor()
```

Gibt die Farbe einer Extrusion zurück oder setzt sie. Nur-Lesen [IColorFormat](../../com.aspose.slides/icolorformat).

**Rückgabe:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getCamera() {#getCamera--}
```
public abstract ICamera getCamera()
```

Gibt die Einstellungen einer Kamera zurück oder setzt sie. Nur-Lesen [ICamera](../../com.aspose.slides/icamera).

**Rückgabe:**
[ICamera](../../com.aspose.slides/icamera)
### getLightRig() {#getLightRig--}
```
public abstract ILightRig getLightRig()
```

Gibt den Typ eines Lichts zurück oder setzt ihn. Nur-Lesen [ILightRig](../../com.aspose.slides/ilightrig).

**Rückgabe:**
[ILightRig](../../com.aspose.slides/ilightrig)
### getMaterial() {#getMaterial--}
```
public abstract int getMaterial()
```

Gibt den Typ eines Materials zurück oder setzt ihn. Lese/Schreib [MaterialPresetType](../../com.aspose.slides/materialpresettype).

**Rückgabe:**
int
### setMaterial(int value) {#setMaterial-int-}
```
public abstract void setMaterial(int value)
```

Gibt den Typ eines Materials zurück oder setzt ihn. Lese/Schreib [MaterialPresetType](../../com.aspose.slides/materialpresettype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |
### getEffective() {#getEffective--}
```
public abstract IThreeDFormatEffectiveData getEffective()
```

Ermittelt wirksame 3-D-Formatierungsdaten mit angewandter Vererbung.

**Rückgabe:**
[IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata) - A [IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata).