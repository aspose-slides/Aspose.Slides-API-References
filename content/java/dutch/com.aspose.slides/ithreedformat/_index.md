---
title: IThreeDFormat
second_title: Aspose.Slides voor Java API-referentie
description: Stelt 3-D-eigenschappen voor.
type: docs
url: /nl/com.aspose.slides/ithreedformat/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IThreeDParamSource](../../com.aspose.slides/ithreedparamsource)
```
public interface IThreeDFormat extends IThreeDParamSource
```

Stelt 3-D-eigenschappen voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getContourWidth()](#getContourWidth--) | Retourneert of stelt de breedte van een 3D-contour in. |
| [setContourWidth(double value)](#setContourWidth-double-) | Retourneert of stelt de breedte van een 3D-contour in. |
| [getExtrusionHeight()](#getExtrusionHeight--) | Retourneert of stelt de hoogte van een extrusie-effect in. |
| [setExtrusionHeight(double value)](#setExtrusionHeight-double-) | Retourneert of stelt de hoogte van een extrusie-effect in. |
| [getDepth()](#getDepth--) | Retourneert of stelt de diepte van een 3D-vorm in. |
| [setDepth(double value)](#setDepth-double-) | Retourneert of stelt de diepte van een 3D-vorm in. |
| [getBevelTop()](#getBevelTop--) | Retourneert of stelt het type van een bovenste 3D-afschuining in. |
| [getBevelBottom()](#getBevelBottom--) | Retourneert of stelt het type van een onderste 3D-afschuining in. |
| [getContourColor()](#getContourColor--) | Retourneert of stelt de kleur van een contour in. |
| [getExtrusionColor()](#getExtrusionColor--) | Retourneert of stelt de kleur van een extrusie in. |
| [getCamera()](#getCamera--) | Retourneert of stelt de instellingen van een camera in. |
| [getLightRig()](#getLightRig--) | Retourneert of stelt het type van een licht in. |
| [getMaterial()](#getMaterial--) | Retourneert of stelt het type van een materiaal in. |
| [setMaterial(int value)](#setMaterial-int-) | Retourneert of stelt het type van een materiaal in. |
| [getEffective()](#getEffective--) | Haalt effectieve 3-D-opmaakgegevens op met de toegepaste overerving. |
### getContourWidth() {#getContourWidth--}
```
public abstract double getContourWidth()
```


Retourneert of stelt de breedte van een 3D-contour in. Lezen/schrijven double.

**Retour:**
double
### setContourWidth(double value) {#setContourWidth-double-}
```
public abstract void setContourWidth(double value)
```


Retourneert of stelt de breedte van een 3D-contour in. Lezen/schrijven double.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | double |  |

### getExtrusionHeight() {#getExtrusionHeight--}
```
public abstract double getExtrusionHeight()
```


Retourneert of stelt de hoogte van een extrusie-effect in. Lezen/schrijven double.

**Retour:**
double
### setExtrusionHeight(double value) {#setExtrusionHeight-double-}
```
public abstract void setExtrusionHeight(double value)
```


Retourneert of stelt de hoogte van een extrusie-effect in. Lezen/schrijven double.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | double |  |

### getDepth() {#getDepth--}
```
public abstract double getDepth()
```


Retourneert of stelt de diepte van een 3D-vorm in. Lezen/schrijven double.

**Retour:**
double
### setDepth(double value) {#setDepth-double-}
```
public abstract void setDepth(double value)
```


Retourneert of stelt de diepte van een 3D-vorm in. Lezen/schrijven double.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | double |  |

### getBevelTop() {#getBevelTop--}
```
public abstract IShapeBevel getBevelTop()
```


Retourneert of stelt het type van een bovenste 3D-afschuining in. Alleen-lezen [IShapeBevel](../../com.aspose.slides/ishapebevel).

**Retour:**
[IShapeBevel](../../com.aspose.slides/ishapebevel)
### getBevelBottom() {#getBevelBottom--}
```
public abstract IShapeBevel getBevelBottom()
```


Retourneert of stelt het type van een onderste 3D-afschuining in. Alleen-lezen [IShapeBevel](../../com.aspose.slides/ishapebevel).

**Retour:**
[IShapeBevel](../../com.aspose.slides/ishapebevel)
### getContourColor() {#getContourColor--}
```
public abstract IColorFormat getContourColor()
```


Retourneert of stelt de kleur van een contour in. Alleen-lezen [IColorFormat](../../com.aspose.slides/icolorformat).

**Retour:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getExtrusionColor() {#getExtrusionColor--}
```
public abstract IColorFormat getExtrusionColor()
```


Retourneert of stelt de kleur van een extrusie in. Alleen-lezen [IColorFormat](../../com.aspose.slides/icolorformat).

**Retour:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getCamera() {#getCamera--}
```
public abstract ICamera getCamera()
```


Retourneert of stelt de instellingen van een camera in. Alleen-lezen [ICamera](../../com.aspose.slides/icamera).

**Retour:**
[ICamera](../../com.aspose.slides/icamera)
### getLightRig() {#getLightRig--}
```
public abstract ILightRig getLightRig()
```


Retourneert of stelt het type van een licht in. Alleen-lezen [ILightRig](../../com.aspose.slides/ilightrig).

**Retour:**
[ILightRig](../../com.aspose.slides/ilightrig)
### getMaterial() {#getMaterial--}
```
public abstract int getMaterial()
```


Retourneert of stelt het type van een materiaal in. Lezen/schrijven [MaterialPresetType](../../com.aspose.slides/materialpresettype).

**Retour:**
int
### setMaterial(int value) {#setMaterial-int-}
```
public abstract void setMaterial(int value)
```


Retourneert of stelt het type van een materiaal in. Lezen/schrijven [MaterialPresetType](../../com.aspose.slides/materialpresettype).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getEffective() {#getEffective--}
```
public abstract IThreeDFormatEffectiveData getEffective()
```


Haalt effectieve 3-D-opmaakgegevens op met de toegepaste overerving.

**Retour:**
[IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata) - A [IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata).